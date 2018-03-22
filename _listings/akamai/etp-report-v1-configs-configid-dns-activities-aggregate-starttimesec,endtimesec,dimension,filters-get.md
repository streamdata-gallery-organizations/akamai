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
  /etp-report/v1/configs/{configId}/dns-activities/aggregate{?startTimeSec,endTimeSec,dimension,filters}:
    get:
      summary: Report DNS Activities Totals
      description: Report DNS Activities Totals
      operationId: etpreportv1configsconfigiddnsactivitiesaggregatestarttimesecendtimesecdimensionfilters
      parameters:
      - in: Number
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: String
        name: dimension
        description: Flag to group the data
        type: string
      - in: Number
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: String
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: Number
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - etp
      - report
      - configurationss
      - configurations
      - dns
      - activities
      - aggregation
      - starttimesec
      - endtimesec
      - dimension
      - filters
      - aggregation
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