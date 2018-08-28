---
name: Plentymarkets
x-slug: plentymarkets
description: plentymarkets is an all-in-one e-commerce ERP solution, which combines
  a comprehensive stock management system with a versatile shop system and effortless
  multichannel sales. Thanks to comprehensive functions and interfaces that include
  all steps of the e-commerce value chain, you can use the cloud based software to
  completely automate all of your e-business processes as well as your companys own
  individual processes.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
x-kinRank: "7"
x-alexaRank: ""
tags: Locations
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/apis.md
specificationVersion: "0.14"
apis:
- name: plentymarkets REST-API - List all accounting locations
  x-api-slug: restaccountingstoreslocations-get
  description: List all accounting locations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountingstoreslocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountingstoreslocations-get-openapi.md
- name: plentymarkets REST-API - List accounting locations of a client
  x-api-slug: restaccountingstoresplentyidlocations-get
  description: Lists accounting locations of a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountingstoresplentyidlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountingstoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - List stock of a variation per storage locations
  x-api-slug: restitemsidvariationsvariationidstockstoragelocations-get
  description: Lists stock of a variation per storage location. The ID of the item
    and the ID of the variation must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restitemsidvariationsvariationidstockstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restitemsidvariationsvariationidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - List storage locations
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get
  description: Lists storage locations. The id of the warehouse, the id of the rack
    and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-get-openapi.md
- name: plentymarkets REST-API - List storage locations
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get
  description: Lists storage locations that belong to a warehouse. The id of the warehouse
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Delete multiple warehouse locations
  x-api-slug: restwarehouseslocations-delete
  description: Deletes multiple warehouse locations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocations-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocations-delete-openapi.md
- name: plentymarkets REST-API - Edit the purpose and status for a group of storage
    locations
  x-api-slug: restwarehouseslocationsgroup-put
  description: Edits the purpose and status for a group of storage locations by passing
    the group storage location ID (can be sent as mass assignment)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsgroup-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsgroup-put-openapi.md
- name: plentymarkets REST-API - List warehouse locations
  x-api-slug: restwarehouseswarehouseidlocations-get
  description: Lists all warehouse locations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocations-get-openapi.md
- name: plentymarkets REST-API - Create an accounting location
  x-api-slug: restaccountinglocations-post
  description: Creates an accounting location for a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocations-post-openapi.md
- name: plentymarkets REST-API - Delete an accounting location
  x-api-slug: restaccountinglocationslocationid-delete
  description: Deletes an accounting location. The ID of the accounting location must
    be specified. Standard accounting locations can not be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-delete-openapi.md
- name: plentymarkets REST-API - Get an accounting location
  x-api-slug: restaccountinglocationslocationid-get
  description: Gets an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Update an accounting location
  x-api-slug: restaccountinglocationslocationid-put
  description: Updates an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-put-openapi.md
- name: plentymarkets REST-API - Get debtor account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationiddebtor-account-configurations-get
  description: Gets the debtor account configuration of an accounting location. The
    ID of the accounting location has to be specified. The debtor account configuration
    can contain one standard debtor account only or e.g. several accounts for each
    country of delivery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get a posting key configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidposting-key-configurations-get
  description: Gets a posting key configuration of an accounting location. The ID
    of the accounting location has to be specified. The posting key configuration
    can contain up to 4 posting keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-key-configurations-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidrevenue-account-configurations-get
  description: Gets the revenue account configuration of an accounting location. A
    revenue account location configuration contains several revenue accounts. The
    ID of the accounting location has to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidrevenue-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Create a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
  description: Creates a storage location. The id of the warehouse, the id of the
    rack and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the warehouse, the id of the rack,
    the id of the shelf and the id of the storage location must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the storage location and the id
    of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations of an accounting location
  x-api-slug: restvatlocationslocationid-get
  description: Lists the VAT configurations for all countries of one accounting location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for the standard accounting
    location of a client
  x-api-slug: restvatstandard-get
  description: Gets the VAT configuration currently used for the country of the standard
    accounting location of a client (store). The ID of the client (store) must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatstandard-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location layout
  x-api-slug: restwarehouseslayouts-post
  description: Creates a warehouse location layout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslayouts-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location
  x-api-slug: restwarehouseslocations-post
  description: Creates a warehouse location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocations-post-openapi.md
