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
  /config-media-security/v1/security/{policyID}/revertDelete:
    put:
      summary: Restore a Policy Deletion
      description: Restore a Policy Deletion
      operationId: configmediasecurityv1securitypolicyidrevertdelete
      parameters:
      - in: Number
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - configurations
      - media
      - security
      - security
      - policy
      - revertdelete
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