---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Dataflow API Bridge dataflows retrieval
  description: Retrieves the list of Bridge dataflows available in the scope.
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