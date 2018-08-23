---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Dynamic Mapping Delete an asset and its location data
  description: Delete the asset specified by the collection name. Any location data
    associated with the asset are also deleted.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/collections/{collectionName}/assets/{assetId}:
    put:
      summary: Add an asset location into a collection.
      description: |-
        Insert a location entry into the named collection for the given asset identifier and timestamp. In addition to
        adding the new asset location, the request also controls the retention of the location history that is
        stored for the given asset in the given collection.

          - If the mandatory property retain_history is set to false then all existing location history for the
          given asset is removed before the new location is added.

          - If the retain_history property is set to true and the optional property purge_history_before is not set
          then the new location is added to the existing set of locations for the given asset.

          - If retain_history is set to true and the optional property purge_history_before is set then any existing
          locations for the given asset that have a timestamp that is older than the supplied purge_history_before
          timestamp are first deleted. Next the new location is added to the set of locations that remain.

          - If the set of location entries for the given asset (after any possible removals) contains a location entry
           with the same timestamp as the new location then the location of that entry is updated rather than a new
           location entry being added.

          - Note the new entry is always added or used to update an existing entry.
      operationId: insert-a-location-entry-into-the-named-collection-for-the-given-asset-identifier-and-timestamp-in-ad
      x-api-path-slug: v1collectionscollectionnameassetsassetid-put
      parameters:
      - in: body
        name: body
        description: An object containing the location of the asset at a given timestamp,
          together with additional properties to controlthe retention of any existing
          asset location history
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Asset
      - Location
      - Into
      - Collection
    delete:
      summary: Delete an asset and its location data
      description: Delete the asset specified by the collection name. Any location
        data associated with the asset are also deleted.
      operationId: delete-the-asset-specified-by-the-collection-name-any-location-data-associated-with-the-asset-are-al
      x-api-path-slug: v1collectionscollectionnameassetsassetid-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Asset
      - Its
      - Location
      - Data
    get:
      summary: Return the latest location data for an asset
      description: |-
        Returns the latest location entry for the given asset. The timestamp and location data for the
        given entry is included in the response.
      operationId: returns-the-latest-location-entry-for-the-given-asset-the-timestamp-and-location-data-for-thegiven-e
      x-api-path-slug: v1collectionscollectionnameassetsassetid-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Return
      - Latest
      - Location
      - Dataan
      - Asset
  /v1/collections/{collectionName}/assets/{assetId}/query:
    post:
      summary: Return locations for an asset by query condition for given customer
        id and collection name.
      description: |-
        Returns the locations for an asset by three types of query for a given customer id and collection name.
        The returned locations are in descending order of time.
        Three types of query:
        1. type=latest: The latest n locations will be returned.
        2. type=timeperiod: Locations within a time period will be returned.
        3. type=bbox: Locations within a time period and a spatial bounding box will be returned.
      operationId: returns-the-locations-for-an-asset-by-three-types-of-query-for-a-given-customer-id-and-collection-na
      x-api-path-slug: v1collectionscollectionnameassetsassetidquery-post
      parameters:
      - in: body
        name: body
        description: The parameters for the query for asset locations
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Return
      - Locationsan
      - Asset
      - By
      - Query
      - Conditiongiven
      - Customer
      - Id
      - Collection
      - Name
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