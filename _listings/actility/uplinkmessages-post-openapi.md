---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Dataflow API Uplink data reception
  description: Endpoint to be used by the LRC to push uplink data in order to use
    ThingPark X dataflows.
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
    post:
      summary: Constant maps creation
      description: Creates a new custom constant map for the subscriber.
      operationId: creates-a-new-custom-constant-map-for-the-subscriber
      x-api-path-slug: constantmaps-post
      parameters:
      - in: body
        name: constantMap
        description: Contents of the constant map to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Maps
      - Creation
  /constantMaps/{constantMapRef}:
    get:
      summary: Constant map retrieval
      description: Retrieves the constant map corresponding to the provided constant
        map ref..
      operationId: retrieves-the-constant-map-corresponding-to-the-provided-constant-map-ref
      x-api-path-slug: constantmapsconstantmapref-get
      parameters:
      - in: path
        name: constantMapRef
        description: Ref of the constant map to retrieve
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Map
      - Retrieval
    put:
      summary: Constant map update
      description: Updates the constant map corresponding to the provided constant
        map ref. This is only authorized if the constant map has been created by the
        subscriber (not provided by the system).
      operationId: updates-the-constant-map-corresponding-to-the-provided-constant-map-ref-this-is-only-authorized-if-t
      x-api-path-slug: constantmapsconstantmapref-put
      parameters:
      - in: body
        name: constantMap
        description: Contents of the constant map to update
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: constantMapRef
        description: Ref of the constant map to update
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Map
      - Update
    delete:
      summary: Constant map deletion
      description: Deletes the constant map corresponding to the provided constant
        map ref. This is only authorized if the constant map has been created by the
        subscriber (not provided by the system).
      operationId: deletes-the-constant-map-corresponding-to-the-provided-constant-map-ref-this-is-only-authorized-if-t
      x-api-path-slug: constantmapsconstantmapref-delete
      parameters:
      - in: path
        name: constantMapRef
        description: Ref of the constant map to delete
      responses:
        200:
          description: OK
      tags:
      - Constant
      - Map
      - Deletion
  /binderClasses:
    get:
      summary: Binder processor classes retrieval
      description: Retrieves the list of system-wide processor classes providing binder
        (e.g. with a device) behaviour.
      operationId: retrieves-the-list-of-systemwide-processor-classes-providing-binder-eg-with-a-device-behaviour
      x-api-path-slug: binderclasses-get
      responses:
        200:
          description: OK
      tags:
      - Binder
      - Processor
      - Classes
      - Retrieval
  /driverClasses:
    get:
      summary: Driver processor classes retrieval
      description: Retrieves the list of system-wide processor classes providing driver
        behaviour.
      operationId: retrieves-the-list-of-systemwide-processor-classes-providing-driver-behaviour
      x-api-path-slug: driverclasses-get
      responses:
        200:
          description: OK
      tags:
      - Driver
      - Processor
      - Classes
      - Retrieval
  /connectorClasses:
    get:
      summary: Connector processor classes retrieval
      description: Retrieves the list of system-wide processor classes providing connector
        behaviour.
      operationId: retrieves-the-list-of-systemwide-processor-classes-providing-connector-behaviour
      x-api-path-slug: connectorclasses-get
      responses:
        200:
          description: OK
      tags:
      - Connector
      - Processor
      - Classes
      - Retrieval
  /events:
    get:
      summary: Dataflow events retrieval
      description: Retrieves the list of events for all configured dataflows in scope.
      operationId: retrieves-the-list-of-events-for-all-configured-dataflows-in-scope
      x-api-path-slug: events-get
      parameters:
      - in: query
        name: dataflowRef
        description: Ref of the dataflow for which events should be retrieved
      responses:
        200:
          description: OK
      tags:
      - Dataflow
      - Events
      - Retrieval
  /uplinkMessages:
    post:
      summary: Uplink data reception
      description: Endpoint to be used by the LRC to push uplink data in order to
        use ThingPark X dataflows.
      operationId: endpoint-to-be-used-by-the-lrc-to-push-uplink-data-in-order-to-use-thingpark-x-dataflows
      x-api-path-slug: uplinkmessages-post
      parameters:
      - in: body
        name: data
        description: Uplink data frame in ThingPark XML or JSON format
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Uplink
      - Data
      - Reception
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