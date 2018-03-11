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
  /security-monitor/v1/report-packs/{reportPackId}/data-sources:
    get:
      summary: List Data Sources
      description: List Data Sources
      operationId: securitymonitorv1reportpacksreportpackiddatasources
      parameters:
      - in: Number
        name: reportPackId
        description: Report pack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - security
      - monitor
      - report
      - packs
      - reportpack
      - data
      - sources
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