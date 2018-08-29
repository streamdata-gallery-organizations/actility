---
name: Actility
x-slug: actility
description: 'Actility is the leader in low power wide area (LoRaWAN and 3GPP) network
  connectivity management for the Internet of Things: the ThingPark platform'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
x-kinRank: "7"
x-alexaRank: "637591"
tags: Actility
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/apis.md
specificationVersion: "0.14"
apis:
- name: ThingPark DX Admin API - Token Generation
  x-api-slug: oauthtoken-post
  description: Generates and retrieves a token for a client.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//admin/v140/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/oauthtoken-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/oauthtoken-post-openapi.md
- name: ThingPark DX Admin API - Token Revocation
  x-api-slug: oauthrevoke-token-post
  description: Revokes a token.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//admin/v140/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/oauthrevoke-token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/oauthrevoke-token-post-openapi.md
- name: ThingPark DX Admin API - Token Info Retrieval
  x-api-slug: oauthtokeninfo-get
  description: Retrieves information about a valid token.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//admin/v140/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/oauthtokeninfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/oauthtokeninfo-get-openapi.md
- name: ThingPark DX Admin API - Profiles Retrieval
  x-api-slug: profiles-get
  description: Retrieves all available profiles. By default only retrieves ACTILITY-owned
    profiles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//admin/v140/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/profiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/profiles-get-openapi.md
- name: ThingPark DX Admin API - Profile Retrieval
  x-api-slug: profilesprofileid-get
  description: Retrieves the profile corresponding to the provided profile Id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//admin/v140/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/profilesprofileid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/profilesprofileid-get-openapi.md
- name: ThingPark DX Core API - Suppliers retrieval
  x-api-slug: suppliers-get
  description: Retrieves a list of suppliers existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/suppliers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/suppliers-get-openapi.md
- name: ThingPark DX Core API - Supplier creation
  x-api-slug: suppliers-post
  description: Creates a new supplier with a primary user having all admin rights.
    Note that the supplier id can be chosen. If not fully specified, the supplier
    id and name attribute values are deduced from the primaryUser attribute values.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/suppliers-post-openapi.md
- name: ThingPark DX Core API - Supplier retrieval
  x-api-slug: supplierssupplierref-get
  description: Retrieves the supplier corresponding to the provided supplier ref,
    if that supplier is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/supplierssupplierref-get-openapi.md
- name: ThingPark DX Core API - Supplier update
  x-api-slug: supplierssupplierref-put
  description: Updates the supplier corresponding to the provided supplier ref, if
    that supplier is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/supplierssupplierref-put-openapi.md
- name: ThingPark DX Core API - Supplier deletion
  x-api-slug: supplierssupplierref-delete
  description: Deletes the supplier corresponding to the provided supplier ref, if
    that supplier is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/supplierssupplierref-delete-openapi.md
- name: ThingPark DX Core API - Vendors retrieval
  x-api-slug: vendors-get
  description: Retrieves a list of vendors existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/vendors-get-openapi.md
- name: ThingPark DX Core API - Vendor creation
  x-api-slug: vendors-post
  description: Creates a new vendor with a primary user having all admin rights. Note
    that the vendor id can be chosen. If not fully specified, the vendor id and name
    attribute values are deduced from the primaryUser attribute values.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/vendors-post-openapi.md
- name: ThingPark DX Core API - Vendor retrieval
  x-api-slug: vendorsvendorref-get
  description: Retrieves the vendor corresponding to the provided vendor ref, if that
    vendor is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/vendorsvendorref-get-openapi.md
- name: ThingPark DX Core API - Vendor update
  x-api-slug: vendorsvendorref-put
  description: Updates the vendor corresponding to the provided vendor ref, if that
    vendor is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/vendorsvendorref-put-openapi.md
- name: ThingPark DX Core API - Vendor deletion
  x-api-slug: vendorsvendorref-delete
  description: Deletes the vendor corresponding to the provided vendor ref, if that
    vendor is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/vendorsvendorref-delete-openapi.md
