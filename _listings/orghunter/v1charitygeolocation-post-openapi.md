---
swagger: "2.0"
x-collection-name: OrgHunter
x-complete: 0
info:
  title: Org Hunter Get details!
  description: This operation detail data.
  version: 1.0.0
host: data.orghunter.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/charitygeolocation:
    post:
      summary: Get details!
      description: This operation detail data.
      operationId: postV1Charitygeolocation
      x-api-path-slug: v1charitygeolocation-post
      parameters:
      - in: query
        name: ein
        description: ein (Employer Identification Number)
      responses:
        200:
          description: OK
      tags:
      - Charity
      - Geo
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