- name: plentymarkets REST-API - Get warehouse location details
  x-api-slug: restwarehouseslocationsdetails-get
  description: Gets warehouse location details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdetails-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensions-post
  description: Creates a warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensions-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
  description: Deletes a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
  description: Gets a warehouse location dimension by ID. The warehouse location ID
    is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
  description: Updates a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-put-openapi.md
- name: plentymarkets REST-API - Create a warehouse location level
  x-api-slug: restwarehouseslocationslevels-post
  description: Creates a warehouse location level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevels-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
  description: Deletes a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
  description: Gets a warehouse location level by ID. The warehouse location ID is
    required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
  description: Updates a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-put-openapi.md
- name: plentymarkets REST-API - Create multiple warehouse location dimensions
  x-api-slug: restwarehouseslocationsmultiple-dimensions-post
  description: Creates multiple warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsmultiple-dimensions-post-openapi.md
- name: plentymarkets REST-API - Generate warehouse location preview and saves it
  x-api-slug: restwarehouseslocationspreviews-post
  description: Generates warehouse location preview and saves it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationspreviews-post-openapi.md
- name: plentymarkets REST-API - Generate the warehouse location label
  x-api-slug: restwarehouseslocationswarehouseidlabel-get
  description: Generates the warehouse location label
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouseidlabel-get-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-delete
  description: Deletes a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-get
  description: Gets a warehouse location by ID. The warehouse location ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-put
  description: Updates a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-put-openapi.md
- name: plentymarkets REST-API - Get a warehouse location structure
  x-api-slug: restwarehousesstructurewarehouseid-get
  description: Gets a warehouse location structure by warehouse ID. The warehouse
    ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehousesstructurewarehouseid-get-openapi.md
- name: plentymarkets REST-API - List warehouse location dimensions
  x-api-slug: restwarehouseswarehouseidlocationsdimensions-get
  description: Lists all warehouse location dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationsdimensions-get-openapi.md
- name: plentymarkets REST-API - List warehouse location levels
  x-api-slug: restwarehouseswarehouseidlocationslevels-get
  description: Lists all warehouse location levels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationslevels-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId
  x-api-slug: restaccountinglocationslocationidposting-accounts-get
  description: Get all posting accounts by locationid.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId and type
  x-api-slug: restaccountinglocationslocationidtypeposting-accounts-get
  description: Get all posting accounts by locationid and type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidtypeposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Create an accounting location
  x-api-slug: restaccountinglocations-post
  description: Creates an accounting location for a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocations-post-openapi.md
- name: plentymarkets REST-API - Delete an accounting location
  x-api-slug: restaccountinglocationslocationid-delete
  description: Deletes an accounting location. The ID of the accounting location must
    be specified. Standard accounting locations can not be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-delete-openapi.md
- name: plentymarkets REST-API - Get an accounting location
  x-api-slug: restaccountinglocationslocationid-get
  description: Gets an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Update an accounting location
  x-api-slug: restaccountinglocationslocationid-put
  description: Updates an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-put-openapi.md
- name: plentymarkets REST-API - Get debtor account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationiddebtor-account-configurations-get
  description: Gets the debtor account configuration of an accounting location. The
    ID of the accounting location has to be specified. The debtor account configuration
    can contain one standard debtor account only or e.g. several accounts for each
    country of delivery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get a posting key configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidposting-key-configurations-get
  description: Gets a posting key configuration of an accounting location. The ID
    of the accounting location has to be specified. The posting key configuration
    can contain up to 4 posting keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-key-configurations-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidrevenue-account-configurations-get
  description: Gets the revenue account configuration of an accounting location. A
    revenue account location configuration contains several revenue accounts. The
    ID of the accounting location has to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidrevenue-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Create a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
  description: Creates a storage location. The id of the warehouse, the id of the
    rack and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the warehouse, the id of the rack,
    the id of the shelf and the id of the storage location must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the storage location and the id
    of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations of an accounting location
  x-api-slug: restvatlocationslocationid-get
  description: Lists the VAT configurations for all countries of one accounting location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for the standard accounting
    location of a client
  x-api-slug: restvatstandard-get
  description: Gets the VAT configuration currently used for the country of the standard
    accounting location of a client (store). The ID of the client (store) must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatstandard-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location layout
  x-api-slug: restwarehouseslayouts-post
  description: Creates a warehouse location layout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslayouts-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location
  x-api-slug: restwarehouseslocations-post
  description: Creates a warehouse location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocations-post-openapi.md
