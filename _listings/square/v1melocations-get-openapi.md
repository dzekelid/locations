---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Provides details for a business's locations, including
    their IDs.
  description: Provides details for a business's locations, including their IDs.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/me/locations:
    get:
      summary: Provides details for a business's locations, including their IDs.
      description: Provides details for a business's locations, including their IDs.
      operationId: v1.me.locations.get
      x-api-path-slug: v1melocations-get
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Businesss
      - Locations
      - ""
      - Including
      - Their
      - IDs
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---