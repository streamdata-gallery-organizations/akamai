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
  /cloudlets/api/v2/policies/{policyId}/activations{?network,propertyName}:
    get:
      summary: List Policy Activations
      description: List Policy Activations
      operationId: cloudletsapiv2policiespolicyidactivationsnetworkpropertyname
      parameters:
      - in: String
        name: network
        description: Returns only activations for the selected network, either staging
          or prod
        type: string
      - in: Number
        name: policyId
        description: The ID of the policy
        type: string
      - in: String
        name: propertyName
        description: Returns only activations for the selected property
        type: string
      responses:
        200:
          description: OK
      tags:
      - cloudlets
      - policies
      - activations
      - network
      - propertyname
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