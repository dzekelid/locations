---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 1
info:
  title: Shopify API
  description: todo-add-description
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/locations/8790723.json:
    get:
      summary: Get a single location
      description: Get a single location.
      operationId: getAdminLocations8790723.json
      x-api-path-slug: adminlocations8790723-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Location
  /admin/locations.json:
    get:
      summary: Get a list of all locations for a shop
      description: Get a list of all locations for a shop.
      operationId: getAdminLocations.json
      x-api-path-slug: adminlocations-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Locationsa
      - Shop
---