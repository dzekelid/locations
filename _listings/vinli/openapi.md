swagger: "2.0"
x-collection-name: Vinli
x-complete: 1
info:
  title: Vinli
  description: todo-add-description
  version: 1.0.0
host: events.vin.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /devices/62976d30-b6dc-40f1-8422-ccc367572101/locations:
    get:
      summary: Locations Request
      description: Locations request.
      operationId: Devices62976d30B6dc40f18422Ccc367572101LocationsGet
      x-api-path-slug: devices62976d30b6dc40f18422ccc367572101locations-get
      parameters:
      - in: header
        name: Accept
      - in: query
        name: fields
      responses:
        200:
          description: OK
      tags:
      - Locations
      - Request