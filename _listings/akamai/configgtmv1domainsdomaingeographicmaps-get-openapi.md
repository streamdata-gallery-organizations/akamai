---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API List Geographic Maps
  description: List Geographic Maps
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
  /galaxy/v1/clients:
    get:
      summary: List Clients
      description: List Clients
      operationId: galaxyv1clientsincludedeleteddebugself
      x-api-path-slug: galaxyv1clients-get
      parameters:
      - in: query
        name: debug
        description: The flag to include debug members in the response JSON
        type: string
      - in: query
        name: includeDeleted
        description: The flag to include deleted customers
        type: string
      - in: query
        name: self
        description: The flag to get its own client information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Clients
      - Includedeleted
      - debug
      - self
    post:
      summary: Add a Client
      description: Add a Client
      operationId: galaxyv1clients
      x-api-path-slug: galaxyv1clients-post
      parameters:
      - in: query
        name: clientId
        description: Client ID of the device, maximum 50 characters
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
      - Clients
  /galaxy/v1/clients/{clientId}:
    put:
      summary: Modify a Client
      description: Modify a Client
      operationId: galaxyv1clientsclientid
      x-api-path-slug: galaxyv1clientsclientid-put
      parameters:
      - in: query
        name: clientId
        description: Client ID of the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Clients
      - Client
    delete:
      summary: Remove a Client
      description: Remove a Client
      operationId: galaxyv1clientsclientid
      x-api-path-slug: galaxyv1clientsclientid-delete
      parameters:
      - in: query
        name: clientId
        description: Client ID of the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Clients
      - Client
  /galaxy/v1/customers/{clientId}/op/deactivate:
    post:
      summary: Deactivate a Client
      description: Deactivate a Client
      operationId: galaxyv1customersclientidopdeactivate
      x-api-path-slug: galaxyv1customersclientidopdeactivate-post
      parameters:
      - in: query
        name: clientId
        description: Client ID of the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
      - Client
      - Op
      - Deactivate
  /galaxy/v1/customers/{clientId}/op/reactivate:
    post:
      summary: Reactivate a Client
      description: Reactivate a Client
      operationId: galaxyv1customersclientidopreactivate
      x-api-path-slug: galaxyv1customersclientidopreactivate-post
      parameters:
      - in: query
        name: clientId
        description: Client ID of the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Customers
      - Client
      - Op
      - Reactivate
  /galaxy/v1/client_groups:
    get:
      summary: Get Client Groups
      description: Get Client Groups
      operationId: galaxyv1client-groupsincludedeleteddebugself
      x-api-path-slug: galaxyv1client-groups-get
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
      - Client
      - Groups
      - Includedeleted
      - debug
      - self
    post:
      summary: Associate Multiple Activation Files for a DPC
      description: Associate Multiple Activation Files for a DPC
      operationId: galaxyv1client-groups
      x-api-path-slug: galaxyv1client-groups-post
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
      - Client
      - Groups
  /galaxy/v1/devices/{deviceId}:
    get:
      summary: Get a Device
      description: Get a Device
      operationId: galaxyv1devicesdeviceiddebug
      x-api-path-slug: galaxyv1devicesdeviceid-get
      parameters:
      - in: query
        name: debug
        description: The flag to include debug members in the response JSON
        type: string
      - in: query
        name: deviceId
        description: Identifies the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Devices
      - Device
      - Debug
    put:
      summary: Modify a Device
      description: Modify a Device
      operationId: galaxyv1devicesdeviceid
      x-api-path-slug: galaxyv1devicesdeviceid-put
      parameters:
      - in: query
        name: deviceId
        description: Identifies the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Devices
      - Device
    post:
      summary: Add a Device
      description: Add a Device
      operationId: galaxyv1devicesdeviceid
      x-api-path-slug: galaxyv1devicesdeviceid-post
      parameters:
      - in: query
        name: deviceId
        description: Identifies the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Devices
      - Device
    delete:
      summary: Remove a Device
      description: Remove a Device
      operationId: galaxyv1devicesdeviceid
      x-api-path-slug: galaxyv1devicesdeviceid-delete
      parameters:
      - in: query
        name: deviceId
        description: Identifies the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Devices
      - Device
  /galaxy/v1/devices/{deviceId}/op/deactivate:
    post:
      summary: Deactivate a Device
      description: Deactivate a Device
      operationId: galaxyv1devicesdeviceidopdeactivate
      x-api-path-slug: galaxyv1devicesdeviceidopdeactivate-post
      parameters:
      - in: query
        name: deviceId
        description: Identifies the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Devices
      - Device
      - Op
      - Deactivate
  /galaxy/v1/devices/{deviceId}/op/reactivate:
    post:
      summary: Reactivate a Device
      description: Reactivate a Device
      operationId: galaxyv1devicesdeviceidopreactivate
      x-api-path-slug: galaxyv1devicesdeviceidopreactivate-post
      parameters:
      - in: query
        name: deviceId
        description: Identifies the device, maximum 50 characters
        type: string
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Devices
      - Device
      - Op
      - Reactivate
  /galaxy/v1/build:
    get:
      summary: Get Build Information
      description: Get Build Information
      operationId: galaxyv1build
      x-api-path-slug: galaxyv1build-get
      responses:
        200:
          description: OK
      tags:
      - Galaxy
      - Build
  /billing-center-api/v2/contracts/{contractId}/products/{productId}/statistics:
    get:
      summary: List Statistics per Contract
      description: List Statistics per Contract
      operationId: billingcenterapiv2contractscontractidproductsproductidstatisticsyearmonthfromyearfrommonthtoyeartomo
      x-api-path-slug: billingcenterapiv2contractscontractidproductsproductidstatistics-get
      parameters:
      - in: query
        name: contractId
        description: Identifies the contract under which data is aggregated
        type: string
      - in: query
        name: fromMonth
        description: The month starting the range of aggregated data
        type: string
      - in: query
        name: fromYear
        description: The year starting the range of aggregated data
        type: string
      - in: query
        name: month
        description: The month for which data is aggregated
        type: string
      - in: query
        name: productId
        description: Identifies the product under which data is aggregated
        type: string
      - in: query
        name: toMonth
        description: The month ending the range of aggregated data
        type: string
      - in: query
        name: toYear
        description: The year ending the range of aggregated data
        type: string
      - in: query
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Billing
      - Center
      - Contracts
      - Contract
      - Products
      - Product
      - Statistics
      - Year
      - month
      - fromyear
      - frommonth
      - toyear
      - tomonth
  /billing-center-api/v2/contracts/{contractId}/products/{productId}/measures:
    get:
      summary: List Usage per Contract
      description: List Usage per Contract
      operationId: billingcenterapiv2contractscontractidproductsproductidmeasuresyearmonthfromyearfrommonthtoyeartomont
      x-api-path-slug: billingcenterapiv2contractscontractidproductsproductidmeasures-get
      parameters:
      - in: query
        name: billingDayOnly
        description: Aggregates cumulative data as of the end of the billing period,
          typically the end of the month, otherwise the day the contract&#8217;s term
          expires
        type: string
      - in: query
        name: contractId
        description: Identifies the contract under which data is aggregated
        type: string
      - in: query
        name: fromMonth
        description: The month starting the range of aggregated data
        type: string
      - in: query
        name: fromYear
        description: The year starting the range of aggregated data
        type: string
      - in: query
        name: month
        description: The month for which data is aggregated
        type: string
      - in: query
        name: productId
        description: Identifies the product under which data is aggregated
        type: string
      - in: query
        name: statisticName
        description: Reports on a specific statistic, otherwise reports all statistics
          by default
        type: string
      - in: query
        name: toMonth
        description: The month ending the range of aggregated data
        type: string
      - in: query
        name: toYear
        description: The year ending the range of aggregated data
        type: string
      - in: query
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Billing
      - Center
      - Contracts
      - Contract
      - Products
      - Product
      - Measures
      - Year
      - month
      - fromyear
      - frommonth
      - toyear
      - tomonth
      - statisticname
      - billingdayonly
  /billing-center-api/v2/reporting-groups/{reportingGroupId}/products/{productId}/statistics:
    get:
      summary: List Statistics per Reporting Group
      description: List Statistics per Reporting Group
      operationId: billingcenterapiv2reportinggroupsreportinggroupidproductsproductidstatisticsyearmonthfromyearfrommon
      x-api-path-slug: billingcenterapiv2reportinggroupsreportinggroupidproductsproductidstatistics-get
      parameters:
      - in: query
        name: fromMonth
        description: The month starting the range of aggregated data
        type: string
      - in: query
        name: fromYear
        description: The year starting the range of aggregated data
        type: string
      - in: query
        name: month
        description: The month for which data is aggregated
        type: string
      - in: query
        name: productId
        description: Identifies the product under which data is aggregated
        type: string
      - in: query
        name: reportingGroupId
        description: Identifies the unique reporting group
        type: string
      - in: query
        name: toMonth
        description: The month ending the range of aggregated data
        type: string
      - in: query
        name: toYear
        description: The year ending the range of aggregated data
        type: string
      - in: query
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Billing
      - Center
      - Reporting
      - Groups
      - Reportinggroup
      - Products
      - Product
      - Statistics
      - Year
      - month
      - fromyear
      - frommonth
      - toyear
      - tomonth
  /billing-center-api/v2/reporting-groups/{reportingGroupId}/products/{productId}/measures:
    get:
      summary: List Usage per Reporting Group
      description: List Usage per Reporting Group
      operationId: billingcenterapiv2reportinggroupsreportinggroupidproductsproductidmeasuresyearmonthfromyearfrommonth
      x-api-path-slug: billingcenterapiv2reportinggroupsreportinggroupidproductsproductidmeasures-get
      parameters:
      - in: query
        name: billingDayOnly
        description: Aggregates cumulative data as of the end of the billing period,
          typically the end of the month, otherwise the day the contract&#8217;s term
          expires
        type: string
      - in: query
        name: fromMonth
        description: The month starting the range of aggregated data
        type: string
      - in: query
        name: fromYear
        description: The year starting the range of aggregated data
        type: string
      - in: query
        name: month
        description: The month for which data is aggregated
        type: string
      - in: query
        name: productId
        description: Identifies the product under which data is aggregated
        type: string
      - in: query
        name: reportingGroupId
        description: Identifies the unique reporting group
        type: string
      - in: query
        name: statisticName
        description: Reports on a specific statistic, otherwise reports all statistics
          by default
        type: string
      - in: query
        name: toMonth
        description: The month ending the range of aggregated data
        type: string
      - in: query
        name: toYear
        description: The year ending the range of aggregated data
        type: string
      - in: query
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Billing
      - Center
      - Reporting
      - Groups
      - Reportinggroup
      - Products
      - Product
      - Measures
      - Year
      - month
      - fromyear
      - frommonth
      - toyear
      - tomonth
      - statisticname
      - billingdayonly
  /cases/v1/{category}:
    get:
      summary: List Cases per Category
      description: List Cases per Category
      operationId: casesv1category
      x-api-path-slug: casesv1category-get
      parameters:
      - in: query
        name: category
        description: Category of lists to retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Category
    post:
      summary: Create a Case
      description: Create a Case
      operationId: casesv1category
      x-api-path-slug: casesv1category-post
      parameters:
      - in: query
        name: category
        description: Category of lists to retrieve
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Category
  /cases/v1/PS:
    get:
      summary: List Professional Services Cases
      description: List Professional Services Cases
      operationId: casesv1ps
      x-api-path-slug: casesv1ps-get
      responses:
        200:
          description: OK
      tags:
      - Cases
    post:
      summary: Create a Professional Services Case
      description: Create a Professional Services Case
      operationId: casesv1ps
      x-api-path-slug: casesv1ps-post
      responses:
        200:
          description: OK
      tags:
      - Cases
  /cases/v1/portal-user:
    get:
      summary: List Cases
      description: List Cases
      operationId: casesv1portaluserstatustypecategory
      x-api-path-slug: casesv1portaluser-get
      parameters:
      - in: query
        name: category
        description: ts for technicalSupport, or etc (currently ignored)
        type: string
      - in: query
        name: status
        description: Retrieves all if missing, both active and closed cases
        type: string
      - in: query
        name: type
        description: Retrieves all if missing, both user and company cases
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Portal
      - User
      - Status
      - type
      - category
  /cases/v1/portal-user/case/{caseId}:
    get:
      summary: Get a Case
      description: Get a Case
      operationId: casesv1portalusercasecaseid
      x-api-path-slug: casesv1portalusercasecaseid-get
      parameters:
      - in: query
        name: caseId
        description: Unique identifier for the support ticket
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Portal
      - User
      - Cases
      - ""
  /cases/v1/portal-user/case/{caseId}/notes:
    post:
      summary: Comment on a Case
      description: Comment on a Case
      operationId: casesv1portalusercasecaseidnotes
      x-api-path-slug: casesv1portalusercasecaseidnotes-post
      parameters:
      - in: query
        name: caseId
        description: Unique identifier for the support ticket
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Portal
      - User
      - Cases
      - Notes
  /cases/v1/portal-user/case/{caseId}/files:
    post:
      summary: Upload a File Attachment
      description: Upload a File Attachment
      operationId: casesv1portalusercasecaseidfiles
      x-api-path-slug: casesv1portalusercasecaseidfiles-post
      parameters:
      - in: query
        name: caseId
        description: Unique identifier for the support ticket
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Portal
      - User
      - Cases
      - Files
  /cases/v1/portal-user/case/{caseId}/request-close:
    put:
      summary: Close a Request
      description: Close a Request
      operationId: casesv1portalusercasecaseidrequestclose
      x-api-path-slug: casesv1portalusercasecaseidrequestclose-put
      parameters:
      - in: query
        name: caseId
        description: Unique identifier for the support ticket
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cases
      - Portal
      - User
      - Cases
      - Request
      - Close
  /ccu/v3/invalidate/url/{network}:
    post:
      summary: Invalidate by URL
      description: Invalidate by URL
      operationId: ccuv3invalidateurlnetwork
      x-api-path-slug: ccuv3invalidateurlnetwork-post
      parameters:
      - in: query
        name: network
        description: The network on which you want to invalidate the URL, either production
          or staging
        type: string
      responses:
        200:
          description: OK
      tags:
      - Ccu
      - Invalate
      - Url
      - Network
  /ccu/v3/delete/url/{network}:
    post:
      summary: Delete by URL
      description: Delete by URL
      operationId: ccuv3deleteurlnetwork
      x-api-path-slug: ccuv3deleteurlnetwork-post
      parameters:
      - in: query
        name: network
        description: The network on which you want to delete the URL, either production
          or staging
        type: string
      responses:
        200:
          description: OK
      tags:
      - Ccu
      - Delete
      - Url
      - Network
  /ccu/v2/queues/{queueName}:
    get:
      summary: Get Current Queue Size
      description: Get Current Queue Size
      operationId: ccuv2queuesqueuename
      x-api-path-slug: ccuv2queuesqueuename-get
      parameters:
      - in: query
        name: queueName
        description: Name of the queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - Ccu
      - Queues
      - Queues
    post:
      summary: Add a Request
      description: Add a Request
      operationId: ccuv2queuesqueuename
      x-api-path-slug: ccuv2queuesqueuename-post
      parameters:
      - in: query
        name: queueName
        description: Name of the queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - Ccu
      - Queues
      - Queues
  /ccu/v2/purges/{purgeId}:
    get:
      summary: Get Purge Status
      description: Get Purge Status
      operationId: ccuv2purgespurgeid
      x-api-path-slug: ccuv2purgespurgeid-get
      parameters:
      - in: query
        name: purgeId
        description: The purgeId returned from the POST to the queue
        type: string
      responses:
        200:
          description: OK
      tags:
      - Ccu
      - Purges
  cloudletId:
    get:
      summary: List Cloudlets
      description: List Cloudlets
      operationId: cloudletid
      x-api-path-slug: cloudletid-get
      parameters:
      - in: query
        name: cloudletId
        description: For GET operations, returns only policies for this particular
          cloudletId
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlet
  /cloudlets/api/v2/group-info:
    get:
      summary: List Groups
      description: List Groups
      operationId: cloudletsapiv2groupinfo
      x-api-path-slug: cloudletsapiv2groupinfo-get
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Group
      - Information
  /cloudlets/api/v2/group-info/{groupId}:
    get:
      summary: Get a Group
      description: Get a Group
      operationId: cloudletsapiv2groupinfogroupid
      x-api-path-slug: cloudletsapiv2groupinfogroupid-get
      parameters:
      - in: query
        name: groupId
        description: For GET operations, returns only policies associated with the
          group ID entered
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Group
      - Information
      - Group
  /cloudlets/api/v2/policies:
    get:
      summary: List Policies
      description: List Policies
      operationId: cloudletsapiv2policiesgidincludedeletedcloudletid
      x-api-path-slug: cloudletsapiv2policies-get
      parameters:
      - in: query
        name: cloudletId
        description: For GET operations, returns only policies for this particular
          cloudletId
        type: string
      - in: query
        name: gid
        description: For GET operations, returns only policies associated with the
          group ID (gid) entered
        type: string
      - in: query
        name: includeDeleted
        description: For GET operations, includes deleted policies in the results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - G
      - includedeleted
      - cloudlet
    post:
      summary: Create a Policy
      description: Create a Policy
      operationId: cloudletsapiv2policiesclonepolicyidversion
      x-api-path-slug: cloudletsapiv2policies-post
      parameters:
      - in: query
        name: clonePolicyId
        description: If cloning an existing policy, this parameter is the ID of the
          policy (policyId) you want to clone
        type: string
      - in: query
        name: version
        description: For POST operations, indicates the version of the existing policy
          to use for the new policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Clonepolicy
      - version
  /cloudlets/api/v2/policies/{policyId}:
    get:
      summary: Get a Policy
      description: Get a Policy
      operationId: cloudletsapiv2policiespolicyid
      x-api-path-slug: cloudletsapiv2policiespolicyid-get
      parameters:
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
    put:
      summary: Update a Policy
      description: Update a Policy
      operationId: cloudletsapiv2policiespolicyid
      x-api-path-slug: cloudletsapiv2policiespolicyid-put
      parameters:
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
    delete:
      summary: Remove a Policy
      description: Remove a Policy
      operationId: cloudletsapiv2policiespolicyid
      x-api-path-slug: cloudletsapiv2policiespolicyid-delete
      parameters:
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
  /cloudlets/api/v2/policies/{policyId}/versions:
    get:
      summary: List Policy Versions
      description: List Policy Versions
      operationId: cloudletsapiv2policiespolicyidversionsincluderulesmatchruleformat
      x-api-path-slug: cloudletsapiv2policiespolicyidversions-get
      parameters:
      - in: query
        name: includeRules
        description: Includes the match rules for all policy versions in the results
        type: string
      - in: query
        name: matchRuleFormat
        description: Returns the matchRuleFormat version string, which shows the version
          of the Cloudlet-specific matchRules used
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Includerules
      - Rules
    post:
      summary: Create a New Policy Version
      description: Create a New Policy Version
      operationId: cloudletsapiv2policiespolicyidversionsmatchruleformatcloneversion
      x-api-path-slug: cloudletsapiv2policiespolicyidversions-post
      parameters:
      - in: query
        name: cloneVersion
        description: If cloning an existing policy version, this parameter value is
          the number of the policy version you want to clone
        type: string
      - in: query
        name: matchRuleFormat
        description: Returns the matchRuleFormat version string, which shows the version
          of the Cloudlet-specific matchRules used
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Matchruleformat
      - cloneversion
  /cloudlets/api/v2/policies/{policyId}/versions/{version}:
    get:
      summary: Get a Policy Version
      description: Get a Policy Version
      operationId: cloudletsapiv2policiespolicyidversionsversionomitrulesmatchruleformat
      x-api-path-slug: cloudletsapiv2policiespolicyidversionsversion-get
      parameters:
      - in: query
        name: matchRuleFormat
        description: Returns the matchRuleFormat version string, which shows the version
          of the Cloudlet-specific matchRules used
        type: string
      - in: query
        name: omitRules
        description: Excludes the match rules from the results
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: version
        description: The version number of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Omitrules
      - Rules
    put:
      summary: Update a Policy Version
      description: Update a Policy Version
      operationId: cloudletsapiv2policiespolicyidversionsversionmatchruleformat
      x-api-path-slug: cloudletsapiv2policiespolicyidversionsversion-put
      parameters:
      - in: query
        name: matchRuleFormat
        description: Returns the matchRuleFormat version string, which shows the version
          of the Cloudlet-specific matchRules used
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: version
        description: The version number of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Matchruleformat
    delete:
      summary: Remove a Policy Version
      description: Remove a Policy Version
      operationId: cloudletsapiv2policiespolicyidversionsversionomitrulesmatchruleformat
      x-api-path-slug: cloudletsapiv2policiespolicyidversionsversion-delete
      parameters:
      - in: query
        name: matchRuleFormat
        description: Returns the matchRuleFormat version string, which shows the version
          of the Cloudlet-specific matchRules used
        type: string
      - in: query
        name: omitRules
        description: Excludes the match rules from the results
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: version
        description: The version number of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Omitrules
      - Rules
  /cloudlets/api/v2/policies/{policyId}/versions/{version}/rules:
    post:
      summary: Add a Version Rule
      description: Add a Version Rule
      operationId: cloudletsapiv2policiespolicyidversionsversionrulesindex
      x-api-path-slug: cloudletsapiv2policiespolicyidversionsversionrules-post
      parameters:
      - in: query
        name: index
        description: The order within the current list of rules where you want to
          add the new rule
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: version
        description: The version number of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Rules
      - Index
  /cloudlets/api/v2/policies/{policyId}/versions/{version}/rules/{akaRuleId}:
    get:
      summary: Get a Version Rule
      description: Get a Version Rule
      operationId: cloudletsapiv2policiespolicyidversionsversionrulesakaruleid
      x-api-path-slug: cloudletsapiv2policiespolicyidversionsversionrulesakaruleid-get
      parameters:
      - in: query
        name: akaRuleId
        description: The ID of the rule within the policy version
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: version
        description: The version number of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Rules
      - Akarule
    put:
      summary: Update a Version Rule
      description: Update a Version Rule
      operationId: cloudletsapiv2policiespolicyidversionsversionrulesakaruleid
      x-api-path-slug: cloudletsapiv2policiespolicyidversionsversionrulesakaruleid-put
      parameters:
      - in: query
        name: akaRuleId
        description: The ID of the rule within the policy version
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: version
        description: The version number of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Rules
      - Akarule
  /cloudlets/api/v2/properties:
    get:
      summary: List Associated Properties
      description: List Associated Properties
      operationId: cloudletsapiv2properties
      x-api-path-slug: cloudletsapiv2properties-get
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Properties
  /cloudlets/api/v2/{policyId}/properties:
    get:
      summary: Get Associated Properties for a Policy
      description: Get Associated Properties for a Policy
      operationId: cloudletsapiv2policyidproperties
      x-api-path-slug: cloudletsapiv2policyidproperties-get
      parameters:
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policy
      - Properties
  /cloudlets/api/v2/origins:
    get:
      summary: List Cloudlets Origins
      description: List Cloudlets Origins
      operationId: cloudletsapiv2originstype
      x-api-path-slug: cloudletsapiv2origins-get
      parameters:
      - in: query
        name: type
        description: Returns data for a specific type of origin as defined in Property
          Manager
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Type
  /cloudlets/api/v2/origins/{originId}:
    get:
      summary: Get a Cloudlets Origin
      description: Get a Cloudlets Origin
      operationId: cloudletsapiv2originsoriginid
      x-api-path-slug: cloudletsapiv2originsoriginid-get
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
    put:
      summary: Update a Cloudlets Origin
      description: Update a Cloudlets Origin
      operationId: cloudletsapiv2originsoriginid
      x-api-path-slug: cloudletsapiv2originsoriginid-put
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
  /cloudlets/api/v2/origins/{originId}/versions:
    get:
      summary: List Cloudlets Origin Versions
      description: List Cloudlets Origin Versions
      operationId: cloudletsapiv2originsoriginidversions
      x-api-path-slug: cloudletsapiv2originsoriginidversions-get
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Versions
    post:
      summary: Create a Cloudlets Origin Version
      description: Create a Cloudlets Origin Version
      operationId: cloudletsapiv2originsoriginidversions
      x-api-path-slug: cloudletsapiv2originsoriginidversions-post
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Versions
  /cloudlets/api/v2/origins/{originId}/versions/{version}:
    get:
      summary: Get a Cloudlets Origin Version
      description: Get a Cloudlets Origin Version
      operationId: cloudletsapiv2originsoriginidversionsversionvalidate
      x-api-path-slug: cloudletsapiv2originsoriginidversionsversion-get
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      - in: query
        name: validate
        description: For GET operations, verifies that the current settings for the
          selected originId and version are valid
        type: string
      - in: query
        name: version
        description: The origin version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Versions
    put:
      summary: Update a Cloudlets Origin Version
      description: Update a Cloudlets Origin Version
      operationId: cloudletsapiv2originsoriginidversionsversionvalidate
      x-api-path-slug: cloudletsapiv2originsoriginidversionsversion-put
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      - in: query
        name: validate
        description: For GET operations, verifies that the current settings for the
          selected originId and version are valid
        type: string
      - in: query
        name: version
        description: The origin version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Versions
  /cloudlets/api/v2/origins/currentActivations:
    get:
      summary: List Current Cloudlets Origin Activations
      description: List Current Cloudlets Origin Activations
      operationId: cloudletsapiv2originscurrentactivations
      x-api-path-slug: cloudletsapiv2originscurrentactivations-get
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Activations
  /cloudlets/api/v2/origins/{originId}/activations:
    get:
      summary: List Activations for a Cloudlets Origin
      description: List Activations for a Cloudlets Origin
      operationId: cloudletsapiv2originsoriginidactivations
      x-api-path-slug: cloudletsapiv2originsoriginidactivations-get
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Activations
    post:
      summary: Activate a Cloudlets Origin Version
      description: Activate a Cloudlets Origin Version
      operationId: cloudletsapiv2originsoriginidactivations
      x-api-path-slug: cloudletsapiv2originsoriginidactivations-post
      parameters:
      - in: query
        name: originId
        description: Unique identifier for the origin
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Origins
      - Activations
  /cloudlets/api/v2/policies/{policyId}/activations:
    get:
      summary: List Policy Activations
      description: List Policy Activations
      operationId: cloudletsapiv2policiespolicyidactivationsnetworkpropertyname
      x-api-path-slug: cloudletsapiv2policiespolicyidactivations-get
      parameters:
      - in: query
        name: network
        description: Returns only activations for the selected network, either staging
          or prod
        type: string
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: propertyName
        description: Returns only activations for the selected property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Activations
      - Network
      - propertyname
  /cloudlets/api/v2/policies/{policyId}/versions/{version}/activations:
    post:
      summary: Activate a Policy Version
      description: Activate a Policy Version
      operationId: cloudletsapiv2policiespolicyidversionsversionactivations
      x-api-path-slug: cloudletsapiv2policiespolicyidversionsversionactivations-post
      parameters:
      - in: query
        name: policyId
        description: The ID of the policy
        type: string
      - in: query
        name: version
        description: The version number of the policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Policies
      - Versions
      - Activations
  /cloudlets/api/v2/schemas/{schemaName}:
    get:
      summary: Get a Schema
      description: Get a Schema
      operationId: cloudletsapiv2schemasschemaname
      x-api-path-slug: cloudletsapiv2schemasschemaname-get
      parameters:
      - in: query
        name: schemaName
        description: The name of the JSON schema file
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudlets
      - Schemas
  cloudletCode:
    get:
      summary: List Schemas per Cloudlet
      description: List Schemas per Cloudlet
      operationId: cloudletcode
      x-api-path-slug: cloudletcode-get
      parameters:
      - in: query
        name: cloudletType
        description: The two- or three- letter code of the Cloudlet you want to view
          all schemas for
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cloudletcode
  /cps/v2/enrollments:
    post:
      summary: Create an Enrollment
      description: Create an Enrollment
      operationId: cpsv2enrollmentscontractid
      x-api-path-slug: cpsv2enrollments-post
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract under which to create a new
          enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Contract
    get:
      summary: List Enrollments
      description: List Enrollments
      operationId: cpsv2enrollmentscontractid
      x-api-path-slug: cpsv2enrollments-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract under which to create a new
          enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Contract
  /cps/v2/enrollments/{enrollmentId}:
    get:
      summary: Get an Enrollment
      description: Get an Enrollment
      operationId: cpsv2enrollmentsenrollmentid
      x-api-path-slug: cpsv2enrollmentsenrollmentid-get
      parameters:
      - in: query
        name: enrollmentId
        description: Unique integer identifer for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Enrollment
    put:
      summary: Update an Enrollment
      description: Update an Enrollment
      operationId: cpsv2enrollmentsenrollmentiddeploynotbeforedeploynotafterallowcancelpendingchanges
      x-api-path-slug: cpsv2enrollmentsenrollmentid-put
      parameters:
      - in: query
        name: allow-cancel-pending-changes
        description: When enabled, allows this update to cancel and replace in-process
          changes
        type: string
      - in: query
        name: deploy-not-after
        description: The latest date the certificate can be deployed to the network,
          formatted as YYYY-MM-DD
        type: string
      - in: query
        name: deploy-not-before
        description: The earliest date the certificate can be deployed to the network,
          formatted as YYYY-MM-DD
        type: string
      - in: query
        name: enrollmentId
        description: Integer identifier for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Enrollment
      - Deploy
      - Not
      - Before
      - deploy
      - Not
      - After
      - allow
      - Cancel
      - Pending
      - Changes
    delete:
      summary: Delete an Enrollment
      description: Delete an Enrollment
      operationId: cpsv2enrollmentsenrollmentiddeploynotbeforedeploynotafterallowcancelpendingchanges
      x-api-path-slug: cpsv2enrollmentsenrollmentid-delete
      parameters:
      - in: query
        name: allow-cancel-pending-changes
        description: When enabled, allows this update to cancel and replace in-process
          changes
        type: string
      - in: query
        name: deploy-not-after
        description: The latest date the certificate can be deployed to the network,
          formatted as YYYY-MM-DD
        type: string
      - in: query
        name: deploy-not-before
        description: The earliest date the certificate can be deployed to the network,
          formatted as YYYY-MM-DD
        type: string
      - in: query
        name: enrollmentId
        description: Integer identifier for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Enrollment
      - Deploy
      - Not
      - Before
      - deploy
      - Not
      - After
      - allow
      - Cancel
      - Pending
      - Changes
  /cps/v2/enrollments/{enrollmentId}/changes/{changeId}:
    get:
      summary: Get Change Status
      description: Get Change Status
      operationId: cpsv2enrollmentsenrollmentidchangeschangeid
      x-api-path-slug: cpsv2enrollmentsenrollmentidchangeschangeid-get
      parameters:
      - in: query
        name: changeId
        description: Unique integer identifer for the change
        type: string
      - in: query
        name: enrollmentId
        description: Unique integer identifer for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Enrollment
      - Changes
      - Change
    delete:
      summary: Cancel a Change
      description: Cancel a Change
      operationId: cpsv2enrollmentsenrollmentidchangeschangeid
      x-api-path-slug: cpsv2enrollmentsenrollmentidchangeschangeid-delete
      parameters:
      - in: query
        name: changeId
        description: Unique integer identifer for the change
        type: string
      - in: query
        name: enrollmentId
        description: Unique integer identifer for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Enrollment
      - Changes
      - Change
  info:
    get:
      summary: Confirm a Change
      description: Confirm a Change
      operationId: info
      x-api-path-slug: info-get
      parameters:
      - in: query
        name: changeId
        description: Unique integer identifer for the change
        type: string
      - in: query
        name: enrollmentId
        description: Unique integer identifer for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Information
  update:
    post:
      summary: Submit a Change
      description: Submit a Change
      operationId: update
      x-api-path-slug: update-post
      parameters:
      - in: query
        name: changeId
        description: Unique integer identifer for the change
        type: string
      - in: query
        name: enrollmentId
        description: Unique integer identifer for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Update
  /cps/v2/enrollments/{enrollmentId}/deployments/production:
    get:
      summary: Get a Certificate
      description: Get a Certificate
      operationId: cpsv2enrollmentsenrollmentiddeploymentsproduction
      x-api-path-slug: cpsv2enrollmentsenrollmentiddeploymentsproduction-get
      parameters:
      - in: query
        name: enrollmentId
        description: Unique integer identifer for the enrollment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cps
      - Enrollments
      - Enrollment
      - Deployments
      - Production
  /cps/v2/sample&#8211;500:
    get:
      summary: Get Sample 500 Response
      description: Get Sample 500 Response
      operationId: cpsv2sample8211500
      x-api-path-slug: cpsv2sample8211500-get
      responses:
        200:
          description: OK
      tags:
      - Samples
  /cps/v2/sample&#8211;404:
    get:
      summary: Get Sample 404 Response
      description: Get Sample 404 Response
      operationId: cpsv2sample8211404
      x-api-path-slug: cpsv2sample8211404-get
      responses:
        200:
          description: OK
      tags:
      - Samples
  /diagnostic-tools/v1/locations:
    get:
      summary: List Locations
      description: List Locations
      operationId: diagnostictoolsv1locations
      x-api-path-slug: diagnostictoolsv1locations-get
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Locations
  /diagnostic-tools/v1/dig:
    get:
      summary: Run dig
      description: Run dig
      operationId: diagnostictoolsv1dighostnamequerytypelocationsourceip
      x-api-path-slug: diagnostictoolsv1dig-get
      parameters:
      - in: query
        name: hostname
        description: the domain name you want to get information about
        type: string
      - in: query
        name: location
        description: Location of Akamai server from which you want to run dig
        type: string
      - in: query
        name: queryType
        description: 'query type for the dig; valid types are:'
        type: string
      - in: query
        name: sourceIp
        description: CDN server IP to run DIG from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Dig
      - Hostname
      - querytype
      - location
      - sourceip
  /diagnostic-tools/v1/mtr:
    get:
      summary: Run mtr
      description: Run mtr
      operationId: diagnostictoolsv1mtrdestinationdomainlocationsourceip
      x-api-path-slug: diagnostictoolsv1mtr-get
      parameters:
      - in: query
        name: destinationDomain
        description: The domain name you want to get information about
        type: string
      - in: query
        name: location
        description: Location of Akamai Server you want to run dig from
        type: string
      - in: query
        name: sourceIp
        description: CDN server IP to run MTR from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Mtr
      - Destinationdomain
      - location
      - sourceip
  /diagnostic-tools/v1/akamaitranslator:
    get:
      summary: Translate Hostname
      description: Translate Hostname
      operationId: diagnostictoolsv1akamaitranslatorhostname
      x-api-path-slug: diagnostictoolsv1akamaitranslator-get
      parameters:
      - in: query
        name: hostname
        description: Hostname for which to retrieve ARL information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Akamaitranslator
      - Hostname
  /diagnostic-tools/v1/errortranslator:
    get:
      summary: Translate Error Code
      description: Translate Error Code
      operationId: diagnostictoolsv1errortranslatorerrorcode
      x-api-path-slug: diagnostictoolsv1errortranslator-get
      parameters:
      - in: query
        name: errorCode
        description: Error code or reference number you want to translate, which typically
          appears on an error page
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Errortranslator
      - Errorcode
  /diagnostic-tools/v1/ipgeolocator:
    get:
      summary: Get IP Geolocation Data
      description: Get IP Geolocation Data
      operationId: diagnostictoolsv1ipgeolocatorip
      x-api-path-slug: diagnostictoolsv1ipgeolocator-get
      parameters:
      - in: query
        name: ip
        description: IP Address
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Ipgeolocator
      - Ip
  /diagnostic-tools/v1/verifycdnip:
    get:
      summary: Is This a CDN IP
      description: Is This a CDN IP
      operationId: diagnostictoolsv1verifycdnipip
      x-api-path-slug: diagnostictoolsv1verifycdnip-get
      parameters:
      - in: query
        name: ip
        description: IP Address you want to determine is included in the Akamai network
        type: string
      responses:
        200:
          description: OK
      tags:
      - Diagnostic
      - Tools
      - Verifycdnip
      - IP Addresses
      - CDN
  token:
    get:
      summary: Get a Zone
      description: Get a Zone
      operationId: token
      x-api-path-slug: token-get
      parameters:
      - in: query
        name: zone
        description: Domain zone, encapsulating any nested subdomains
        type: string
      responses:
        200:
          description: OK
      tags:
      - Token
    post:
      summary: Add or Modify a Zone
      description: Add or Modify a Zone
      operationId: token
      x-api-path-slug: token-post
      parameters:
      - in: query
        name: zone
        description: Domain zone, encapsulating any nested subdomains
        type: string
      responses:
        200:
          description: OK
      tags:
      - Token
  /data-dns/v1/traffic/{zone}:
    get:
      summary: Get Traffic Report
      description: Get Traffic Report
      operationId: datadnsv1trafficzonestartstart-timeendend-timeend-timetime-zoneinclude-estimates
      x-api-path-slug: datadnsv1trafficzone-get
      parameters:
      - in: query
        name: end
        description: End date, in yyyymmdd format
        type: string
      - in: query
        name: end_time
        description: End time, in HH:mm format
        type: string
      - in: query
        name: include_estimates
        description: Flag to include estimated data
        type: string
      - in: query
        name: start
        description: Start date, in yyyymmdd format
        type: string
      - in: query
        name: start_time
        description: Start time, in HH:mm format
        type: string
      - in: query
        name: time_zone
        description: Timezone to use when formatting result set
        type: string
      - in: query
        name: zone
        description: Name of Zone
        type: string
      responses:
        200:
          description: OK
      tags:
      - Data
      - DNS
      - Traffic
      - Zone
      - Start
      - start
      - Time
      - end
      - end
      - Time
      - end
      - Time
      - Zone
      - Estimates
  /etp-report/v1/configs/{configId}/threat-events/aggregate:
    get:
      summary: Report Security Event Aggregation
      description: Report Security Event Aggregation
      operationId: etpreportv1configsconfigidthreateventsaggregatestarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidthreateventsaggregate-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Threat
      - Events
      - Aggregation
      - Starttimesec
      - endtimesec
      - dimension
      - filters
      - Aggregation
  /etp-report/v1/configs/{configId}/threat-events/details:
    get:
      summary: Report Security Event Details
      description: Report Security Event Details
      operationId: etpreportv1configsconfigidthreateventsdetailsstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidthreateventsdetails-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Threat
      - Events
      - Details
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/threat-events/time-series:
    get:
      summary: Report Security Event Time Series
      description: Report Security Event Time Series
      operationId: etpreportv1configsconfigidthreateventstimeseriesstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidthreateventstimeseries-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Threat
      - Events
      - Time
      - Series
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/aup-events/details:
    get:
      summary: Report AUP Event Details
      description: Report AUP Event Details
      operationId: etpreportv1configsconfigidaupeventsdetailsstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidaupeventsdetails-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Aup
      - Events
      - Details
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/aup-events/time-series:
    get:
      summary: Report AUP Event Time Series
      description: Report AUP Event Time Series
      operationId: etpreportv1configsconfigidaupeventstimeseriesstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigidaupeventstimeseries-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - Aup
      - Events
      - Time
      - Series
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/dns-activities/time-series:
    get:
      summary: Report DNS Activity Time Series
      description: Report DNS Activity Time Series
      operationId: etpreportv1configsconfigiddnsactivitiestimeseriesstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigiddnsactivitiestimeseries-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - DNS
      - Activities
      - Time
      - Series
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/dns-activities/aggregate:
    get:
      summary: Report DNS Activities Totals
      description: Report DNS Activities Totals
      operationId: etpreportv1configsconfigiddnsactivitiesaggregatestarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigiddnsactivitiesaggregate-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - DNS
      - Activities
      - Aggregation
      - Starttimesec
      - endtimesec
      - dimension
      - filters
      - Aggregation
  /events/v2/{accountId}/events:
    get:
      summary: List Events
      description: List Events
      operationId: eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid
      x-api-path-slug: eventsv2accountidevents-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: customerEventId
        description: Event identifier for your own use
        type: string
      - in: query
        name: endRange
        description: End of event, specified as epoch time milliseconds
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field that should be used to sort the result set
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      - in: query
        name: startRange
        description: Start of event, specified as epoch time milliseconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Startrange
      - endrange
      - sortfield
      - sortorder
      - startindex
      - limit
      - customerevent
    post:
      summary: POST a New Event
      description: POST a New Event
      operationId: eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid
      x-api-path-slug: eventsv2accountidevents-post
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: customerEventId
        description: Event identifier for your own use
        type: string
      - in: query
        name: endRange
        description: End of event, specified as epoch time milliseconds
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field that should be used to sort the result set
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      - in: query
        name: startRange
        description: Start of event, specified as epoch time milliseconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Startrange
      - endrange
      - sortfield
      - sortorder
      - startindex
      - limit
      - customerevent
    put:
      summary: PUT a New Event
      description: PUT a New Event
      operationId: eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid
      x-api-path-slug: eventsv2accountidevents-put
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: customerEventId
        description: Event identifier for your own use
        type: string
      - in: query
        name: endRange
        description: End of event, specified as epoch time milliseconds
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field that should be used to sort the result set
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      - in: query
        name: startRange
        description: Start of event, specified as epoch time milliseconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Startrange
      - endrange
      - sortfield
      - sortorder
      - startindex
      - limit
      - customerevent
    delete:
      summary: Remove Events
      description: Remove Events
      operationId: eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid
      x-api-path-slug: eventsv2accountidevents-delete
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: customerEventId
        description: Event identifier for your own use
        type: string
      - in: query
        name: endRange
        description: End of event, specified as epoch time milliseconds
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field that should be used to sort the result set
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      - in: query
        name: startRange
        description: Start of event, specified as epoch time milliseconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Startrange
      - endrange
      - sortfield
      - sortorder
      - startindex
      - limit
      - customerevent
  /events/v2/{accountId}/events/recurring:
    post:
      summary: Create a Recurring Event
      description: Create a Recurring Event
      operationId: eventsv2accountideventsrecurringfrequencynumberoftimes
      x-api-path-slug: eventsv2accountideventsrecurring-post
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: frequency
        description: Periodicity of the recurring event
        type: string
      - in: query
        name: numberOfTimes
        description: Number of times/periods to follow
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Recurring
      - Frequency
      - numberoftimes
  /events/v2/{accountId}/events/{eventId}:
    get:
      summary: Get Event with its Services
      description: Get Event with its Services
      operationId: eventsv2accountideventseventidservices
      x-api-path-slug: eventsv2accountideventseventid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: services
        description: Value must be detail, otherwise only returns basic event details
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Services
    post:
      summary: Modify an Event, with POST
      description: Modify an Event, with POST
      operationId: eventsv2accountideventseventid
      x-api-path-slug: eventsv2accountideventseventid-post
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
    put:
      summary: Modify an Event, with PUT
      description: Modify an Event, with PUT
      operationId: eventsv2accountideventseventid
      x-api-path-slug: eventsv2accountideventseventid-put
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
    delete:
      summary: Remove an Event
      description: Remove an Event
      operationId: eventsv2accountideventseventid
      x-api-path-slug: eventsv2accountideventseventid-delete
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
  /events/v2/{accountId}/events/{eventId}/services:
    get:
      summary: List Services
      description: List Services
      operationId: eventsv2accountideventseventidservices
      x-api-path-slug: eventsv2accountideventseventidservices-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Services
  /events/v2/{accountId}/events/id:
    get:
      summary: List Range of Events
      description: List Range of Events
      operationId: eventsv2accountideventsidstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid
      x-api-path-slug: eventsv2accountideventsid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: customerEventId
        description: Event identifier for your own use
        type: string
      - in: query
        name: endRange
        description: End of event, specified as epoch time milliseconds
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field that should be used to sort the result set
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      - in: query
        name: startRange
        description: Start of event, specified as epoch time milliseconds
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - ""
      - Startrange
      - endrange
      - sortfield
      - sortorder
      - startindex
      - limit
      - customerevent
  /events/v2/{accountId}/events/live:
    get:
      summary: List Events in Progress
      description: List Events in Progress
      operationId: eventsv2accountideventslive
      x-api-path-slug: eventsv2accountideventslive-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Live
  /events/v2/{accountId}/events/live/{time}:
    get:
      summary: List Events Current for Specific Time
      description: List Events Current for Specific Time
      operationId: eventsv2accountideventslivetime
      x-api-path-slug: eventsv2accountideventslivetime-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: time
        description: The epoch time
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Live
      - Time
  /events/v2/{accountId}/events/upcoming:
    get:
      summary: List Upcoming Events
      description: List Upcoming Events
      operationId: eventsv2accountideventsupcoming
      x-api-path-slug: eventsv2accountideventsupcoming-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Upcoming
  /events/v2/{accountId}/events/upcoming/{rangeInHours}:
    get:
      summary: List Impending Events
      description: List Impending Events
      operationId: eventsv2accountideventsupcomingrangeinhours
      x-api-path-slug: eventsv2accountideventsupcomingrangeinhours-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: rangeInHours
        description: The range of data in number of hours
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Upcoming
      - Rangeinhours
  /events/v2/{accountId}/events/alerts:
    get:
      summary: List Alerts
      description: List Alerts
      operationId: eventsv2accountideventsalerts
      x-api-path-slug: eventsv2accountideventsalerts-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Alerts
  /events/v2/{accountId}/events/{eventId}/alerts:
    get:
      summary: List Alerts per Event
      description: List Alerts per Event
      operationId: eventsv2accountideventseventidalerts
      x-api-path-slug: eventsv2accountideventseventidalerts-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Alerts
  data:
    get:
      summary: Get Event Traffic Data by CP Code
      description: Get Event Traffic Data by CP Code
      operationId: data
      x-api-path-slug: data-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Data
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/bandwidth/{cpcode}:
    get:
      summary: Get Edge Bandwidth per CP Code
      description: Get Edge Bandwidth per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeedgebandwidthcpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeedgebandwidthcpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Edge
      - Bandwth
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/requests/{cpcode}:
    get:
      summary: Get Event&#8217;s Edge Requests, per CP Code
      description: Get Event&#8217;s Edge Requests, per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeedgerequestscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeedgerequestscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Edge
      - Requests
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/status:
    get:
      summary: Get Event&#8217;s Status Totals
      description: Get Event&#8217;s Status Totals
      operationId: eventsv2accountideventseventidtrafficdatacpcodeedgestatus
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeedgestatus-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Edge
      - Status
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/status/{cpcode}:
    get:
      summary: Get Event&#8217;s Status Totals per CP Code
      description: Get Event&#8217;s Status Totals per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeedgestatuscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeedgestatuscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Edge
      - Status
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/bandwidth:
    get:
      summary: Get Event&#8217;s Bandwidth Data
      description: Get Event&#8217;s Bandwidth Data
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidth
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidth-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Bandwth
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/bandwidth/{cpcode}:
    get:
      summary: Get Event&#8217;s Bandwidth Data per CP Code
      description: Get Event&#8217;s Bandwidth Data per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidthcpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidthcpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Bandwth
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/requests:
    get:
      summary: Get Event&#8217;s Origin Requests
      description: Get Event&#8217;s Origin Requests
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginrequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginrequests-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Requests
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/requests/{cpcode}:
    get:
      summary: Get Event&#8217;s Origin Requests per CP Code
      description: Get Event&#8217;s Origin Requests per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginrequestscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginrequestscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Requests
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/status:
    get:
      summary: Get Event&#8217;s Origin Statuses
      description: Get Event&#8217;s Origin Statuses
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginstatus
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginstatus-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Status
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/status/{cpcode}:
    get:
      summary: Get Event&#8217;s Origin Statuses per CP Code
      description: Get Event&#8217;s Origin Statuses per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodeoriginstatuscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodeoriginstatuscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Origin
      - Status
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/bandwidth:
    get:
      summary: Get Event&#8217;s I/O Bandwidth
      description: Get Event&#8217;s I/O Bandwidth
      operationId: eventsv2accountideventseventidtrafficdatacpcodebandwidth
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodebandwidth-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Bandwth
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/bandwidth/{cpcode}:
    get:
      summary: Get Event&#8217;s I/O Bandwidth per CP Code
      description: Get Event&#8217;s I/O Bandwidth per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcodebandwidthcpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcodebandwidthcpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Bandwth
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/requests:
    get:
      summary: Get Event&#8217;s Requests
      description: Get Event&#8217;s Requests
      operationId: eventsv2accountideventseventidtrafficdatacpcoderequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcoderequests-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Requests
  /events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/requests/{cpcode}:
    get:
      summary: Get Event&#8217;s Requests per CP Code
      description: Get Event&#8217;s Requests per CP Code
      operationId: eventsv2accountideventseventidtrafficdatacpcoderequestscpcode
      x-api-path-slug: eventsv2accountideventseventidtrafficdatacpcoderequestscpcode-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: cpcode
        description: The CP code associated with the given event
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Cpcode
      - Requests
      - Cpcode
  /events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/flashlive:
    get:
      summary: Get Entry Point Data for Flash Live Streams
      description: Get Entry Point Data for Flash Live Streams
      operationId: eventsv2accountideventseventidtrafficdataentrypointflashlive
      x-api-path-slug: eventsv2accountideventseventidtrafficdataentrypointflashlive-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Entrypoint
      - Flashlive
  /events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/flashlive/{streamId}:
    get:
      summary: Get Entry Point Data for a Flash Live Stream
      description: Get Entry Point Data for a Flash Live Stream
      operationId: eventsv2accountideventseventidtrafficdataentrypointflashlivestreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdataentrypointflashlivestreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Entrypoint
      - Flashlive
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/universallive:
    get:
      summary: Get Entry Point Data for Universal Live Streams
      description: Get Entry Point Data for Universal Live Streams
      operationId: eventsv2accountideventseventidtrafficdataentrypointuniversallive
      x-api-path-slug: eventsv2accountideventseventidtrafficdataentrypointuniversallive-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Entrypoint
      - Universallive
  /events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/universallive/{streamId}:
    get:
      summary: Get Entry Point Data for a Universal Live Stream
      description: Get Entry Point Data for a Universal Live Stream
      operationId: eventsv2accountideventseventidtrafficdataentrypointuniversallivestreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdataentrypointuniversallivestreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Entrypoint
      - Universallive
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressbw:
    get:
      summary: Get Aggregate Data for Flash Live Streams
      description: Get Aggregate Data for Flash Live Streams
      operationId: eventsv2accountideventseventidtrafficdataflegressbw
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressbw-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Fl
      - Egressbw
      - Aggregation
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressbw/{streamId}:
    get:
      summary: Get Aggregate Data for a Flash Live Stream
      description: Get Aggregate Data for a Flash Live Stream
      operationId: eventsv2accountideventseventidtrafficdataflegressbwstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressbwstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Fl
      - Egressbw
      - Stream
      - Aggregation
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressrequests:
    get:
      summary: Get Request Data for Flash Live Streams
      description: Get Request Data for Flash Live Streams
      operationId: eventsv2accountideventseventidtrafficdataflegressrequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressrequests-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Fl
      - Egressrequests
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressrequests/{streamId}:
    get:
      summary: Get Request Data for a Flash Live Stream
      description: Get Request Data for a Flash Live Stream
      operationId: eventsv2accountideventseventidtrafficdataflegressrequestsstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressrequestsstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Fl
      - Egressrequests
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressviewers:
    get:
      summary: Get Viewer Data for Flash Live Streams
      description: Get Viewer Data for Flash Live Streams
      operationId: eventsv2accountideventseventidtrafficdataflegressviewers
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressviewers-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Fl
      - Egressviewers
  /events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressviewers/{streamId}:
    get:
      summary: Get Viewer Data for a Flash Live Stream
      description: Get Viewer Data for a Flash Live Stream
      operationId: eventsv2accountideventseventidtrafficdataflegressviewersstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdataflegressviewersstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Fl
      - Egressviewers
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressbw:
    get:
      summary: Get Aggregate Data for Silverlight Live Streams
      description: Get Aggregate Data for Silverlight Live Streams
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressbw
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressbw-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Hdsll
      - Egress
      - Aggregation
  streamId:
    get:
      summary: Get Silverlight Live Stream
      description: Get Silverlight Live Stream
      operationId: streamid
      x-api-path-slug: streamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressrequests:
    get:
      summary: Get Request Data for Silverlight Live Streams
      description: Get Request Data for Silverlight Live Streams
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressrequests
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressrequests-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Hdsll
      - Egressrequests
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressrequests/{streamId}:
    get:
      summary: Get Request Data for a Silverlight Live Stream
      description: Get Request Data for a Silverlight Live Stream
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressrequestsstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressrequestsstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Hdsll
      - Egressrequests
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressstatus:
    get:
      summary: Get Status Data for Silverlight Live Streams
      description: Get Status Data for Silverlight Live Streams
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressstatus
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressstatus-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Hdsll
      - Egressstatus
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressstatus/{streamId}:
    get:
      summary: Get Status Data for a Silverlight Live Stream
      description: Get Status Data for a Silverlight Live Stream
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressstatusstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressstatusstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Hdsll
      - Egressstatus
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressviewers:
    get:
      summary: Get Viewer Data for Silverlight Live Streams
      description: Get Viewer Data for Silverlight Live Streams
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressviewers
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressviewers-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Hdsll
      - Egressviewers
  /events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressviewers/{streamId}:
    get:
      summary: Get Viewer Data for a Silverlight Live Stream
      description: Get Viewer Data for a Silverlight Live Stream
      operationId: eventsv2accountideventseventidtrafficdatahdsllegressviewersstreamid
      x-api-path-slug: eventsv2accountideventseventidtrafficdatahdsllegressviewersstreamid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Hdsll
      - Egressviewers
      - Stream
  /events/v2/{accountId}/events/{eventId}/trafficdata/srip/connections:
    get:
      summary: Get SRIP Connections
      description: Get SRIP Connections
      operationId: eventsv2accountideventseventidtrafficdatasripconnections
      x-api-path-slug: eventsv2accountideventseventidtrafficdatasripconnections-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Srip
      - Connections
  /events/v2/{accountId}/events/{eventId}/trafficdata/srip/connections/{slotId}:
    get:
      summary: Get SRIP Connections per Slot
      description: Get SRIP Connections per Slot
      operationId: eventsv2accountideventseventidtrafficdatasripconnectionsslotid
      x-api-path-slug: eventsv2accountideventseventidtrafficdatasripconnectionsslotid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: slotId
        description: Unique identifier for the slot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Srip
      - Connections
      - Slot
  /events/v2/{accountId}/events/{eventId}/trafficdata/srip/sourcebandwidth:
    get:
      summary: Get SRIP Bandwidth
      description: Get SRIP Bandwidth
      operationId: eventsv2accountideventseventidtrafficdatasripsourcebandwidth
      x-api-path-slug: eventsv2accountideventseventidtrafficdatasripsourcebandwidth-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Srip
      - Sourcebandwth
  /events/v2/{accountId}/events/{eventId}/trafficdata/srip/sourcebandwidth/{slotId}:
    get:
      summary: Get SRIP Bandwidth per Slot
      description: Get SRIP Bandwidth per Slot
      operationId: eventsv2accountideventseventidtrafficdatasripsourcebandwidthslotid
      x-api-path-slug: eventsv2accountideventseventidtrafficdatasripsourcebandwidthslotid-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: slotId
        description: Unique identifier for the slot
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Events
      - Event
      - Trafficdata
      - Srip
      - Sourcebandwth
      - Slot
  deliveryFormat:
    get:
      summary: Get Edge Bandwidth for Universal Live Streams
      description: Get Edge Bandwidth for Universal Live Streams
      operationId: deliveryformat
      x-api-path-slug: deliveryformat-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: deliveryFormat
        description: The stream format, discussed above
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: range
        description: The range, in minutes, of data to retrieve
        type: string
      - in: query
        name: streamId
        description: Unique identifier for the stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Deliveryformat
  timeAggInterval:
    get:
      summary: Get Audience Size
      description: Get Audience Size
      operationId: timeagginterval
      x-api-path-slug: timeagginterval-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: endDate
        description: The end date
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: reportPackID
        description: Unique numeric identifier for the report pack
        type: string
      - in: query
        name: startDate
        description: The start date
        type: string
      - in: query
        name: timeAggInterval
        description: Defaults to 60 minutes
        type: string
      responses:
        200:
          description: OK
      tags:
      - Audience
  clientside_qos1_live:
    get:
      summary: Get Report Packs
      description: Get Report Packs
      operationId: clientside-qos1-live
      x-api-path-slug: clientside-qos1-live-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Clients
  /events/v2/{accountId}/sites/cpcodes:
    get:
      summary: List CP Codes
      description: List CP Codes
      operationId: eventsv2accountidsitescpcodes
      x-api-path-slug: eventsv2accountidsitescpcodes-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Sites
      - Cpcodes
  /events/v2/{accountId}/srip:
    get:
      summary: List IPA and SXL Configurations
      description: List IPA and SXL Configurations
      operationId: eventsv2accountidsripsortfieldsortorderlimitstartindex
      x-api-path-slug: eventsv2accountidsrip-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field to sort the result set, either description or hostname
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Srip
      - Sortfield
      - sortorder
      - limit
      - startindex
  /events/v2/{accountId}/streams/flashlive:
    get:
      summary: List Flash Live Streams
      description: List Flash Live Streams
      operationId: eventsv2accountidstreamsflashlive
      x-api-path-slug: eventsv2accountidstreamsflashlive-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Streams
      - Flashlive
  /events/v2/{accountId}/streams/silverlightlive:
    get:
      summary: List Silverlight Live Streams
      description: List Silverlight Live Streams
      operationId: eventsv2accountidstreamssilverlightlive
      x-api-path-slug: eventsv2accountidstreamssilverlightlive-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Streams
      - Silverlightlive
  /events/v2/{accountId}/streams/universallive:
    get:
      summary: List Universal Live Streams
      description: List Universal Live Streams
      operationId: eventsv2accountidstreamsuniversallivesortfieldsortorderlimitstartindex
      x-api-path-slug: eventsv2accountidstreamsuniversallive-get
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: limit
        description: The maximum number of pagination records to include
        type: string
      - in: query
        name: sortField
        description: The field to sort the result set, either description or hostname
        type: string
      - in: query
        name: sortOrder
        description: The direction of the sort, asc for ascending or desc for descending
        type: string
      - in: query
        name: startIndex
        description: The zero-origin index at which to start the batch of paginated
          results
        type: string
      responses:
        200:
          description: OK
      tags:
      - Events
      - Account
      - Streams
      - Universallive
      - Sortfield
      - sortorder
      - limit
      - startindex
  /feo/v1/purge:
    post:
      summary: Purge a Configuration
      description: Purge a Configuration
      operationId: feov1purge
      x-api-path-slug: feov1purge-post
      responses:
        200:
          description: OK
      tags:
      - Feo
      - Purge
  /imaging/v0/policies/{id}:
    get:
      summary: Get a Policy
      description: Get a Policy
      operationId: imagingv0policiesid
      x-api-path-slug: imagingv0policiesid-get
      parameters:
      - in: query
        name: id
        description: Unique policy identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Policies
    put:
      summary: Add or Modify a Policy
      description: Add or Modify a Policy
      operationId: imagingv0policiesid
      x-api-path-slug: imagingv0policiesid-put
      parameters:
      - in: query
        name: id
        description: Unique policy identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Policies
    delete:
      summary: Remove a Policy
      description: Remove a Policy
      operationId: imagingv0policiesid
      x-api-path-slug: imagingv0policiesid-delete
      parameters:
      - in: query
        name: id
        description: Unique policy identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Policies
  /imaging/v0/policies:
    get:
      summary: List Policies
      description: List Policies
      operationId: imagingv0policies
      x-api-path-slug: imagingv0policies-get
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Policies
  id:
    get:
      summary: Get Policy History
      description: Get Policy History
      operationId: id
      x-api-path-slug: id-get
      parameters:
      - in: query
        name: id
        description: Unique policy identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Policies
      - History
    delete:
      summary: Remove an Image Collection
      description: Remove an Image Collection
      operationId: id
      x-api-path-slug: id-delete
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Images
  /imaging/v0/images:
    get:
      summary: List a Policy&#8217;s Images
      description: List a Policy&#8217;s Images
      operationId: imagingv0imagespolicyid
      x-api-path-slug: imagingv0images-get
      parameters:
      - in: query
        name: policyId
        description: Identifies the policy for which to get associated images
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Images
      - Policy
  /imaging/v0/images/{id}:
    get:
      summary: Get an Image
      description: Get an Image
      operationId: imagingv0imagesid
      x-api-path-slug: imagingv0imagesid-get
      parameters:
      - in: query
        name: id
        description: Identifies the image for which to retrieve metadata
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Images
  /imaging/v0/imagecollections:
    get:
      summary: List Image Collections By Tag
      description: List Image Collections By Tag
      operationId: imagingv0imagecollectionstag
      x-api-path-slug: imagingv0imagecollections-get
      parameters:
      - in: query
        name: tag
        description: Image tag you want to match in a collection
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
      - Tag
  /imaging/v0/imagecollections/{id}:
    get:
      summary: Get an Image Collection
      description: Get an Image Collection
      operationId: imagingv0imagecollectionsid
      x-api-path-slug: imagingv0imagecollectionsid-get
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
    put:
      summary: Add or Modify an Image Collection
      description: Add or Modify an Image Collection
      operationId: imagingv0imagecollectionsid
      x-api-path-slug: imagingv0imagecollectionsid-put
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
  /imaging/v0/imagecollections/tags/{id}:
    get:
      summary: Get an Image Collection&#8217;s Tags
      description: Get an Image Collection&#8217;s Tags
      operationId: imagingv0imagecollectionstagsid
      x-api-path-slug: imagingv0imagecollectionstagsid-get
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
      - Tags
    put:
      summary: Modify an Image Collection&#8217;s Tags
      description: Modify an Image Collection&#8217;s Tags
      operationId: imagingv0imagecollectionstagsid
      x-api-path-slug: imagingv0imagecollectionstagsid-put
      parameters:
      - in: query
        name: id
        description: 'Unique identifier for the image collection '
        type: string
      responses:
        200:
          description: OK
      tags:
      - Imaging
      - V0
      - Imagecollections
      - Tags
  /invoicing-api/v2/accounts/{accountId}/invoices:
    get:
      summary: List Account&#8217;s Invoices
      description: List Account&#8217;s Invoices
      operationId: invoicingapiv2accountsaccountidinvoicesyearmonth
      x-api-path-slug: invoicingapiv2accountsaccountidinvoices-get
      parameters:
      - in: query
        name: accountId
        description: Identifies the account under which data is aggregated
        type: string
      - in: query
        name: month
        description: The month for which data is aggregated
        type: string
      - in: query
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Accounts
      - Account
      - Invoices
      - Year
      - month
  /invoicing-api/v2/contracts/{contractId}/invoices:
    get:
      summary: List Contract&#8217;s Invoices
      description: List Contract&#8217;s Invoices
      operationId: invoicingapiv2contractscontractidinvoicesyearmonth
      x-api-path-slug: invoicingapiv2contractscontractidinvoices-get
      parameters:
      - in: query
        name: contractId
        description: Identifies the contract under which data is aggregated
        type: string
      - in: query
        name: month
        description: The month for which data is aggregated
        type: string
      - in: query
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Contracts
      - Contract
      - Invoices
      - Year
      - month
  /invoicing-api/v2/contracts/{contractId}/invoices/{invoiceNumber}/files:
    get:
      summary: List Contract&#8217;s Invoice Files
      description: List Contract&#8217;s Invoice Files
      operationId: invoicingapiv2contractscontractidinvoicesinvoicenumberfiles
      x-api-path-slug: invoicingapiv2contractscontractidinvoicesinvoicenumberfiles-get
      parameters:
      - in: query
        name: contractId
        description: Identifies the contract under which data is aggregated
        type: string
      - in: query
        name: invoiceNumber
        description: Identifies each unique invoice
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Contracts
      - Contract
      - Invoices
      - Invoicenumber
      - Files
  Content-Type:
    get:
      summary: Download an Invoice File
      description: Download an Invoice File
      operationId: contenttype
      x-api-path-slug: contenttype-get
      parameters:
      - in: query
        name: contractId
        description: Identifies the contract under which data is aggregated
        type: string
      - in: query
        name: filename
        description: Identifies each invoice file
        type: string
      - in: query
        name: invoiceNumber
        description: Identifies each unique invoice
        type: string
      responses:
        200:
          description: OK
      tags:
      - Content
      - Type
  /invoicing-api/v2/contracts/{contractId}/products/{productId}/geo-billing-files:
    get:
      summary: Download Geobilling Files
      description: Download Geobilling Files
      operationId: invoicingapiv2contractscontractidproductsproductidgeobillingfilesyearmonthday
      x-api-path-slug: invoicingapiv2contractscontractidproductsproductidgeobillingfiles-get
      parameters:
      - in: query
        name: contractId
        description: Identifies the contract under which data is aggregated
        type: string
      - in: query
        name: day
        description: The day for which data is aggregated
        type: string
      - in: query
        name: month
        description: The month for which data is aggregated
        type: string
      - in: query
        name: productId
        description: Identifies the product under which data is aggregated
        type: string
      - in: query
        name: year
        description: The year for which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Contracts
      - Contract
      - Products
      - Product
      - Geo
      - Billing
      - Files
      - Year
      - month
      - day
  /invoicing-api/v2/accounts/{accountId}/notifications:
    get:
      summary: List Notifications
      description: List Notifications
      operationId: invoicingapiv2accountsaccountidnotifications
      x-api-path-slug: invoicingapiv2accountsaccountidnotifications-get
      parameters:
      - in: query
        name: accountId
        description: Identifies the account under which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Accounts
      - Account
      - Notifications
    post:
      summary: Create a Notification
      description: Create a Notification
      operationId: invoicingapiv2accountsaccountidnotifications
      x-api-path-slug: invoicingapiv2accountsaccountidnotifications-post
      parameters:
      - in: query
        name: accountId
        description: Identifies the account under which data is aggregated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Accounts
      - Account
      - Notifications
  /invoicing-api/v2/accounts/{accountId}/notifications/{notificationId}:
    get:
      summary: Get a Notification
      description: Get a Notification
      operationId: invoicingapiv2accountsaccountidnotificationsnotificationid
      x-api-path-slug: invoicingapiv2accountsaccountidnotificationsnotificationid-get
      parameters:
      - in: query
        name: accountId
        description: Identifies the account under which data is aggregated
        type: string
      - in: query
        name: notificationId
        description: Identifies each notification
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Accounts
      - Account
      - Notifications
      - Notification
    put:
      summary: Modify a Notification
      description: Modify a Notification
      operationId: invoicingapiv2accountsaccountidnotificationsnotificationid
      x-api-path-slug: invoicingapiv2accountsaccountidnotificationsnotificationid-put
      parameters:
      - in: query
        name: accountId
        description: Identifies the account under which data is aggregated
        type: string
      - in: query
        name: notificationId
        description: Identifies each notification
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Accounts
      - Account
      - Notifications
      - Notification
    delete:
      summary: Remove a Notification
      description: Remove a Notification
      operationId: invoicingapiv2accountsaccountidnotificationsnotificationid
      x-api-path-slug: invoicingapiv2accountsaccountidnotificationsnotificationid-delete
      parameters:
      - in: query
        name: accountId
        description: Identifies the account under which data is aggregated
        type: string
      - in: query
        name: notificationId
        description: Identifies each notification
        type: string
      responses:
        200:
          description: OK
      tags:
      - Invoicing
      - Accounts
      - Account
      - Notifications
      - Notification
  acgObject:
    get:
      summary: List Configurations
      description: List Configurations
      operationId: acgobject
      x-api-path-slug: acgobject-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
  serviceId:
    post:
      summary: Create a Configuration
      description: Create a Configuration
      operationId: serviceid
      x-api-path-slug: serviceid-post
      parameters:
      - in: query
        name: serviceId
        description: ID of the configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service
    get:
      summary: Get a Configuration
      description: Get a Configuration
      operationId: serviceid
      x-api-path-slug: serviceid-get
      parameters:
      - in: query
        name: serviceId
        description: ID of the configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service
    put:
      summary: Modify a Configuration
      description: Modify a Configuration
      operationId: serviceid
      x-api-path-slug: serviceid-put
      parameters:
      - in: query
        name: serviceId
        description: ID of the configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service
    delete:
      summary: Remove a Configuration
      description: Remove a Configuration
      operationId: serviceid
      x-api-path-slug: serviceid-delete
      parameters:
      - in: query
        name: serviceId
        description: ID of the configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Service
  sourceServiceId:
    post:
      summary: Copy a Configuration
      description: Copy a Configuration
      operationId: sourceserviceid
      x-api-path-slug: sourceserviceid-post
      parameters:
      - in: query
        name: sourceServiceId
        description: ID of the source configuration for copy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Services
  /lds/v1/configurations/resume/{serviceId}:
    post:
      summary: Resume a Configuration
      description: Resume a Configuration
      operationId: ldsv1configurationsresumeserviceid
      x-api-path-slug: ldsv1configurationsresumeserviceid-post
      parameters:
      - in: query
        name: serviceId
        description: ID of the configuration
        type: string
      responses:
        200:
          description: OK
      tags:
      - Lds
      - Configurationsurations
      - Resume
      - Service
  /lds/v1/redeliveries:
    get:
      summary: List Redeliveries
      description: List Redeliveries
      operationId: ldsv1redeliveries
      x-api-path-slug: ldsv1redeliveries-get
      responses:
        200:
          description: OK
      tags:
      - Lds
      - Redeliveries
    post:
      summary: Create a Redelivery
      description: Create a Redelivery
      operationId: ldsv1redeliveries
      x-api-path-slug: ldsv1redeliveries-post
      responses:
        200:
          description: OK
      tags:
      - Lds
      - Redeliveries
  redeliveryId:
    get:
      summary: Get a Redelivery
      description: Get a Redelivery
      operationId: redeliveryid
      x-api-path-slug: redeliveryid-get
      parameters:
      - in: query
        name: redeliveryId
        description: ID of the redelivery
        type: string
      responses:
        200:
          description: OK
      tags:
      - Redelivery
  key:
    get:
      summary: Get a Dictionary
      description: Get a Dictionary
      operationId: key
      x-api-path-slug: key-get
      parameters:
      - in: query
        name: currentValueKey
        description: Value of current key
        type: string
      - in: query
        name: dictionaryName
        description: Dictionary name value
        type: string
      - in: query
        name: objectId
        description: The acgObject identifier
        type: string
      - in: query
        name: objectType
        description: The acgObject type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Key
  /lds/v1/dictionaries/{dictionaryName}/validation/data:
    get:
      summary: Get Validation Context
      description: Get Validation Context
      operationId: ldsv1dictionariesdictionarynamevalidationdata
      x-api-path-slug: ldsv1dictionariesdictionarynamevalidationdata-get
      parameters:
      - in: query
        name: dictionaryName
        description: Dictionary name value
        type: string
      responses:
        200:
          description: OK
      tags:
      - Lds
      - Dictionaries
      - Dictionaryname
      - Valation
      - Data
  /media-reports/v1/download-delivery/dimensions:
    get:
      summary: List Download Delivery Dimensions
      description: List Download Delivery Dimensions
      operationId: mediareportsv1downloaddeliverydimensions
      x-api-path-slug: mediareportsv1downloaddeliverydimensions-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Download
      - Delivery
      - Dimensions
  /media-reports/v1/download-delivery/metrics:
    get:
      summary: List Download Delivery Metrics
      description: List Download Delivery Metrics
      operationId: mediareportsv1downloaddeliverymetrics
      x-api-path-slug: mediareportsv1downloaddeliverymetrics-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Download
      - Delivery
      - Metrics
  filterParams:
    get:
      summary: Get Download Delivery Data
      description: Get Download Delivery Data
      operationId: filterparams
      x-api-path-slug: filterparams-get
      parameters:
      - in: query
        name: aggregation
        description: The aggregation in which the data is required to be grouped
        type: string
      - in: query
        name: cpcodes
        description: Comma-separated CP codes for which the data is required
        type: string
      - in: query
        name: deliveryFormat
        description: One of sp_hds, sp_hls, hls, smooth, others, or all for stream
          packaging HDS, stream packaging HLS, HLS, microsoft smooth streaming, other
          formats and all formats respectively
        type: string
      - in: query
        name: deliveryOption
        description: 'One of the following values: http for non-secure traffic, ssl
          for secure traffic (Shared Certificate), essl for secure traffic (Customer
          Certificate), or all'
        type: string
      - in: query
        name: deliveryType
        description: One of live, vod, or all
        type: string
      - in: query
        name: dimensions
        description: Comma-separated IDs of required dimensions
        type: string
      - in: query
        name: endDate
        description: The end date string in format mm/dd/yyyy:HH:MM
        type: string
      - in: query
        name: filterParams
        description: The UTF&#8211;8 URL-encoded JSON string of the filter parameters
          based on which the data is filtered
        type: string
      - in: query
        name: ipVersion
        description: One of ipv4, ipv6, or all
        type: string
      - in: query
        name: limit
        description: The number of rows to return
        type: string
      - in: query
        name: metrics
        description: Comma-separated IDs of required metrics
        type: string
      - in: query
        name: offset
        description: The offset of the row from which the data should start
        type: string
      - in: query
        name: sortParams
        description: The UTF&#8211;8 URL-encoded JSON string of the sort parameters
          based on which the data is sorted
        type: string
      - in: query
        name: startDate
        description: The start date string in format mm/dd/yyyy:HH:MM
        type: string
      - in: query
        name: streams
        description: Comma-separated Stream IDs for which the data is required
        type: string
      responses:
        200:
          description: OK
      tags:
      - Filterparams
  /media-reports/v1/object-delivery/metrics:
    get:
      summary: List Object Delivery Metrics
      description: List Object Delivery Metrics
      operationId: mediareportsv1objectdeliverymetrics
      x-api-path-slug: mediareportsv1objectdeliverymetrics-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Object
      - Delivery
      - Metrics
  /media-reports/v1/adaptive-media-delivery/metrics:
    get:
      summary: List Adaptive Media Delivery Metrics
      description: List Adaptive Media Delivery Metrics
      operationId: mediareportsv1adaptivemediadeliverymetrics
      x-api-path-slug: mediareportsv1adaptivemediadeliverymetrics-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Adaptive
      - Media
      - Delivery
      - Metrics
  /media-reports/v1/rtmp-media-delivery/metrics:
    get:
      summary: List RTMP Media Delivery Metrics
      description: List RTMP Media Delivery Metrics
      operationId: mediareportsv1rtmpmediadeliverymetrics
      x-api-path-slug: mediareportsv1rtmpmediadeliverymetrics-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Rtmp
      - Media
      - Delivery
      - Metrics
  /media-reports/v1/wholesale-delivery/metrics:
    get:
      summary: List Wholesale Delivery Metrics
      description: List Wholesale Delivery Metrics
      operationId: mediareportsv1wholesaledeliverymetrics
      x-api-path-slug: mediareportsv1wholesaledeliverymetrics-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Wholesale
      - Delivery
      - Metrics
  /media-reports/v1/media-services-live/http-ingest/metrics:
    get:
      summary: List HTTP Ingest Metrics
      description: List HTTP Ingest Metrics
      operationId: mediareportsv1mediaserviceslivehttpingestmetrics
      x-api-path-slug: mediareportsv1mediaserviceslivehttpingestmetrics-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Media
      - Services
      - Live
      - Http
      - Ingest
      - Metrics
  /media-reports/v1/media-services-live/rtmp-ingest/dimensions:
    get:
      summary: List RTMP Ingest Dimensions
      description: List RTMP Ingest Dimensions
      operationId: mediareportsv1mediaserviceslivertmpingestdimensions
      x-api-path-slug: mediareportsv1mediaserviceslivertmpingestdimensions-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Media
      - Services
      - Live
      - Rtmp
      - Ingest
      - Dimensions
  /media-reports/v1/media-services-live/rtmp-ingest/metrics:
    get:
      summary: List RTMP Ingest Metrics
      description: List RTMP Ingest Metrics
      operationId: mediareportsv1mediaserviceslivertmpingestmetrics
      x-api-path-slug: mediareportsv1mediaserviceslivertmpingestmetrics-get
      responses:
        200:
          description: OK
      tags:
      - Media
      - Reports
      - Media
      - Services
      - Live
      - Rtmp
      - Ingest
      - Metrics
  /config-media-live/v1/live:
    get:
      summary: List Domains
      description: List Domains
      operationId: configmedialivev1live
      x-api-path-slug: configmedialivev1live-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
    post:
      summary: Create a Domain
      description: Create a Domain
      operationId: configmedialivev1live
      x-api-path-slug: configmedialivev1live-post
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
  /config-media-live/v1/live/{domain}:
    get:
      summary: Get a Domain
      description: Get a Domain
      operationId: configmedialivev1livedomain
      x-api-path-slug: configmedialivev1livedomain-get
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
    delete:
      summary: Remove a Domain
      description: Remove a Domain
      operationId: configmedialivev1livedomain
      x-api-path-slug: configmedialivev1livedomain-delete
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
  /config-media-live/v1/live/{domain}/stream:
    get:
      summary: List Streams
      description: List Streams
      operationId: configmedialivev1livedomainstream
      x-api-path-slug: configmedialivev1livedomainstream-get
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
    post:
      summary: Create a New Stream
      description: Create a New Stream
      operationId: configmedialivev1livedomainstream
      x-api-path-slug: configmedialivev1livedomainstream-post
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
  /config-media-live/v1/live/{domain}/stream/{streamId}:
    get:
      summary: Get a Stream
      description: Get a Stream
      operationId: configmedialivev1livedomainstreamstreamid
      x-api-path-slug: configmedialivev1livedomainstreamstreamid-get
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
      - Stream
    delete:
      summary: Remove a Stream
      description: Remove a Stream
      operationId: configmedialivev1livedomainstreamstreamid
      x-api-path-slug: configmedialivev1livedomainstreamstreamid-delete
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
      - Stream
    put:
      summary: Modify a Stream
      description: Modify a Stream
      operationId: configmedialivev1livedomainstreamstreamid
      x-api-path-slug: configmedialivev1livedomainstreamstreamid-put
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
      - Stream
  /config-media-live/v1/live/{domain}/stream/{streamId}/event:
    get:
      summary: List Events
      description: List Events
      operationId: configmedialivev1livedomainstreamstreamidevent
      x-api-path-slug: configmedialivev1livedomainstreamstreamidevent-get
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
      - Stream
      - Event
  /config-media-live/v1/live/{domain}/stream/{streamId}/event/{eventName}:
    get:
      summary: Get an Event
      description: Get an Event
      operationId: configmedialivev1livedomainstreamstreamideventeventname
      x-api-path-slug: configmedialivev1livedomainstreamstreamideventeventname-get
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: eventName
        description: Human-readable event name
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
      - Stream
      - Event
      - Eventname
    put:
      summary: Modify an Event
      description: Modify an Event
      operationId: configmedialivev1livedomainstreamstreamideventeventname
      x-api-path-slug: configmedialivev1livedomainstreamstreamideventeventname-put
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: eventName
        description: Human-readable event name
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
      - Stream
      - Event
      - Eventname
    delete:
      summary: Remove an Event
      description: Remove an Event
      operationId: configmedialivev1livedomainstreamstreamideventeventname
      x-api-path-slug: configmedialivev1livedomainstreamstreamideventeventname-delete
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: eventName
        description: Human-readable event name
        type: string
      - in: query
        name: streamId
        description: Unique identifier for each stream
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Stream
      - Stream
      - Event
      - Eventname
  /config-media-live/v1/live/{domain}/version:
    post:
      summary: Create a New Version
      description: Create a New Version
      operationId: configmedialivev1livedomainversion
      x-api-path-slug: configmedialivev1livedomainversion-post
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Version
  /config-media-live/v1/live/{domain}/version/{versionId}:
    get:
      summary: Get a Version
      description: Get a Version
      operationId: configmedialivev1livedomainversionversionid
      x-api-path-slug: configmedialivev1livedomainversionversionid-get
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: versionId
        description: Domain&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Version
  /config-media-live/v1/live/{domain}/version/{versionId}/activation:
    get:
      summary: Get Activation Status
      description: Get Activation Status
      operationId: configmedialivev1livedomainversionversionidactivation
      x-api-path-slug: configmedialivev1livedomainversionversionidactivation-get
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: versionId
        description: Domain&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Version
      - Activation
    put:
      summary: Activate a Version
      description: Activate a Version
      operationId: configmedialivev1livedomainversionversionidactivation
      x-api-path-slug: configmedialivev1livedomainversionversionidactivation-put
      parameters:
      - in: query
        name: domain
        description: Unique identifier for each domain
        type: string
      - in: query
        name: versionId
        description: Domain&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Domain
      - Version
      - Activation
  /config-media-live/v1/api/live/utils/archivelocation:
    get:
      summary: List Archive Locations
      description: List Archive Locations
      operationId: configmedialivev1apiliveutilsarchivelocation
      x-api-path-slug: configmedialivev1apiliveutilsarchivelocation-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Archives
  /config-media-live/v1/live/utils/contacts:
    get:
      summary: List Contacts
      description: List Contacts
      operationId: configmedialivev1liveutilscontacts
      x-api-path-slug: configmedialivev1liveutilscontacts-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Contacts
  /config-media-live/v1/live/utils/countries:
    get:
      summary: List Countries
      description: List Countries
      operationId: configmedialivev1liveutilscountries
      x-api-path-slug: configmedialivev1liveutilscountries-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Countries
  /config-media-live/v1/live/utils/cpcode:
    get:
      summary: List CP Codes
      description: List CP Codes
      operationId: configmedialivev1liveutilscpcode
      x-api-path-slug: configmedialivev1liveutilscpcode-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Cpcode
  /config-media-live/v1/live/utils/delivery/format:
    get:
      summary: List Delivery Formats
      description: List Delivery Formats
      operationId: configmedialivev1liveutilsdeliveryformat
      x-api-path-slug: configmedialivev1liveutilsdeliveryformat-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Delivery
      - Format
  /config-media-live/v1/live/utils/ingest/format:
    get:
      summary: List Ingest Formats
      description: List Ingest Formats
      operationId: configmedialivev1liveutilsingestformat
      x-api-path-slug: configmedialivev1liveutilsingestformat-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Live
      - Live
      - Utils
      - Ingest
      - Format
  /network-list/v1/network_lists:
    get:
      summary: List Network Lists
      description: List Network Lists
      operationId: networklistv1network-listslisttypeextendedincludedeprecatedincludeelements
      x-api-path-slug: networklistv1network-lists-get
      parameters:
      - in: query
        name: extended
        description: If enabled, returns more verbose data such as creation date and
          activation status
        type: string
      - in: query
        name: includeDeprecated
        description: When enabled, includes network lists that have been deleted
        type: string
      - in: query
        name: includeElements
        description: When enabled, includes the full list of IP or GEO elements, otherwise
          when disabled only provides high-level data about the network list
        type: string
      - in: query
        name: listType
        description: Filters by the network list type, either GEO or IP
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Listtype
      - extended
      - includedeprecated
      - includeelements
    post:
      summary: Create a Network List
      description: Create a Network List
      operationId: networklistv1network-listslisttypeextendedincludedeprecatedincludeelements
      x-api-path-slug: networklistv1network-lists-post
      parameters:
      - in: query
        name: extended
        description: If enabled, returns more verbose data such as creation date and
          activation status
        type: string
      - in: query
        name: includeDeprecated
        description: When enabled, includes network lists that have been deleted
        type: string
      - in: query
        name: includeElements
        description: When enabled, includes the full list of IP or GEO elements, otherwise
          when disabled only provides high-level data about the network list
        type: string
      - in: query
        name: listType
        description: Filters by the network list type, either GEO or IP
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Listtype
      - extended
      - includedeprecated
      - includeelements
  /network-list/v1/network_lists/{networkListId}:
    put:
      summary: Modify a Network List
      description: Modify a Network List
      operationId: networklistv1network-listsnetworklistidextended
      x-api-path-slug: networklistv1network-listsnetworklistid-put
      parameters:
      - in: query
        name: extended
        description: If enabled, returns more verbose data such as creation date and
          activation status
        type: string
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Extended
    get:
      summary: Get a Network List
      description: Get a Network List
      operationId: networklistv1network-listsnetworklistidextended
      x-api-path-slug: networklistv1network-listsnetworklistid-get
      parameters:
      - in: query
        name: extended
        description: If enabled, returns more verbose data such as creation date and
          activation status
        type: string
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Extended
    post:
      summary: Add to a Network List
      description: Add to a Network List
      operationId: networklistv1network-listsnetworklistidextended
      x-api-path-slug: networklistv1network-listsnetworklistid-post
      parameters:
      - in: query
        name: extended
        description: If enabled, returns more verbose data such as creation date and
          activation status
        type: string
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Extended
  /network-list/v1/network_lists/{networkListId}/element:
    put:
      summary: Add an Element
      description: Add an Element
      operationId: networklistv1network-listsnetworklistidelement
      x-api-path-slug: networklistv1network-listsnetworklistidelement-put
      parameters:
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Element
    delete:
      summary: Remove an Element
      description: Remove an Element
      operationId: networklistv1network-listsnetworklistidelementelement
      x-api-path-slug: networklistv1network-listsnetworklistidelement-delete
      parameters:
      - in: query
        name: element
        description: Identifies the IP or GEO item to delete
        type: string
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Element
      - Element
  /network-list/v1/network_lists/{networkListId}/activate:
    post:
      summary: Activate a Network List
      description: Activate a Network List
      operationId: networklistv1network-listsnetworklistidactivateenv
      x-api-path-slug: networklistv1network-listsnetworklistidactivate-post
      parameters:
      - in: query
        name: env
        description: Specifies the target network environment, either production or
          staging
        type: string
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Activate
      - Env
  /network-list/v1/network_lists/{networkListId}/status:
    get:
      summary: Get Activation Status
      description: Get Activation Status
      operationId: networklistv1network-listsnetworklistidstatusenv
      x-api-path-slug: networklistv1network-listsnetworklistidstatus-get
      parameters:
      - in: query
        name: env
        description: Specifies the target network environment, either production or
          staging
        type: string
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Status
      - Env
  /network-list/v1/network_lists/{networkListId}/history:
    get:
      summary: Get Activation Snapshot
      description: Get Activation Snapshot
      operationId: networklistv1network-listsnetworklistidhistorysync2dpointextended
      x-api-path-slug: networklistv1network-listsnetworklistidhistory-get
      parameters:
      - in: query
        name: extended
        description: If enabled, returns more verbose data such as creation date and
          activation status
        type: string
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      - in: query
        name: sync%2dpoint
        description: Indicates how many times the network list has been modified
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - History
      - Sync%2dpoint
      - extended
  /network-list/v1/network_lists/search:
    get:
      summary: Search Network Lists
      description: Search Network Lists
      operationId: networklistv1network-listssearchexpressionlisttypeextendedincludedeprecated
      x-api-path-slug: networklistv1network-listssearch-get
      parameters:
      - in: query
        name: expression
        description: Matches items included in network lists
        type: string
      - in: query
        name: extended
        description: If enabled, returns more verbose data such as creation date and
          activation status
        type: string
      - in: query
        name: includeDeprecated
        description: When enabled, includes network lists that have been deleted
        type: string
      - in: query
        name: listType
        description: Filters by the network list type, either GEO or IP
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Search
      - Expression
      - listtype
      - extended
      - includedeprecated
  /network-list/v1/network_lists/{networkListId}/share:
    post:
      summary: Share a Network List
      description: Share a Network List
      operationId: networklistv1network-listsnetworklistidshare
      x-api-path-slug: networklistv1network-listsnetworklistidshare-post
      parameters:
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - Network
      - List
      - Network
      - Lists
      - Networklist
      - Share
  ALL:
    get:
      summary: List Sharing Status
      description: List Sharing Status
      operationId: all
      x-api-path-slug: all-get
      parameters:
      - in: query
        name: networkListId
        description: Unique identifier for the network list, corresponding to the
          unique-id within the data
        type: string
      responses:
        200:
          description: OK
      tags:
      - All
  /prolexic-analytics/v1/events/contract/{contract}:
    get:
      summary: List Events
      description: List Events
      operationId: prolexicanalyticsv1eventscontractcontract
      x-api-path-slug: prolexicanalyticsv1eventscontractcontract-get
      parameters:
      - in: query
        name: contract
        description: Name of contract events should be attached to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Prolexic
      - Analytics
      - Events
      - Contract
      - Contract
  /prolexic-analytics/v1/critical-events/contract/{contract}:
    get:
      summary: List Critical Events
      description: List Critical Events
      operationId: prolexicanalyticsv1criticaleventscontractcontract
      x-api-path-slug: prolexicanalyticsv1criticaleventscontractcontract-get
      parameters:
      - in: query
        name: contract
        description: Name of contract events should be attached to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Prolexic
      - Analytics
      - Critical
      - Events
      - Contract
      - Contract
  /prolexic-analytics/v1/metric-types:
    get:
      summary: List Metric Types
      description: List Metric Types
      operationId: prolexicanalyticsv1metrictypes
      x-api-path-slug: prolexicanalyticsv1metrictypes-get
      responses:
        200:
          description: OK
      tags:
      - Prolexic
      - Analytics
      - Metric
      - Types
  type:
    post:
      summary: Get Metrics Data
      description: Get Metrics Data
      operationId: type
      x-api-path-slug: type-post
      responses:
        200:
          description: OK
      tags:
      - Type
  /prolexic-analytics/v1/attack-reports/contract/{contract}/start/{start}/end/{end}:
    get:
      summary: List Attack Reports
      description: List Attack Reports
      operationId: prolexicanalyticsv1attackreportscontractcontractstartstartendend
      x-api-path-slug: prolexicanalyticsv1attackreportscontractcontractstartstartendend-get
      parameters:
      - in: query
        name: contract
        description: Name of contract attack reports belong to
        type: string
      - in: query
        name: end
        description: Unix timestamp for end of attack report search
        type: string
      - in: query
        name: start
        description: Unix timestamp for beginning of attack report search
        type: string
      responses:
        200:
          description: OK
      tags:
      - Prolexic
      - Analytics
      - Attack
      - Reports
      - Contract
      - Contract
      - Start
      - Start
      - End
      - End
  /prolexic-analytics/v1/attack-report/contract/{contract}/attack-id/{attackId}:
    get:
      summary: Get an Attack Report
      description: Get an Attack Report
      operationId: prolexicanalyticsv1attackreportcontractcontractattackidattackid
      x-api-path-slug: prolexicanalyticsv1attackreportcontractcontractattackidattackid-get
      parameters:
      - in: query
        name: attackId
        description: Integer matching the attackId of the attack desired
        type: string
      - in: query
        name: contract
        description: Name of contract attack report belong to
        type: string
      responses:
        200:
          description: OK
      tags:
      - Prolexic
      - Analytics
      - Attack
      - Report
      - Contract
      - Contract
      - Attack
      - ""
      - Attack
  /papi/v0/groups/:
    get:
      summary: List Groups
      description: List Groups
      operationId: papiv0groups
      x-api-path-slug: papiv0groups-get
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Groups
  /papi/v0/contracts/:
    get:
      summary: List Contracts
      description: List Contracts
      operationId: papiv0contracts
      x-api-path-slug: papiv0contracts-get
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Contracts
  /papi/v0/products/{:
    get:
      summary: List Products
      description: List Products
      operationId: papiv0productscontractid
      x-api-path-slug: papiv0products-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Products
      - Contract
  /papi/v0/cpcodes/:
    get:
      summary: List CP Codes
      description: List CP Codes
      operationId: papiv0cpcodescontractidgroupid
      x-api-path-slug: papiv0cpcodes-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Cpcodes
      - Contract
      - group
    post:
      summary: Create a New CP Code
      description: Create a New CP Code
      operationId: papiv0cpcodescontractidgroupid
      x-api-path-slug: papiv0cpcodes-post
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Cpcodes
      - Contract
      - group
  /papi/v0/cpcodes/{cpcodeId}:
    get:
      summary: Get a CP Code
      description: Get a CP Code
      operationId: papiv0cpcodescpcodeidcontractidgroupid
      x-api-path-slug: papiv0cpcodescpcodeid-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: cpcodeId
        description: Unique identifier for the CP code
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Cpcodes
      - Cpcode
      - Contract
      - group
  /papi/v0/edgehostnames/:
    get:
      summary: List Edge Hostnames
      description: List Edge Hostnames
      operationId: papiv0edgehostnamescontractidgroupidoptions
      x-api-path-slug: papiv0edgehostnames-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: options
        description: Comma-separated list of options to enable; mapDetails enables
          extra mapping-related information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Edgehostnames
      - Contract
      - group
      - options
    post:
      summary: Create a New Edge Hostname
      description: Create a New Edge Hostname
      operationId: papiv0edgehostnamescontractidgroupidoptions
      x-api-path-slug: papiv0edgehostnames-post
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: options
        description: Comma-separated list of options to enable; mapDetails enables
          extra mapping-related information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Edgehostnames
      - Contract
      - group
      - options
  /papi/v0/edgehostnames/{edgeHostnameId}:
    get:
      summary: Get an Edge Hostname
      description: Get an Edge Hostname
      operationId: papiv0edgehostnamesedgehostnameidcontractidgroupidoptions
      x-api-path-slug: papiv0edgehostnamesedgehostnameid-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: edgeHostnameId
        description: Unique identifier for the edge hostname
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: options
        description: Comma-separated list of options to enable; mapDetails enables
          extra mapping-related information
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Edgehostnames
      - Edgehostname
      - Contract
      - group
      - options
  /papi/v0/properties/{:
    get:
      summary: List Properties
      description: List Properties
      operationId: papiv0propertiescontractidgroupid
      x-api-path-slug: papiv0properties-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Contract
      - group
  /papi/v0/properties/:
    post:
      summary: Create or Clone a Property
      description: Create or Clone a Property
      operationId: papiv0propertiescontractidgroupid
      x-api-path-slug: papiv0properties-post
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Contract
      - group
  /papi/v0/properties/{propertyId}:
    get:
      summary: Get a Property
      description: Get a Property
      operationId: papiv0propertiespropertyidcontractidgroupid
      x-api-path-slug: papiv0propertiespropertyid-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Contract
      - group
  /papi/v0/properties/{propertyId}/versions:
    get:
      summary: List Property Versions
      description: List Property Versions
      operationId: papiv0propertiespropertyidversionscontractidgroupid
      x-api-path-slug: papiv0propertiespropertyidversions-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Versions
      - Contract
      - group
  createFromVersion:
    post:
      summary: Create a New Property Version
      description: Create a New Property Version
      operationId: createfromversion
      x-api-path-slug: createfromversion-post
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Versions
  /papi/v0/properties/{propertyId}/versions/latest:
    get:
      summary: Get a Property&#8217;s Latest Version
      description: Get a Property&#8217;s Latest Version
      operationId: papiv0propertiespropertyidversionslatestcontractidgroupidactivatedon
      x-api-path-slug: papiv0propertiespropertyidversionslatest-get
      parameters:
      - in: query
        name: activatedOn
        description: If present, returns the latest version activated on the given
          network, either STAGING or PRODUCTION
        type: string
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Versions
      - Latest
      - Contract
      - group
      - activatedon
  'Accept: text/xml':
    get:
      summary: Get a Property Version
      description: Get a Property Version
      operationId: accept-textxml
      x-api-path-slug: accept-textxml-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Accept
      - Text
      - Xml
  /papi/v0/properties/{propertyId}/versions/{propertyVersion}/available-criteria:
    get:
      summary: List Available Criteria
      description: List Available Criteria
      operationId: papiv0propertiespropertyidversionspropertyversionavailablecriteriacontractidgroupid
      x-api-path-slug: papiv0propertiespropertyidversionspropertyversionavailablecriteria-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Versions
      - Propertyversion
      - Available
      - Criteria
      - Contract
      - group
  /papi/v0/properties/{propertyId}/versions/{propertyVersion}/hostnames/:
    get:
      summary: List a Property Version&#8217;s Hostnames
      description: List a Property Version&#8217;s Hostnames
      operationId: papiv0propertiespropertyidversionspropertyversionhostnamescontractidgroupid
      x-api-path-slug: papiv0propertiespropertyidversionspropertyversionhostnames-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Versions
      - Propertyversion
      - Hostnames
      - Contract
      - group
  cnameFrom:
    put:
      summary: Update a Property Version&#8217;s Hostnames
      description: Update a Property Version&#8217;s Hostnames
      operationId: cnamefrom
      x-api-path-slug: cnamefrom-put
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - CName
      - DNS
  /papi/v0/properties/{propertyId}/versions/{propertyVersion}/rules/:
    get:
      summary: Get a Property Version&#8217;s Rule Tree
      description: Get a Property Version&#8217;s Rule Tree
      operationId: papiv0propertiespropertyidversionspropertyversionrulescontractidgroupid
      x-api-path-slug: papiv0propertiespropertyidversionspropertyversionrules-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Versions
      - Propertyversion
      - Rules
      - Contract
      - group
    head:
      summary: Get a Rule Tree&#8217;s Digest
      description: Get a Rule Tree&#8217;s Digest
      operationId: papiv0propertiespropertyidversionspropertyversionrulescontractidgroupid
      x-api-path-slug: papiv0propertiespropertyidversionspropertyversionrules-head
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Versions
      - Propertyversion
      - Rules
      - Contract
      - group
    put:
      summary: Update a Property Version&#8217;s Rule Tree
      description: Update a Property Version&#8217;s Rule Tree
      operationId: papiv0propertiespropertyidversionspropertyversionrulescontractidgroupid
      x-api-path-slug: papiv0propertiespropertyidversionspropertyversionrules-put
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      - in: query
        name: propertyVersion
        description: Property&#8217;s incremental version number
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Versions
      - Propertyversion
      - Rules
      - Contract
      - group
  /papi/v0/properties/{propertyId}/activations/:
    get:
      summary: List a Property&#8217;s Activations
      description: List a Property&#8217;s Activations
      operationId: papiv0propertiespropertyidactivationscontractidgroupid
      x-api-path-slug: papiv0propertiespropertyidactivations-get
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Properties
      - Property
      - Activations
      - Contract
      - group
  '{&quot;type&quot;:&quot;/papi/v0/activation-warnings-not-acknowledged&quot;}':
    post:
      summary: Create a New Activation
      description: Create a New Activation
      operationId: createNewActvation
      x-api-path-slug: quottypequotquotpapiv0activationwarningsnotacknowledgedquot-post
      parameters:
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Activations
  Retry-After:
    get:
      summary: Get an Activation
      description: Get an Activation
      operationId: retryafter
      x-api-path-slug: retryafter-get
      parameters:
      - in: query
        name: activationId
        description: Unique identifier for the activation
        type: string
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Retry
      - After
  status:
    delete:
      summary: Cancel a Pending Activation
      description: Cancel a Pending Activation
      operationId: status
      x-api-path-slug: status-delete
      parameters:
      - in: query
        name: activationId
        description: Unique identifier for the activation
        type: string
      - in: query
        name: contractId
        description: Unique identifier for the contract
        type: string
      - in: query
        name: groupId
        description: Unique identifier for the group
        type: string
      - in: query
        name: propertyId
        description: Unique identifier for the property
        type: string
      responses:
        200:
          description: OK
      tags:
      - Status
  /papi/v0/rule-formats:
    get:
      summary: List Available Rule Formats
      description: List Available Rule Formats
      operationId: papiv0ruleformats
      x-api-path-slug: papiv0ruleformats-get
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Rule
      - Formats
  /papi/v0/schemas/request/{filename}:
    get:
      summary: Get a Request&#8217;s JSON Schema
      description: Get a Request&#8217;s JSON Schema
      operationId: papiv0schemasrequestfilename
      x-api-path-slug: papiv0schemasrequestfilename-get
      parameters:
      - in: query
        name: filename
        description: Schema&#8217;s filename
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Schemas
      - Request
      - Filename
  /papi/v0/schemas/products/{productId}/{ruleFormat}:
    get:
      summary: Get a Rule Format&#8217;s JSON Schema
      description: Get a Rule Format&#8217;s JSON Schema
      operationId: papiv0schemasproductsproductidruleformat
      x-api-path-slug: papiv0schemasproductsproductidruleformat-get
      parameters:
      - in: query
        name: productId
        description: Unique identifier for the product
        type: string
      - in: query
        name: ruleFormat
        description: Name of the rule format, either one frozen to a specific date,
          or representing the latest set of behaviors and criteria
        type: string
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Schemas
      - Products
      - Product
      - Ruleformat
  /papi/v0/client-settings:
    get:
      summary: Get Client Settings
      description: Get Client Settings
      operationId: papiv0clientsettings
      x-api-path-slug: papiv0clientsettings-get
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Client
      - Settings
    put:
      summary: Update Client Settings
      description: Update Client Settings
      operationId: papiv0clientsettings
      x-api-path-slug: papiv0clientsettings-put
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Client
      - Settings
  /papi/v0/build:
    get:
      summary: Get Build Details
      description: Get Build Details
      operationId: papiv0build
      x-api-path-slug: papiv0build-get
      responses:
        200:
          description: OK
      tags:
      - Papi
      - V0
      - Build
  /config-saas-registration/v1/applications/:
    get:
      summary: List Applications
      description: List Applications
      operationId: configsaasregistrationv1applicationscontractid
      x-api-path-slug: configsaasregistrationv1applications-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Contract
    post:
      summary: Create a New Application
      description: Create a New Application
      operationId: configsaasregistrationv1applicationscontractid
      x-api-path-slug: configsaasregistrationv1applications-post
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Contract
  /config-saas-registration/v1/applications/{surrogateId}/:
    get:
      summary: Get an Application
      description: Get an Application
      operationId: configsaasregistrationv1applicationssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1applicationssurrogateid-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Surrogate
      - Contract
    delete:
      summary: Remove an Application
      description: Remove an Application
      operationId: configsaasregistrationv1applicationssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1applicationssurrogateid-delete
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Surrogate
      - Contract
    put:
      summary: Modify an Application
      description: Modify an Application
      operationId: configsaasregistrationv1applicationssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1applicationssurrogateid-put
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Applications
      - Surrogate
      - Contract
  /config-saas-registration/v1/customers/:
    get:
      summary: List Customers
      description: List Customers
      operationId: configsaasregistrationv1customerscontractid
      x-api-path-slug: configsaasregistrationv1customers-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Customers
      - Contract
    post:
      summary: Create a New Customer
      description: Create a New Customer
      operationId: configsaasregistrationv1customerscontractid
      x-api-path-slug: configsaasregistrationv1customers-post
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Customers
      - Contract
  /config-saas-registration/v1/customers/{surrogateId}/:
    get:
      summary: Get a Customer
      description: Get a Customer
      operationId: configsaasregistrationv1customerssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1customerssurrogateid-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 456
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Customers
      - Surrogate
      - Contract
    delete:
      summary: Remove a Customer
      description: Remove a Customer
      operationId: configsaasregistrationv1customerssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1customerssurrogateid-delete
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 456
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Customers
      - Surrogate
      - Contract
    put:
      summary: Modify a Customer
      description: Modify a Customer
      operationId: configsaasregistrationv1customerssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1customerssurrogateid-put
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 456
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Customers
      - Surrogate
      - Contract
  /config-saas-registration/v1/pairs/:
    get:
      summary: List Pairs
      description: List Pairs
      operationId: configsaasregistrationv1pairscontractid
      x-api-path-slug: configsaasregistrationv1pairs-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Pairs
      - Contract
    post:
      summary: Create a New Pair
      description: Create a New Pair
      operationId: configsaasregistrationv1pairscontractid
      x-api-path-slug: configsaasregistrationv1pairs-post
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Pairs
      - Contract
  /config-saas-registration/v1/pairs/{surrogateId}/:
    get:
      summary: Get a Pair
      description: Get a Pair
      operationId: configsaasregistrationv1pairssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1pairssurrogateid-get
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Pairs
      - Surrogate
      - Contract
    delete:
      summary: Remove a Pair
      description: Remove a Pair
      operationId: configsaasregistrationv1pairssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1pairssurrogateid-delete
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Pairs
      - Surrogate
      - Contract
    put:
      summary: Modify a Pair
      description: Modify a Pair
      operationId: configsaasregistrationv1pairssurrogateidcontractid
      x-api-path-slug: configsaasregistrationv1pairssurrogateid-put
      parameters:
      - in: query
        name: contractId
        description: such as A-1234
        type: string
      - in: query
        name: surrogateId
        description: such as 123
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Saas
      - Registration
      - Pairs
      - Surrogate
      - Contract
  /config-media-security/v1/security:
    get:
      summary: List Policies
      description: List Policies
      operationId: configmediasecurityv1security
      x-api-path-slug: configmediasecurityv1security-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
    post:
      summary: Create a Policy
      description: Create a Policy
      operationId: configmediasecurityv1security
      x-api-path-slug: configmediasecurityv1security-post
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
  /config-media-security/v1/security/{policyID}:
    get:
      summary: Get a Policy
      description: Get a Policy
      operationId: configmediasecurityv1securitypolicyid
      x-api-path-slug: configmediasecurityv1securitypolicyid-get
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
    put:
      summary: Modify a Policy
      description: Modify a Policy
      operationId: configmediasecurityv1securitypolicyid
      x-api-path-slug: configmediasecurityv1securitypolicyid-put
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
    delete:
      summary: Mark a Policy for Deletion
      description: Mark a Policy for Deletion
      operationId: configmediasecurityv1securitypolicyid
      x-api-path-slug: configmediasecurityv1securitypolicyid-delete
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
  /config-media-security/v1/security/{policyID}/{environment}:
    get:
      summary: Get Policy per Environment
      description: Get Policy per Environment
      operationId: configmediasecurityv1securitypolicyidenvironment
      x-api-path-slug: configmediasecurityv1securitypolicyidenvironment-get
      parameters:
      - in: query
        name: environment
        description: The environment
        type: string
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
      - Environment
  /config-media-security/v1/security/{policyID}/clonePolicy:
    post:
      summary: Clone a Policy
      description: Clone a Policy
      operationId: configmediasecurityv1securitypolicyidclonepolicy
      x-api-path-slug: configmediasecurityv1securitypolicyidclonepolicy-post
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
      - Clonepolicy
  /config-media-security/v1/security/{policyID}/promote:
    put:
      summary: Promote a Policy
      description: Promote a Policy
      operationId: configmediasecurityv1securitypolicyidpromote
      x-api-path-slug: configmediasecurityv1securitypolicyidpromote-put
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
      - Promote
  /config-media-security/v1/security/{policyID}/promoteDelete:
    delete:
      summary: Remove a Policy
      description: Remove a Policy
      operationId: configmediasecurityv1securitypolicyidpromotedelete
      x-api-path-slug: configmediasecurityv1securitypolicyidpromotedelete-delete
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
      - Promotedelete
  /config-media-security/v1/security/{policyID}/revertDelete:
    put:
      summary: Restore a Policy Deletion
      description: Restore a Policy Deletion
      operationId: configmediasecurityv1securitypolicyidrevertdelete
      x-api-path-slug: configmediasecurityv1securitypolicyidrevertdelete-put
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
      - Revertdelete
  /config-media-security/v1/security/{policyID}/revertEdit:
    put:
      summary: Restore a Policy Edit
      description: Restore a Policy Edit
      operationId: configmediasecurityv1securitypolicyidrevertedit
      x-api-path-slug: configmediasecurityv1securitypolicyidrevertedit-put
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Policy
      - Revertedit
  /config-media-security/v1/security/live/{domain}/policy:
    get:
      summary: Get an HD Config Policy
      description: Get an HD Config Policy
      operationId: configmediasecurityv1securitylivedomainpolicy
      x-api-path-slug: configmediasecurityv1securitylivedomainpolicy-get
      parameters:
      - in: query
        name: domain
        description: The fully qualified domain name for the host in question
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Live
      - Domain
      - Policy
    put:
      summary: Modify an HD Config Policy
      description: Modify an HD Config Policy
      operationId: configmediasecurityv1securitylivedomainpolicy
      x-api-path-slug: configmediasecurityv1securitylivedomainpolicy-put
      parameters:
      - in: query
        name: domain
        description: The fully qualified domain name for the host in question
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Live
      - Domain
      - Policy
  /config-media-security/v1/security/live/{domain}/policy/{environment}:
    get:
      summary: Get an HD Config Policy per Environment
      description: Get an HD Config Policy per Environment
      operationId: configmediasecurityv1securitylivedomainpolicyenvironment
      x-api-path-slug: configmediasecurityv1securitylivedomainpolicyenvironment-get
      parameters:
      - in: query
        name: domain
        description: The fully qualified domain name for the host in question
        type: string
      - in: query
        name: environment
        description: The environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Live
      - Domain
      - Policy
      - Environment
  /config-media-security/v1/security/live/{policyID}/policyassignments:
    get:
      summary: List Policy Assignments
      description: List Policy Assignments
      operationId: configmediasecurityv1securitylivepolicyidpolicyassignments
      x-api-path-slug: configmediasecurityv1securitylivepolicyidpolicyassignments-get
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Live
      - Policy
      - Policyassignments
  /config-media-security/v1/security/live/{policyID}/policyassignments/{environment}:
    get:
      summary: Get a Policy Assignment
      description: Get a Policy Assignment
      operationId: configmediasecurityv1securitylivepolicyidpolicyassignmentsenvironment
      x-api-path-slug: configmediasecurityv1securitylivepolicyidpolicyassignmentsenvironment-get
      parameters:
      - in: query
        name: environment
        description: The environment
        type: string
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Live
      - Policy
      - Policyassignments
      - Environment
  /config-media-security/v1/security/live/{policyID}/policyassignments/promote:
    put:
      summary: Promote a Policy Assignment
      description: Promote a Policy Assignment
      operationId: configmediasecurityv1securitylivepolicyidpolicyassignmentspromote
      x-api-path-slug: configmediasecurityv1securitylivepolicyidpolicyassignmentspromote-put
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Live
      - Policy
      - Policyassignments
      - Promote
  /config-media-security/v1/security/live/{policyID}/policyassignments/revert:
    put:
      summary: Revert a Policy Assignment Promotion
      description: Revert a Policy Assignment Promotion
      operationId: configmediasecurityv1securitylivepolicyidpolicyassignmentsrevert
      x-api-path-slug: configmediasecurityv1securitylivepolicyidpolicyassignmentsrevert-put
      parameters:
      - in: query
        name: policyID
        description: The ID of the policy to fetch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Live
      - Policy
      - Policyassignments
      - Revert
  /config-media-security/v1/security/countries:
    get:
      summary: List Countries
      description: List Countries
      operationId: configmediasecurityv1securitycountries
      x-api-path-slug: configmediasecurityv1securitycountries-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Countries
  /config-media-security/v1/security/dmas:
    get:
      summary: List Designated Market Areas
      description: List Designated Market Areas
      operationId: configmediasecurityv1securitydmas
      x-api-path-slug: configmediasecurityv1securitydmas-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Dmas
  /config-media-security/v1/security/regions:
    get:
      summary: List Regions
      description: List Regions
      operationId: configmediasecurityv1securityregions
      x-api-path-slug: configmediasecurityv1securityregions-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Regions
  /config-media-security/v1/security/regions/{countryCode}:
    get:
      summary: List Regions per Country
      description: List Regions per Country
      operationId: configmediasecurityv1securityregionscountrycode
      x-api-path-slug: configmediasecurityv1securityregionscountrycode-get
      parameters:
      - in: query
        name: countryCode
        description: The country code
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Regions
      - Countrycode
  /config-media-security/v1/security/acgs:
    get:
      summary: List Access Control Groups
      description: List Access Control Groups
      operationId: configmediasecurityv1securityacgs
      x-api-path-slug: configmediasecurityv1securityacgs-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Media
      - Security
      - Security
      - Acgs
  /config-secure-provisioning-service/v1/sps-requests:
    post:
      summary: Create a Request
      description: Create a Request
      operationId: configsecureprovisioningservicev1spsrequestscontractidgroupidafterinformation
      x-api-path-slug: configsecureprovisioningservicev1spsrequests-post
      parameters:
      - in: query
        name: after
        description: If specified for GET requests, returns only the SPS requests
          created after the date entered
        type: string
      - in: query
        name: contractId
        description: For POST requests, the ID of the contract associated with the
          new policy
        type: string
      - in: query
        name: groupId
        description: For POST requests, the ID of the group associated with the new
          policy
        type: string
      - in: query
        name: information
        description: If specified for GET requests, returns parameters posted with
          the SPS request resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Secure
      - Provisioning
      - Service
      - Sps
      - Requests
      - Contract
      - group
      - after
      - information
    get:
      summary: List SPS Requests
      description: List SPS Requests
      operationId: configsecureprovisioningservicev1spsrequestscontractidgroupidafterinformation
      x-api-path-slug: configsecureprovisioningservicev1spsrequests-get
      parameters:
      - in: query
        name: after
        description: If specified for GET requests, returns only the SPS requests
          created after the date entered
        type: string
      - in: query
        name: contractId
        description: For POST requests, the ID of the contract associated with the
          new policy
        type: string
      - in: query
        name: groupId
        description: For POST requests, the ID of the group associated with the new
          policy
        type: string
      - in: query
        name: information
        description: If specified for GET requests, returns parameters posted with
          the SPS request resource
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Secure
      - Provisioning
      - Service
      - Sps
      - Requests
      - Contract
      - group
      - after
      - information
  subscriptionId:
    post:
      summary: Create a Secure Edge Hostname
      description: Create a Secure Edge Hostname
      operationId: subscriptionid
      x-api-path-slug: subscriptionid-post
      parameters:
      - in: query
        name: contractId
        description: The ID of the contract associated with the new policy
        type: string
      - in: query
        name: groupId
        description: The ID of the group associated with the new policy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Subscription
  name:
    get:
      summary: List Report Packs
      description: List Report Packs
      operationId: name
      x-api-path-slug: name-get
      responses:
        200:
          description: OK
      tags:
      - Name
  /security-monitor/v1/report-packs/{reportPackId}:
    get:
      summary: Get a Report Pack
      description: Get a Report Pack
      operationId: securitymonitorv1reportpacksreportpackid
      x-api-path-slug: securitymonitorv1reportpacksreportpackid-get
      parameters:
      - in: query
        name: reportPackId
        description: Report pack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security
      - Monitor
      - Report
      - Packs
      - Reportpack
  /security-monitor/v1/report-packs/{reportPackId}/data-stores:
    get:
      summary: List Data Stores
      description: List Data Stores
      operationId: securitymonitorv1reportpacksreportpackiddatastores
      x-api-path-slug: securitymonitorv1reportpacksreportpackiddatastores-get
      parameters:
      - in: query
        name: reportPackId
        description: Report pack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security
      - Monitor
      - Report
      - Packs
      - Reportpack
      - Data
      - Stores
  /security-monitor/v1/report-packs/{reportPackId}/data-stores/{dataStoreId}:
    get:
      summary: Get a Data Store
      description: Get a Data Store
      operationId: securitymonitorv1reportpacksreportpackiddatastoresdatastoreid
      x-api-path-slug: securitymonitorv1reportpacksreportpackiddatastoresdatastoreid-get
      parameters:
      - in: query
        name: dataStoreId
        description: Data store ID
        type: string
      - in: query
        name: reportPackId
        description: Report pack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security
      - Monitor
      - Report
      - Packs
      - Reportpack
      - Data
      - Stores
      - Datastore
  /security-monitor/v1/report-packs/{reportPackId}/data-sources:
    get:
      summary: List Data Sources
      description: List Data Sources
      operationId: securitymonitorv1reportpacksreportpackiddatasources
      x-api-path-slug: securitymonitorv1reportpacksreportpackiddatasources-get
      parameters:
      - in: query
        name: reportPackId
        description: Report pack ID
        type: string
      responses:
        200:
          description: OK
      tags:
      - Security
      - Monitor
      - Report
      - Packs
      - Reportpack
      - Data
      - Sources
  /sla-api/v1/test-quotas:
    get:
      summary: List Test Configuration Quotas
      description: List Test Configuration Quotas
      operationId: slaapiv1testquotas
      x-api-path-slug: slaapiv1testquotas-get
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Test
      - Quotas
  /sla-api/v1/tests:
    post:
      summary: Create a New Test Configuration
      description: Create a New Test Configuration
      operationId: slaapiv1tests
      x-api-path-slug: slaapiv1tests-post
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
    get:
      summary: List Test Configurations
      description: List Test Configurations
      operationId: slaapiv1testsslatestids
      x-api-path-slug: slaapiv1tests-get
      parameters:
      - in: query
        name: slaTestIds
        description: One or more IDs of SLA tests, comma separated
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
      - Slatests
  /sla-api/v1/tests/{id}:
    delete:
      summary: Delete a Test Configuration
      description: Delete a Test Configuration
      operationId: slaapiv1testsid
      x-api-path-slug: slaapiv1testsid-delete
      parameters:
      - in: query
        name: id
        description: The test&#8217;s unique identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
    put:
      summary: Update a Test Configuration
      description: Update a Test Configuration
      operationId: slaapiv1testsid
      x-api-path-slug: slaapiv1testsid-put
      parameters:
      - in: query
        name: id
        description: The test&#8217;s unique identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
    get:
      summary: Get a Test Configuration
      description: Get a Test Configuration
      operationId: slaapiv1testsid
      x-api-path-slug: slaapiv1testsid-get
      parameters:
      - in: query
        name: id
        description: The test&#8217;s unique identifier
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
  /sla-api/v1/agent-groups:
    get:
      summary: List Agent Groups
      description: List Agent Groups
      operationId: slaapiv1agentgroups
      x-api-path-slug: slaapiv1agentgroups-get
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Agent
      - Groups
  /sla-api/v1/tests/{slaTestId}/reports/performance:
    get:
      summary: List Performance Reports
      description: List Performance Reports
      operationId: slaapiv1testsslatestidreportsperformancestartend
      x-api-path-slug: slaapiv1testsslatestidreportsperformance-get
      parameters:
      - in: query
        name: end
        description: Timestamp for the end of the data window, in UTC 8601 format
        type: string
      - in: query
        name: slaTestId
        description: Unique identifier for the test you wish to run a report on
        type: string
      - in: query
        name: start
        description: Timestamp for the start of the data window, in UTC 8601 format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
      - Slatest
      - Reports
      - Performance
      - Start
      - end
  /sla-api/v1/tests/{slaTestId}/reports/availability:
    get:
      summary: List Availability Reports
      description: List Availability Reports
      operationId: slaapiv1testsslatestidreportsavailabilitystartend
      x-api-path-slug: slaapiv1testsslatestidreportsavailability-get
      parameters:
      - in: query
        name: end
        description: Timestamp for the end of data window, in UTC 8601 format
        type: string
      - in: query
        name: slaTestId
        description: Unique identifier for the test you wish to run a report on
        type: string
      - in: query
        name: start
        description: Timestamp for the start of the data window, in UTC 8601 format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Sla
      - Tests
      - Slatest
      - Reports
      - Availability
      - Start
      - end
  /siteshield/v1/maps:
    get:
      summary: List Maps
      description: List Maps
      operationId: siteshieldv1maps
      x-api-path-slug: siteshieldv1maps-get
      responses:
        200:
          description: OK
      tags:
      - Siteshield
      - Maps
  /siteshield/v1/maps/{id}:
    get:
      summary: Get a Map
      description: Get a Map
      operationId: siteshieldv1mapsid
      x-api-path-slug: siteshieldv1mapsid-get
      parameters:
      - in: query
        name: id
        description: Numeric id of the Note to perform action with
        type: string
      responses:
        200:
          description: OK
      tags:
      - Siteshield
      - Maps
  /siteshield/v1/maps/{id}/acknowledge:
    post:
      summary: Acknowledge a Map
      description: Acknowledge a Map
      operationId: siteshieldv1mapsidacknowledge
      x-api-path-slug: siteshieldv1mapsidacknowledge-post
      parameters:
      - in: query
        name: id
        description: Numeric id of the Note to perform action with
        type: string
      responses:
        200:
          description: OK
      tags:
      - Siteshield
      - Maps
      - ""
      - Acknowledge
  /config-gtm/v1/domains/:
    get:
      summary: List Domains
      description: List Domains
      operationId: configgtmv1domains
      x-api-path-slug: configgtmv1domains-get
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
  /config-gtm/v1/domains/{domain}:
    get:
      summary: Get a Domain
      description: Get a Domain
      operationId: configgtmv1domainsdomain
      x-api-path-slug: configgtmv1domainsdomain-get
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
    put:
      summary: Create or Update a Domain
      description: Create or Update a Domain
      operationId: configgtmv1domainsdomain
      x-api-path-slug: configgtmv1domainsdomain-put
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
  /config-gtm/v1/domains/{domain}/datacenters:
    get:
      summary: List Data Centers
      description: List Data Centers
      operationId: configgtmv1domainsdomaindatacenters
      x-api-path-slug: configgtmv1domainsdomaindatacenters-get
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Datacenters
    post:
      summary: Create a Data Center
      description: Create a Data Center
      operationId: configgtmv1domainsdomaindatacenters
      x-api-path-slug: configgtmv1domainsdomaindatacenters-post
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Datacenters
  /config-gtm/v1/domains/{domain}/datacenters/{datacenterId}:
    get:
      summary: Get a Data Center
      description: Get a Data Center
      operationId: configgtmv1domainsdomaindatacentersdatacenterid
      x-api-path-slug: configgtmv1domainsdomaindatacentersdatacenterid-get
      parameters:
      - in: query
        name: datacenterId
        description: Numeric id of the data center
        type: string
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Datacenters
      - Datacenter
    put:
      summary: Update a Data Center
      description: Update a Data Center
      operationId: configgtmv1domainsdomaindatacentersdatacenterid
      x-api-path-slug: configgtmv1domainsdomaindatacentersdatacenterid-put
      parameters:
      - in: query
        name: datacenterId
        description: Numeric id of the data center
        type: string
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Datacenters
      - Datacenter
    delete:
      summary: Remove a Data Center
      description: Remove a Data Center
      operationId: configgtmv1domainsdomaindatacentersdatacenterid
      x-api-path-slug: configgtmv1domainsdomaindatacentersdatacenterid-delete
      parameters:
      - in: query
        name: datacenterId
        description: Numeric id of the data center
        type: string
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Datacenters
      - Datacenter
  /config-gtm/v1/domains/{domain}/properties:
    get:
      summary: List Properties
      description: List Properties
      operationId: configgtmv1domainsdomainproperties
      x-api-path-slug: configgtmv1domainsdomainproperties-get
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Properties
  /config-gtm/v1/domains/{domain}/properties/{propertyName}:
    get:
      summary: Get a Property
      description: Get a Property
      operationId: configgtmv1domainsdomainpropertiespropertyname
      x-api-path-slug: configgtmv1domainsdomainpropertiespropertyname-get
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      - in: query
        name: propertyName
        description: Name of property to create or update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Properties
      - Propertyname
    put:
      summary: Create or Update a Property
      description: Create or Update a Property
      operationId: configgtmv1domainsdomainpropertiespropertyname
      x-api-path-slug: configgtmv1domainsdomainpropertiespropertyname-put
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      - in: query
        name: propertyName
        description: Name of property to create or update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Properties
      - Propertyname
    delete:
      summary: Remove a Property
      description: Remove a Property
      operationId: configgtmv1domainsdomainpropertiespropertyname
      x-api-path-slug: configgtmv1domainsdomainpropertiespropertyname-delete
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      - in: query
        name: propertyName
        description: Name of property to create or update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Properties
      - Propertyname
  /config-gtm/v1/domains/{domain}/resources:
    get:
      summary: List Resources
      description: List Resources
      operationId: configgtmv1domainsdomainresources
      x-api-path-slug: configgtmv1domainsdomainresources-get
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Resources
  /config-gtm/v1/domains/{domain}/resources/{resourceName}:
    get:
      summary: Get a Resource
      description: Get a Resource
      operationId: configgtmv1domainsdomainresourcesresourcename
      x-api-path-slug: configgtmv1domainsdomainresourcesresourcename-get
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      - in: query
        name: resourceName
        description: Name of Resource to create or update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Resources
      - Resourcename
    put:
      summary: Create or Update a Resource
      description: Create or Update a Resource
      operationId: configgtmv1domainsdomainresourcesresourcename
      x-api-path-slug: configgtmv1domainsdomainresourcesresourcename-put
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      - in: query
        name: resourceName
        description: Name of Resource to create or update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Resources
      - Resourcename
    delete:
      summary: Remove a Resource
      description: Remove a Resource
      operationId: configgtmv1domainsdomainresourcesresourcename
      x-api-path-slug: configgtmv1domainsdomainresourcesresourcename-delete
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      - in: query
        name: resourceName
        description: Name of Resource to create or update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Resources
      - Resourcename
  /config-gtm/v1/domains/{domain}/geographic-maps:
    get:
      summary: List Geographic Maps
      description: List Geographic Maps
      operationId: configgtmv1domainsdomaingeographicmaps
      x-api-path-slug: configgtmv1domainsdomaingeographicmaps-get
      parameters:
      - in: query
        name: domain
        description: Name of Traffic Management domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configurations
      - Gtm
      - Domains
      - Geographic
      - Maps
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