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
  /diagnostic-tools/v1/verifycdnip:
    get:
      summary: Is This a CDN IP
      description: Is This a CDN IP
      operationId: diagnostictoolsv1verifycdnipip
      parameters:
      - in: String
        name: ip
        description: IP Address you want to determine is included in the Akamai network
        type: string
      responses:
        200:
          description: OK
      tags:
      - diagnostic
      - tools
      - verifycdnip
      - ip addresses
      - cdn
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