- name: ThingPark DX Core API - Subscribers retrieval
  x-api-slug: subscribers-get
  description: Retrieves a list of subscribers existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/subscribers-get-openapi.md
- name: ThingPark DX Core API - Subscriber creation
  x-api-slug: subscribers-post
  description: Creates a new subscriber. If not fully specified, the subscriber name,
    contactEmail and organization attribute values are deduced from the primaryUser
    attribute values.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/subscribers-post-openapi.md
- name: ThingPark DX Core API - Subscriber retrieval
  x-api-slug: subscriberssubscriberref-get
  description: Retrieves the subscriber corresponding to the provided subscriber ref,
    if that subscriber is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/subscriberssubscriberref-get-openapi.md
- name: ThingPark DX Core API - Subscriber update
  x-api-slug: subscriberssubscriberref-put
  description: Updates the subscriber corresponding to the provided subscriber ref,
    if that subscriber is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/subscriberssubscriberref-put-openapi.md
- name: ThingPark DX Core API - Subscriber deletion
  x-api-slug: subscriberssubscriberref-delete
  description: Deletes the subscriber corresponding to the provided subscriber ref,
    if that subscriber is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/subscriberssubscriberref-delete-openapi.md
- name: ThingPark DX Core API - Users retrieval
  x-api-slug: users-get
  description: Retrieves a list of users existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/users-get-openapi.md
- name: ThingPark DX Core API - User creation
  x-api-slug: users-post
  description: Creates a new user. Enclosing party depends on authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/users-post-openapi.md
- name: ThingPark DX Core API - User retrieval
  x-api-slug: usersuserref-get
  description: Retrieves the user corresponding to the provided user ref, if that
    user is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/usersuserref-get-openapi.md
- name: ThingPark DX Core API - User update
  x-api-slug: usersuserref-put
  description: Updates the user corresponding to the provided user ref, if that user
    is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/usersuserref-put-openapi.md
- name: ThingPark DX Core API - User deletion
  x-api-slug: usersuserref-delete
  description: Deletes the user corresponding to the provided user ref, if that user
    is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/usersuserref-delete-openapi.md
- name: ThingPark DX Core API - Offers retrieval
  x-api-slug: offers-get
  description: Retrieves a list of offers existing within authorized scopes. In case
    of a vendor scope, it retrieves all offers of that vendor. In case of a subscriber
    scope, it retrieves all offers subscribed by that subscriber.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/offers-get-openapi.md
- name: ThingPark DX Core API - Offers creation
  x-api-slug: offers-post
  description: Creates a new offer. if not specified, 'state' is automatically set
    to 'ACTIVE'. Note that the offer id MUST start with the vendor id followed by
    a slash (e.g. 'vendor-id/offer-id').
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/offers-post-openapi.md
- name: ThingPark DX Core API - Offer retrieval
  x-api-slug: offersofferref-get
  description: Retrieves the offer corresponding to the provided offer ref, if that
    offer is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/offersofferref-get-openapi.md
- name: ThingPark DX Core API - Offer update
  x-api-slug: offersofferref-put
  description: Updates the offer corresponding to the provided offer ref, if that
    offer is within authorized scopes. Only 'name' and 'state' attributes can be updated.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/offersofferref-put-openapi.md
- name: ThingPark DX Core API - Offer deletion
  x-api-slug: offersofferref-delete
  description: Deletes the offer corresponding to the provided offer ref, if that
    offer is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/offersofferref-delete-openapi.md
- name: ThingPark DX Core API - Orders retrieval
  x-api-slug: orders-get
  description: Retrieves a list of orders existing within authorized scopes. In case
    of a vendor scope, it retrieves all orders allowed by that vendor. In case of
    a subscriber scope, it retrieves all orders performed by that subscriber.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/orders-get-openapi.md
- name: ThingPark DX Core API - Order creation
  x-api-slug: orders-post
  description: Creates an order, i.e. creates a subscription to a predefined offer
    for an existing subscriber.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/orders-post-openapi.md
