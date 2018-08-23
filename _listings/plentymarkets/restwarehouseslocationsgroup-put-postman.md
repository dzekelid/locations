{
  "info": {
    "name": "Plentymarkets Edit the purpose and status for a group of storage locations",
    "_postman_id": "92647786-7c39-4604-8739-7f9d4daba6f2",
    "description": "Edits the purpose and status for a group of storage locations by passing the group storage location ID (can be sent as mass assignment)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "f3c9eb25-8e4c-45b4-8b99-e93403dcf366",
          "name": "getRestAccountingStoresLocations",
          "request": {
            "url": "http://example.com/rest/accounting/stores/locations",
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
            "description": "List all accounting locations."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ee95284-1071-4e9c-9edf-04bad90d9406"
            }
          ]
        },
        {
          "id": "d51ca991-4171-48de-b1b5-5f296e7e7666",
          "name": "getRestAccountingStoresPlentyLocations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/accounting/stores/:plentyId/locations"
              ],
              "query": [
                {
                  "key": "locationId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "plentyId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Lists accounting locations of a client. The plenty ID of the client must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e223c28b-de52-4848-8722-d48a53a102e2"
            }
          ]
        },
        {
          "id": "7c96f680-499b-44ee-8c20-680164ada1ae",
          "name": "getRestItemsVariationsVariationStockStoragelocations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/:id/variations/:variationId/stock/storageLocations"
              ],
              "query": [
                {
                  "key": "columns",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "itemId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "itemsPerPage",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "variationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Lists stock of a variation per storage location. The ID of the item and the ID of the variation must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06ea4c10-dbe7-41f1-bd98-ae039a0a0399"
            }
          ]
        },
        {
          "id": "805a1f03-a678-4595-9756-faf8023cedd9",
          "name": "getRestStockmanagementWarehousesWarehouseManagementRacksRackShelvesShelfStoragelocations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/stockmanagement/warehouses/:warehouseId/management/racks/:rackId/shelves/:shelfId/storageLocations"
              ],
              "query": [
                {
                  "key": "columns",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "itemsPerPage",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "rackId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "shelfId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "warehouseId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Lists storage locations. The id of the warehouse, the id of the rack and the id of the shelf must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2345d387-4d62-4427-904a-e0fcf7948efd"
            }
          ]
        },
        {
          "id": "2d4bed8e-acbe-48d2-8ee4-c179b8ad8f4b",
          "name": "getRestStockmanagementWarehousesWarehouseManagementStoragelocations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/stockmanagement/warehouses/:warehouseId/management/storageLocations"
              ],
              "query": [
                {
                  "key": "columns",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "itemsPerPage",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "with",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "warehouseId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Lists storage locations that belong to a warehouse. The id of the warehouse must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6cf60af-7c3f-46c2-a9c2-aecd1d0e4545"
            }
          ]
        }
      ]
    },
    {
      "name": "Multiple",
      "item": [
        {
          "id": "400b2817-d1b8-47a9-82d9-5ebc43d2ac22",
          "name": "deleteRestWarehousesLocations",
          "request": {
            "url": "http://example.com/rest/warehouses/locations",
            "method": "DELETE",
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
            "description": "Deletes multiple warehouse locations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af14ed72-469b-4603-943e-0fb1fa7bdb84"
            }
          ]
        }
      ]
    },
    {
      "name": "Edit",
      "item": [
        {
          "id": "85a1df96-dc8e-44b4-805c-11386b6076c0",
          "name": "putRestWarehousesLocationsGroup",
          "request": {
            "url": "http://example.com/rest/warehouses/locations/group",
            "method": "PUT",
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
            "description": "Edits the purpose and status for a group of storage locations by passing the group storage location ID (can be sent as mass assignment)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34631819-d7b2-4f53-823f-f1fb916e293c"
            }
          ]
        }
      ]
    }
  ]
}