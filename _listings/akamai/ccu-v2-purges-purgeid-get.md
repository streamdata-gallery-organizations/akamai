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
  /ccu/v2/purges/{purgeId}:
    get:
      summary: Get Purge Status
      description: Get Purge Status
      operationId: ccuv2purgespurgeid
      parameters:
      - in: String
        name: purgeId
        description: The purgeId returned from the POST to the queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - ccu
      - purges
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