- name: ThingPark DX Core API - Order retrieval
  x-api-slug: ordersorderref-get
  description: Retrieves the order corresponding to the provided order ref, if that
    order is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/ordersorderref-get-openapi.md
- name: ThingPark DX Core API - Order cancellation
  x-api-slug: ordersorderref-delete
  description: Cancels all subscriptions related to the provided order ref, if that
    order is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/ordersorderref-delete-openapi.md
- name: ThingPark DX Core API - Applications retrieval
  x-api-slug: applications-get
  description: Retrieves a list of applications existing within authorized scopes.
    In case of an operator or a vendor scope, it retrieves all applications available.
    In case of a subscriber scope, it retrieves all applications within subscribed
    offers. In case of a supplier scope, it retrieves all applications provided by
    that supplier.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/applications-get-openapi.md
- name: ThingPark DX Core API - Access code generation
  x-api-slug: accesscodes-post
  description: Generates a new access code. If it is of type 'userAccessCode', the
    provided userId must reference an user within authorized scopes. This access code
    can then be used to access the targetted application without re-typing credentials
    (ThingPark SSO). In order to do so, the code needs to be appended to the application
    portal URL, i.e. 'portalUrl?userAccessCode=code'.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/accesscodes-post-openapi.md
- name: ThingPark DX Core API - Access code validation
  x-api-slug: accesscodes-get
  description: Validates the access code value and retrieves extended access code
    information such as user information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/accesscodes-get-openapi.md
- name: ThingPark DX Core API - Devices retrieval
  x-api-slug: devices-get
  description: 'Retrieves a list of devices existing within authorized scopes. Note
    that for each device, by default only the following information is retrieved:
    ''ref'', ''name'', ''EUI'', ''networkAddress''.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devices-get-openapi.md
- name: ThingPark DX Core API - Device creation
  x-api-slug: devices-post
  description: Creates a new device. If no 'routingProfileId' or 'processingStrategyId'
    values are provided, then 'processingStrategyId' will be automatically set to
    'DATAFLOW'. If no 'connectivityPlanId' value is provided, then the first connectivity
    plan of the subscriber with available connections will be assigned to the device.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devices-post-openapi.md
- name: ThingPark DX Core API - Device retrieval
  x-api-slug: devicesdeviceref-get
  description: Retrieves the device corresponding to the provided device ref, if that
    device is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicesdeviceref-get-openapi.md
- name: ThingPark DX Core API - Device update
  x-api-slug: devicesdeviceref-put
  description: 'Updates the device corresponding to the provided device ref, if that
    device is within authorized scopes. Only following attributes can be updated:
    ''name'', ''routingProfileId'', ''processingStrategyId'', ''connectivityPlanId'',
    ''deviceProfileId'' and ''applicationEUI''. To update other attributes, device
    must be deleted than re-created.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicesdeviceref-put-openapi.md
- name: ThingPark DX Core API - Device deletion
  x-api-slug: devicesdeviceref-delete
  description: Deletes the device corresponding to the provided device ref, if that
    device is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicesdeviceref-delete-openapi.md
- name: ThingPark DX Core API - Device profiles retrieval
  x-api-slug: deviceprofiles-get
  description: Retrieves the list of existing device profiles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/deviceprofiles-get-openapi.md
- name: ThingPark DX Core API - Connectivity plans retrieval
  x-api-slug: connectivityplans-get
  description: Retrieves a list of connectivity plans existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/connectivityplans-get-openapi.md
- name: ThingPark DX Core API - Routing profiles retrieval
  x-api-slug: routingprofiles-get
  description: Retrieves a list of existing routing profiles within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/routingprofiles-get-openapi.md
- name: ThingPark DX Core API - Routing profiles creation
  x-api-slug: routingprofiles-post
  description: Creates a new routing profile.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/routingprofiles-post-openapi.md
- name: ThingPark DX Core API - Routing profile retrieval
  x-api-slug: routingprofilesroutingprofileref-get
  description: Retrieves the routing profile corresponding to the provided routing
    profile ref, if that routing profile is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/routingprofilesroutingprofileref-get-openapi.md
