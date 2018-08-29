{
  "info": {
    "name": "ThingPark DX Core API Suppliers retrieval",
    "_postman_id": "8d5c4c2e-ec7c-4b7b-b344-d36df8550c18",
    "description": "Retrieves a list of suppliers existing within authorized scopes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Suppliers",
      "item": [
        {
          "id": "aac4afb0-d00f-4d29-8e96-15deb113c246",
          "name": "retrieves-a-list-of-suppliers-existing-within-authorized-scopes",
          "request": {
            "url": "http://dx-api.thingpark.com/core/v141/api/suppliers?supplierId=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a list of suppliers existing within authorized scopes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cdedfefb-7fb6-4aed-a349-0f7f61c2c1f7"
            }
          ]
        }
      ]
    }
  ]
}