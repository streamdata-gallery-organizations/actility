{
  "info": {
    "name": "ThingPark DX Admin API Profiles Retrieval",
    "_postman_id": "1cdfbae9-1cf7-4b64-b3dd-dda40e9f8235",
    "description": "Retrieves all available profiles. By default only retrieves ACTILITY-owned profiles.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Token",
      "item": [
        {
          "id": "01c45436-5a55-48c7-b26c-55461166b975",
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
              "id": "dd41302c-497d-4f7b-8126-fbe76acff135"
            }
          ]
        },
        {
          "id": "9ecdbe6b-bf5f-4cf4-b357-a10aa919159d",
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
              "id": "248139ab-8e3d-42f1-af38-5d2a6b07db63"
            }
          ]
        },
        {
          "id": "67fbe2f0-cb42-45f8-9cbb-7cf9009c09cb",
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
              "id": "31fb42e7-0e6c-44f3-95f8-c5a094b5dba7"
            }
          ]
        }
      ]
    },
    {
      "name": "Profiles",
      "item": [
        {
          "id": "e96a20e2-d3c7-4ef8-afd4-5d8727cbb4bf",
          "name": "retrieves-all-available-profiles-by-default-only-retrieves-actilityowned-profiles",
          "request": {
            "url": "http://dx-api.thingpark.com/admin/v140/api/profiles",
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
            "description": "Retrieves all available profiles. By default only retrieves ACTILITY-owned profiles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e57ebb0-3270-46db-a101-5fc6b5a9b949"
            }
          ]
        }
      ]
    }
  ]
}