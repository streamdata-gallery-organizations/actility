{
  "info": {
    "name": "ThingPark DX Admin API Token Revocation",
    "_postman_id": "febbd515-9fee-40c9-9f3c-d69c3b5db485",
    "description": "Revokes a token.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Token",
      "item": [
        {
          "id": "a7abeb22-c817-478b-bf10-854b6e3b10cf",
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
              "id": "f9634c4f-990e-47ba-8055-ff7527cf2a53"
            }
          ]
        },
        {
          "id": "b7f2cfd2-eb2d-41cb-bd6e-d704cc109f9e",
          "name": "revokes-a-token",
          "request": {
            "url": "http://dx-api.thingpark.com/admin/v140/api/oauth/revoke_token?access_token=%7B%7D",
            "method": "POST",
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
            "description": "Revokes a token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d309b59e-f766-4cf2-8021-4c6c577b853b"
            }
          ]
        }
      ]
    }
  ]
}