- name: ThingPark DX Core API - Routing profile update
  x-api-slug: routingprofilesroutingprofileref-put
  description: Updates the routing profile corresponding to the provided routing profile
    ref, if that routing profile is within authorized scopes. Note that the 'default'
    attribute can only be updated from 'false' to 'true' (thus updating 'default'
    attribute for the previous default routing profile from 'true' to 'false').
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/routingprofilesroutingprofileref-put-openapi.md
- name: ThingPark DX Core API - Routing profile deletion
  x-api-slug: routingprofilesroutingprofileref-delete
  description: Deletes the routing profile corresponding to the provided routing profile
    ref, if that routing profile is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/routingprofilesroutingprofileref-delete-openapi.md
- name: ThingPark DX Core API - Frame statistics retrieval
  x-api-slug: deviceframestatistics-get
  description: Retrieves frame statistics of the devices corresponding to the provided
    parameters, if those devices are within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/deviceframestatistics-get-openapi.md
- name: ThingPark DX Core API - Health statistics retrieval
  x-api-slug: devicehealthstatistics-get
  description: Retrieves health statistics for all devices within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicehealthstatistics-get-openapi.md
- name: ThingPark DX Core API - AS key retrieval
  x-api-slug: askeys-get
  description: Retrieves a list of AS keys existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeys-get-openapi.md
- name: ThingPark DX Core API - AS key creation
  x-api-slug: askeys-post
  description: Creates a new AS key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeys-post-openapi.md
- name: ThingPark DX Core API - AS key retrieval
  x-api-slug: askeysaskeyref-get
  description: Retrieves the AS key corresponding to the provided AS key ref, if that
    AS key is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeysaskeyref-get-openapi.md
- name: ThingPark DX Core API - AS key update
  x-api-slug: askeysaskeyref-put
  description: Updates the AS key corresponding to the provided asKey ref, if that
    AS key is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeysaskeyref-put-openapi.md
- name: ThingPark DX Core API - AS key deletion
  x-api-slug: askeysaskeyref-delete
  description: Deletes the AS key corresponding to the provided asKeyRef, if that
    AS key is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeysaskeyref-delete-openapi.md
- name: ThingPark DX Core API - HSM groups retrieval
  x-api-slug: hsmgroups-get
  description: Retrieves a list of HSM groups existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/hsmgroups-get-openapi.md
- name: ThingPark DX Core API - Base stations retrieval
  x-api-slug: basestations-get
  description: Retrieves a list of base stations existing within authorized scopes.
    Note that in case of an OPERATOR scope, only supplier-owned base stations are
    returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestations-get-openapi.md
- name: ThingPark DX Core API - Base stations creation
  x-api-slug: basestations-post
  description: Creates a new base station.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestations-post-openapi.md
- name: ThingPark DX Core API - Base station retrieval
  x-api-slug: basestationsbasestationref-get
  description: Retrieves the base station corresponding to the provided base station
    ref, if that base station is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationsbasestationref-get-openapi.md
- name: ThingPark DX Core API - Base station update
  x-api-slug: basestationsbasestationref-put
  description: Updates the base station corresponding to the provided base station
    ref, if that base station is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationsbasestationref-put-openapi.md
- name: ThingPark DX Core API - Base station deletion
  x-api-slug: basestationsbasestationref-delete
  description: Deletes the base station corresponding to the provided base station
    ref, if that base station is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationsbasestationref-delete-openapi.md
- name: ThingPark DX Core API - Base station profiles retrieval
  x-api-slug: basestationprofiles-get
  description: Retrieves the list of existing base station profiles.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationprofiles-get-openapi.md
- name: ThingPark DX Core API - Frame statistics retrieval
  x-api-slug: basestationframestatistics-get
  description: Retrieves frame statistics of the base stations corresponding to the
    provided parameters, if those base stations are within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationframestatistics-get-openapi.md
- name: ThingPark DX Core API - Health statistics retrieval
  x-api-slug: basestationhealthstatistics-get
  description: Retrieves health statistics for all base stations within authorized
    scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationhealthstatistics-get-openapi.md