- name: plentymarkets REST-API - Get warehouse location details
  x-api-slug: restwarehouseslocationsdetails-get
  description: Gets warehouse location details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdetails-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensions-post
  description: Creates a warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensions-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
  description: Deletes a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
  description: Gets a warehouse location dimension by ID. The warehouse location ID
    is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
  description: Updates a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-put-openapi.md
- name: plentymarkets REST-API - Create a warehouse location level
  x-api-slug: restwarehouseslocationslevels-post
  description: Creates a warehouse location level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevels-post-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
  description: Deletes a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
  description: Gets a warehouse location level by ID. The warehouse location ID is
    required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
  description: Updates a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-put-openapi.md
- name: plentymarkets REST-API - Create multiple warehouse location dimensions
  x-api-slug: restwarehouseslocationsmultiple-dimensions-post
  description: Creates multiple warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsmultiple-dimensions-post-openapi.md
- name: plentymarkets REST-API - Generate warehouse location preview and saves it
  x-api-slug: restwarehouseslocationspreviews-post
  description: Generates warehouse location preview and saves it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationspreviews-post-openapi.md
- name: plentymarkets REST-API - Generate the warehouse location label
  x-api-slug: restwarehouseslocationswarehouseidlabel-get
  description: Generates the warehouse location label
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouseidlabel-get-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-delete
  description: Deletes a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-delete-openapi.md
- name: plentymarkets REST-API - Get a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-get
  description: Gets a warehouse location by ID. The warehouse location ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-put
  description: Updates a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-put-openapi.md
- name: plentymarkets REST-API - Get a warehouse location structure
  x-api-slug: restwarehousesstructurewarehouseid-get
  description: Gets a warehouse location structure by warehouse ID. The warehouse
    ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehousesstructurewarehouseid-get-openapi.md
- name: plentymarkets REST-API - List warehouse location dimensions
  x-api-slug: restwarehouseswarehouseidlocationsdimensions-get
  description: Lists all warehouse location dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationsdimensions-get-openapi.md
- name: plentymarkets REST-API - List warehouse location levels
  x-api-slug: restwarehouseswarehouseidlocationslevels-get
  description: Lists all warehouse location levels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationslevels-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId
  x-api-slug: restaccountinglocationslocationidposting-accounts-get
  description: Get all posting accounts by locationid.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId and type
  x-api-slug: restaccountinglocationslocationidtypeposting-accounts-get
  description: Get all posting accounts by locationid and type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidtypeposting-accounts-get-openapi.md
- name: plentymarkets REST-API - List warehouse location levels
  x-api-slug: restwarehouseswarehouseidlocationslevels-get
  description: Lists all warehouse location levels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationslevels-get-openapi.md
- name: plentymarkets REST-API - List warehouse location levels
  x-api-slug: restwarehouseswarehouseidlocationslevels-get
  description: Lists all warehouse location levels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationslevels-get-openapi.md
- name: plentymarkets REST-API - List warehouse location levels
  x-api-slug: restwarehouseswarehouseidlocationslevels-get
  description: Lists all warehouse location levels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationslevels-get-openapi.md
- name: plentymarkets REST-API - List warehouse location dimensions
  x-api-slug: restwarehouseswarehouseidlocationsdimensions-get
  description: Lists all warehouse location dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationsdimensions-get-openapi.md
