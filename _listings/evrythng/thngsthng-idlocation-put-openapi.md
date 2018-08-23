---
swagger: "2.0"
x-collection-name: EVRYTHNG
x-complete: 0
info:
  title: EVRYTHNG /thngs/{id}/location (U)
  description: USER updates the location of a thng.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /thngs/{THNG_ID}/location:
    put:
      summary: /thngs/{id}/location (U)
      description: USER updates the location of a thng.
      operationId: ThngsLocationByTHNGIDPut
      x-api-path-slug: thngsthng-idlocation-put
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: THNG_ID
      responses:
        200:
          description: OK
      tags:
      - Thngs
      - THNG
      - ID
      - Location
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