swagger: "2.0"
x-collection-name: Amadeus
x-complete: 1
info:
  title: Amadeus
  description: amadeus-api-is-a-toolkit-designed-for-travel-agencies-who-want-to-develop-their-own-travel-products-rather-than-using-offtheshelf-solutions--with-this-tool-you-can-build-your-very-own-customised-applications-that-link-in-a-stable-and-secure-dialogue-with-our-global-distribution-system-gds-
  contact:
    name: Amadeus Innovation and Research
    url: https://sandbox.amadeus.com
  version: 1.0.0
host: api.sandbox.amadeus.com
basePath: /v1.2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /location/{code}:
    get:
      summary: Get Location Code
      description: |-
        This service retrieves the location information corresponding to a IATA city or airport code.

        When provided with an IATA code, the service determines whether this code could relate to a city code, an airport code or both. If the city could contain multiple airports, it will return all possible airports that correspond to that city code.

        This API is based on the Amadeus supported Geobases open-source project. If you wish to make your own database with all IATA location information, in order to get faster reponses, you can download the latest raw data from their github page.
      operationId: getLocationCode
      x-api-path-slug: locationcode-get
      parameters:
      - in: path
        name: code
        description: IATA location code for which further information is required
      responses:
        200:
          description: OK
      tags:
      - Location
      - Code