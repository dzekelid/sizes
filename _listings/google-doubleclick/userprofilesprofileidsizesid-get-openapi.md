---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Get Size
  version: 1.0.0
  description: Gets one size by ID.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/sizes:
    get:
      summary: Get Sizes
      description: Retrieves a list of sizes, possibly filtered.
      operationId: dfareporting.sizes.list
      x-api-path-slug: userprofilesprofileidsizes-get
      parameters:
      - in: query
        name: height
        description: Select only sizes with this height
      - in: query
        name: iabStandard
        description: Select only IAB standard sizes
      - in: query
        name: ids
        description: Select only sizes with these IDs
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: width
        description: Select only sizes with this width
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Size
    post:
      summary: Insert Size
      description: Inserts a new size.
      operationId: dfareporting.sizes.insert
      x-api-path-slug: userprofilesprofileidsizes-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Size
  /userprofiles/{profileId}/sizes/{id}:
    get:
      summary: Get Size
      description: Gets one size by ID.
      operationId: dfareporting.sizes.get
      x-api-path-slug: userprofilesprofileidsizesid-get
      parameters:
      - in: path
        name: id
        description: Size ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Size
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