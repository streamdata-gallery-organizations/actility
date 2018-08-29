{
  "info": {
    "name": "ThingPark DX Admin API Token Info Retrieval",
    "_postman_id": "5ddc2d1a-d51f-4a1e-899f-1368af64f1e9",
    "description": "Retrieves information about a valid token.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Token",
      "item": [
        {
          "id": "4eb5b18b-a3bc-4acf-b100-c2d6d8e22f50",
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
              "id": "4bf8479a-62e3-49ce-97a8-f8b8d67a4a38"
            }
          ]
        },
        {
          "id": "a05d2bed-85dd-4f55-b807-ae11cd08c5ed",
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
              "id": "15c5c329-3a22-471a-b314-3aa1171061dc"
            }
          ]
        },
        {
          "id": "08325c58-d7af-42fb-9dce-0020458a23bf",
          "name": "retrieves-information-about-a-valid-token",
          "request": {
            "url": "http://dx-api.thingpark.com/admin/v140/api/oauth/tokeninfo?access_token=%7B%7D",
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
            "description": "Retrieves information about a valid token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f59e1ac1-8c28-40c9-a9f8-b7c8318ec089"
            }
          ]
        }
      ]
    }
  ]
}