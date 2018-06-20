---
name: ClimaCell
x-slug: climacell
description: ClimaCell provides the most accurate weather data in the world by integrating
  proprietary data extracted from wireless networks and other new sensing technologies
  with data from traditional sensors. With 90% correlation to ground truth (vs. 50%
  using radar), it&rsquo;s the best you can get for your enterprise.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
x-kinRank: "9"
x-alexaRank: "617213"
tags: Locations
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/climacell/apis.md
specificationVersion: "0.14"
apis:
- name: ClimaCell Get Locations
  x-api-slug: climacell
  description: |-
    ### List all Locations
    Pages through the list of the Locations for your user account. You can specify the maximum number of results to be retuned, and from which result to start.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations
  tags: Weather,Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/climacell/locations-get-openapi.md
- name: ClimaCell Post Locations
  x-api-slug: climacell
  description: |-
    ### Create a Location

    Creates a new Location in your organization, and name it. The name of the location is used in the notifications for triggered alerts at the location.
    ###
    The system attaches a unique ID to each location you create. This ID is used to refer to the location and manage it in the following ```locations``` API calls.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations
  tags: Weather,Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/climacell/locations-post-openapi.md
- name: ClimaCell Get Locations Location
  x-api-slug: climacell
  description: |-
    ### Retrieve a Location

    Get a single location back with its information by specifying its ```location_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations/{location_id}
  tags: Weather,Locations,Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/climacell/locationslocation-id-get-openapi.md
- name: ClimaCell Put Locations Location
  x-api-slug: climacell
  description: |-
    ### Update a Location

    Updates the details of a Location designated by its ```location_id```.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations/{location_id}
  tags: Weather,Locations,Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/climacell/locationslocation-id-put-openapi.md
- name: ClimaCell Delete Locations Location
  x-api-slug: climacell
  description: |-
    ### Delete a Location

    Removes a location with the ```location_id``` from the system. If the location was part of any alert, the alert is removed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2//locations/{location_id}
  tags: Weather,Locations,Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/climacell/locationslocation-id-delete-openapi.md
- name: ClimaCell
  x-api-slug: climacell
  description: ClimaCell provides the most accurate weather data in the world by integrating
    proprietary data extracted from wireless networks and other new sensing technologies
    with data from traditional sensors. With 90% correlation to ground truth (vs.
    50% using radar), it&rsquo;s the best you can get for your enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28707-climacell.jpg
  humanURL: https://www.climacell.co
  baseURL: https://api2.climacell.co//v2
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/climacell/openapi.md
x-common:
- type: x-blog
  url: https://www.climacell.co/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/climacell
- type: x-developer
  url: https://www.climacell.co/api/
- type: x-email
  url: info@climacell.co
- type: x-email
  url: support@climacell.co
- type: x-email
  url: sales@climacell.co
- type: x-faq
  url: https://developer.climacell.co/FAQ
- type: x-github
  url: https://github.com/climacell
- type: x-pricing
  url: https://developer.climacell.co/
- type: x-privacy-policy
  url: https://www.climacell.co/privacy/
- type: x-terms-of-service
  url: https://www.climacell.co/terms-of-service/
- type: x-twitter
  url: https://twitter.com/WeatherRevealed
- type: x-website
  url: https://www.climacell.co
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---