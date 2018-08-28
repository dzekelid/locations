swagger: "2.0"
x-collection-name: Site24x7
x-complete: 1
info:
  title: User Group API
  description: the-user-group-api-
  version: 1.0.0
host: www.site24x7.com.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /location_profiles/{profile_id}:
    get:
      summary: Retrieve Location Profile
      description: Retrieve configuration of a location profile.
      operationId: retrieve-location-profile
      x-api-path-slug: location-profilesprofile-id-get
      responses:
        Maximum record size:
          description: 100 KiB
        Maximum number of records per datastore:
          description: "100,000"
        Maximum datastore size:
          description: 10 MiB
        Maximum size of a delta:
          description: 2 MiB
      tags:
      - Location Profiles
    delete:
      summary: Delete Location Profile
      description: Delete an existing location profile.
      operationId: delete-location-profile
      x-api-path-slug: location-profilesprofile-id-delete
      responses:
        Maximum record size:
          description: 100 KiB
        Maximum number of records per datastore:
          description: "100,000"
        Maximum datastore size:
          description: 10 MiB
        Maximum size of a delta:
          description: 2 MiB
      tags:
      - Location Profiles