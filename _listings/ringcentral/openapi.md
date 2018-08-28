swagger: "2.0"
x-collection-name: RingCentral
x-complete: 1
info:
  title: RingCentral Connect Platform API Explorer
  description: this-is-an-interactive-api-explorer-for-the-ringcentral-connect-platform--to-use-this-service-you-will-need-to-have-a-developer-account---links--a-hrefhttpsnetstorage-ringcentral-comdpwapiexplorerrcplatform-basic-ymlv20180514092722-target-blankringcentral-api-specaspannbspnbspopenapi-fka-swagger-formatnbspnbspnbspnbspspana-hrefhttpsgithub-comoaiopenapispecification-target-blanklearn-more-about-openapia
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