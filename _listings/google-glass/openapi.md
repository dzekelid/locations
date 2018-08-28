swagger: "2.0"
x-collection-name: Google Glass
x-complete: 1
info:
  title: Google Mirror
  description: interacts-with-glass-users-via-the-timeline-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /mirror/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /locations:
    get:
      summary: Get Locations
      description: Retrieves a list of locations for the user.
      operationId: mirror.locations.list
      x-api-path-slug: locations-get
      responses:
        200:
          description: OK
      tags:
      - Location
  /locations/{id}:
    get:
      summary: Get Location
      description: Gets a single location by ID.
      operationId: mirror.locations.get
      x-api-path-slug: locationsid-get
      parameters:
      - in: path
        name: id
        description: The ID of the location or latest for the last known location
      responses:
        200:
          description: OK
      tags:
      - Location