---
swagger: "2.0"
x-collection-name: AWS WAF
x-complete: 1
info:
  title: AWS WAF API
  version: 1.0.0
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
  /?Action=ListSizeConstraintSets:
    get:
      summary: List Size Constraint Sets
      description: 'Service: AWS WAFReturns an array of.'
      operationId: listSizeConstraintSets
      x-api-path-slug: actionlistsizeconstraintsets-get
      parameters:
      - in: query
        name: Limit
        description: Specifies the number of SizeConstraintSet objects that you want
          AWS WAF to return for this request
        type: string
      - in: query
        name: NextMarker
        description: If you specify a value for Limit and you have more SizeConstraintSets
          than the value of Limit, AWS WAF returns a NextMarker value in the response
          that allows you to list another group of SizeConstraintSets
        type: string
      responses:
        200:
          description: OK
      tags:
      - Size Constraint Sets
  /?Action=UpdateSizeConstraintSet:
    get:
      summary: Update Size Constraint Set
      description: 'Service: AWS WAFInserts or deletes.'
      operationId: updateSizeConstraintSet
      x-api-path-slug: actionupdatesizeconstraintset-get
      parameters:
      - in: query
        name: ChangeToken
        description: The value returned by the most recent call to GetChangeToken
        type: string
      - in: query
        name: SizeConstraintSetId
        description: The SizeConstraintSetId of the SizeConstraintSet that you want
          to update
        type: string
      - in: query
        name: Updates
        description: An array of SizeConstraintSetUpdate objects that you want to
          insert into or delete from a SizeConstraintSet
        type: string
      responses:
        200:
          description: OK
      tags:
      - Size Constraint Set
---