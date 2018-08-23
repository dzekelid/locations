---
swagger: "2.0"
x-collection-name: OnSched
x-complete: 0
info:
  title: OnSched Returns a list of business locations.
  description: "Use this api end point if you have multiple business locations in
    your company.\r\nThe results are returned in pages. Use the offset and limit parameters
    to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
    the other query parameters to optionally filter the results list."
  termsOfService: None
  contact:
    name: OnSched.com
    url: https://onsched.com
    email: info@onsched.com
  version: 1.0.0
host: api.onsched.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /consumer/v1/locations:
    get:
      summary: Returns a list of business locations.
      description: "Use this api end point if you have multiple business locations
        in your company.\r\nThe results are returned in pages. Use the offset and
        limit parameters to control the page start and size. Default offset is 0,
        and limit is 20.\r\nUse the other query parameters to optionally filter the
        results list."
      operationId: ConsumerV1LocationsGet
      x-api-path-slug: consumerv1locations-get
      parameters:
      - in: query
        name: limit
        description: Page limit, default 20
      - in: query
        name: name
        description: Location name(full or partial) to filter on
      - in: query
        name: offset
        description: Starting row of page, default 0
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