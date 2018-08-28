{
  "info": {
    "name": "Dezrez Gets a location",
    "_postman_id": "e2b98884-7a83-4398-8aff-8afbf6812b44",
    "description": "Gets a location.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Historical",
      "item": [
        {
          "id": "b417d35f-8a1b-4622-99d2-c26d96222767",
          "name": "HistoricalPrice_GetWithinRadiusOfLocationBypropertyIdBylatitudeBylongitudeBymileRadiusBypropertyType",
          "request": {
            "url": "http://api.dezrez.com/api/property/historicalprices/radius?latitude=%7B%7D&leaseType=%7B%7D&longitude=%7B%7D&mileRadius=%7B%7D&pageNumber=%7B%7D&pageSize=%7B%7D&propertyId=%7B%7D&propertyType=%7B%7D&styleType=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get historical prices within a radius of a location."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f634acda-0601-489f-a42c-6d266b4c4152"
            }
          ]
        }
      ]
    },
    {
      "name": "S",
      "item": [
        {
          "id": "b82bd405-85c8-4dc7-80c9-a083a9b6625d",
          "name": "Location_GetByidBytypeBysource",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/location/:id"
              ],
              "query": [
                {
                  "key": "source",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "type",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a location."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "601e0d1b-0630-43c4-83e6-bd10cf7394fa"
            }
          ]
        }
      ]
    }
  ]
}