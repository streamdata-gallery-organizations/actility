{
  "info": {
    "name": "ThingPark DX Dataflow API Constant maps retrieval",
    "_postman_id": "b3f6f13e-766e-4076-b402-69827864d70f",
    "description": "Retrieves the list of constant maps (both system-provided and custom) available in the scope.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Constant",
      "item": [
        {
          "id": "a9655600-025d-49fd-bae5-1fe2ec270510",
          "name": "retrieves-the-list-of-constant-maps-both-systemprovided-and-custom-available-in-the-scope",
          "request": {
            "url": "http://dx-api.thingpark.com/dataflow/v021/api/constantMaps",
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
            "description": "Retrieves the list of constant maps (both system-provided and custom) available in the scope."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "22f3b06c-74ec-40a0-b40b-b3602cd012eb"
            }
          ]
        }
      ]
    }
  ]
}