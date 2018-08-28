---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 0
info:
  title: GIGANDCROWD Get Gigme Place Placeid Reviews Page Pagesize
  version: 1.0.0
  description: Get gigme place placeid reviews page pagesize.
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/gigme/place/{placeId}/reviews/{page}/{pageSize}:
    get:
      summary: Get Gigme Place Placeid Reviews Page Pagesize
      description: Get gigme place placeid reviews page pagesize.
      operationId: getApiV1GigmePlacePlaceReviewsPagePagesize
      x-api-path-slug: apiv1gigmeplaceplaceidreviewspagepagesize-get
      parameters:
      - in: path
        name: page
      - in: path
        name: pageSize
      - in: path
        name: placeId
      responses:
        200:
          description: OK
      tags:
      - Gigme
      - Place
      - Placeid
      - Reviews
      - Page
      - Pagesize
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