- name: plentymarkets REST-API - List warehouse location dimensions
  x-api-slug: restwarehouseswarehouseidlocationsdimensions-get
  description: Lists all warehouse location dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationsdimensions-get-openapi.md
- name: plentymarkets REST-API - List warehouse location dimensions
  x-api-slug: restwarehouseswarehouseidlocationsdimensions-get
  description: Lists all warehouse location dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseswarehouseidlocationsdimensions-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location structure
  x-api-slug: restwarehousesstructurewarehouseid-get
  description: Gets a warehouse location structure by warehouse ID. The warehouse
    ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehousesstructurewarehouseid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location structure
  x-api-slug: restwarehousesstructurewarehouseid-get
  description: Gets a warehouse location structure by warehouse ID. The warehouse
    ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehousesstructurewarehouseid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location structure
  x-api-slug: restwarehousesstructurewarehouseid-get
  description: Gets a warehouse location structure by warehouse ID. The warehouse
    ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehousesstructurewarehouseid-get-openapi.md
- name: plentymarkets REST-API - Update a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-put
  description: Updates a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-put-openapi.md
- name: plentymarkets REST-API - Update a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-put
  description: Updates a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-put-openapi.md
- name: plentymarkets REST-API - Update a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-put
  description: Updates a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-put-openapi.md
- name: plentymarkets REST-API - Get a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-get
  description: Gets a warehouse location by ID. The warehouse location ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-get
  description: Gets a warehouse location by ID. The warehouse location ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-get
  description: Gets a warehouse location by ID. The warehouse location ID is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-get-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-delete
  description: Deletes a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-delete-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-delete
  description: Deletes a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-delete-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location
  x-api-slug: restwarehouseslocationswarehouselocationid-delete
  description: Deletes a warehouse location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouselocationid-delete-openapi.md
- name: plentymarkets REST-API - Generate the warehouse location label
  x-api-slug: restwarehouseslocationswarehouseidlabel-get
  description: Generates the warehouse location label
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouseidlabel-get-openapi.md
- name: plentymarkets REST-API - Generate the warehouse location label
  x-api-slug: restwarehouseslocationswarehouseidlabel-get
  description: Generates the warehouse location label
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouseidlabel-get-openapi.md
- name: plentymarkets REST-API - Generate the warehouse location label
  x-api-slug: restwarehouseslocationswarehouseidlabel-get
  description: Generates the warehouse location label
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationswarehouseidlabel-get-openapi.md
- name: plentymarkets REST-API - Generate warehouse location preview and saves it
  x-api-slug: restwarehouseslocationspreviews-post
  description: Generates warehouse location preview and saves it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationspreviews-post-openapi.md
- name: plentymarkets REST-API - Generate warehouse location preview and saves it
  x-api-slug: restwarehouseslocationspreviews-post
  description: Generates warehouse location preview and saves it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationspreviews-post-openapi.md
- name: plentymarkets REST-API - Generate warehouse location preview and saves it
  x-api-slug: restwarehouseslocationspreviews-post
  description: Generates warehouse location preview and saves it
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationspreviews-post-openapi.md
- name: plentymarkets REST-API - Create multiple warehouse location dimensions
  x-api-slug: restwarehouseslocationsmultiple-dimensions-post
  description: Creates multiple warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsmultiple-dimensions-post-openapi.md
- name: plentymarkets REST-API - Create multiple warehouse location dimensions
  x-api-slug: restwarehouseslocationsmultiple-dimensions-post
  description: Creates multiple warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsmultiple-dimensions-post-openapi.md
- name: plentymarkets REST-API - Create multiple warehouse location dimensions
  x-api-slug: restwarehouseslocationsmultiple-dimensions-post
  description: Creates multiple warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsmultiple-dimensions-post-openapi.md
- name: plentymarkets REST-API - Update a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
  description: Updates a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-put-openapi.md
- name: plentymarkets REST-API - Update a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
  description: Updates a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-put-openapi.md
- name: plentymarkets REST-API - Update a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-put
  description: Updates a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-put-openapi.md
