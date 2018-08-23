---
swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 0
info:
  title: LH Public Lounges
  version: "1.0"
  description: Lounge information
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /offers/lounges/{location}:
    get:
      summary: Lounges
      description: Lounge information
      operationId: OffersLoungesByLocationGet
      x-api-path-slug: offersloungeslocation-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: query
        name: cabinClass
        description: 'Cabin class: M, E, C, F (Acceptable values are: , M, E, C, F)'
      - in: query
        name: lang
        description: Language code
      - in: path
        name: location
        description: 3-leter IATA airport or city code (e
      - in: query
        name: tierCode
        description: 'Frequent flyer level (FTL, SGC, SEN, HON) (Acceptable values
          are: , FTL, SGC, SEN, HON)'
      responses:
        200:
          description: OK
      tags:
      - Offers
      - Lounges
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