{
  "info": {
    "name": "ThingPark DX Maker API Factory devices retrieval",
    "_postman_id": "d63e0a97-4050-4faa-820e-7be3d4faf06e",
    "description": "Retrieves all factory devices.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Factory",
      "item": [
        {
          "id": "31f94959-bd00-48c3-a0f4-157a29a8c833",
          "name": "retrieves-all-factory-devices",
          "request": {
            "url": "http://dx-api.thingpark.com/maker/v011/api/factoryDevices?deviceEUI=%7B%7D&pageIndex=%7B%7D",
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
            "description": "Retrieves all factory devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9167070c-cc28-4669-b10e-9062e283d322"
            }
          ]
        }
      ]
    }
  ]
}