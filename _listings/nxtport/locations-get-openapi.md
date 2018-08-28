---
swagger: "2.0"
x-collection-name: NxtPort
x-complete: 0
info:
  title: NxtPort UN Location Codes API Get Locations
  description: This api will return a (paged) list of locations that match the search
    parameters (query parameters) ordered by the name without diacritics.
  version: 1.0.0
host: api.nxtport.eu
basePath: /unlocodes/v1
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---