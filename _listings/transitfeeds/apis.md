---
name: TransitFeeds
x-slug: transitfeeds
description: The best source of open official public transit data. Maintained by @qzervaas
  + others
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26209-rta-service-alerts.jpg
x-kinRank: "7"
x-alexaRank: "558301"
tags: Locations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/transitfeeds/apis.md
specificationVersion: "0.14"
apis:
- name: TransitFeeds API - Retrieve a list of locations.
  x-api-slug: getlocations-get
  description: |-
    Retrieve a list of locations. Each location (except for the root) has a parent location, and each
    location has zero or more child locations. This hierarchy is generally structured so countries contain
    states, states contain cities (although this typically depends on the country).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/26209-rta-service-alerts.jpg
  humanURL: https://transitfeeds.com
  baseURL: https://api.transitfeeds.com//v1
  tags: Transit, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/transitfeeds/getlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/transitfeeds/getlocations-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://transavia.api.gallery.streamdata.io
- type: x-twitter
  url: https://twitter.com/TransitFeeds
- type: x-website
  url: https://transitfeeds.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---