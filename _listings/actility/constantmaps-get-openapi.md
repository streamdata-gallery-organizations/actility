---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Dataflow API Constant maps retrieval
  description: Retrieves the list of constant maps (both system-provided and custom)
    available in the scope.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /dataflow/v021/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /bridgeDataflows:
    get:
      summary: Bridge dataflows retrieval
      description: Retrieves the list of Bridge dataflows available in the scope.
      operationId: retrieves-the-list-of-bridge-dataflows-available-in-the-scope
      x-api-path-slug: bridgedataflows-get
      responses:
        200:
          description: OK
      tags:
      - Bridge
      - Dataflows
      - Retrieval
    post:
      summary: Bridge dataflow creation
      description: Creates a new Bridge dataflow.
      operationId: creates-a-new-bridge-dataflow
      x-api-path-slug: bridgedataflows-post
      parameters:
      - in: body
        name: bridgeDataflow
        description: Contents of the Bridge dataflow to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bridge
      - Dataflow
      - Creation
  /bridgeDataflows/{bridgeDataflowRef}:
    get:
      summary: Bridge dataflow retrieval
      description: Retrieves the Bridge dataflow corresponding to the provided order
        ref, if that order is within authorized scopes.
      operationId: retrieves-the-bridge-dataflow-corresponding-to-the-provided-order-ref-if-that-order-is-within-author
      x-api-path-slug: bridgedataflowsbridgedataflowref-get
      parameters:
      - in: path
        name: bridgeDataflowRef
        description: Ref of the Bridge dataflow to retrieve
      responses:
        200:
          description: OK
      tags:
      - Bridge
      - Dataflow
      - Retrieval
    put:
      summary: Bridge dataflow update
      description: Updates the Bridge dataflow corresponding to the provided Bridge
        dataflow ref, if that dataflow is within authorized scopes. Note that when
        updating a dataflow, all existing attributs must be provided next to your
        changes.
      operationId: updates-the-bridge-dataflow-corresponding-to-the-provided-bridge-dataflow-ref-if-that-dataflow-is-wi
      x-api-path-slug: bridgedataflowsbridgedataflowref-put
      parameters:
      - in: body
        name: bridgeDataflow
        description: Contents of the Bridge dataflow to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: bridgeDataflowRef
        description: Ref of the Bridge dataflow to update
      responses:
        200:
          description: OK
      tags:
      - Bridge
      - Dataflow
      - Update
    delete:
      summary: Bridge dataflow deletion
      description: Deletes the Bridge dataflow corresponding to the provided Bridge
        dataflow ref, if that dataflow is within authorized scopes.
      operationId: deletes-the-bridge-dataflow-corresponding-to-the-provided-bridge-dataflow-ref-if-that-dataflow-is-wi
      x-api-path-slug: bridgedataflowsbridgedataflowref-delete
      parameters:
      - in: path
        name: bridgeDataflowRef
        description: Ref of the Bridge dataflow to delete
      responses:
        200:
          description: OK
      tags:
      - Bridge
      - Dataflow
      - Deletion
  /constantMaps:
    get:
      summary: Constant maps retrieval
      description: Retrieves the list of constant maps (both system-provided and custom)
        available in the scope.
      operationId: retrieves-the-list-of-constant-maps-both-systemprovided-and-custom-available-in-the-scope
      x-api-path-slug: constantmaps-get
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Maps
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