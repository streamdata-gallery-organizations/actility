---
swagger: "2.0"
x-collection-name: Actility
x-complete: 0
info:
  title: ThingPark DX Core API Supplier retrieval
  description: Retrieves the supplier corresponding to the provided supplier ref,
    if that supplier is within authorized scopes.
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
  /oauth/token:
    post:
      summary: Token Generation
      description: Generates and retrieves a token for a client.
      operationId: generates-and-retrieves-a-token-for-a-client
      x-api-path-slug: oauthtoken-post
      parameters:
      - in: formData
        name: client_id
        description: Id of the client
      - in: formData
        name: client_secret
        description: Secret of the client
      - in: formData
        name: grant_type
        description: Type of the OAuth2 grant workflow
      - in: query
        name: renewToken
        description: Forces the token to be renewed
      - in: query
        name: validityPeriod
        description: Validity of the new token
      responses:
        200:
          description: OK
      tags:
      - Token
      - Generation
  /oauth/revoke_token:
    post:
      summary: Token Revocation
      description: Revokes a token.
      operationId: revokes-a-token
      x-api-path-slug: oauthrevoke-token-post
      parameters:
      - in: query
        name: access_token
        description: Value of the token to revoke
      responses:
        200:
          description: OK
      tags:
      - Token
      - Revocation
  /oauth/tokeninfo:
    get:
      summary: Token Info Retrieval
      description: Retrieves information about a valid token.
      operationId: retrieves-information-about-a-valid-token
      x-api-path-slug: oauthtokeninfo-get
      parameters:
      - in: query
        name: access_token
        description: Value of the token for which info is requested
      responses:
        200:
          description: OK
      tags:
      - Token
      - Info
      - Retrieval
  /profiles:
    get:
      summary: Profiles Retrieval
      description: Retrieves all available profiles. By default only retrieves ACTILITY-owned
        profiles.
      operationId: retrieves-all-available-profiles-by-default-only-retrieves-actilityowned-profiles
      x-api-path-slug: profiles-get
      responses:
        200:
          description: OK
      tags:
      - Profiles
      - Retrieval
  /profiles/{profileId}:
    get:
      summary: Profile Retrieval
      description: Retrieves the profile corresponding to the provided profile Id.
      operationId: retrieves-the-profile-corresponding-to-the-provided-profile-id
      x-api-path-slug: profilesprofileid-get
      parameters:
      - in: path
        name: profileId
        description: Id of the profile to retrieve
      responses:
        200:
          description: OK
      tags:
      - Profile
      - Retrieval
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