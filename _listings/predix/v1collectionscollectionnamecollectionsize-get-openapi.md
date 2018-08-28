---
swagger: "2.0"
x-collection-name: Predix
x-complete: 0
info:
  title: Predix Intelligent Mapping Return the size of a collection.
  description: |-
    Returns the size of the specified collection to decide whether to use the whole collection for spatial query
    or not.
  version: 1.0.0
host: insights-api.data-services.predix.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/collections/{collectionName}/collectionSize:
    get:
      summary: Return the size of a collection.
      description: |-
        Returns the size of the specified collection to decide whether to use the whole collection for spatial query
        or not.
      operationId: returns-the-size-of-the-specified-collection-to-decide-whether-to-use-the-whole-collection-for-spati
      x-api-path-slug: v1collectionscollectionnamecollectionsize-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Return
      - Size
      - Of
      - Collection
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