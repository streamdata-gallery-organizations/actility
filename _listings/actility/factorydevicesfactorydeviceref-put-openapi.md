---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Maker API Factory device update
  description: Updates the factory device corresponding to the provided factoryDeviceRef.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---