---
swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
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
  /api/v1/place/{placeId}/reviews/{page}/{pageSize}:
    get:
      summary: Get Place Placeid Reviews Page Pagesize
      description: Get place placeid reviews page pagesize.
      operationId: getApiV1PlacePlaceReviewsPagePagesize
      x-api-path-slug: apiv1placeplaceidreviewspagepagesize-get
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
      - Place
      - Placeid
      - Reviews
      - Page
      - Pagesize
---