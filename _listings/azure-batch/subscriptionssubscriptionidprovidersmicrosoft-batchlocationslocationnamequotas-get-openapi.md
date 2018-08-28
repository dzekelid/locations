---
swagger: "2.0"
x-collection-name: Azure Batch
x-complete: 0
info:
  title: Azure Batch API Location Get Quotas
  version: 1.0.0
  description: Gets the Batch service quotas for the specified subscription at the
    given location.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.Batch/locations/{locationName}/quotas:
    get:
      summary: Location Get Quotas
      description: Gets the Batch service quotas for the specified subscription at
        the given location.
      operationId: Location_GetQuotas
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-batchlocationslocationnamequotas-get
      parameters:
      - in: path
        name: locationName
        description: The desired region for the quotas
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Location Quotas
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