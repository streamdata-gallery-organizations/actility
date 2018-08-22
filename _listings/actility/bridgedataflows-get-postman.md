{
  "info": {
    "name": "ThingPark DX Dataflow API Bridge dataflows retrieval",
    "_postman_id": "c2269c60-00f6-4825-96cd-3f0e18c14fd2",
    "description": "Retrieves the list of Bridge dataflows available in the scope.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Bridge",
      "item": [
        {
          "id": "2ce4064f-a910-409b-8ea5-ac5aa939628c",
          "name": "retrieves-the-list-of-bridge-dataflows-available-in-the-scope",
          "request": {
            "url": "http://dx-api.thingpark.com/dataflow/v021/api/bridgeDataflows",
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
            "description": "Retrieves the list of Bridge dataflows available in the scope."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "15aeae28-4397-4589-9d01-38244e1b0f77"
            }
          ]
        }
      ]
    }
  ]
}