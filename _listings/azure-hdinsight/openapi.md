---
swagger: "2.0"
x-collection-name: Azure HDInsight
x-complete: 1
info:
  title: HDInsightManagementClient
  description: the-hdinsight-management-client-
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
  /subscriptions/{subscriptionId}/providers/Microsoft.HDInsight/locations/{location}/capabilities:
    get:
      summary: Location Get Capabilities
      description: Gets the capabilities for the specified location.
      operationId: Location_GetCapabilities
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-hdinsightlocationslocationcapabilities-get
      parameters:
      - in: path
        name: location
        description: The location to get capabilities for
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Location Capabilities
---