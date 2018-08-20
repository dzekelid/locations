---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Put Locations Location
  description: |-
    ### Update a Location

    Updates the details of a Location designated by its ```location_id```.
  version: 1.0.0
host: api2.climacell.co
basePath: /v2
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
      description: |-
        ### List all Locations
        Pages through the list of the Locations for your user account. You can specify the maximum number of results to be retuned, and from which result to start.
      operationId: -list-all-locationspages-through-the-list-of-the-locations-for-your-user-account-you-can-specify-the
      x-api-path-slug: locations-get
      parameters:
      - in: query
        name: limit
        description: The maximum number of records to load
      - in: query
        name: offset
        description: The number of records to skip
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
    post:
      summary: Post Locations
      description: |-
        ### Create a Location

        Creates a new Location in your organization, and name it. The name of the location is used in the notifications for triggered alerts at the location.
        ###
        The system attaches a unique ID to each location you create. This ID is used to refer to the location and manage it in the following ```locations``` API calls.
      operationId: -create-a-locationcreates-a-new-location-in-your-organization-and-name-it-the-name-of-the-location-i
      x-api-path-slug: locations-post
      parameters:
      - in: body
        name: location
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
  /locations/{location_id}:
    get:
      summary: Get Locations Location
      description: |-
        ### Retrieve a Location

        Get a single location back with its information by specifying its ```location_id```.
      operationId: -retrieve-a-locationget-a-single-location-back-with-its-information-by-specifying-its-location-id
      x-api-path-slug: locationslocation-id-get
      parameters:
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
    put:
      summary: Put Locations Location
      description: |-
        ### Update a Location

        Updates the details of a Location designated by its ```location_id```.
      operationId: -update-a-locationupdates-the-details-of-a-location-designated-by-its-location-id
      x-api-path-slug: locationslocation-id-put
      parameters:
      - in: body
        name: location
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: UUID of the Location
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Locations
      - Location
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