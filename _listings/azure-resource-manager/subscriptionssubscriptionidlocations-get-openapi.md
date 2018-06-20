---
swagger: "2.0"
x-collection-name: Azure Resource Manager
x-complete: 0
info:
  title: Azure Resource Manager API Gets all available geo-locations.
  description: This operation provides all the locations that are available for resource
    providers; however, each resource provider may support a subset of this list.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/locations:
    get:
      summary: Gets all available geo-locations.
      description: This operation provides all the locations that are available for
        resource providers; however, each resource provider may support a subset of
        this list.
      operationId: Subscriptions_ListLocations
      x-api-path-slug: subscriptionssubscriptionidlocations-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: subscriptionId
        description: The ID of the target subscription
      responses:
        200:
          description: OK
      tags:
      - S All Available Geo-locations.
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