---
swagger: "2.0"
x-collection-name: Coord
x-complete: 0
info:
  title: Coord Parking Search API Get a list of off-street parking locations.
  description: |-
    Find all of the locations within a given are and return their pricing information and
    (when present) availability. If the `duration_m` parameter is set, total cost for a stay
    of that duration will also be returned.
  version: 1.0.0
host: api.coord.co
basePath: /v1/search/parking
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /location:
    get:
      summary: Get a list of off-street parking locations.
      description: |-
        Find all of the locations within a given are and return their pricing information and
        (when present) availability. If the `duration_m` parameter is set, total cost for a stay
        of that duration will also be returned.
      operationId: get_locations
      x-api-path-slug: location-get
      parameters:
      - in: query
        name: access_key
        description: The API access key for the request
      - in: query
        name: duration_m
        description: The expected length of time, in minutes, that the car will remainparked
          for
      - in: query
        name: latitude
        description: Latitude to return results for
      - in: query
        name: location_ids
        description: Comma separated list of the location IDs to include in the search
      - in: query
        name: longitude
        description: Longitude to return results for
      - in: query
        name: parking_start_time
        description: The ISO-8601 formatted string representing the time when the
          vehicle will arrive atthe parking location
      - in: query
        name: radius_km
        description: Distance, in kilometers, from (latitude, longitude) we will returnresults
          for
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Off-street
      - Parking
      - Locations
  /location/{system_id}/{location_id}:
    get:
      summary: Get detailed information on a bike location, as a GeoJSON Feature.
      description: |-
        A bike location may be a single bike station (which can have multiple docked bikes) or a
        single dockless bike itself. All working docks are returned, but only free and rentable
        dockless bikes are returned.

        ### Example

        #### Request:
        `curl -G "https://api.coord.co/v1/bike/location/CitiBike/482?access_key="`

        #### Response:
        ```
        {
          "geometry": {
            "coordinates": [
              -73.99931783,
              40.73935542
            ],
            "type": "Point"
          },
          "id": "CitiBike-482",
          "properties": {
            "is_renting": true,
            "is_returning": true,
            "last_reported": "2018-05-17T15:41:06.000Z",
            "lat": 40.73935542,
            "location_id": "482",
            "location_type": "bike_station_dock",
            "lon": -73.99931783,
            "name": "W 15 St & 7 Ave",
            "num_bikes_available": 19,
            "num_docks_available": 19,
            "region_id": "71",
            "system_id": "CitiBike"
          },
          "type": "Feature"
        }
        ```
      operationId: get_bike_location
      x-api-path-slug: locationsystem-idlocation-id-get
      parameters:
      - in: query
        name: access_key
        description: The API access key for the request
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Detailed
      - Information
      - "On"
      - Bike
      - Location
      - ""
      - As
      - GeoJSON
      - Feature
  /bylocation/all_rules:
    get:
      summary: Find the rules for curbs near a location.
      description: |-
        Find all of the curbs within a given radius of a particular point, and return all of their
        rules across all times of day, days of the week, times of year, etc.
      operationId: get_by_location
      x-api-path-slug: bylocationall-rules-get
      parameters:
      - in: query
        name: access_key
        description: The API access key for the request
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Find
      - Rulescurbs
      - Near
      - Location
  /bylocation/time_rules:
    get:
      summary: Find the rules for curbs near a location at a certain time.
      description: |-
        Find the rules for a given curb at a given time and on a given day. You can also use this
        to find all of the places that it is possible to perform a given action (for instance, find
        all the loading zones, or everywhere with two-hour parking).
      operationId: get_at_time_by_location
      x-api-path-slug: bylocationtime-rules-get
      parameters:
      - in: query
        name: access_key
        description: The API access key for the request
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Find
      - Rulescurbs
      - Near
      - Location
      - At
      - Certain
      - Time
  /{location_id}/session:
    get:
      summary: Retrieve a location's sessions
      description: |-
        Retrieve information about all existing sessions at a location.

        On success, the response will be a list of existing sessions. At most one will still be
        active:
        ```
          [
            {
              "id":1,
              "start_time":"2018-04-12T00:14:20.292Z",
              "end_time":"2018-04-12T04:10:13.456Z",
              "user_id":"00000000-0000-0000-0000-000000000000"
            },
            {
              "id":2,
              "start_time":"2018-04-12T00:14:20.292Z",
              "user_id":"00000000-0000-0000-0000-000000000000"
            }
          ]
        ```
      operationId: get_location_sessions
      x-api-path-slug: location-idsession-get
      parameters:
      - in: query
        name: access_key
        description: The API access key for the request
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Locations
      - Sessions
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