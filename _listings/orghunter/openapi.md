swagger: "2.0"
x-collection-name: OrgHunter
x-complete: 1
info:
  title: Org Hunter
  description: get-the-latest-irs-data-and-most-up-to-date-charity-information-for-your-website-or-application
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