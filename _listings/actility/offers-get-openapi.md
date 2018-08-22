---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Core API Offers retrieval
  description: Retrieves a list of offers existing within authorized scopes. In case
    of a vendor scope, it retrieves all offers of that vendor. In case of a subscriber
    scope, it retrieves all offers subscribed by that subscriber.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /core/v141/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /suppliers:
    get:
      summary: Suppliers retrieval
      description: Retrieves a list of suppliers existing within authorized scopes.
      operationId: retrieves-a-list-of-suppliers-existing-within-authorized-scopes
      x-api-path-slug: suppliers-get
      parameters:
      - in: query
        name: supplierId
        description: Id of the supplier to search for
      responses:
        200:
          description: OK
      tags:
      - Suppliers
      - Retrieval
    post:
      summary: Supplier creation
      description: Creates a new supplier with a primary user having all admin rights.
        Note that the supplier id can be chosen. If not fully specified, the supplier
        id and name attribute values are deduced from the primaryUser attribute values.
      operationId: creates-a-new-supplier-with-a-primary-user-having-all-admin-rights-note-that-the-supplier-id-can-be-
      x-api-path-slug: suppliers-post
      parameters:
      - in: body
        name: supplier
        description: Contents of the supplier to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Supplier
      - Creation
  /suppliers/{supplierRef}:
    get:
      summary: Supplier retrieval
      description: Retrieves the supplier corresponding to the provided supplier ref,
        if that supplier is within authorized scopes.
      operationId: retrieves-the-supplier-corresponding-to-the-provided-supplier-ref-if-that-supplier-is-within-authori
      x-api-path-slug: supplierssupplierref-get
      parameters:
      - in: path
        name: supplierRef
        description: Ref of the supplier to retrieve
      responses:
        200:
          description: OK
      tags:
      - Supplier
      - Retrieval
    put:
      summary: Supplier update
      description: Updates the supplier corresponding to the provided supplier ref,
        if that supplier is within authorized scopes.
      operationId: updates-the-supplier-corresponding-to-the-provided-supplier-ref-if-that-supplier-is-within-authorize
      x-api-path-slug: supplierssupplierref-put
      parameters:
      - in: body
        name: supplier
        description: Contents of the supplier to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: supplierRef
        description: Ref of the supplier to update
      responses:
        200:
          description: OK
      tags:
      - Supplier
      - Update
    delete:
      summary: Supplier deletion
      description: Deletes the supplier corresponding to the provided supplier ref,
        if that supplier is within authorized scopes.
      operationId: deletes-the-supplier-corresponding-to-the-provided-supplier-ref-if-that-supplier-is-within-authorize
      x-api-path-slug: supplierssupplierref-delete
      parameters:
      - in: path
        name: supplierRef
        description: Ref of the supplier to delete
      responses:
        200:
          description: OK
      tags:
      - Supplier
      - Deletion
  /vendors:
    get:
      summary: Vendors retrieval
      description: Retrieves a list of vendors existing within authorized scopes.
      operationId: retrieves-a-list-of-vendors-existing-within-authorized-scopes
      x-api-path-slug: vendors-get
      parameters:
      - in: query
        name: vendorId
        description: Id of the vendor to search for
      responses:
        200:
          description: OK
      tags:
      - Vendors
      - Retrieval
    post:
      summary: Vendor creation
      description: Creates a new vendor with a primary user having all admin rights.
        Note that the vendor id can be chosen. If not fully specified, the vendor
        id and name attribute values are deduced from the primaryUser attribute values.
      operationId: creates-a-new-vendor-with-a-primary-user-having-all-admin-rights-note-that-the-vendor-id-can-be-chos
      x-api-path-slug: vendors-post
      parameters:
      - in: body
        name: vendor
        description: Contents of the vendor to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Vendor
      - Creation
  /vendors/{vendorRef}:
    get:
      summary: Vendor retrieval
      description: Retrieves the vendor corresponding to the provided vendor ref,
        if that vendor is within authorized scopes.
      operationId: retrieves-the-vendor-corresponding-to-the-provided-vendor-ref-if-that-vendor-is-within-authorized-sc
      x-api-path-slug: vendorsvendorref-get
      parameters:
      - in: path
        name: vendorRef
        description: Ref of the vendor to retrieve
      responses:
        200:
          description: OK
      tags:
      - Vendor
      - Retrieval
    put:
      summary: Vendor update
      description: Updates the vendor corresponding to the provided vendor ref, if
        that vendor is within authorized scopes.
      operationId: updates-the-vendor-corresponding-to-the-provided-vendor-ref-if-that-vendor-is-within-authorized-scop
      x-api-path-slug: vendorsvendorref-put
      parameters:
      - in: body
        name: vendor
        description: Contents of the vendor to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: vendorRef
        description: Ref of the vendor to update
      responses:
        200:
          description: OK
      tags:
      - Vendor
      - Update
    delete:
      summary: Vendor deletion
      description: Deletes the vendor corresponding to the provided vendor ref, if
        that vendor is within authorized scopes.
      operationId: deletes-the-vendor-corresponding-to-the-provided-vendor-ref-if-that-vendor-is-within-authorized-scop
      x-api-path-slug: vendorsvendorref-delete
      parameters:
      - in: path
        name: vendorRef
        description: Ref of the vendor to delete
      responses:
        200:
          description: OK
      tags:
      - Vendor
      - Deletion
  /subscribers:
    get:
      summary: Subscribers retrieval
      description: Retrieves a list of subscribers existing within authorized scopes.
      operationId: retrieves-a-list-of-subscribers-existing-within-authorized-scopes
      x-api-path-slug: subscribers-get
      parameters:
      - in: query
        name: applicationId
        description: Id of an application which has been subscribed by the searched
          subscribers
      - in: query
        name: contactEmail
        description: Contact email of the subscriber to search for
      - in: query
        name: subscriberId
        description: Id of the subscriber to search for
      responses:
        200:
          description: OK
      tags:
      - Subscribers
      - Retrieval
    post:
      summary: Subscriber creation
      description: Creates a new subscriber. If not fully specified, the subscriber
        name, contactEmail and organization attribute values are deduced from the
        primaryUser attribute values.
      operationId: creates-a-new-subscriber-if-not-fully-specified-the-subscriber-name-contactemail-and-organization-at
      x-api-path-slug: subscribers-post
      parameters:
      - in: body
        name: subscriber
        description: Contents of the subscriber to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Subscriber
      - Creation
  /subscribers/{subscriberRef}:
    get:
      summary: Subscriber retrieval
      description: Retrieves the subscriber corresponding to the provided subscriber
        ref, if that subscriber is within authorized scopes.
      operationId: retrieves-the-subscriber-corresponding-to-the-provided-subscriber-ref-if-that-subscriber-is-within-a
      x-api-path-slug: subscriberssubscriberref-get
      parameters:
      - in: path
        name: subscriberRef
        description: Ref of the subscriber to retrieve
      responses:
        200:
          description: OK
      tags:
      - Subscriber
      - Retrieval
    put:
      summary: Subscriber update
      description: Updates the subscriber corresponding to the provided subscriber
        ref, if that subscriber is within authorized scopes.
      operationId: updates-the-subscriber-corresponding-to-the-provided-subscriber-ref-if-that-subscriber-is-within-aut
      x-api-path-slug: subscriberssubscriberref-put
      parameters:
      - in: body
        name: subscriber
        description: Contents of the subscriber to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: subscriberRef
        description: Ref of the subscriber to update
      responses:
        200:
          description: OK
      tags:
      - Subscriber
      - Update
    delete:
      summary: Subscriber deletion
      description: Deletes the subscriber corresponding to the provided subscriber
        ref, if that subscriber is within authorized scopes.
      operationId: deletes-the-subscriber-corresponding-to-the-provided-subscriber-ref-if-that-subscriber-is-within-aut
      x-api-path-slug: subscriberssubscriberref-delete
      parameters:
      - in: query
        name: force
        description: If true, forces the deletion of all orders, devices and base
          stations attached to the subscriber, before deleting the subscriber
      - in: path
        name: subscriberRef
        description: Ref of the subscriber to delete
      responses:
        200:
          description: OK
      tags:
      - Subscriber
      - Deletion
  /users:
    get:
      summary: Users retrieval
      description: Retrieves a list of users existing within authorized scopes.
      operationId: retrieves-a-list-of-users-existing-within-authorized-scopes
      x-api-path-slug: users-get
      parameters:
      - in: query
        name: email
        description: Email of the user to search for
      - in: query
        name: userId
        description: Id of the user to search for
      responses:
        200:
          description: OK
      tags:
      - Users
      - Retrieval
    post:
      summary: User creation
      description: Creates a new user. Enclosing party depends on authorized scopes.
      operationId: creates-a-new-user-enclosing-party-depends-on-authorized-scopes
      x-api-path-slug: users-post
      parameters:
      - in: body
        name: user
        description: Contents of the user to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - User
      - Creation
  /users/{userRef}:
    get:
      summary: User retrieval
      description: Retrieves the user corresponding to the provided user ref, if that
        user is within authorized scopes.
      operationId: retrieves-the-user-corresponding-to-the-provided-user-ref-if-that-user-is-within-authorized-scopes
      x-api-path-slug: usersuserref-get
      parameters:
      - in: path
        name: userRef
        description: Ref of the user to retrieve
      responses:
        200:
          description: OK
      tags:
      - User
      - Retrieval
    put:
      summary: User update
      description: Updates the user corresponding to the provided user ref, if that
        user is within authorized scopes.
      operationId: updates-the-user-corresponding-to-the-provided-user-ref-if-that-user-is-within-authorized-scopes
      x-api-path-slug: usersuserref-put
      parameters:
      - in: query
        name: resetPassword
        description: Indicates if the user password must be resetted and a new password
          must be sent to the users current email
      - in: body
        name: user
        description: Contents of the user to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userRef
        description: Ref of the user to update
      responses:
        200:
          description: OK
      tags:
      - User
      - Update
    delete:
      summary: User deletion
      description: Deletes the user corresponding to the provided user ref, if that
        user is within authorized scopes.
      operationId: deletes-the-user-corresponding-to-the-provided-user-ref-if-that-user-is-within-authorized-scopes
      x-api-path-slug: usersuserref-delete
      parameters:
      - in: path
        name: userRef
        description: Ref of the user to delete
      responses:
        200:
          description: OK
      tags:
      - User
      - Deletion
  /offers:
    get:
      summary: Offers retrieval
      description: Retrieves a list of offers existing within authorized scopes. In
        case of a vendor scope, it retrieves all offers of that vendor. In case of
        a subscriber scope, it retrieves all offers subscribed by that subscriber.
      operationId: retrieves-a-list-of-offers-existing-within-authorized-scopes-in-case-of-a-vendor-scope-it-retrieves-
      x-api-path-slug: offers-get
      parameters:
      - in: query
        name: offerId
        description: Id of the offer to search for
      responses:
        200:
          description: OK
      tags:
      - Offers
      - Retrieval
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