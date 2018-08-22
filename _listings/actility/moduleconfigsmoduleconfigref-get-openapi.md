---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Location API Module configuration retrieval
  description: Retrieves the module configuration corresponding to the provided ref.
  version: 1.0.0
host: dx-api.thingpark.com
basePath: /location/v110
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /feeds:
    post:
      summary: Feed request
      description: Feeds the platform with geolocation data. Data is then dispatched
        and processed based on available information.
      operationId: feeds-the-platform-with-geolocation-data-data-is-then-dispatched-and-processed-based-on-available-in
      x-api-path-slug: feeds-post
      parameters:
      - in: body
        name: feedRequest
        description: Contents of the feed request
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Feed
      - Request
  /moduleConfigs:
    get:
      summary: Module configurations retrieval
      description: Retrieves the list of existing module configurations.
      operationId: retrieves-the-list-of-existing-module-configurations
      x-api-path-slug: moduleconfigs-get
      responses:
        200:
          description: OK
      tags:
      - Module
      - Configurations
      - Retrieval
    post:
      summary: Module configuration creation
      description: Creates a new module configuration.
      operationId: creates-a-new-module-configuration
      x-api-path-slug: moduleconfigs-post
      parameters:
      - in: body
        name: moduleConfig
        description: Contents of the module configuration to create
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Module
      - Configuration
      - Creation
  /moduleConfigs/{moduleConfigRef}:
    get:
      summary: Module configuration retrieval
      description: Retrieves the module configuration corresponding to the provided
        ref.
      operationId: retrieves-the-module-configuration-corresponding-to-the-provided-ref
      x-api-path-slug: moduleconfigsmoduleconfigref-get
      parameters:
      - in: path
        name: moduleConfigRef
        description: Ref of the module configuration to retrieve
      responses:
        200:
          description: OK
      tags:
      - Module
      - Configuration
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