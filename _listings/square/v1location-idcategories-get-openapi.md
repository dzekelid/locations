---
swagger: "2.0"
x-collection-name: Square
x-complete: 0
info:
  title: Square Connect API Lists all of a location's item categories.
  description: Lists all of a location's item categories.
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/me/locations:
    get:
      summary: Provides details for a business's locations, including their IDs.
      description: Provides details for a business's locations, including their IDs.
      operationId: v1.me.locations.get
      x-api-path-slug: v1melocations-get
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Detailsa
      - Businesss
      - Locations
      - ""
      - Including
      - Their
      - IDs
  /v1/{location_id}/bank-accounts:
    get:
      summary: Provides non-confidential details for all of a location's associated
        bank accounts. This endpoint does not provide full bank account numbers, and
        there is no way to obtain a full bank account number with the Connect API.
      description: Provides non-confidential details for all of a location's associated
        bank accounts. This endpoint does not provide full bank account numbers, and
        there is no way to obtain a full bank account number with the Connect API.
      operationId: ListBankAccounts
      x-api-path-slug: v1location-idbankaccounts-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list bank accounts for
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Non-confidential
      - Details
      - Of
      - Locations
      - Associated
      - Bank
      - Accounts
      - ""
      - This
      - Endpoint
      - Does
      - Not
      - Provide
      - Full
      - Bank
      - Account
      - Numbers
      - ""
      - There
      - Is
      - "No"
      - Way
      - To
      - Obtain
      - Full
      - Bank
      - Account
      - Number
      - Connect
  /v1/{location_id}/cash-drawer-shifts:
    get:
      summary: Provides the details for all of a location's cash drawer shifts during
        a date range. The date range you specify cannot exceed 90 days.
      description: Provides the details for all of a location's cash drawer shifts
        during a date range. The date range you specify cannot exceed 90 days.
      operationId: ListCashDrawerShifts
      x-api-path-slug: v1location-idcashdrawershifts-get
      parameters:
      - in: query
        name: begin_time
        description: The beginning of the requested reporting period, in ISO 8601
          format
      - in: query
        name: end_time
        description: The beginning of the requested reporting period, in ISO 8601
          format
      - in: path
        name: location_id
        description: The ID of the location to list cash drawer shifts for
      - in: query
        name: order
        description: The order in which cash drawer shifts are listed in the response,
          based on their created_at field
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Details
      - Of
      - Locations
      - Cash
      - Drawer
      - Shifts
      - During
      - Date
      - Range
      - ""
      - Date
      - Range
      - You
      - Specify
      - Cannot
      - Exceed
      - "90"
      - Days
  /v1/{location_id}/categories:
    get:
      summary: Lists all of a location's item categories.
      description: Lists all of a location's item categories.
      operationId: ListCategories
      x-api-path-slug: v1location-idcategories-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list categories for
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Of
      - Locations
      - Item
      - Categories
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