swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 1
info:
  title: AWS Elastic Beanstalk API
  version: 1.0.0
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