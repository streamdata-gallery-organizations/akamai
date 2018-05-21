---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Reactivate a Customer
  description: Reactivate a Customer
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /galaxy/v1/customers:
    get:
      summary: List Customers
      description: List Customers
      operationId: galaxyv1customersincludedeleteddebug
      x-api-path-slug: galaxyv1customers-get
      parameters:
      - in: query
        name: debug
        description: The flag to include debug members in the response JSON
        type: string
      - in: query
        name: includeDeleted
        description: The flag to include deleted customers
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
      - Includedeleted
      - debug
    post:
      summary: Add a Customer
      description: Add a Customer
      operationId: galaxyv1customers
      x-api-path-slug: galaxyv1customers-post
      parameters:
      - in: query
        name: akamaiCustomerId
        description: Akamai ID of the customer, maximum 50 characters
        type: string
      - in: query
        name: debug
        description: The flag to include debug members in the response JSON
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
  /galaxy/v1/customers/{akamaiCustomerId}:
    put:
      summary: Modify a Customer
      description: Modify a Customer
      operationId: galaxyv1customersakamaicustomerid
      x-api-path-slug: galaxyv1customersakamaicustomerid-put
      parameters:
      - in: query
        name: akamaiCustomerId
        description: Akamai ID of the customer, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
      - Akamaicustomer
    delete:
      summary: Remove a Customer
      description: Remove a Customer
      operationId: galaxyv1customersakamaicustomerid
      x-api-path-slug: galaxyv1customersakamaicustomerid-delete
      parameters:
      - in: query
        name: akamaiCustomerId
        description: Akamai ID of the customer, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
      - Akamaicustomer
  /galaxy/v1/customers/{akamaiCustomerId}/op/deactivate:
    post:
      summary: Deactivate a Customer
      description: Deactivate a Customer
      operationId: galaxyv1customersakamaicustomeridopdeactivate
      x-api-path-slug: galaxyv1customersakamaicustomeridopdeactivate-post
      parameters:
      - in: query
        name: akamaiCustomerId
        description: Akamai ID of the customer, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
      - Akamaicustomer
      - Op
      - Deactivate
  /galaxy/v1/customers/{akamaiCustomerId}/op/reactivate:
    post:
      summary: Reactivate a Customer
      description: Reactivate a Customer
      operationId: galaxyv1customersakamaicustomeridopreactivate
      x-api-path-slug: galaxyv1customersakamaicustomeridopreactivate-post
      parameters:
      - in: query
        name: akamaiCustomerId
        description: Akamai ID of the customer, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
      - Akamaicustomer
      - Op
      - Reactivate
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