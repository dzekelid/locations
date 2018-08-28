---
name: OnSched
x-slug: onsched
description: Build secure and scalable custom apps for Online Booking. Our flexible
  API provides many options for availability and booking. OnSched is an API first
  booking software that allows you to bring your design to life by creating your own
  booking flow. Using our robust API you can customize the interaction between your
  consumers and vendors while we do all the leg work behind the scenes. Want to offer
  online booking to your vendors? Ask about our white labelling solutions and rebrand
  our software as your own.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
x-kinRank: "7"
x-alexaRank: ""
tags: Locations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/onsched/apis.md
specificationVersion: "0.14"
apis:
- name: OnSched API - Returns a list of business locations.
  x-api-slug: consumerv1locations-get
  description: "Use this api end point if you have multiple business locations in
    your company.\r\nThe results are returned in pages. Use the offset and limit parameters
    to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
    the other query parameters to optionally filter the results list."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/onsched/consumerv1locations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/onsched/consumerv1locations-get-openapi.md
- name: OnSched API - Returns a business location object.
  x-api-slug: consumerv1locationsid-get
  description: The result returned is a single location object. An id is required
    to find the location. Find location id's using the GET consumer/v1/locations end
    point,
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/onsched/consumerv1locationsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/onsched/consumerv1locationsid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://onenote.api.gallery.streamdata.io
- type: x-api-stack
  url: http://onsched.stack.network
- type: x-documentation
  url: https://www.onsched.com/api/docs/
- type: x-pricing
  url: https://www.onsched.com/index.html#self-service
- type: x-website
  url: http://www.onsched.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---