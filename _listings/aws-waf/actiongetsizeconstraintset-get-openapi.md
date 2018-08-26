---
swagger: "2.0"
x-collection-name: AWS WAF
x-complete: 0
info:
  title: AWS WAF API Get Size Constraint Set
  version: 1.0.0
  description: 'Service: AWS WAFReturns the.'
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateSizeConstraintSet:
    get:
      summary: Create Size Constraint Set
      description: 'Service: AWS WAFCreates a SizeConstraintSet.'
      operationId: createSizeConstraintSet
      x-api-path-slug: actioncreatesizeconstraintset-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: Name
        description: A friendly name or description of the SizeConstraintSet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Size Constraint Set
  /?Action=DeleteSizeConstraintSet:
    get:
      summary: Delete Size Constraint Set
      description: 'Service: AWS WAFPermanently deletes a.'
      operationId: deleteSizeConstraintSet
      x-api-path-slug: actiondeletesizeconstraintset-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: SizeConstraintSetId
        description: The SizeConstraintSetId of the SizeConstraintSet that you want
          to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Size Constraint Set
  /?Action=GetSizeConstraintSet:
    get:
      summary: Get Size Constraint Set
      description: 'Service: AWS WAFReturns the.'
      operationId: getSizeConstraintSet
      x-api-path-slug: actiongetsizeconstraintset-get
      parameters:
      - in: query
        name: SizeConstraintSetId
        description: The SizeConstraintSetId of the SizeConstraintSet that you want
          to get
        type: string
      responses:
        200:
          description: OK
      tags:
      - Size Constraint Set
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