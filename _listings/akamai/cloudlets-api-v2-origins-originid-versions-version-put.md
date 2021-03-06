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
  /cloudlets/api/v2/origins/{originId}/versions/{version}:
    put:
      summary: Update a Cloudlets Origin Version
      description: Update a Cloudlets Origin Version
      operationId: cloudletsapiv2originsoriginidversionsversionvalidate
      parameters:
      - in: String
        name: originId
        description: Unique identifier for the origin
        type: string
      - in: Boolean
        name: validate
        description: For GET operations, verifies that the current settings for the
          selected originId and version are valid
        type: string
      - in: Number
        name: version
        description: The origin version
        type: string
      responses:
        200:
          description: OK
      tags:
      - cloudlets
      - origins
      - versions
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