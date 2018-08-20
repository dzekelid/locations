---
swagger: "2.0"
x-collection-name: FullContact
x-complete: 1
info:
  title: FullContact Location API
  description: the-api-for-managing-fullcontact-locations
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
---