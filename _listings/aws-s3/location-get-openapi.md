---
swagger: "2.0"
x-collection-name: AWS S3
x-complete: 0
info:
  title: AWS S3 GET Bucket location
  version: 1.0.0
  description: This implementation of the GET operation uses thelocation subresource
    to return a bucket's region
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?location:
    get:
      summary: GET Bucket location
      description: This implementation of the GET operation uses thelocation subresource
        to return a bucket's region
      operationId: get-bucket-location
      x-api-path-slug: location-get
      responses:
        200:
          description: OK
      tags:
      - Bucket
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