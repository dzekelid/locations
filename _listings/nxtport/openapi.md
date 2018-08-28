swagger: "2.0"
x-collection-name: NxtPort
x-complete: 1
info:
  title: Portcall+ API (sandbox)
  description: portplus-api
  version: 1.0.0
host: api-sb.nxtport.eu
basePath: /PortCallPlus/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/locations:
    get:
      summary: List
      description: List all Locations with their details. Locations have a type, name
        and the ISRS Locode.
      operationId: getApiV1Locations
      x-api-path-slug: apiv1locations-get
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      responses:
        200:
          description: OK
      tags:
      - List
    post:
      summary: Create
      description: Create a new Location
      operationId: postApiV1Locations
      x-api-path-slug: apiv1locations-post
      parameters:
      - in: query
        name: api_token
        description: authentication token of user making the request
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Create
  /locations:
    get:
      summary: Get Locations
      description: This api will return a (paged) list of locations that match the
        search parameters (query parameters) ordered by the name without diacritics.
      operationId: searchLocations
      x-api-path-slug: locations-get
      parameters:
      - in: query
        name: code
        description: 3-character location code
      - in: query
        name: country
        description: 2-character country code
      - in: query
        name: page
        description: the page number to allow paging (needs to be an integer > 0)
      - in: query
        name: searchterm
        description: Part of the name of the location without diacritics
      - in: query
        name: size
        description: the page size to allow paging (needs to be an integer 0 < pagesize
          < 1000)
      - in: query
        name: subdiv
        description: 3-character subdivision code
      responses:
        200:
          description: OK
      tags:
      - Locations
  /locations/{latitude}/{longitude}/{radius}:
    get:
      summary: Get Locations Latitude Longitude Radius
      description: This api will return locations in a certain radius of a point,
        ordered by distance , not necessarily in the same country
      operationId: locations_getinNeighbourhood
      x-api-path-slug: locationslatitudelongituderadius-get
      parameters:
      - in: path
        name: latitude
        description: the latitude of the specified point
      - in: path
        name: longitude
        description: the longitude of the specified point
      - in: query
        name: page
        description: the page number to allow paging (needs to be an integer > 0)
      - in: path
        name: radius
        description: the radius in km (max 75km)
      - in: query
        name: size
        description: the page size to allow paging (needs to be an integer 0 < pagesize
          < 1000)
      responses:
        200:
          description: OK
      tags:
      - Locations
      - Latitude
      - Longitude
      - Radius
  /locations/{locode}:
    get:
      summary: Get Locations Locode
      description: Get the details of 1 location based on the locode.
      operationId: locations_getByCountryAndLocode
      x-api-path-slug: locationslocode-get
      parameters:
      - in: path
        name: locode
        description: 5-character location code (country code + location code)
      responses:
        200:
          description: OK
      tags:
      - Locations
      - Locode