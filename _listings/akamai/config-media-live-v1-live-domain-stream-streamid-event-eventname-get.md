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
  /config-media-live/v1/live/{domain}/stream/{streamId}/event/{eventName}:
    get:
      summary: Get an Event
      description: Get an Event
      operationId: configmedialivev1livedomainstreamstreamideventeventname
      parameters:
      - in: String
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: String
        name: eventName
        description: Human-readable event name
        type: string
      - in: Number
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - configurations
      - media
      - live
      - live
      - domain
      - stream
      - stream
      - event
      - eventname
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