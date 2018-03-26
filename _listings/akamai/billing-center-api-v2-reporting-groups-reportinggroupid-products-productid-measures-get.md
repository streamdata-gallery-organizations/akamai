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
  /billing-center-api/v2/reporting-groups/{reportingGroupId}/products/{productId}/measures:
    get:
      summary: List Usage per Reporting Group
      description: List Usage per Reporting Group
      operationId: billingcenterapiv2reportinggroupsreportinggroupidproductsproductidmeasuresyearmonthfromyearfrommonth
      parameters:
      - in: Boolean
        name: billingDayOnly
        description: Aggregates cumulative data as of the end of the billing period,
          typically the end of the month, otherwise the day the contract&#8217;s term
          expires
        type: string
      - in: Integer
        name: fromMonth
        description: The month starting the range of aggregated data
        type: string
      - in: Integer
        name: fromYear
        description: The year starting the range of aggregated data
        type: string
      - in: Integer
        name: month
        description: The month for which data is aggregated
        type: string
      - in: String
        name: productId
        description: Identifies the product under which data is aggregated
        type: string
      - in: String
        name: reportingGroupId
        description: Identifies the unique reporting group
        type: string
      - in: String
        name: statisticName
        description: Reports on a specific statistic, otherwise reports all statistics
          by default
        type: string
      - in: Integer
        name: toMonth
        description: The month ending the range of aggregated data
        type: string
      - in: Integer
        name: toYear
        description: The year ending the range of aggregated data
        type: string
      - in: Integer
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - billing
      - center
      - reporting
      - groups
      - reportinggroup
      - products
      - product
      - measures
      - year
      - month
      - fromyear
      - frommonth
      - toyear
      - tomonth
      - statisticname
      - billingdayonly
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