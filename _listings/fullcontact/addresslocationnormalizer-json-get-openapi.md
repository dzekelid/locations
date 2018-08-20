---
swagger: "2.0"
x-collection-name: FullContact
x-complete: 0
info:
  title: FullContact Location Normalization
  description: The Location Normalization method takes semi-structured location data
    via the place parameter, provided as a string, and returns structured location
    data in either JSON or XML format.
  termsOfService: https://www.fullcontact.com/terms/
  version: 1.0.0
host: api.fullcontact.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /address/locationNormalizer.json:
    get:
      summary: Location Normalization
      description: The Location Normalization method takes semi-structured location
        data via the place parameter, provided as a string, and returns structured
        location data in either JSON or XML format.
      operationId: normalizeLocation
      x-api-path-slug: addresslocationnormalizer-json-get
      parameters:
      - in: query
        name: apiKey
        description: This API key is assigned to you by FullContact
      - in: query
        name: casing
        description: Uppercase, lowercase, title case
      - in: query
        name: includeZeroPopulation
        description: Appending includeZeroPopulation=true, will display 0 population
          census locations
      - in: query
        name: place
        description: The place parameter allows you to pass a semi-structured location
          string which can include continent, country, state, city, or county
      responses:
        200:
          description: OK
      tags:
      - Address
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