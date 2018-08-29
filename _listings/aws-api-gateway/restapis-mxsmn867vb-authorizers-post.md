---
swagger: "2.0"
info:
  title: AWS API Gateway API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapis/mxsmn867vb/authorizers:
    post:
      summary: Authorizer Create
      description: Creates an Authorizer resource
      operationId: authorizerCreate
      parameters:
      - in: header
        name: '&quot;authorizerResultTtlInSeconds&quot;'
        type: string
      - in: header
        name: '&quot;authType&quot;'
        type: string
      - in: header
        name: '&quot;identitySource&quot;'
        type: string
      - in: header
        name: '&quot;name&quot;'
        type: string
      - in: header
        name: '&quot;type&quot;'
        type: string
      - in: header
        name: Authorization
        type: string
      - in: header
        name: Content-Type
        type: string
      - in: header
        name: Host
        type: string
      - in: header
        name: X-Amz-Date
        type: string
      responses:
        200:
          description: OK
      tags:
      - authorizer
definitions: []
x-collection-name: AWS API Gateway
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