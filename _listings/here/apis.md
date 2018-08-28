---
name: HERE
x-slug: here
description: HERE Technologies enables people, enterprises and cities around the world
  to harness the power of location and create innovative solutions that make our lives
  safer and more efficient. We transform information from devices, vehicles, infrastructure
  and...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
x-kinRank: "7"
x-alexaRank: "3011"
tags: Locations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: Custom Location Extension API - Find Locations within a Bounding Box
  x-api-slug: bbox-get
  description: |-
    *Request a list of user-defined locations within a defined area*

    The request uses the `bbox` endpoint, and the bounding box is specified by adding the `bbox` parameter to the request URL.



    * **layerId**  `text`
     \- Unique indicator used to retrieve a dataset

    * **bbox**  `bbox`
     \- Restricts results to be found within this bounding box

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-openapi.md
- name: Custom Location Extension API - Find the Five Nearest Locations
  x-api-slug: proximity-get
  description: |-
    *Request a list of user-defined locations within a circle around a fixed point*

    The search uses the `proximity` endpoint. The definition of the location and limit of the search is specified using  `coord` and `radius` parameters, and the number of results returned limited by adding the `limit` parameter to the request URL.



    * **layerId**  `text`
     \- Unique indicator used to retrieve a dataset

    * **coord**  `latlng`
     \- Center of the proximity search

    * **radius**  `number`
     \- width of the search corridor

    * **limit**  `number`
     \- The limit of the number of items contained in the response.

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-openapi.md
- name: Custom Location Extension API - Find Locations along a pre-defined Route
  x-api-slug: routecorridor-get
  description: |-
    *Request a list of user-defined locations along a pre-defined route*

    The route has been pre-calculated and the `routeid` has already been acquired from a previous routing request. A route-based corridor search is requested using the `corridor` endpoint and by adding the `routeid` parameter to the request URL, along with a corridor `width`.



    * **layerId**  `text`
     \- Unique indicator used to retrieve a dataset

    * **routeId**  `text`
     \- A <b>previously</b> calculated routeId

    * **radius**  `number`
     \- Width of the search corridor

    * **limit**  `number`
     \- The limit of the number of items contained in the response.

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/routecorridor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/routecorridor-get-openapi.md
- name: Custom Location Extension API - Find Locations using Corridor
  x-api-slug: corridor-get
  description: |-
    *Request a list of user-defined locations near to a given corridor*

    The route corridor consists of a series of latitude, longitude pairs defining the waypoints of a route, along with a defined width. A corridor search is requested using the `corridor` endpoint and by adding a series of comma delimited latitude, longitude waypoints to the `route` parameter of the request URL, along with a `radius` for the search.



    * **layerId**  `text`
     \- Unique indicator used to retrieve a dataset

    * **route**  `text`
     \- A type of spatial filter. The corridor is defined by its path and width. The path is a line along the center of the corridor represented by a series of latitude/longitude pairs. Corridor width is given in meters.

    * **radius**  `number`
     \- width of the search corridor

    * **app_id**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

    * **app_code**  `text`
     \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/corridor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/corridor-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
- name: Public Transport API - All Next Departures from a Location
  x-api-slug: metarouterrestboardservicev1multiboardby-geocoord-json-get
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
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Technology, Mobile, internet, API Provider, Profiles, General Data, Relative
    Data, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/metarouterrestboardservicev1multiboardby-geocoord-json-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
- type: x-api-gallery
  url: http://healthcare.gov.api.gallery.streamdata.io
- type: x-api-stack
  url: http://here.stack.network
- type: x-blog
  url: https://developer.here.com/blog
- type: x-crunchbase
  url: https://crunchbase.com/organization/here-inc
- type: x-developer
  url: https://developer.here.com
- type: x-email
  url: dirk.popp@here.com
- type: x-email
  url: sebastian.kurme@here.com
- type: x-email
  url: jordan.stark@here.com
- type: x-email
  url: amy.stupavsky@here.com
- type: x-email
  url: minna.laub@here.com
- type: x-email
  url: stefanie.sirc@here.com
- type: x-email
  url: rachel.kuta@here.com
- type: x-email
  url: laurel.davis-lyons@here.com
- type: x-email
  url: linda.bradley@here.com
- type: x-email
  url: press@here.com
- type: x-twitter
  url: https://twitter.com/here
- type: x-website
  url: https://here.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---