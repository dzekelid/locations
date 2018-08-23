---
swagger: "2.0"
x-collection-name: Google Cloud Key Management Service
x-complete: 1
info:
  title: Google Cloud Key Management Service (KMS)
  description: manages-encryption-for-your-cloud-services-the-same-way-you-do-onpremise--you-can-generate-use-rotate-and-destroy-aes256-encryption-keys-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: cloudkms.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}/locations:
    get:
      summary: Get Locations
      description: Lists information about the supported locations for this service.
      operationId: cloudkms.projects.locations.list
      x-api-path-slug: v1namelocations-get
      parameters:
      - in: query
        name: filter
        description: The standard list filter
      - in: path
        name: name
        description: The resource that owns the locations collection, if applicable
      - in: query
        name: pageSize
        description: The standard list page size
      - in: query
        name: pageToken
        description: The standard list page token
      responses:
        200:
          description: OK
      tags:
      - Location
  /v1/{name}:decrypt:
    post:
      summary: Decrypt Data
      description: Decrypt data that was protected by Encrypt.
      operationId: cloudkms.projects.locations.keyRings.cryptoKeys.decrypt
      x-api-path-slug: v1namedecrypt-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Location
---