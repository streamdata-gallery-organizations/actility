{
  "info": {
    "name": "ThingPark DX Admin API Token Generation",
    "_postman_id": "12e89d59-a68a-4afb-8358-ef50fe1bbf62",
    "description": "Generates and retrieves a token for a client.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Token",
      "item": [
        {
          "id": "946b8f1f-0908-4775-8906-56e9a06cb5d8",
          "name": "generates-and-retrieves-a-token-for-a-client",
          "request": {
            "url": "http://dx-api.thingpark.com/admin/v140/api/oauth/token?renewToken=%7B%7D&validityPeriod=%7B%7D",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "client_id",
                  "value": "{}",
                  "disabled": false,
                  "description": "Id of the client"
                },
                {
                  "key": "client_secret",
                  "value": "{}",
                  "disabled": false,
                  "description": "Secret of the client"
                },
                {
                  "key": "grant_type",
                  "value": "{}",
                  "disabled": false,
                  "description": "Type of the OAuth2 grant workflow"
                }
              ]
            },
            "description": "Generates and retrieves a token for a client."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66f03a7e-0b74-4183-8684-0f64a022b138"
            }
          ]
        }
      ]
    }
  ]
}