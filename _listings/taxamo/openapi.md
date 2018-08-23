---
swagger: "2.0"
x-collection-name: Taxamo
x-complete: 1
info:
  title: Taxamo
  description: taxamos-elegant-suite-of-apis-and-comprehensive-reporting-dashboard-enables-digital-merchants-to-easily-comply-with-eu-regulatory-requirements-on-tax-calculation-evidence-collection-tax-return-creation-and-data-storage-
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
---