{
  "info": {
    "name": "Shopify Get a single location",
    "_postman_id": "ab0610de-a3ac-4687-b9d1-81f5a0d376fc",
    "description": "Get a single location.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Commerce",
      "item": [
        {
          "id": "f07a79d7-6d0b-47d3-a360-76d51be9bc69",
          "name": "getAdminLocations8790723.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/locations/8790723.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
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
            "description": "Get a single location."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1ead109-da95-4bb6-9503-4ee571c733d4"
            }
          ]
        },
        {
          "id": "089f7aa7-6b80-435d-b290-6a51368e083d",
          "name": "getAdminLocations.json",
          "request": {
            "url": "http://DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com/admin/locations.json",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
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
            "description": "Get a list of all locations for a shop."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b881cb05-784d-4002-9d32-d4c9eefca159"
            }
          ]
        }
      ]
    }
  ]
}