- name: ThingPark DX Core API - Signal statistics retrieval
  x-api-slug: basestationsbasestationrefchannelschannelnamesignalstatistics-get
  description: Retrieves signal statistics (RSSI and SNR metrics) for a specific channel
    of the base station corresponding to the provided base station ref, if that base
    station is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationsbasestationrefchannelschannelnamesignalstatistics-get-openapi.md
- name: ThingPark DX Core API - Duty cycle statistics retrieval
  x-api-slug: basestationsbasestationrefchannelschannelnamedutycyclestatistics-get
  description: Retrieves duty cycle statistics for a specific channel of the base
    station corresponding to the provided base station ref, if that base station is
    within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationsbasestationrefchannelschannelnamedutycyclestatistics-get-openapi.md
- name: ThingPark DX Core API - LRC packet statistics retrieval
  x-api-slug: basestationsbasestationreflrcpacketstatistics-get
  description: Retrieves packets statistics between the LRC and the base station corresponding
    to the provided base station ref, if that base station is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationsbasestationreflrcpacketstatistics-get-openapi.md
- name: ThingPark DX Core API - ISM Bands retrieval
  x-api-slug: ismbands-get
  description: Retrieves a list of ISM Bands existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/ismbands-get-openapi.md
- name: ThingPark DX Core API - Device alarms retrieval
  x-api-slug: devicealarms-get
  description: Retrieves a list of device alarms existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicealarms-get-openapi.md
- name: ThingPark DX Core API - Device alarm retrieval
  x-api-slug: devicealarmsdevicealarmref-get
  description: Retrieves the device alarm corresponding to the provided device alarm
    ref, if that device alarm is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicealarmsdevicealarmref-get-openapi.md
- name: ThingPark DX Core API - Device alarm acknowledgement
  x-api-slug: devicealarmsdevicealarmrefacks-post
  description: Acknowledges a device alarm.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicealarmsdevicealarmrefacks-post-openapi.md
- name: ThingPark DX Core API - Base station alarms retrieval
  x-api-slug: basestationalarms-get
  description: Retrieves a list of base station alarms existing within authorized
    scopes. Note that in case of an OPERATOR scope, only supplier-owned base station
    alarms are returned.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationalarms-get-openapi.md
- name: ThingPark DX Core API - Base station alarm retrieval
  x-api-slug: basestationalarmsbasestationalarmref-get
  description: Retrieves the base station alarm corresponding to the provided base
    station alarm ref, if that base station alarm is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationalarmsbasestationalarmref-get-openapi.md
- name: ThingPark DX Core API - Base station alarm acknowledgement
  x-api-slug: basestationalarmsbasestationalarmrefacks-post
  description: Acknowledges a base station alarm.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/basestationalarmsbasestationalarmrefacks-post-openapi.md
- name: ThingPark DX Core API - Downlink message sending
  x-api-slug: devicesdevicedownlinkmessages-post
  description: Sends a new downlink message to the device, if that device is within
    authorized scopes. The message is queued in the LRC until the device is able to
    retrieve it (depending on its configured class).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//core/v141/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/devicesdevicedownlinkmessages-post-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflows retrieval
  x-api-slug: bridgedataflows-get
  description: Retrieves the list of Bridge dataflows available in the scope.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/bridgedataflows-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/bridgedataflows-get-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflow creation
  x-api-slug: bridgedataflows-post
  description: Creates a new Bridge dataflow.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/bridgedataflows-post-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflow retrieval
  x-api-slug: bridgedataflowsbridgedataflowref-get
  description: Retrieves the Bridge dataflow corresponding to the provided order ref,
    if that order is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/bridgedataflowsbridgedataflowref-get-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflow update
  x-api-slug: bridgedataflowsbridgedataflowref-put
  description: Updates the Bridge dataflow corresponding to the provided Bridge dataflow
    ref, if that dataflow is within authorized scopes. Note that when updating a dataflow,
    all existing attributs must be provided next to your changes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/bridgedataflowsbridgedataflowref-put-openapi.md
