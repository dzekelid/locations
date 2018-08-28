---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Location List
  description: "Returns all available locations for a certain state.\nUsage Plan Group\nLight\nError
    Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error Message\n   \n \n\n400\nCMN-101\nParameter
    [orderBy] value is invalid\n\n\n404\nCMN-102\nResource for parameter [location]
    is not found"
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/dictionary/location:
    get:
      summary: Get Location List
      description: "Returns all available locations for a certain state.\nUsage Plan
        Group\nLight\nError Codes\n\n \n  \n   HTTP Code\n   Error Code\n   Error
        Message\n   \n \n\n400\nCMN-101\nParameter [orderBy] value is invalid\n\n\n404\nCMN-102\nResource
        for parameter [location] is not found"
      operationId: listLocations
      x-api-path-slug: restapiv1-0dictionarylocation-get
      parameters:
      - in: query
        name: orderBy
        description: Sorts results by the property specified
      - in: query
        name: page
        description: Indicates the page number to retrieve
      - in: query
        name: perPage
        description: Indicates the page size (number of items)
      - in: query
        name: stateId
        description: Internal identifier of a state
      - in: query
        name: withNxx
        description: Specifies if nxx codes are returned
      responses:
        200:
          description: OK
      tags:
      - Location
      - List
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