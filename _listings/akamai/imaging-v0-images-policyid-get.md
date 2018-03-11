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
  /imaging/v0/images{?policyId}:
    get:
      summary: List a Policy&#8217;s Images
      description: List a Policy&#8217;s Images
      operationId: imagingv0imagespolicyid
      parameters:
      - in: String
        name: policyId
        description: Identifies the policy for which to get associated images
        type: string
      responses:
        200:
          description: OK
      tags:
      - imaging
      - v0
      - images
      - policy
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