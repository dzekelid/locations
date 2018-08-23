---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/accounting/stores/locations:
    get:
      summary: List all accounting locations
      description: List all accounting locations.
      operationId: getRestAccountingStoresLocations
      x-api-path-slug: restaccountingstoreslocations-get
      responses:
        200:
          description: OK
      tags:
      - List
      - ""
      - Accounting
      - Locations
  /rest/accounting/stores/{plentyId}/locations:
    get:
      summary: List accounting locations of a client
      description: Lists accounting locations of a client. The plenty ID of the client
        must be specified.
      operationId: getRestAccountingStoresPlentyLocations
      x-api-path-slug: restaccountingstoresplentyidlocations-get
      parameters:
      - in: query
        name: locationId
        description: The plenty ID
      - in: path
        name: plentyId
      responses:
        200:
          description: OK
      tags:
      - List
      - Accounting
      - Locations
      - Of
      - Client
  /rest/items/{id}/variations/{variationId}/stock/storageLocations:
    get:
      summary: List stock of a variation per storage locations
      description: Lists stock of a variation per storage location. The ID of the
        item and the ID of the variation must be specified.
      operationId: getRestItemsVariationsVariationStockStoragelocations
      x-api-path-slug: restitemsidvariationsvariationidstockstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: path
        name: id
      - in: query
        name: itemId
        description: The ID of the item
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Variation
      - Per
      - Storage
      - Locations
  /rest/stockmanagement/warehouses/{warehouseId}/management/racks/{rackId}/shelves/{shelfId}/storageLocations:
    get:
      summary: List storage locations
      description: Lists storage locations. The id of the warehouse, the id of the
        rack and the id of the shelf must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementRacksRackShelvesShelfStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: query
        name: itemsPerPage
        description: Number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: rackId
      - in: path
        name: shelfId
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - List
      - Storage
      - Locations
    post:
      summary: Create a storage location
      description: Creates a storage location. The id of the warehouse, the id of
        the rack and the id of the shelf must be specified.
      operationId: postRestStockmanagementWarehousesWarehouseManagementRacksRackShelvesShelfStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
      parameters:
      - in: path
        name: rackId
      - in: path
        name: shelfId
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Location
  /rest/stockmanagement/warehouses/{warehouseId}/management/storageLocations:
    get:
      summary: List storage locations
      description: Lists storage locations that belong to a warehouse. The id of the
        warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: query
        name: itemsPerPage
        description: Number of items per page
      - in: query
        name: page
        description: The requested page
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - List
      - Storage
      - Locations
  /rest/warehouses/locations:
    delete:
      summary: Delete multiple warehouse locations
      description: Deletes multiple warehouse locations
      operationId: deleteRestWarehousesLocations
      x-api-path-slug: restwarehouseslocations-delete
      responses:
        200:
          description: OK
      tags:
      - Multiple
      - Warehouse
      - Locations
    post:
      summary: Create a warehouse location
      description: Creates a warehouse location.
      operationId: postRestWarehousesLocations
      x-api-path-slug: restwarehouseslocations-post
      parameters:
      - in: query
        name: label
        description: The label of the warehouse location
      - in: query
        name: levelId
        description: The warehouse location level ID of the warehouse location
      - in: query
        name: position
        description: The position of the warehouse location
      - in: query
        name: purposeKey
        description: The location type key of the warehouse location
      - in: query
        name: statusKey
        description: The location status key of the warehouse location
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
  /rest/warehouses/locations/group:
    put:
      summary: Edit the purpose and status for a group of storage locations
      description: Edits the purpose and status for a group of storage locations by
        passing the group storage location ID (can be sent as mass assignment)
      operationId: putRestWarehousesLocationsGroup
      x-api-path-slug: restwarehouseslocationsgroup-put
      responses:
        200:
          description: OK
      tags:
      - Edit
      - Purpose
      - Statusa
      - Group
      - Of
      - Storage
      - Locations
  /rest/warehouses/{warehouseId}/locations:
    get:
      summary: List warehouse locations
      description: Lists all warehouse locations.
      operationId: getRestWarehousesWarehouseLocations
      x-api-path-slug: restwarehouseswarehouseidlocations-get
      parameters:
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - List
      - Warehouse
      - Locations
  /rest/accounting/locations:
    post:
      summary: Create an accounting location
      description: Creates an accounting location for a client. The plenty ID of the
        client must be specified.
      operationId: postRestAccountingLocations
      x-api-path-slug: restaccountinglocations-post
      parameters:
      - in: body
        name: /rest/accounting/locations
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}:
    delete:
      summary: Delete an accounting location
      description: Deletes an accounting location. The ID of the accounting location
        must be specified. Standard accounting locations can not be deleted.
      operationId: deleteRestAccountingLocationsLocation
      x-api-path-slug: restaccountinglocationslocationid-delete
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
    get:
      summary: Get an accounting location
      description: Gets an accounting location. The ID of the accounting location
        must be specified.
      operationId: getRestAccountingLocationsLocation
      x-api-path-slug: restaccountinglocationslocationid-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
    put:
      summary: Update an accounting location
      description: Updates an accounting location. The ID of the accounting location
        must be specified.
      operationId: putRestAccountingLocationsLocation
      x-api-path-slug: restaccountinglocationslocationid-put
      parameters:
      - in: body
        name: /rest/accounting/locations/{locationId}
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}/debtor_account_configurations:
    get:
      summary: Get debtor account configuration of an accounting location
      description: Gets the debtor account configuration of an accounting location.
        The ID of the accounting location has to be specified. The debtor account
        configuration can contain one standard debtor account only or e.g. several
        accounts for each country of delivery.
      operationId: getRestAccountingLocationsLocationDebtorAccountConfigurations
      x-api-path-slug: restaccountinglocationslocationiddebtor-account-configurations-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Debtor
      - Account
      - Configuration
      - Of
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}/posting_key_configurations:
    get:
      summary: Get a posting key configuration of an accounting location
      description: Gets a posting key configuration of an accounting location. The
        ID of the accounting location has to be specified. The posting key configuration
        can contain up to 4 posting keys.
      operationId: getRestAccountingLocationsLocationAddingKeyConfigurations
      x-api-path-slug: restaccountinglocationslocationidposting-key-configurations-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Key
      - Configuration
      - Of
      - Accounting
      - Location
  /rest/accounting/locations/{locationId}/revenue_account_configurations:
    get:
      summary: Get the revenue account configuration of an accounting location
      description: Gets the revenue account configuration of an accounting location.
        A revenue account location configuration contains several revenue accounts.
        The ID of the accounting location has to be specified.
      operationId: getRestAccountingLocationsLocationRevenueAccountConfigurations
      x-api-path-slug: restaccountinglocationslocationidrevenue-account-configurations-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Revenue
      - Account
      - Configuration
      - Of
      - Accounting
      - Location
  /rest/stockmanagement/warehouses/{warehouseId}/management/racks/{rackId}/shelves/{shelfId}/storageLocations/{storageLocationId}:
    get:
      summary: Get a storage location
      description: Gets a storage location. The id of the warehouse, the id of the
        rack, the id of the shelf and the id of the storage location must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementRacksRackShelvesShelfStoragelocationsStoragelocat
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: rackId
      - in: path
        name: shelfId
      - in: path
        name: storageLocationId
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Location
  /rest/stockmanagement/warehouses/{warehouseId}/management/storageLocations/{storageLocationId}:
    get:
      summary: Get a storage location
      description: Gets a storage location. The id of the storage location and the
        id of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseManagementStoragelocationsStoragelocation
      x-api-path-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
      parameters:
      - in: query
        name: columns
        description: The attributes to be loaded
      - in: path
        name: storageLocationId
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: The relations to be loaded
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Location
  /rest/stockmanagement/warehouses/{warehouseId}/stock/storageLocations:
    get:
      summary: List stock of a warehouse per storage location
      description: Lists stock of a warehouse for each variation and storage location.
        The stock will only be listed if the stock is positive. Negative stock will
        not be listed. The ID of the warehouse must be specified.
      operationId: getRestStockmanagementWarehousesWarehouseStockStoragelocations
      x-api-path-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
      parameters:
      - in: query
        name: columns
        description: The properties to be loaded
      - in: query
        name: itemsPerPage
        description: The number of items per page
      - in: query
        name: page
        description: The requested page
      - in: query
        name: storageLocationId
        description: Filter that restricts the search result to stock of a storage
          location
      - in: query
        name: updatedAtFrom
        description: Filter that restricts the search result to stock that were last
          updated on the specified date
      - in: query
        name: updatedAtTo
        description: Filter that restricts the search result to stock that were last
          updated within a specified period of time
      - in: query
        name: variationId
        description: Filter that restricts the search result to stock with a variation
      - in: path
        name: warehouseId
      - in: query
        name: with
        description: Load additional relations for a StockStorageLocation
      responses:
        200:
          description: OK
      tags:
      - List
      - Stock
      - Of
      - Warehouse
      - Per
      - Storage
      - Location
  /rest/stores/{plentyId}/locations:
    get:
      summary: Get the ID of an accounting location of a country
      description: Gets the ID of an accounting location of a country. The plenty
        ID of the client and the ID of the country must be specified.
      operationId: getRestStoresPlentyLocations
      x-api-path-slug: reststoresplentyidlocations-get
      parameters:
      - in: query
        name: countryId
        description: The ID of the country of the accounting location
      - in: path
        name: plentyId
      responses:
        200:
          description: OK
      tags:
      - ID
      - Of
      - Accounting
      - Location
      - Of
      - Country
  /rest/vat/locations/{locationId}:
    get:
      summary: List VAT configurations of an accounting location
      description: Lists the VAT configurations for all countries of one accounting
        location
      operationId: getRestVatLocationsLocation
      x-api-path-slug: restvatlocationslocationid-get
      parameters:
      - in: query
        name: columns[]
        description: The attributes of the VAT configuration
      - in: path
        name: locationId
      - in: query
        name: with[]
        description: The relations to load with the VAT object
      responses:
        200:
          description: OK
      tags:
      - List
      - VAT
      - Configurations
      - Of
      - Accounting
      - Location
  /rest/vat/locations/{locationId}/countries/{countryId}/date/{date}:
    get:
      summary: Get a VAT configuration for a country in a location.
      description: Gets the VAT configuration found by matching the given location,
        delivery country and date of validity.
      operationId: getRestVatLocationsLocationCountriesCountryDateDate
      x-api-path-slug: restvatlocationslocationidcountriescountryiddatedate-get
      parameters:
      - in: query
        name: columns[]
        description: The attributes of the VAT configuration
      - in: path
        name: countryId
      - in: path
        name: date
      - in: path
        name: locationId
      - in: query
        name: startDate
        description: The date of validity
      - in: query
        name: with[]
        description: The relations to load with the VAT object
      responses:
        200:
          description: OK
      tags:
      - VAT
      - Configurationa
      - Country
      - In
      - Location
  /rest/vat/standard:
    get:
      summary: Get a VAT configuration for the standard accounting location of a client
      description: Gets the VAT configuration currently used for the country of the
        standard accounting location of a client (store). The ID of the client (store)
        must be specified.
      operationId: getRestVatStandard
      x-api-path-slug: restvatstandard-get
      parameters:
      - in: query
        name: plentyId
        description: The plenty ID of the client (store)
      - in: query
        name: startedAt
        description: The date in the W3C format when the vat configuration went into
          effect
      responses:
        200:
          description: OK
      tags:
      - VAT
      - Configurationthe
      - Standard
      - Accounting
      - Location
      - Of
      - Client
  /rest/warehouses/layouts:
    post:
      summary: Create a warehouse location layout
      description: Creates a warehouse location layout
      operationId: postRestWarehousesLayouts
      x-api-path-slug: restwarehouseslayouts-post
      parameters:
      - in: query
        name: dimensionId
        description: The warehouse location dimension ID of the warehouse location
          level
      - in: query
        name: isActiveForPickupPath
        description: Active flag for pickup path of the warehouse location dimension
      - in: query
        name: label
        description: The label of the warehouse location
      - in: query
        name: level
        description: The level of the warehouse location dimension
      - in: query
        name: levelId
        description: The warehouse location level ID of the warehouse location
      - in: query
        name: name
        description: The name of the warehouse location dimension
      - in: query
        name: parentId
        description: The parent ID of the warehouse location dimension
      - in: query
        name: position
        description: The position of the warehouse location level
      - in: query
        name: purposeKey
        description: The location type key of the warehouse location
      - in: query
        name: separator
        description: The separator of the warehouse location dimension
      - in: query
        name: shortcut
        description: The shortcut of the warehouse location dimension
      - in: query
        name: statusKey
        description: The location status key of the warehouse location
      - in: query
        name: warehouseId
        description: The warehouse ID of the warehouse location dimension
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Layout
  /rest/warehouses/locations/details:
    get:
      summary: Get warehouse location details
      description: Gets warehouse location details
      operationId: getRestWarehousesLocationsDetails
      x-api-path-slug: restwarehouseslocationsdetails-get
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Details
  /rest/warehouses/locations/dimensions:
    post:
      summary: Create a warehouse location dimension
      description: Creates a warehouse location dimension.
      operationId: postRestWarehousesLocationsDimensions
      x-api-path-slug: restwarehouseslocationsdimensions-post
      parameters:
      - in: query
        name: isActiveForPickupPath
        description: Active flag for pickup path of the warehouse location dimension
      - in: query
        name: level
        description: The level of the warehouse location dimension
      - in: query
        name: name
        description: The name of the warehouse location dimension
      - in: query
        name: parentId
        description: The parent ID of the warehouse location dimension
      - in: query
        name: separator
        description: The separator of the warehouse location dimension
      - in: query
        name: shortcut
        description: The shortcut of the warehouse location dimension
      - in: query
        name: warehouseId
        description: The warehouse ID of the warehouse location dimension
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
  /rest/warehouses/locations/dimensions/{warehouseLocationDimensionId}:
    delete:
      summary: Delete a warehouse location dimension
      description: Deletes a warehouse location dimension
      operationId: deleteRestWarehousesLocationsDimensionsWarehouselocationdimension
      x-api-path-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
      parameters:
      - in: path
        name: warehouseLocationDimensionId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
    get:
      summary: Get a warehouse location dimension
      description: Gets a warehouse location dimension by ID. The warehouse location
        ID is required.
      operationId: getRestWarehousesLocationsDimensionsWarehouselocationdimension
      x-api-path-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
      parameters:
      - in: path
        name: warehouseLocationDimensionId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
    put:
      summary: Update a warehouse location dimension
      description: Updates a warehouse location dimension
      operationId: putRestWarehousesLocationsDimensionsWarehouselocationdimension
      x-api-path-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
      parameters:
      - in: path
        name: warehouseLocationDimensionId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Dimension
  /rest/warehouses/locations/levels:
    post:
      summary: Create a warehouse location level
      description: Creates a warehouse location level.
      operationId: postRestWarehousesLocationsLevels
      x-api-path-slug: restwarehouseslocationslevels-post
      parameters:
      - in: query
        name: dimensionId
        description: The warehouse location dimension ID of the warehouse location
          level
      - in: query
        name: name
        description: The name of the warehouse location level
      - in: query
        name: parentId
        description: The parent ID of the warehouse location level
      - in: query
        name: position
        description: The position of the warehouse location level
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
  /rest/warehouses/locations/levels/{warehouseLocationLevelId}:
    delete:
      summary: Delete a warehouse location level
      description: Deletes a warehouse location level
      operationId: deleteRestWarehousesLocationsLevelsWarehouselocationlevel
      x-api-path-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
      parameters:
      - in: path
        name: warehouseLocationLevelId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
    get:
      summary: Get a warehouse location level
      description: Gets a warehouse location level by ID. The warehouse location ID
        is required.
      operationId: getRestWarehousesLocationsLevelsWarehouselocationlevel
      x-api-path-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
      parameters:
      - in: path
        name: warehouseLocationLevelId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
    put:
      summary: Update a warehouse location level
      description: Updates a warehouse location level
      operationId: putRestWarehousesLocationsLevelsWarehouselocationlevel
      x-api-path-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
      parameters:
      - in: path
        name: warehouseLocationLevelId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Level
  /rest/warehouses/locations/multiple_dimensions:
    post:
      summary: Create multiple warehouse location dimensions
      description: Creates multiple warehouse location dimension.
      operationId: postRestWarehousesLocationsMultipleDimensions
      x-api-path-slug: restwarehouseslocationsmultiple-dimensions-post
      responses:
        200:
          description: OK
      tags:
      - Multiple
      - Warehouse
      - Location
      - Dimensions
  /rest/warehouses/locations/previews:
    post:
      summary: Generate warehouse location preview and saves it
      description: Generates warehouse location preview and saves it
      operationId: postRestWarehousesLocationsPreviews
      x-api-path-slug: restwarehouseslocationspreviews-post
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Warehouse
      - Location
      - Preview
      - Saves
      - It
  /rest/warehouses/locations/{warehouseId}/label:
    get:
      summary: Generate the warehouse location label
      description: Generates the warehouse location label
      operationId: getRestWarehousesLocationsWarehouseLabel
      x-api-path-slug: restwarehouseslocationswarehouseidlabel-get
      parameters:
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Generate
      - Warehouse
      - Location
      - Label
  /rest/warehouses/locations/{warehouseLocationId}:
    delete:
      summary: Delete a warehouse location
      description: Deletes a warehouse location
      operationId: deleteRestWarehousesLocationsWarehouselocation
      x-api-path-slug: restwarehouseslocationswarehouselocationid-delete
      parameters:
      - in: path
        name: warehouseLocationId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
    get:
      summary: Get a warehouse location
      description: Gets a warehouse location by ID. The warehouse location ID is required.
      operationId: getRestWarehousesLocationsWarehouselocation
      x-api-path-slug: restwarehouseslocationswarehouselocationid-get
      parameters:
      - in: path
        name: warehouseLocationId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
    put:
      summary: Update a warehouse location
      description: Updates a warehouse location
      operationId: putRestWarehousesLocationsWarehouselocation
      x-api-path-slug: restwarehouseslocationswarehouselocationid-put
      parameters:
      - in: path
        name: warehouseLocationId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
  /rest/warehouses/structure/{warehouseId}:
    get:
      summary: Get a warehouse location structure
      description: Gets a warehouse location structure by warehouse ID. The warehouse
        ID is required.
      operationId: getRestWarehousesStructureWarehouse
      x-api-path-slug: restwarehousesstructurewarehouseid-get
      parameters:
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - Warehouse
      - Location
      - Structure
  /rest/warehouses/{warehouseId}/locations/dimensions:
    get:
      summary: List warehouse location dimensions
      description: Lists all warehouse location dimensions.
      operationId: getRestWarehousesWarehouseLocationsDimensions
      x-api-path-slug: restwarehouseswarehouseidlocationsdimensions-get
      parameters:
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - List
      - Warehouse
      - Location
      - Dimensions
  /rest/warehouses/{warehouseId}/locations/levels:
    get:
      summary: List warehouse location levels
      description: Lists all warehouse location levels.
      operationId: getRestWarehousesWarehouseLocationsLevels
      x-api-path-slug: restwarehouseswarehouseidlocationslevels-get
      parameters:
      - in: path
        name: warehouseId
      responses:
        200:
          description: OK
      tags:
      - List
      - Warehouse
      - Location
      - Levels
  /rest/accounting/locations/{locationId}/posting_accounts:
    get:
      summary: Get all posting accounts by locationId
      description: Get all posting accounts by locationid.
      operationId: getRestAccountingLocationsLocationAddingAccounts
      x-api-path-slug: restaccountinglocationslocationidposting-accounts-get
      parameters:
      - in: path
        name: locationId
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accounts
      - By
      - LocationId
  /rest/accounting/locations/{locationId}/{type}/posting_accounts:
    get:
      summary: Get all posting accounts by locationId and type
      description: Get all posting accounts by locationid and type.
      operationId: getRestAccountingLocationsLocationTypeAddingAccounts
      x-api-path-slug: restaccountinglocationslocationidtypeposting-accounts-get
      parameters:
      - in: path
        name: locationId
      - in: path
        name: type
      responses:
        200:
          description: OK
      tags:
      - Posting
      - Accounts
      - By
      - LocationId
      - Type
---