- name: plentymarkets REST-API - Get a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
  description: Gets a warehouse location level by ID. The warehouse location ID is
    required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
  description: Gets a warehouse location level by ID. The warehouse location ID is
    required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-get
  description: Gets a warehouse location level by ID. The warehouse location ID is
    required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-get-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
  description: Deletes a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-delete-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
  description: Deletes a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-delete-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location level
  x-api-slug: restwarehouseslocationslevelswarehouselocationlevelid-delete
  description: Deletes a warehouse location level
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevelswarehouselocationlevelid-delete-openapi.md
- name: plentymarkets REST-API - Create a warehouse location level
  x-api-slug: restwarehouseslocationslevels-post
  description: Creates a warehouse location level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevels-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location level
  x-api-slug: restwarehouseslocationslevels-post
  description: Creates a warehouse location level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevels-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location level
  x-api-slug: restwarehouseslocationslevels-post
  description: Creates a warehouse location level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationslevels-post-openapi.md
- name: plentymarkets REST-API - Update a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
  description: Updates a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-put-openapi.md
- name: plentymarkets REST-API - Update a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
  description: Updates a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-put-openapi.md
- name: plentymarkets REST-API - Update a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-put
  description: Updates a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-put-openapi.md
- name: plentymarkets REST-API - Get a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
  description: Gets a warehouse location dimension by ID. The warehouse location ID
    is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
  description: Gets a warehouse location dimension by ID. The warehouse location ID
    is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-get-openapi.md
- name: plentymarkets REST-API - Get a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-get
  description: Gets a warehouse location dimension by ID. The warehouse location ID
    is required.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-get-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
  description: Deletes a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-delete-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
  description: Deletes a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-delete-openapi.md
- name: plentymarkets REST-API - Delete a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensionswarehouselocationdimensionid-delete
  description: Deletes a warehouse location dimension
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensionswarehouselocationdimensionid-delete-openapi.md
- name: plentymarkets REST-API - Create a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensions-post
  description: Creates a warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensions-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensions-post
  description: Creates a warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensions-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location dimension
  x-api-slug: restwarehouseslocationsdimensions-post
  description: Creates a warehouse location dimension.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdimensions-post-openapi.md
- name: plentymarkets REST-API - Get warehouse location details
  x-api-slug: restwarehouseslocationsdetails-get
  description: Gets warehouse location details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdetails-get-openapi.md
- name: plentymarkets REST-API - Get warehouse location details
  x-api-slug: restwarehouseslocationsdetails-get
  description: Gets warehouse location details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdetails-get-openapi.md
- name: plentymarkets REST-API - Get warehouse location details
  x-api-slug: restwarehouseslocationsdetails-get
  description: Gets warehouse location details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocationsdetails-get-openapi.md
- name: plentymarkets REST-API - Create a warehouse location
  x-api-slug: restwarehouseslocations-post
  description: Creates a warehouse location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocations-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location
  x-api-slug: restwarehouseslocations-post
  description: Creates a warehouse location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocations-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location
  x-api-slug: restwarehouseslocations-post
  description: Creates a warehouse location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslocations-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location layout
  x-api-slug: restwarehouseslayouts-post
  description: Creates a warehouse location layout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslayouts-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location layout
  x-api-slug: restwarehouseslayouts-post
  description: Creates a warehouse location layout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslayouts-post-openapi.md
- name: plentymarkets REST-API - Create a warehouse location layout
  x-api-slug: restwarehouseslayouts-post
  description: Creates a warehouse location layout
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restwarehouseslayouts-post-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for the standard accounting
    location of a client
  x-api-slug: restvatstandard-get
  description: Gets the VAT configuration currently used for the country of the standard
    accounting location of a client (store). The ID of the client (store) must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatstandard-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for the standard accounting
    location of a client
  x-api-slug: restvatstandard-get
  description: Gets the VAT configuration currently used for the country of the standard
    accounting location of a client (store). The ID of the client (store) must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatstandard-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for the standard accounting
    location of a client
  x-api-slug: restvatstandard-get
  description: Gets the VAT configuration currently used for the country of the standard
    accounting location of a client (store). The ID of the client (store) must be
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatstandard-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - Get a VAT configuration for a country in a location.
  x-api-slug: restvatlocationslocationidcountriescountryiddatedate-get
  description: Gets the VAT configuration found by matching the given location, delivery
    country and date of validity.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationidcountriescountryiddatedate-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations of an accounting location
  x-api-slug: restvatlocationslocationid-get
  description: Lists the VAT configurations for all countries of one accounting location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationid-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations of an accounting location
  x-api-slug: restvatlocationslocationid-get
  description: Lists the VAT configurations for all countries of one accounting location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationid-get-openapi.md
