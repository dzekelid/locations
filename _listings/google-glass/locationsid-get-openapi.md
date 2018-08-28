---
swagger: "2.0"
x-collection-name: Google Glass
x-complete: 0
info:
  title: Google Glass APIs Get Location
  description: Gets a single location by ID.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /mirror/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /locations:
    get:
      summary: Get Locations
      description: Retrieves a list of locations for the user.
      operationId: mirror.locations.list
      x-api-path-slug: locations-get
      responses:
        200:
          description: OK
      tags:
      - Location
  /locations/{id}:
    get:
      summary: Get Location
      description: Gets a single location by ID.
      operationId: mirror.locations.get
      x-api-path-slug: locationsid-get
      parameters:
      - in: path
        name: id
        description: The ID of the location or latest for the last known location
      responses:
        200:
          description: OK
      tags:
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