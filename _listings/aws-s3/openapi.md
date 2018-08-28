swagger: "2.0"
x-collection-name: AWS S3
x-complete: 1
info:
  title: No Title
  version: 1.0.0
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