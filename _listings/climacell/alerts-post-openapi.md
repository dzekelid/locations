---
swagger: "2.0"
x-collection-name: ClimaCell
x-complete: 0
info:
  title: ClimaCell Post Alerts
  description: |-
    ### Create an Alert
    Creates a new Alert with the following information:

    * ```name``` - Alert Name
    * ```location_name``` - Location name for which the alert pertains (location has to be created earlier)
    * ```notice``` - Prior notice in seconds
    * ```conditions``` - logical expression defining a weather event such as: rain with intensity of more than 1 mm/hr. Several expressions can be concatenated with ???or??? logical operator. An alert will trigger for it if any of its contained conditions are met. ORs can contain any number of conditions.

    NOTE:??? AND condition ??? coming soon

    ### In addition to the format below, this is an example with an "OR" conditional statement:
      ```
      {
        "name": "alert with or",
        "location_name": "your-location-name",
        "notice": 3600,
        "conditions": [
          {
            "or": [
              {
                "parameter": "Rain",
                "value": 0.15,
                "operator": "lt"
              },
              {
                "parameter": "Temperature",
                "value": 25,
                "operator": "lt"
              }
            ]
          }
        ],
        "groups": [
          {
            "name": "your-group-name",
            "delivery": {
              "sms": true,
              "email": false
            }
          }
        ],
        "webhooks": [507f1f77bcf86cd799439011]
      }
      ```
    ### In addition to the format below, this is an example with an "AND" conditional statement:

      ```
      {
        "name": "alert with AND conditions",
        "location_name": "your-location-name",
        "notice": 3600,
        "conditions": [
          {
            "parameter": "Rain",
            "value": 0.15,
            "operator": "gt"
          },
          {
            "parameter": "Temperature",
            "value": 40,
            "operator": "lt"
          }
        ],
        "groups": [
          {
            "name": "your-group-name",
            "delivery": {
              "sms": true,
              "email": false
            }
          }
        ],
        "webhooks": [507f1f77bcf86cd799439011]
      }
      ```
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
    delete:
      summary: Delete Locations Location
      description: |-
        ### Delete a Location

        Removes a location with the ```location_id``` from the system. If the location was part of any alert, the alert is removed.
      operationId: -delete-a-locationremoves-a-location-with-the-location-id-from-the-system-if-the-location-was-part-o
      x-api-path-slug: locationslocation-id-delete
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
  /alerts:
    post:
      summary: Post Alerts
      description: |-
        ### Create an Alert
        Creates a new Alert with the following information:

        * ```name``` - Alert Name
        * ```location_name``` - Location name for which the alert pertains (location has to be created earlier)
        * ```notice``` - Prior notice in seconds
        * ```conditions``` - logical expression defining a weather event such as: rain with intensity of more than 1 mm/hr. Several expressions can be concatenated with ???or??? logical operator. An alert will trigger for it if any of its contained conditions are met. ORs can contain any number of conditions.

        NOTE:??? AND condition ??? coming soon

        ### In addition to the format below, this is an example with an "OR" conditional statement:
          ```
          {
            "name": "alert with or",
            "location_name": "your-location-name",
            "notice": 3600,
            "conditions": [
              {
                "or": [
                  {
                    "parameter": "Rain",
                    "value": 0.15,
                    "operator": "lt"
                  },
                  {
                    "parameter": "Temperature",
                    "value": 25,
                    "operator": "lt"
                  }
                ]
              }
            ],
            "groups": [
              {
                "name": "your-group-name",
                "delivery": {
                  "sms": true,
                  "email": false
                }
              }
            ],
            "webhooks": [507f1f77bcf86cd799439011]
          }
          ```
        ### In addition to the format below, this is an example with an "AND" conditional statement:

          ```
          {
            "name": "alert with AND conditions",
            "location_name": "your-location-name",
            "notice": 3600,
            "conditions": [
              {
                "parameter": "Rain",
                "value": 0.15,
                "operator": "gt"
              },
              {
                "parameter": "Temperature",
                "value": 40,
                "operator": "lt"
              }
            ],
            "groups": [
              {
                "name": "your-group-name",
                "delivery": {
                  "sms": true,
                  "email": false
                }
              }
            ],
            "webhooks": [507f1f77bcf86cd799439011]
          }
          ```
      operationId: -create-an-alertcreates-a-new-alert-with-the-following-information-name--alert-name-location-name--l
      x-api-path-slug: alerts-post
      parameters:
      - in: body
        name: alert
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Weather
      - Alerts
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