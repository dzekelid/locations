---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 0
info:
  title: AWS Elastic Beanstalk API Create Storage Location
  version: 1.0.0
  description: Creates the Amazon S3 storage location for the account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateStorageLocation:
    get:
      summary: Create Storage Location
      description: Creates the Amazon S3 storage location for the account.
      operationId: createStorageLocation
      x-api-path-slug: actioncreatestoragelocation-get
      parameters:
      - in: query
        name: S3Bucket
        description: The name of the Amazon S3 bucket created
        type: string
      responses:
        200:
          description: OK
      tags:
      - Storage Location
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