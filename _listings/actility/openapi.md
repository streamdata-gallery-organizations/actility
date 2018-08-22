---
swagger: "2.0"
x-collection-name: Actility
x-complete: 1
info:
  title: ThingPark DX Maker API
  description: api-providing-features-for-device-makers-such-as-preprovisioning-on-standalone-join-servers-
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /maker/v011/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /factoryDevices:
    get:
      summary: Factory devices retrieval
      description: Retrieves all factory devices.
      operationId: retrieves-all-factory-devices
      x-api-path-slug: factorydevices-get
      parameters:
      - in: query
        name: deviceEUI
        description: EUI of the factory device to retrieve
      - in: query
        name: pageIndex
        description: If set, enables pagination and returns only the 100 factory devices
          of the specified page
      responses:
        200:
          description: OK
      tags:
      - Factory
      - Devices
      - Retrieval
    post:
      summary: Factory device creation
      description: Creates a factory device.
      operationId: creates-a-factory-device
      x-api-path-slug: factorydevices-post
      parameters:
      - in: body
        name: deviceFactory
        description: Contents of the factory device
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Factory
      - Device
      - Creation
  /factoryDevices/{factoryDeviceRef}:
    get:
      summary: Factory device retrieval
      description: Retrieves the factory device corresponding to the provided factoryDeviceRef.
      operationId: retrieves-the-factory-device-corresponding-to-the-provided-factorydeviceref
      x-api-path-slug: factorydevicesfactorydeviceref-get
      parameters:
      - in: path
        name: factoryDeviceRef
        description: Ref of the factory device to retrieve
      responses:
        200:
          description: OK
      tags:
      - Factory
      - Device
      - Retrieval
    put:
      summary: Factory device update
      description: Updates the factory device corresponding to the provided factoryDeviceRef.
      operationId: updates-the-factory-device-corresponding-to-the-provided-factorydeviceref
      x-api-path-slug: factorydevicesfactorydeviceref-put
      parameters:
      - in: body
        name: device
        description: Contents of the factory device to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: factoryDeviceRef
        description: Ref of the factory device to update
      responses:
        200:
          description: OK
      tags:
      - Factory
      - Device
      - Update
    delete:
      summary: Factory device deletion
      description: Deletes the factory device corresponding to the provided factoryDeviceRef.
      operationId: deletes-the-factory-device-corresponding-to-the-provided-factorydeviceref
      x-api-path-slug: factorydevicesfactorydeviceref-delete
      parameters:
      - in: path
        name: factoryDeviceRef
        description: Ref of the factory device to delete
      responses:
        200:
          description: OK
      tags:
      - Factory
      - Device
      - Deletion
  /appKeyGens:
    post:
      summary: AppKey generation
      description: Generate some encrypted VendorKeys with an HSM. Encrypted VendorKeys
        can be decrypted with the private part of provided RSA key. A VendorKey is
        a concatenation of an AppKey (128 bits) and hsmEncryptedAppKey (128 bits).
      operationId: generate-some-encrypted-vendorkeys-with-an-hsm-encrypted-vendorkeys-can-be-decrypted-with-the-privat
      x-api-path-slug: appkeygens-post
      parameters:
      - in: body
        name: appKeyGen
        description: Configuration for AppKey generation
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: number
        description: Define the number of AppKey generated
      responses:
        200:
          description: OK
      tags:
      - AppKey
      - Generation
  /asKeys:
    get:
      summary: AS keys retrieval
      description: Retrieves the list of AS keys existing within authorized scopes.
      operationId: retrieves-the-list-of-as-keys-existing-within-authorized-scopes
      x-api-path-slug: askeys-get
      parameters:
      - in: query
        name: pageIndex
        description: If set, enables pagination and returns only the 100 AS keys of
          the specified page
      responses:
        200:
          description: OK
      tags:
      - AS
      - Keys
      - Retrieval
    post:
      summary: AS key creation
      description: Creates a new AS key.
      operationId: creates-a-new-as-key
      x-api-path-slug: askeys-post
      parameters:
      - in: body
        name: asKey
        description: Contents of the AS key to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - AS
      - Key
      - Creation
  /asKeys/{asKeyRef}:
    get:
      summary: AS key retrieval
      description: Retrieves the AS key corresponding to the provided AS key ref,
        if that AS key is within authorized scopes.
      operationId: retrieves-the-as-key-corresponding-to-the-provided-as-key-ref-if-that-as-key-is-within-authorized-sc
      x-api-path-slug: askeysaskeyref-get
      parameters:
      - in: path
        name: asKeyRef
        description: Ref of the AS key to retrieve
      responses:
        200:
          description: OK
      tags:
      - AS
      - Key
      - Retrieval
    put:
      summary: AS key update
      description: Updates the AS key corresponding to the provided asKey ref, if
        that AS key is within authorized scopes.
      operationId: updates-the-as-key-corresponding-to-the-provided-askey-ref-if-that-as-key-is-within-authorized-scope
      x-api-path-slug: askeysaskeyref-put
      parameters:
      - in: body
        name: asKey
        description: Contents of the AS key to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: asKeyRef
        description: Ref of the AS key to update
      responses:
        200:
          description: OK
      tags:
      - AS
      - Key
      - Update
    delete:
      summary: AS key deletion
      description: Deletes the AS key corresponding to the provided asKeyRef, if that
        AS key is within authorized scopes.
      operationId: deletes-the-as-key-corresponding-to-the-provided-askeyref-if-that-as-key-is-within-authorized-scopes
      x-api-path-slug: askeysaskeyref-delete
      parameters:
      - in: path
        name: asKeyRef
        description: Ref of the AS key to delete
      responses:
        200:
          description: OK
      tags:
      - AS
      - Key
      - Deletion
  /hsmGroups:
    get:
      summary: HSM groups retrieval
      description: Retrieves all HSM groups.
      operationId: retrieves-all-hsm-groups
      x-api-path-slug: hsmgroups-get
      parameters:
      - in: query
        name: pageIndex
        description: If set, enables pagination and returns only the 100 HSM groups
          of the specified page
      responses:
        200:
          description: OK
      tags:
      - HSM
      - Groups
      - Retrieval
---