---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 1
info:
  title: Dezrez.Rezi.Client.Api
  version: 1.0.0
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/property/historicalprices/radius:
    get:
      summary: Get historical prices within a radius of a location
      description: Get historical prices within a radius of a location.
      operationId: HistoricalPrice_GetWithinRadiusOfLocationBypropertyIdBylatitudeBylongitudeBymileRadiusBypropertyType
      x-api-path-slug: apipropertyhistoricalpricesradius-get
      parameters:
      - in: query
        name: latitude
        description: The latitude to search from
      - in: query
        name: leaseType
        description: 'Options are: Freehold, Leasehold'
      - in: query
        name: longitude
        description: The longitude to search from
      - in: query
        name: mileRadius
        description: The radius from the latitude/longitude in miles to search
      - in: query
        name: pageNumber
      - in: query
        name: pageSize
      - in: query
        name: propertyId
        description: The Id of the property whose location will be searched from
      - in: query
        name: propertyType
        description: 'Options are: DetachedHouse, SemiDetachedHouse, TerracedHouse,
          Flat'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: styleType
        description: 'Options are: New, Older'
      responses:
        200:
          description: OK
      tags:
      - Historical
      - Prices
      - Within
      - Radius
      - Of
      - Location
  /api/location/{id}:
    get:
      summary: Gets a location
      description: Gets a location.
      operationId: Location_GetByidBytypeBysource
      x-api-path-slug: apilocationid-get
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: source
      - in: query
        name: type
      responses:
        200:
          description: OK
      tags:
      - S
      - Location
  /api/location/tag/match:
    post:
      summary: Saves a tag to location match
      description: Saves a tag to location match.
      operationId: Location_ProcessTagLocationMatchesBycommands
      x-api-path-slug: apilocationtagmatch-post
      parameters:
      - in: body
        name: commands
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Saves
      - Tag
      - To
      - Location
      - Match
---