- name: ThingPark DX Dataflow API - Bridge dataflow deletion
  x-api-slug: bridgedataflowsbridgedataflowref-delete
  description: Deletes the Bridge dataflow corresponding to the provided Bridge dataflow
    ref, if that dataflow is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/bridgedataflowsbridgedataflowref-delete-openapi.md
- name: ThingPark DX Dataflow API - Constant maps retrieval
  x-api-slug: constantmaps-get
  description: Retrieves the list of constant maps (both system-provided and custom)
    available in the scope.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/constantmaps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/constantmaps-get-openapi.md
- name: ThingPark DX Dataflow API - Constant maps creation
  x-api-slug: constantmaps-post
  description: Creates a new custom constant map for the subscriber.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/constantmaps-post-openapi.md
- name: ThingPark DX Dataflow API - Constant map retrieval
  x-api-slug: constantmapsconstantmapref-get
  description: Retrieves the constant map corresponding to the provided constant map
    ref..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/constantmapsconstantmapref-get-openapi.md
- name: ThingPark DX Dataflow API - Constant map update
  x-api-slug: constantmapsconstantmapref-put
  description: Updates the constant map corresponding to the provided constant map
    ref. This is only authorized if the constant map has been created by the subscriber
    (not provided by the system).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/constantmapsconstantmapref-put-openapi.md
- name: ThingPark DX Dataflow API - Constant map deletion
  x-api-slug: constantmapsconstantmapref-delete
  description: Deletes the constant map corresponding to the provided constant map
    ref. This is only authorized if the constant map has been created by the subscriber
    (not provided by the system).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/constantmapsconstantmapref-delete-openapi.md
- name: ThingPark DX Dataflow API - Binder processor classes retrieval
  x-api-slug: binderclasses-get
  description: Retrieves the list of system-wide processor classes providing binder
    (e.g. with a device) behaviour.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/binderclasses-get-openapi.md
- name: ThingPark DX Dataflow API - Driver processor classes retrieval
  x-api-slug: driverclasses-get
  description: Retrieves the list of system-wide processor classes providing driver
    behaviour.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/driverclasses-get-openapi.md
- name: ThingPark DX Dataflow API - Connector processor classes retrieval
  x-api-slug: connectorclasses-get
  description: Retrieves the list of system-wide processor classes providing connector
    behaviour.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/connectorclasses-get-openapi.md
- name: ThingPark DX Dataflow API - Dataflow events retrieval
  x-api-slug: events-get
  description: Retrieves the list of events for all configured dataflows in scope.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/events-get-openapi.md
- name: ThingPark DX Dataflow API - Uplink data reception
  x-api-slug: uplinkmessages-post
  description: Endpoint to be used by the LRC to push uplink data in order to use
    ThingPark X dataflows.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//dataflow/v021/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/uplinkmessages-post-openapi.md
- name: ThingPark DX Location API - Feed request
  x-api-slug: feeds-post
  description: Feeds the platform with geolocation data. Data is then dispatched and
    processed based on available information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//location/v110
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/feeds-post-openapi.md
- name: ThingPark DX Location API - Module configurations retrieval
  x-api-slug: moduleconfigs-get
  description: Retrieves the list of existing module configurations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//location/v110
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/moduleconfigs-get-openapi.md
- name: ThingPark DX Location API - Module configuration creation
  x-api-slug: moduleconfigs-post
  description: Creates a new module configuration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//location/v110
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/moduleconfigs-post-openapi.md
- name: ThingPark DX Location API - Module configuration retrieval
  x-api-slug: moduleconfigsmoduleconfigref-get
  description: Retrieves the module configuration corresponding to the provided ref.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//location/v110
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/moduleconfigsmoduleconfigref-get-openapi.md
- name: ThingPark DX Location API - Module configuration update
  x-api-slug: moduleconfigsmoduleconfigref-put
  description: Updates the module configuration corresponding to the provided ref.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//location/v110
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/moduleconfigsmoduleconfigref-put-openapi.md
- name: ThingPark DX Location API - Module configuration deletion
  x-api-slug: moduleconfigsmoduleconfigref-delete
  description: Deletes the module configuration corresponding to the provided ref.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//location/v110
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/moduleconfigsmoduleconfigref-delete-openapi.md
- name: ThingPark DX Location API - Tracker command sending
  x-api-slug: trackercommands-post
  description: Sends a downlink command to a supported Abeeway tracker.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//location/v110
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/trackercommands-post-openapi.md
- name: ThingPark DX Maker API - Factory devices retrieval
  x-api-slug: factorydevices-get
  description: Retrieves all factory devices.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/factorydevices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/factorydevices-get-openapi.md
