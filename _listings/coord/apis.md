---
name: Coord
x-slug: coord
description: Coord is a mobility company that creates seamless mobility and self-driving
  experiences today through deep integrations. The company offers bike-share API,
  Curbs API, Tolls API, Routing API and etc.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
x-kinRank: "7"
x-alexaRank: "1035226"
tags: Locations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/apis.md
specificationVersion: "0.14"
apis:
- name: Bike Share API - Get bike locations in the requested search area, as a GeoJSON
    FeatureCollection.
  x-api-slug: location-get
  description: |-
    Get a list of locations given the input parameters. Specify a search area by radius around
    a latitude and longitude, as well as any filter for specific systems. Each location will
    be a GeoJSON Feature, and aggregated into a GeoJSON FeatureCollection.

    ### Example

    #### Request:
    `curl -G "https://api.coord.co/v1/bike/location?latitude=40.742868&longitude=-73.989186&radius_km=0.25&access_key="`

    #### Response:
    ```
    {
      "features": [
        {
          "geometry": {
            "coordinates": [
              -73.98918628692627,
              40.74286877312112
            ],
            "type": "Point"
          },
          "id": "CitiBike-3641",
          "properties": {
            "is_renting": true,
            "is_returning": true,
            "last_reported": "2018-05-17T15:39:24.000Z",
            "lat": 40.74286877312112,
            "location_id": "3641",
            "location_type": "bike_station_dock",
            "lon": -73.98918628692627,
            "name": "Broadway & W 25 St",
            "num_bikes_available": 53,
            "num_docks_available": 1,
            "region_id": "71",
            "system_id": "CitiBike"
          },
          "type": "Feature"
        },
        {
          "geometry": {
            "coordinates": [
              -73.99144871,
              40.74395411
            ],
            "type": "Point"
          },
          "id": "CitiBike-466",
          "properties": {
            "is_renting": true,
            "is_returning": true,
            "last_reported": "2018-05-17T15:32:40.000Z",
            "lat": 40.74395411,
            "location_id": "466",
            "location_type": "bike_station_dock",
            "lon": -73.99144871,
            "name": "W 25 St & 6 Ave",
            "num_bikes_available": 35,
            "region_id": "71",
            "system_id": "CitiBike"
          },
          "type": "Feature"
        }
      ],
      "type": "FeatureCollection"
    }
    ```
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-openapi.md
- name: Bike Share API - Get detailed information on a bike location, as a GeoJSON
    Feature.
  x-api-slug: locationsystem-idlocation-id-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-openapi.md
- name: Bike Share API - Get detailed information on a bike location, as a GeoJSON
    Feature.
  x-api-slug: locationsystem-idlocation-id-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-openapi.md
- name: Bike Share API - Get detailed information on a bike location, as a GeoJSON
    Feature.
  x-api-slug: locationsystem-idlocation-id-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-openapi.md
- name: Bike Share API - Get detailed information on a bike location, as a GeoJSON
    Feature.
  x-api-slug: locationsystem-idlocation-id-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-openapi.md
- name: Bike Share API - Get detailed information on a bike location, as a GeoJSON
    Feature.
  x-api-slug: locationsystem-idlocation-id-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/bike
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationsystem-idlocation-id-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location.
  x-api-slug: bylocationall-rules-get
  description: |-
    Find all of the curbs within a given radius of a particular point, and return all of their
    rules across all times of day, days of the week, times of year, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location at a certain time.
  x-api-slug: bylocationtime-rules-get
  description: |-
    Find the rules for a given curb at a given time and on a given day. You can also use this
    to find all of the places that it is possible to perform a given action (for instance, find
    all the loading zones, or everywhere with two-hour parking).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location.
  x-api-slug: bylocationall-rules-get
  description: |-
    Find all of the curbs within a given radius of a particular point, and return all of their
    rules across all times of day, days of the week, times of year, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location at a certain time.
  x-api-slug: bylocationtime-rules-get
  description: |-
    Find the rules for a given curb at a given time and on a given day. You can also use this
    to find all of the places that it is possible to perform a given action (for instance, find
    all the loading zones, or everywhere with two-hour parking).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location at a certain time.
  x-api-slug: bylocationtime-rules-get
  description: |-
    Find the rules for a given curb at a given time and on a given day. You can also use this
    to find all of the places that it is possible to perform a given action (for instance, find
    all the loading zones, or everywhere with two-hour parking).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location at a certain time.
  x-api-slug: bylocationtime-rules-get
  description: |-
    Find the rules for a given curb at a given time and on a given day. You can also use this
    to find all of the places that it is possible to perform a given action (for instance, find
    all the loading zones, or everywhere with two-hour parking).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location at a certain time.
  x-api-slug: bylocationtime-rules-get
  description: |-
    Find the rules for a given curb at a given time and on a given day. You can also use this
    to find all of the places that it is possible to perform a given action (for instance, find
    all the loading zones, or everywhere with two-hour parking).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationtime-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location.
  x-api-slug: bylocationall-rules-get
  description: |-
    Find all of the curbs within a given radius of a particular point, and return all of their
    rules across all times of day, days of the week, times of year, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location.
  x-api-slug: bylocationall-rules-get
  description: |-
    Find all of the curbs within a given radius of a particular point, and return all of their
    rules across all times of day, days of the week, times of year, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-openapi.md
- name: Curb Search API - Find the rules for curbs near a location.
  x-api-slug: bylocationall-rules-get
  description: |-
    Find all of the curbs within a given radius of a particular point, and return all of their
    rules across all times of day, days of the week, times of year, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/curbs
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/bylocationall-rules-get-openapi.md
- name: Parking Access API - Retrieve a location's sessions
  x-api-slug: location-idsession-get
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/access/parking
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-idsession-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-idsession-get-openapi.md
- name: Parking Search API - Get a list of off-street parking locations.
  x-api-slug: location-get
  description: |-
    Find all of the locations within a given are and return their pricing information and
    (when present) availability. If the `duration_m` parameter is set, total cost for a stay
    of that duration will also be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/parking
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/location-get-openapi.md
- name: Parking Search API - Get a list of off-street parking locations.
  x-api-slug: locationid-get
  description: |-
    Find a single locations within a given are and return their pricing information and
    (when present) availability. If the `duration_m` parameter is set, total cost for a stay
    of that duration will also be returned.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/coord-logo.png
  humanURL: https://coord.co
  baseURL: https://api.coord.co//v1/search/parking
  tags: Parking, Tolls, Bikes, Routes, General Data, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/coord/locationid-get-openapi.md
x-common:
- type: x-blog
  url: https://medium.com/coord
- type: x-blog-rss
  url: https://medium.com/feed/coord
- type: x-openapi
  url: https://jsapi.apiary.io/apis/coordprodsearchtolls.source
- type: x-api-gallery
  url: http://convertapi.api.gallery.streamdata.io
- type: x-api-stack
  url: http://coord.stack.network
- type: x-developer
  url: https://coord.co/docs/
- type: x-pricing
  url: https://coord.co/#pricing
- type: x-twitter
  url: https://twitter.com/coordcity
- type: x-website
  url: https://coord.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---