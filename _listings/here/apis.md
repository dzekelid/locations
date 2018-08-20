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
created: "2018-08-19"
modified: "2018-08-19"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/apis.md
specificationVersion: "0.14"
apis:
- name: HERE Batch Geocoder API
  x-api-slug: here-batch-geocoder-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://batch.geocoder.cit.api.here.com//6.2
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Custom Location Extension API
  x-api-slug: here-custom-location-extension-api
  description: the-here-custom-location-extension-is-a-service-that-stores-and-retrieves-custom-locations-locations-can-be-uploaded-as-csv-files-or-shapefile-standard-compliant-shapes-via-an-administration-website-or-as-xml-files-via-http-post-requests-to-the-restful-api--locations-can-be-retrieved-by-making-an-http-get-requests-to-the-restful-api--the-custom-location-extension-api-provides-solutions-for-the-following-high-level-use-cases-store-custom-sets-of-locations-and-polygons-for-use-with-other-here-apis--perform-a-proximity-search-for-custom-points-of-interest-and-polygons-around-a-specified-location--retrieve-a-set-of-custom-points-of-interest-pois-andor-polygons-within-a-specified-bounding-box--find-all-custom-locations-and-polygons-within-an-isoline-route-result--find-all-custom-locations-and-polygons-within-a-specified-radius-of-a-defined-route--search-custom-indices-generated-from-multiple-fields-from-one-or-more-layers-this-example-set-works-with-version-1-7-7-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-complatformextensionsdocumentationcustomlocation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Mapping, Technology, Mobile, internet, API Provider, Profiles, General Data
    API, Relative Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-openapi.md
- name: HERE Custom Location Extension API
  x-api-slug: here-custom-location-extension-api
  description: the-here-custom-location-extension-is-a-service-that-stores-and-retrieves-custom-locations-locations-can-be-uploaded-as-csv-files-or-shapefile-standard-compliant-shapes-via-an-administration-website-or-as-xml-files-via-http-post-requests-to-the-restful-api--locations-can-be-retrieved-by-making-an-http-get-requests-to-the-restful-api--the-custom-location-extension-api-provides-solutions-for-the-following-high-level-use-cases-store-custom-sets-of-locations-and-polygons-for-use-with-other-here-apis--perform-a-proximity-search-for-custom-points-of-interest-and-polygons-around-a-specified-location--retrieve-a-set-of-custom-points-of-interest-pois-andor-polygons-within-a-specified-bounding-box--find-all-custom-locations-and-polygons-within-an-isoline-route-result--find-all-custom-locations-and-polygons-within-a-specified-radius-of-a-defined-route--search-custom-indices-generated-from-multiple-fields-from-one-or-more-layers-this-example-set-works-with-version-1-7-7-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-complatformextensionsdocumentationcustomlocation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Mapping, Technology, Mobile, internet, API Provider, Profiles, General Data
    API, Relative Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-openapi.md
- name: HERE Custom Location Extension API
  x-api-slug: here-custom-location-extension-api
  description: the-here-custom-location-extension-is-a-service-that-stores-and-retrieves-custom-locations-locations-can-be-uploaded-as-csv-files-or-shapefile-standard-compliant-shapes-via-an-administration-website-or-as-xml-files-via-http-post-requests-to-the-restful-api--locations-can-be-retrieved-by-making-an-http-get-requests-to-the-restful-api--the-custom-location-extension-api-provides-solutions-for-the-following-high-level-use-cases-store-custom-sets-of-locations-and-polygons-for-use-with-other-here-apis--perform-a-proximity-search-for-custom-points-of-interest-and-polygons-around-a-specified-location--retrieve-a-set-of-custom-points-of-interest-pois-andor-polygons-within-a-specified-bounding-box--find-all-custom-locations-and-polygons-within-an-isoline-route-result--find-all-custom-locations-and-polygons-within-a-specified-radius-of-a-defined-route--search-custom-indices-generated-from-multiple-fields-from-one-or-more-layers-this-example-set-works-with-version-1-7-7-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-complatformextensionsdocumentationcustomlocation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Mapping, Technology, Mobile, internet, API Provider, Profiles, General Data
    API, Relative Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/routecorridor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/routecorridor-get-openapi.md
- name: HERE Custom Location Extension API
  x-api-slug: here-custom-location-extension-api
  description: the-here-custom-location-extension-is-a-service-that-stores-and-retrieves-custom-locations-locations-can-be-uploaded-as-csv-files-or-shapefile-standard-compliant-shapes-via-an-administration-website-or-as-xml-files-via-http-post-requests-to-the-restful-api--locations-can-be-retrieved-by-making-an-http-get-requests-to-the-restful-api--the-custom-location-extension-api-provides-solutions-for-the-following-high-level-use-cases-store-custom-sets-of-locations-and-polygons-for-use-with-other-here-apis--perform-a-proximity-search-for-custom-points-of-interest-and-polygons-around-a-specified-location--retrieve-a-set-of-custom-points-of-interest-pois-andor-polygons-within-a-specified-bounding-box--find-all-custom-locations-and-polygons-within-an-isoline-route-result--find-all-custom-locations-and-polygons-within-a-specified-radius-of-a-defined-route--search-custom-indices-generated-from-multiple-fields-from-one-or-more-layers-this-example-set-works-with-version-1-7-7-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-complatformextensionsdocumentationcustomlocation
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Mapping, Technology, Mobile, internet, API Provider, Profiles, General Data
    API, Relative Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/bbox-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/proximity-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/routecorridor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/routecorridor-get-openapi.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/corridor-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/corridor-get-openapi.md
- name: HERE Custom Location Extension API
  x-api-slug: here-custom-location-extension-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://customlocation.cit.api.here.com//v1/search
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Geocoder API
  x-api-slug: here-geocoder-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://geocoder.cit.api.here.com//6.2
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Map Image API
  x-api-slug: here-map-image-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://image.maps.cit.api.here.com//mia/1.6
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Map Tile API
  x-api-slug: here-map-tile-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://1.aerial.maps.cit.api.here.com//maptile/2.1/maptile/newest
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Places API
  x-api-slug: here-places-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://places.demo.api.here.com//places/v1
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Platform Data Extension API
  x-api-slug: here-platform-data-extension-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https:///
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Public Transit API
  x-api-slug: here-public-transit-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://cit.transit.api.here.com//
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Route Match Extension API
  x-api-slug: here-route-match-extension-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://pde.cit.api.here.com//1
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Routing API
  x-api-slug: here-routing-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://route.cit.api.here.com//routing/7.2
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Traffic API
  x-api-slug: here-traffic-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://tiles.traffic.cit.api.here.com//traffic/6.0/tiles/8/133/86/256
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Venue Maps
  x-api-slug: here-venue-maps
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://signature.venue.maps.cit.api.here.com//venues/signature
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Waypoint Sequence Extension API
  x-api-slug: here-waypoint-sequence-extension-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://wse.cit.api.here.com//2
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
- name: HERE Weather API
  x-api-slug: here-weather-api
  description: HERE Technologies enables people, enterprises and cities around the
    world to harness the power of location and create innovative solutions that make
    our lives safer and more efficient. We transform information from devices, vehicles,
    infrastructure and...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/20089-here-maps.jpg
  humanURL: https://developer.here.com
  baseURL: https://weather.cit.api.here.com//weather/1.0
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/here/openapi.md
x-common:
- type: x-blog-rss
  url: https://developer.here.com/blog/feed
- type: x-github
  url: https://github.com/heremaps
- type: x-postman-collection
  url: https://github.com/heremaps/postman-collections
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