- name: plentymarkets REST-API - List VAT configurations of an accounting location
  x-api-slug: restvatlocationslocationid-get
  description: Lists the VAT configurations for all countries of one accounting location
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restvatlocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - Get the ID of an accounting location of a country
  x-api-slug: reststoresplentyidlocations-get
  description: Gets the ID of an accounting location of a country. The plenty ID of
    the client and the ID of the country must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststoresplentyidlocations-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - List stock of a warehouse per storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidstockstoragelocations-get
  description: Lists stock of a warehouse for each variation and storage location.
    The stock will only be listed if the stock is positive. Negative stock will not
    be listed. The ID of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidstockstoragelocations-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the storage location and the id
    of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the storage location and the id
    of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the storage location and the id
    of the warehouse must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the warehouse, the id of the rack,
    the id of the shelf and the id of the storage location must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the warehouse, the id of the rack,
    the id of the shelf and the id of the storage location must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Get a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get
  description: Gets a storage location. The id of the warehouse, the id of the rack,
    the id of the shelf and the id of the storage location must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocationsstoragelocationid-get-openapi.md
- name: plentymarkets REST-API - Create a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
  description: Creates a storage location. The id of the warehouse, the id of the
    rack and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post-openapi.md
- name: plentymarkets REST-API - Create a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
  description: Creates a storage location. The id of the warehouse, the id of the
    rack and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post-openapi.md
- name: plentymarkets REST-API - Create a storage location
  x-api-slug: reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post
  description: Creates a storage location. The id of the warehouse, the id of the
    rack and the id of the shelf must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/reststockmanagementwarehouseswarehouseidmanagementracksrackidshelvesshelfidstoragelocations-post-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidrevenue-account-configurations-get
  description: Gets the revenue account configuration of an accounting location. A
    revenue account location configuration contains several revenue accounts. The
    ID of the accounting location has to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidrevenue-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidrevenue-account-configurations-get
  description: Gets the revenue account configuration of an accounting location. A
    revenue account location configuration contains several revenue accounts. The
    ID of the accounting location has to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidrevenue-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get the revenue account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidrevenue-account-configurations-get
  description: Gets the revenue account configuration of an accounting location. A
    revenue account location configuration contains several revenue accounts. The
    ID of the accounting location has to be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidrevenue-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get a posting key configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidposting-key-configurations-get
  description: Gets a posting key configuration of an accounting location. The ID
    of the accounting location has to be specified. The posting key configuration
    can contain up to 4 posting keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-key-configurations-get-openapi.md
- name: plentymarkets REST-API - Get a posting key configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidposting-key-configurations-get
  description: Gets a posting key configuration of an accounting location. The ID
    of the accounting location has to be specified. The posting key configuration
    can contain up to 4 posting keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-key-configurations-get-openapi.md
- name: plentymarkets REST-API - Get a posting key configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationidposting-key-configurations-get
  description: Gets a posting key configuration of an accounting location. The ID
    of the accounting location has to be specified. The posting key configuration
    can contain up to 4 posting keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-key-configurations-get-openapi.md
