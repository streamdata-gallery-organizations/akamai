---
swagger: "2.0"
info:
  title: Akamai Merged API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /siteshield/v1/maps/{id}/acknowledge:
    post:
      summary: Acknowledge a Map
      description: Acknowledge a Map
      operationId: siteshieldv1mapsidacknowledge
      parameters:
      - in: Number
        name: id
        description: Numeric id of the Note to perform action with
        type: string
      responses:
        200:
          description: OK
      tags:
      - siteshield
      - maps
      - ""
      - acknowledge
definitions: []
x-collection-name: Akamai
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