- name: ThingPark DX Maker API - Factory device creation
  x-api-slug: factorydevices-post
  description: Creates a factory device.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/factorydevices-post-openapi.md
- name: ThingPark DX Maker API - Factory device retrieval
  x-api-slug: factorydevicesfactorydeviceref-get
  description: Retrieves the factory device corresponding to the provided factoryDeviceRef.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/factorydevicesfactorydeviceref-get-openapi.md
- name: ThingPark DX Maker API - Factory device update
  x-api-slug: factorydevicesfactorydeviceref-put
  description: Updates the factory device corresponding to the provided factoryDeviceRef.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/factorydevicesfactorydeviceref-put-openapi.md
- name: ThingPark DX Maker API - Factory device deletion
  x-api-slug: factorydevicesfactorydeviceref-delete
  description: Deletes the factory device corresponding to the provided factoryDeviceRef.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/factorydevicesfactorydeviceref-delete-openapi.md
- name: ThingPark DX Maker API - AppKey generation
  x-api-slug: appkeygens-post
  description: Generate some encrypted VendorKeys with an HSM. Encrypted VendorKeys
    can be decrypted with the private part of provided RSA key. A VendorKey is a concatenation
    of an AppKey (128 bits) and hsmEncryptedAppKey (128 bits).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/appkeygens-post-openapi.md
- name: ThingPark DX Maker API - AS keys retrieval
  x-api-slug: askeys-get
  description: Retrieves the list of AS keys existing within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeys-get-openapi.md
- name: ThingPark DX Maker API - AS key creation
  x-api-slug: askeys-post
  description: Creates a new AS key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeys-post-openapi.md
- name: ThingPark DX Maker API - AS key retrieval
  x-api-slug: askeysaskeyref-get
  description: Retrieves the AS key corresponding to the provided AS key ref, if that
    AS key is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeysaskeyref-get-openapi.md
- name: ThingPark DX Maker API - AS key update
  x-api-slug: askeysaskeyref-put
  description: Updates the AS key corresponding to the provided asKey ref, if that
    AS key is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeysaskeyref-put-openapi.md
- name: ThingPark DX Maker API - AS key deletion
  x-api-slug: askeysaskeyref-delete
  description: Deletes the AS key corresponding to the provided asKeyRef, if that
    AS key is within authorized scopes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/askeysaskeyref-delete-openapi.md
- name: ThingPark DX Maker API - HSM groups retrieval
  x-api-slug: hsmgroups-get
  description: Retrieves all HSM groups.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28250-actility.jpg
  humanURL: https://www.actility.com
  baseURL: https://dx-api.thingpark.com//maker/v011/api
  tags: Technology, SaaS, Enterprise, ISP, Telecommunications, Internet of Things,
    API Provider, Parking, Sensors, Energy, Industrial, Profiles, Relative Data, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/actility/master/_listings/actility/hsmgroups-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.actility.com/blog/feed/
- type: x-github
  url: https://github.com/actility
- type: x-openapi
  url: https://dx-api.thingpark.com/core/latest/tpdx-core-api-contract.json
- type: x-api-gallery
  url: http://actility.api.gallery.streamdata.io
- type: x-api-stack
  url: http://actility.stack.network
- type: x-blog
  url: https://www.actility.com/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/actility
- type: x-developer
  url: https://www.actility.com/developer/
- type: x-twitter
  url: https://twitter.com/Actility
- type: x-website
  url: https://www.actility.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---