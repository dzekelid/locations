---
name: Square
x-slug: square
description: Square helps millions of sellers run their business- from secure credit
  card processing to point of sale solutions. Get paid faster with Square and sign
  up today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
x-kinRank: "9"
x-alexaRank: "2436"
tags: Locations
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect API Provides details for a business's locations, including
    their IDs.
  x-api-slug: square-connect-api
  description: Provides details for a business's locations, including their IDs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/me/locations
  tags: Provides,Detailsa,Businesss,Locations,,Including,Their,IDs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1melocations-get-openapi.md
- name: Square Connect API Provides non-confidential details for all of a location's
    associated bank accounts. This endpoint does not provide full bank account numbers,
    and there is no way to obtain a full bank account number with the Connect API.
  x-api-slug: square-connect-api
  description: Provides non-confidential details for all of a location's associated
    bank accounts. This endpoint does not provide full bank account numbers, and there
    is no way to obtain a full bank account number with the Connect API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/bank-accounts
  tags: Provides,Non-confidential,Details,Of,Locations,Associated,Bank,Accounts,,This,Endpoint,Does,Not,Provide,Full,Bank,Account,Numbers,,There,Is,No,Way,To,Obtain,Full,Bank,Account,Number,Connect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idbankaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idbankaccounts-get-openapi.md
- name: Square Connect API Provides the details for all of a location's cash drawer
    shifts during a date range. The date range you specify cannot exceed 90 days.
  x-api-slug: square-connect-api
  description: Provides the details for all of a location's cash drawer shifts during
    a date range. The date range you specify cannot exceed 90 days.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/cash-drawer-shifts
  tags: Provides,Details,Of,Locations,Cash,Drawer,Shifts,During,Date,Range,,Date,Range,You,Specify,Cannot,Exceed,90,Days
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idcashdrawershifts-get-openapi.md
- name: Square Connect API Lists all of a location's item categories.
  x-api-slug: square-connect-api
  description: Lists all of a location's item categories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/categories
  tags: Lists,,Of,Locations,Item,Categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idcategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idcategories-get-openapi.md
- name: Square Connect API Lists all of a location's discounts.
  x-api-slug: square-connect-api
  description: Lists all of a location's discounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/discounts
  tags: Lists,,Of,Locations,Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-iddiscounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-iddiscounts-get-openapi.md
- name: Square Connect API Lists all of a location's fees (taxes).
  x-api-slug: square-connect-api
  description: Lists all of a location's fees (taxes).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/fees
  tags: Lists,,Of,Locations,Fees,(taxes)
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idfees-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idfees-get-openapi.md
- name: Square Connect API Provides summary information for all of a location's items.
  x-api-slug: square-connect-api
  description: Provides summary information for all of a location's items.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/items
  tags: Provides,Summary,Information,Of,Locations,Items
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-iditems-get-openapi.md
- name: Square Connect API Lists all of a location's modifier lists.
  x-api-slug: square-connect-api
  description: Lists all of a location's modifier lists.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/modifier-lists
  tags: Lists,,Of,Locations,Modifier,Lists
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idmodifierlists-get-openapi.md
- name: Square Connect API Lists all of a location's Favorites pages in Square Register.
  x-api-slug: square-connect-api
  description: Lists all of a location's Favorites pages in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v1/{location_id}/pages
  tags: Lists,,Of,Locations,Favorites,Pages,In,Square,Register
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idpages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v1location-idpages-get-openapi.md
- name: Square Connect API ListLocations
  x-api-slug: square-connect-api
  description: |-
    Provides the details for all of a business's locations.

    Most other Connect API endpoints have a required `location_id` path parameter.
    The `id` field of the [`Location`](#type-location) objects returned by this
    endpoint correspond to that `location_id` parameter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com////v2/locations
  tags: ListLocations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/v2locations-get-openapi.md
- name: Square Connect API
  x-api-slug: square-connect-api
  description: Square helps millions of sellers run their business- from secure credit
    card processing to point of sale solutions. Get paid faster with Square and sign
    up today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://squareup.com
  baseURL: https://connect.squareup.com//
  tags: Locations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/square/openapi.md
x-common:
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-crunchbase
  url: https://crunchbase.com/organization/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-email
  url: press@squareup.com
- type: x-email
  url: security@squareup.com
- type: x-email
  url: lawenforcement@squareup.com
- type: x-email
  url: redemption@squareup.com
- type: x-email
  url: privacy@squareup.com
- type: x-email
  url: community@squareup.com
- type: x-email
  url: noreply@messaging.squareup.com
- type: x-email
  url: ir@squareup.com
- type: x-email
  url: takedowns@squareup.com
- type: x-github
  url: https://github.com/square
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: http://squareup.com
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---