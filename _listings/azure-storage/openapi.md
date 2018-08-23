---
swagger: "2.0"
x-collection-name: Azure Storage
x-complete: 1
info:
  title: StorSimpleSeries8000ManagementClient
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
  /providers/Microsoft.ImportExport/locations:
    get:
      summary: List Locations
      description: Returns a list of locations to which you can ship the disks associated
        with an import or export job. A location is a Microsoft data center region.
      operationId: ListLocations
      x-api-path-slug: providersmicrosoft-importexportlocations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Locations
  /providers/Microsoft.ImportExport/locations/{locationName}:
    get:
      summary: Get Location
      description: Gets a location to which you can ship the disks associated with
        an import or export job. A location is an Azure region.
      operationId: GetLocation
      x-api-path-slug: providersmicrosoft-importexportlocationslocationname-get
      parameters:
      - in: path
        name: locationName
        description: The name of the location
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Location
---