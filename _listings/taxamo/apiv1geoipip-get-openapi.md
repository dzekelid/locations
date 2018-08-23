---
swagger: "2.0"
x-collection-name: Taxamo
x-complete: 0
info:
  title: Taxamo Locate Provided IP Address
  description: Locate provided ip address.
  version: "1"
host: api.taxamo.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/geoip:
    get:
      summary: Locate IP Address
      description: Locate ip address.
      operationId: locateMyIP
      x-api-path-slug: apiv1geoip-get
      responses:
        200:
          description: OK
      tags:
      - Locate
      - IP
      - Ress
  /api/v1/geoip/{ip}:
    get:
      summary: Locate Provided IP Address
      description: Locate provided ip address.
      operationId: locateGivenIP
      x-api-path-slug: apiv1geoipip-get
      parameters:
      - in: path
        name: ip
        description: IP address
      responses:
        200:
          description: OK
      tags:
      - Locate
      - Provided
      - IP
      - Ress
  /api/v1/tax/location/calculate:
    get:
      summary: Calculate Location
      description: Calculate location.
      operationId: calculateTaxLocation
      x-api-path-slug: apiv1taxlocationcalculate-get
      parameters:
      - in: query
        name: billing_country_code
        description: Billing two letter ISO country code
      - in: query
        name: buyer_credit_card_prefix
        description: First 6 digits of buyers credit card prefix
      responses:
        200:
          description: OK
      tags:
      - Calculate
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