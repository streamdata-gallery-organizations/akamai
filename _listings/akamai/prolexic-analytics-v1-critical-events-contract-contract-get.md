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
  /prolexic-analytics/v1/critical-events/contract/{contract}:
    get:
      summary: List Critical Events
      description: List Critical Events
      operationId: prolexicanalyticsv1criticaleventscontractcontract
      parameters:
      - in: String
        name: contract
        description: Name of contract events should be attached to
        type: string
      responses:
        200:
          description: OK
      tags:
      - prolexic
      - analytics
      - critical
      - events
      - contract
      - contract
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