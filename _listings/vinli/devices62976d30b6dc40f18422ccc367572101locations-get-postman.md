{
  "info": {
    "name": "Vinli Locations Request",
    "_postman_id": "22d1ed42-f5a2-4b7d-a44a-d9f9d9944e98",
    "description": "Locations request.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Locations",
      "item": [
        {
          "id": "3135b114-418f-4fb3-9e4a-c437465fa967",
          "name": "Devices62976d30B6dc40f18422Ccc367572101LocationsGet",
          "request": {
            "url": "http://events.vin.li/api/v1/devices/62976d30-b6dc-40f1-8422-ccc367572101/locations?fields=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Locations request."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84fbe6e3-0b3f-4b80-921f-e8800767348c"
            }
          ]
        }
      ]
    }
  ]
}