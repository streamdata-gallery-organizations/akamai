---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 0
info:
  title: Akamai API Submit a Change
  description: Submit a Change
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