- name: plentymarkets REST-API - Get debtor account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationiddebtor-account-configurations-get
  description: Gets the debtor account configuration of an accounting location. The
    ID of the accounting location has to be specified. The debtor account configuration
    can contain one standard debtor account only or e.g. several accounts for each
    country of delivery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get debtor account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationiddebtor-account-configurations-get
  description: Gets the debtor account configuration of an accounting location. The
    ID of the accounting location has to be specified. The debtor account configuration
    can contain one standard debtor account only or e.g. several accounts for each
    country of delivery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Get debtor account configuration of an accounting
    location
  x-api-slug: restaccountinglocationslocationiddebtor-account-configurations-get
  description: Gets the debtor account configuration of an accounting location. The
    ID of the accounting location has to be specified. The debtor account configuration
    can contain one standard debtor account only or e.g. several accounts for each
    country of delivery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationiddebtor-account-configurations-get-openapi.md
- name: plentymarkets REST-API - Update an accounting location
  x-api-slug: restaccountinglocationslocationid-put
  description: Updates an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-put-openapi.md
- name: plentymarkets REST-API - Update an accounting location
  x-api-slug: restaccountinglocationslocationid-put
  description: Updates an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-put-openapi.md
- name: plentymarkets REST-API - Update an accounting location
  x-api-slug: restaccountinglocationslocationid-put
  description: Updates an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-put-openapi.md
- name: plentymarkets REST-API - Get an accounting location
  x-api-slug: restaccountinglocationslocationid-get
  description: Gets an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Get an accounting location
  x-api-slug: restaccountinglocationslocationid-get
  description: Gets an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Get an accounting location
  x-api-slug: restaccountinglocationslocationid-get
  description: Gets an accounting location. The ID of the accounting location must
    be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-get-openapi.md
- name: plentymarkets REST-API - Delete an accounting location
  x-api-slug: restaccountinglocationslocationid-delete
  description: Deletes an accounting location. The ID of the accounting location must
    be specified. Standard accounting locations can not be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-delete-openapi.md
- name: plentymarkets REST-API - Delete an accounting location
  x-api-slug: restaccountinglocationslocationid-delete
  description: Deletes an accounting location. The ID of the accounting location must
    be specified. Standard accounting locations can not be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-delete-openapi.md
- name: plentymarkets REST-API - Delete an accounting location
  x-api-slug: restaccountinglocationslocationid-delete
  description: Deletes an accounting location. The ID of the accounting location must
    be specified. Standard accounting locations can not be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationid-delete-openapi.md
- name: plentymarkets REST-API - Create an accounting location
  x-api-slug: restaccountinglocations-post
  description: Creates an accounting location for a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocations-post-openapi.md
- name: plentymarkets REST-API - Create an accounting location
  x-api-slug: restaccountinglocations-post
  description: Creates an accounting location for a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocations-post-openapi.md
- name: plentymarkets REST-API - Create an accounting location
  x-api-slug: restaccountinglocations-post
  description: Creates an accounting location for a client. The plenty ID of the client
    must be specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocations-post-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId and type
  x-api-slug: restaccountinglocationslocationidtypeposting-accounts-get
  description: Get all posting accounts by locationid and type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidtypeposting-accounts-get-openapi.md
- name: plentymarkets REST-API - Get all posting accounts by locationId
  x-api-slug: restaccountinglocationslocationidposting-accounts-get
  description: Get all posting accounts by locationid.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/plentymarkets.png
  humanURL: http://www.plentymarkets.co.uk
  baseURL: https://example.com//
  tags: ERP, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/locations/master/_listings/plentymarkets/restaccountinglocationslocationidposting-accounts-get-openapi.md
x-common:
- type: x-blog-rss
  url: https://www.plentymarkets.co.uk/?ActionCall=WebActionRSS&rrss_id=1
- type: x-github
  url: https://github.com/plentymarkets
- type: x-twitter
  url: https://twitter.com/plentymarketsuk
- type: x-website
  url: http://www.plentymarkets.co.uk
- type: x-api-gallery
  url: http://pivotal.tracker.api.gallery.streamdata.io
- type: x-api-stack
  url: http://plentymarkets.stack.network
- type: x-blog
  url: https://www.plentymarkets.co.uk/blog/
- type: x-pricing
  url: https://www.plentymarkets.co.uk/prices/
- type: x-website
  url: https://www.plentymarkets.co.uk
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---