---
swagger: "2.0"
x-collection-name: HERE
x-complete: 0
info:
  title: HERE Public Transit API All Next Departures from a Location
  description: "*Request a list of all next departure times and destinations from
    a given location.*\n\nAll next departures from a given location can be requested
    using the `metarouter/rest/boardservice/v1/multiboard/by_geocoord.json` and specifying
    a `time` and `coordinates. `The maximum numbers of nearby stations and number
    of departures per station can be restricted by using the `max_stn` and `max` parameters,
    respectively.\n  \n\n\n\n* **lang**  `text`\n \\- Language of the response\n\n*
    **startX**  `number`\n \\- The longitude of the center point of your search.    e.g.
    `13.377`\n\n* **startY**  `number`\n \\- The latitude of the center point of your
    search.    e.g. `52.515`\n\n* **time**  `text`\n \\- Time in format `yyyy-mm-ddThh:mm:ss`.\n\n*
    **app_id**  `text`\n \\- A 20 bytes Base64 URL-safe encoded string used for the
    authentication of the client application.    You must include an app_code and
    app_code with every request.\n\n* **app_code**  `text`\n \\- A 20 bytes Base64
    URL-safe encoded string used for the authentication of the client application.
    \   You must include an app_code and app_code with every request.\n\n* **max**
    \ `text`\n \\- The  maximum number of next departures per station to be included
    in the response.     The default value is 40.  \n\n* **max_stn**  `text`\n \\-
    \ The maximum number of stations for which departures are required.     The default
    value is 40.    \n\n* **prod**  `text`\n \\- A 16-bit binary number, where each
    bit represents one type of transit.  \n  0: High-speed Trains  \n  1: Intercity/EuroCity
    Trains  \n  2: Inter-regional and fast trains  \n  3: Regional and other trains
    \ \n  4: City trains  \n  5: Buses  \n  6: Boat/Ferries  \n  7: Metro/Subway  \n
    \ 8: Tram  \n  9: Ordered services/Taxi  \n  10: Inclined/Funicular  \n  11: Aerial/Cable
    Car  \n  12: Rapid Bus  \n  13: Monorail  \n  14: Air plane  \n  15: Not yet defined
    \ \n  The default is 1111111111111111, meaning all supported transit types are
    permitted."
  version: 1.0.0
host: cit.transit.api.here.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /metarouter/rest/boardservice/v1/multiboard/by_geocoord.json:
    get:
      summary: All Next Departures from a Location
      description: "*Request a list of all next departure times and destinations from
        a given location.*\n\nAll next departures from a given location can be requested
        using the `metarouter/rest/boardservice/v1/multiboard/by_geocoord.json` and
        specifying a `time` and `coordinates. `The maximum numbers of nearby stations
        and number of departures per station can be restricted by using the `max_stn`
        and `max` parameters, respectively.\n  \n\n\n\n* **lang**  `text`\n \\- Language
        of the response\n\n* **startX**  `number`\n \\- The longitude of the center
        point of your search.    e.g. `13.377`\n\n* **startY**  `number`\n \\- The
        latitude of the center point of your search.    e.g. `52.515`\n\n* **time**
        \ `text`\n \\- Time in format `yyyy-mm-ddThh:mm:ss`.\n\n* **app_id**  `text`\n
        \\- A 20 bytes Base64 URL-safe encoded string used for the authentication
        of the client application.    You must include an app_code and app_code with
        every request.\n\n* **app_code**  `text`\n \\- A 20 bytes Base64 URL-safe
        encoded string used for the authentication of the client application.    You
        must include an app_code and app_code with every request.\n\n* **max**  `text`\n
        \\- The  maximum number of next departures per station to be included in the
        response.     The default value is 40.  \n\n* **max_stn**  `text`\n \\-  The
        maximum number of stations for which departures are required.     The default
        value is 40.    \n\n* **prod**  `text`\n \\- A 16-bit binary number, where
        each bit represents one type of transit.  \n  0: High-speed Trains  \n  1:
        Intercity/EuroCity Trains  \n  2: Inter-regional and fast trains  \n  3: Regional
        and other trains  \n  4: City trains  \n  5: Buses  \n  6: Boat/Ferries  \n
        \ 7: Metro/Subway  \n  8: Tram  \n  9: Ordered services/Taxi  \n  10: Inclined/Funicular
        \ \n  11: Aerial/Cable Car  \n  12: Rapid Bus  \n  13: Monorail  \n  14: Air
        plane  \n  15: Not yet defined  \n  The default is 1111111111111111, meaning
        all supported transit types are permitted."
      operationId: MetarouterRestBoardserviceV1MultiboardByGeocoordJsonGet
      x-api-path-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: lang
      - in: query
        name: max
      - in: query
        name: max_stn
      - in: query
        name: prod
      - in: query
        name: startX
      - in: query
        name: startY
      - in: query
        name: time
      responses:
        200:
          description: OK
      tags:
      - All
      - Next
      - Departures
      - From
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