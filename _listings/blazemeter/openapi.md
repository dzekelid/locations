---
swagger: "2.0"
x-collection-name: BlazeMeter
x-complete: 1
info:
  title: Blazemeter API Explorer
  description: live-api-documentation
  version: 1.0.0
host: a.blazemeter.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /user/locations:
    get:
      summary: Get User Locations
      description: Get user locations.
      operationId: retrieveLocations
      x-api-path-slug: userlocations-get
      responses:
        200:
          description: OK
      tags:
      - Monitoring
      - User
      - Locations
---