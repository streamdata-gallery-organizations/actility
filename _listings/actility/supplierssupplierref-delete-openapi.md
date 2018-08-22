---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Core API Supplier deletion
  description: Deletes the supplier corresponding to the provided supplier ref, if
    that supplier is within authorized scopes.
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