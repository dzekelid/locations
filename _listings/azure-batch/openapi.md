---
swagger: "2.0"
x-collection-name: Azure Batch
x-complete: 1
info:
  title: BatchManagement
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
---