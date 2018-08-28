---
swagger: "2.0"
x-collection-name: Meetup
x-complete: 0
info:
  title: Meetup Find locations
  description: Provides a query interface for finding known locations
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /find/locations:
    get:
      summary: Find locations
      description: Provides a query interface for finding known locations
      operationId: geo
      x-api-path-slug: findlocations-get
      parameters:
      - in: query
        name: lat
        description: Search for locations based on location latitude
        type: string
      - in: query
        name: lon
        description: Search for locations based on location longitude
        type: string
      - in: query
        name: offset
        description: The current offset in the paginated set, represented as an incrementing
          value
        type: string
      - in: query
        name: page
        description: The desired number of locations to return in a single set of
          results
        type: string
      - in: query
        name: query
        description: Search for locations based on city name or zip code
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Search
      - Location
  /2/cities:
    get:
      summary: Cities
      description: Returns Meetup cities. This method supports search by latitude/longitude/radius,
        by country/state, by query term/zip, or a combination of all of these. Location-only
        searches by lat and lon return all cities within a radius of the provided
        coordinates. Searches with a query return up to 10 cities matching the term,
        and can be sorted by size or distance to a given coordinate. 'smart' ordering
        can be used to return the match(es) with the highest member_count, unless
        a smaller size match exists nearby the given coordinates. Query searches are
        supported for country but not country and state
      operationId: cities
      x-api-path-slug: 2cities-get
      parameters:
      - in: query
        name: country
        description: A valid country code
        type: string
      - in: query
        name: lat
        description: Latitude to search
        type: string
      - in: query
        name: lon
        description: Longitude to search
        type: string
      - in: query
        name: query
        description: Search term and/or zip to look for (if this is specified, max
          result size limited to 10)
        type: string
      - in: query
        name: radius
        description: When searching by lat/lon only, specify a radius to search (default
          50 miles)
        type: string
      - in: query
        name: state
        description: A valid state code for the given country, if the country has
          states
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Cities
x-streamrank:
  polling_total_time_average: "0.1"
  polling_size_download_average: "32232.91"
  streaming_total_time_average: "0.06"
  streaming_size_download_average: "16130.59"
  change_yes: "3"
  change_no: "2277"
  time_percentage: "42"
  size_percentage: "50"
  change_percentage: "0"
  last_run: "2018-05-12"
  days_run: "8"
  minute_run: "0"
---