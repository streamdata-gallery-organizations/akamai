---
name: Akamai
x-slug: akamai
description: Akamai Technologies, Inc. is a content delivery network or CDN and cloud
  services provider headquartered in Cambridge, Massachusetts, in the United States.
  Akamais content delivery network is one of the worlds largest distributed computing
  platforms, responsible for serving between 15 and 30 percent of all web traffic.
  The company operates a network of servers around the world and rents capacity on
  these servers to customers who want their websites to work faster by distributing
  content from locations close to the user
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Akamai
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/apis.md
specificationVersion: "0.14"
apis:
- name: Akamai API List Customers
  x-api-slug: akamai-api
  description: List Customers
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers
  tags: Galaxy, Customers, Includedeleted,debug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customers-get-openapi.md
- name: Akamai API Add a Customer
  x-api-slug: akamai-api
  description: Add a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers
  tags: Galaxy, Customers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customers-post-openapi.md
- name: Akamai API Modify a Customer
  x-api-slug: akamai-api
  description: Modify a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers/{akamaiCustomerId}
  tags: Galaxy, Customers, Akamaicustomer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customersakamaicustomerid-put-openapi.md
- name: Akamai API Remove a Customer
  x-api-slug: akamai-api
  description: Remove a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers/{akamaiCustomerId}
  tags: Galaxy, Customers, Akamaicustomer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customersakamaicustomerid-delete-openapi.md
- name: Akamai API Deactivate a Customer
  x-api-slug: akamai-api
  description: Deactivate a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers/{akamaiCustomerId}/op/deactivate
  tags: Galaxy, Customers, Akamaicustomer, Op, Deactivate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customersakamaicustomeridopdeactivate-post-openapi.md
- name: Akamai API Reactivate a Customer
  x-api-slug: akamai-api
  description: Reactivate a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers/{akamaiCustomerId}/op/reactivate
  tags: Galaxy, Customers, Akamaicustomer, Op, Reactivate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customersakamaicustomeridopreactivate-post-openapi.md
- name: Akamai API List Clients
  x-api-slug: akamai-api
  description: List Clients
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/clients
  tags: Galaxy, Clients, Includedeleted,debug,self
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1clients-get-openapi.md
- name: Akamai API Add a Client
  x-api-slug: akamai-api
  description: Add a Client
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/clients
  tags: Galaxy, Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1clients-post-openapi.md
- name: Akamai API Modify a Client
  x-api-slug: akamai-api
  description: Modify a Client
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/clients/{clientId}
  tags: Galaxy, Clients, Client
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1clientsclientid-put-openapi.md
- name: Akamai API Remove a Client
  x-api-slug: akamai-api
  description: Remove a Client
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/clients/{clientId}
  tags: Galaxy, Clients, Client
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1clientsclientid-delete-openapi.md
- name: Akamai API Deactivate a Client
  x-api-slug: akamai-api
  description: Deactivate a Client
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers/{clientId}/op/deactivate
  tags: Galaxy, Customers, Client, Op, Deactivate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customersclientidopdeactivate-post-openapi.md
- name: Akamai API Reactivate a Client
  x-api-slug: akamai-api
  description: Reactivate a Client
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/customers/{clientId}/op/reactivate
  tags: Galaxy, Customers, Client, Op, Reactivate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1customersclientidopreactivate-post-openapi.md
- name: Akamai API Get Client Groups
  x-api-slug: akamai-api
  description: Get Client Groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/client_groups
  tags: Galaxy, Client, Groups, Includedeleted,debug,self
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1client-groups-get-openapi.md
- name: Akamai API Associate Multiple Activation Files for a DPC
  x-api-slug: akamai-api
  description: Associate Multiple Activation Files for a DPC
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/client_groups
  tags: Galaxy, Client, Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1client-groups-post-openapi.md
- name: Akamai API Get a Device
  x-api-slug: akamai-api
  description: Get a Device
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/devices/{deviceId}
  tags: Galaxy, Devices, Device, Debug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1devicesdeviceid-get-openapi.md
- name: Akamai API Modify a Device
  x-api-slug: akamai-api
  description: Modify a Device
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/devices/{deviceId}
  tags: Galaxy, Devices, Device
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1devicesdeviceid-put-openapi.md
- name: Akamai API Add a Device
  x-api-slug: akamai-api
  description: Add a Device
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/devices/{deviceId}
  tags: Galaxy, Devices, Device
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1devicesdeviceid-post-openapi.md
- name: Akamai API Remove a Device
  x-api-slug: akamai-api
  description: Remove a Device
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/devices/{deviceId}
  tags: Galaxy, Devices, Device
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1devicesdeviceid-delete-openapi.md
- name: Akamai API Deactivate a Device
  x-api-slug: akamai-api
  description: Deactivate a Device
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/devices/{deviceId}/op/deactivate
  tags: Galaxy, Devices, Device, Op, Deactivate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1devicesdeviceidopdeactivate-post-openapi.md
- name: Akamai API Reactivate a Device
  x-api-slug: akamai-api
  description: Reactivate a Device
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/devices/{deviceId}/op/reactivate
  tags: Galaxy, Devices, Device, Op, Reactivate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1devicesdeviceidopreactivate-post-openapi.md
- name: Akamai API Get Build Information
  x-api-slug: akamai-api
  description: Get Build Information
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////galaxy/v1/build
  tags: Galaxy, Build
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1build-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/galaxyv1build-get-openapi.md
- name: Akamai API List Statistics per Contract
  x-api-slug: akamai-api
  description: List Statistics per Contract
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/contracts/{contractId}/products/{productId}/statistics
  tags: Billing, Center, Contracts, Contract, Products, Product, Statistics, Year,month,fromyear,frommonth,toyear,tomonth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/billingcenterapiv2contractscontractidproductsproductidstatistics-get-openapi.md
- name: Akamai API List Usage per Contract
  x-api-slug: akamai-api
  description: List Usage per Contract
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/contracts/{contractId}/products/{productId}/measures
  tags: Billing, Center, Contracts, Contract, Products, Product, Measures, Year,month,fromyear,frommonth,toyear,tomonth,statisticname,billingdayonly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/billingcenterapiv2contractscontractidproductsproductidmeasures-get-openapi.md
- name: Akamai API List Statistics per Reporting Group
  x-api-slug: akamai-api
  description: List Statistics per Reporting Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/reporting-groups/{reportingGroupId}/products/{productId}/statistics
  tags: Billing, Center, Reporting, Groups, Reportinggroup, Products, Product, Statistics,
    Year,month,fromyear,frommonth,toyear,tomonth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/billingcenterapiv2reportinggroupsreportinggroupidproductsproductidstatistics-get-openapi.md
- name: Akamai API List Usage per Reporting Group
  x-api-slug: akamai-api
  description: List Usage per Reporting Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////billing-center-api/v2/reporting-groups/{reportingGroupId}/products/{productId}/measures
  tags: Billing, Center, Reporting, Groups, Reportinggroup, Products, Product, Measures,
    Year,month,fromyear,frommonth,toyear,tomonth,statisticname,billingdayonly
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/billingcenterapiv2reportinggroupsreportinggroupidproductsproductidmeasures-get-openapi.md
- name: Akamai API List Cases per Category
  x-api-slug: akamai-api
  description: List Cases per Category
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/{category}
  tags: Cases, Category
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1category-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1category-get-openapi.md
- name: Akamai API Create a Case
  x-api-slug: akamai-api
  description: Create a Case
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/{category}
  tags: Cases, Category
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1category-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1category-post-openapi.md
- name: Akamai API List Professional Services Cases
  x-api-slug: akamai-api
  description: List Professional Services Cases
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/PS
  tags: Cases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1ps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1ps-get-openapi.md
- name: Akamai API Create a Professional Services Case
  x-api-slug: akamai-api
  description: Create a Professional Services Case
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/PS
  tags: Cases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1ps-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1ps-post-openapi.md
- name: Akamai API List Cases
  x-api-slug: akamai-api
  description: List Cases
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/portal-user
  tags: Cases, Portal, User, Status,type,category
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portaluser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portaluser-get-openapi.md
- name: Akamai API Get a Case
  x-api-slug: akamai-api
  description: Get a Case
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/portal-user/case/{caseId}
  tags: 'Cases, Portal, User, Cases, '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portalusercasecaseid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portalusercasecaseid-get-openapi.md
- name: Akamai API Comment on a Case
  x-api-slug: akamai-api
  description: Comment on a Case
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/portal-user/case/{caseId}/notes
  tags: Cases, Portal, User, Cases, Notes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portalusercasecaseidnotes-post-openapi.md
- name: Akamai API Upload a File Attachment
  x-api-slug: akamai-api
  description: Upload a File Attachment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/portal-user/case/{caseId}/files
  tags: Cases, Portal, User, Cases, Files
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portalusercasecaseidfiles-post-openapi.md
- name: Akamai API Close a Request
  x-api-slug: akamai-api
  description: Close a Request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cases/v1/portal-user/case/{caseId}/request-close
  tags: Cases, Portal, User, Cases, Request, Close
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portalusercasecaseidrequestclose-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/casesv1portalusercasecaseidrequestclose-put-openapi.md
- name: Akamai API Invalidate by URL
  x-api-slug: akamai-api
  description: Invalidate by URL
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////ccu/v3/invalidate/url/{network}
  tags: Ccu, Invalate, Url, Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ccuv3invalidateurlnetwork-post-openapi.md
- name: Akamai API Delete by URL
  x-api-slug: akamai-api
  description: Delete by URL
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////ccu/v3/delete/url/{network}
  tags: Ccu, Delete, Url, Network
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ccuv3deleteurlnetwork-post-openapi.md
- name: Akamai API Get Current Queue Size
  x-api-slug: akamai-api
  description: Get Current Queue Size
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////ccu/v2/queues/{queueName}
  tags: Ccu, Queues, Queues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ccuv2queuesqueuename-get-openapi.md
- name: Akamai API Add a Request
  x-api-slug: akamai-api
  description: Add a Request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////ccu/v2/queues/{queueName}
  tags: Ccu, Queues, Queues
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ccuv2queuesqueuename-post-openapi.md
- name: Akamai API Get Purge Status
  x-api-slug: akamai-api
  description: Get Purge Status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////ccu/v2/purges/{purgeId}
  tags: Ccu, Purges
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ccuv2purgespurgeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ccuv2purgespurgeid-get-openapi.md
- name: Akamai API List Cloudlets
  x-api-slug: akamai-api
  description: List Cloudlets
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///cloudletId
  tags: Cloudlet
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletid-get-openapi.md
- name: Akamai API List Groups
  x-api-slug: akamai-api
  description: List Groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/group-info
  tags: Cloudlets, Group, Information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2groupinfo-get-openapi.md
- name: Akamai API Get a Group
  x-api-slug: akamai-api
  description: Get a Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/group-info/{groupId}
  tags: Cloudlets, Group, Information, Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2groupinfogroupid-get-openapi.md
- name: Akamai API List Policies
  x-api-slug: akamai-api
  description: List Policies
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies
  tags: Cloudlets, Policies, G,includedeleted,cloudlet
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policies-get-openapi.md
- name: Akamai API Create a Policy
  x-api-slug: akamai-api
  description: Create a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies
  tags: Cloudlets, Policies, Clonepolicy,version
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policies-post-openapi.md
- name: Akamai API Get a Policy
  x-api-slug: akamai-api
  description: Get a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}
  tags: Cloudlets, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyid-get-openapi.md
- name: Akamai API Update a Policy
  x-api-slug: akamai-api
  description: Update a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}
  tags: Cloudlets, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyid-put-openapi.md
- name: Akamai API Remove a Policy
  x-api-slug: akamai-api
  description: Remove a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}
  tags: Cloudlets, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyid-delete-openapi.md
- name: Akamai API List Policy Versions
  x-api-slug: akamai-api
  description: List Policy Versions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions
  tags: Cloudlets, Policies, Versions, Includerules, Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversions-get-openapi.md
- name: Akamai API Create a New Policy Version
  x-api-slug: akamai-api
  description: Create a New Policy Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions
  tags: Cloudlets, Policies, Versions, Matchruleformat,cloneversion
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversions-post-openapi.md
- name: Akamai API Get a Policy Version
  x-api-slug: akamai-api
  description: Get a Policy Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}
  tags: Cloudlets, Policies, Versions, Omitrules, Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversion-get-openapi.md
- name: Akamai API Update a Policy Version
  x-api-slug: akamai-api
  description: Update a Policy Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}
  tags: Cloudlets, Policies, Versions, Matchruleformat
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversion-put-openapi.md
- name: Akamai API Remove a Policy Version
  x-api-slug: akamai-api
  description: Remove a Policy Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}
  tags: Cloudlets, Policies, Versions, Omitrules, Rules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversion-delete-openapi.md
- name: Akamai API Add a Version Rule
  x-api-slug: akamai-api
  description: Add a Version Rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}/rules
  tags: Cloudlets, Policies, Versions, Rules, Index
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversionrules-post-openapi.md
- name: Akamai API Get a Version Rule
  x-api-slug: akamai-api
  description: Get a Version Rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}/rules/{akaRuleId}
  tags: Cloudlets, Policies, Versions, Rules, Akarule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversionrulesakaruleid-get-openapi.md
- name: Akamai API Update a Version Rule
  x-api-slug: akamai-api
  description: Update a Version Rule
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}/rules/{akaRuleId}
  tags: Cloudlets, Policies, Versions, Rules, Akarule
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversionrulesakaruleid-put-openapi.md
- name: Akamai API List Associated Properties
  x-api-slug: akamai-api
  description: List Associated Properties
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/properties
  tags: Cloudlets, Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2properties-get-openapi.md
- name: Akamai API Get Associated Properties for a Policy
  x-api-slug: akamai-api
  description: Get Associated Properties for a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/{policyId}/properties
  tags: Cloudlets, Policy, Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policyidproperties-get-openapi.md
- name: Akamai API List Cloudlets Origins
  x-api-slug: akamai-api
  description: List Cloudlets Origins
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins
  tags: Cloudlets, Origins, Type
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2origins-get-openapi.md
- name: Akamai API Get a Cloudlets Origin
  x-api-slug: akamai-api
  description: Get a Cloudlets Origin
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}
  tags: Cloudlets, Origins
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginid-get-openapi.md
- name: Akamai API Update a Cloudlets Origin
  x-api-slug: akamai-api
  description: Update a Cloudlets Origin
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}
  tags: Cloudlets, Origins
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginid-put-openapi.md
- name: Akamai API List Cloudlets Origin Versions
  x-api-slug: akamai-api
  description: List Cloudlets Origin Versions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/versions
  tags: Cloudlets, Origins, Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginidversions-get-openapi.md
- name: Akamai API Create a Cloudlets Origin Version
  x-api-slug: akamai-api
  description: Create a Cloudlets Origin Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/versions
  tags: Cloudlets, Origins, Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginidversions-post-openapi.md
- name: Akamai API Get a Cloudlets Origin Version
  x-api-slug: akamai-api
  description: Get a Cloudlets Origin Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/versions/{version}
  tags: Cloudlets, Origins, Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginidversionsversion-get-openapi.md
- name: Akamai API Update a Cloudlets Origin Version
  x-api-slug: akamai-api
  description: Update a Cloudlets Origin Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/versions/{version}
  tags: Cloudlets, Origins, Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginidversionsversion-put-openapi.md
- name: Akamai API List Current Cloudlets Origin Activations
  x-api-slug: akamai-api
  description: List Current Cloudlets Origin Activations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/currentActivations
  tags: Cloudlets, Origins, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originscurrentactivations-get-openapi.md
- name: Akamai API List Activations for a Cloudlets Origin
  x-api-slug: akamai-api
  description: List Activations for a Cloudlets Origin
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/activations
  tags: Cloudlets, Origins, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginidactivations-get-openapi.md
- name: Akamai API Activate a Cloudlets Origin Version
  x-api-slug: akamai-api
  description: Activate a Cloudlets Origin Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/origins/{originId}/activations
  tags: Cloudlets, Origins, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2originsoriginidactivations-post-openapi.md
- name: Akamai API List Policy Activations
  x-api-slug: akamai-api
  description: List Policy Activations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/activations
  tags: Cloudlets, Policies, Activations, Network,propertyname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidactivations-get-openapi.md
- name: Akamai API Activate a Policy Version
  x-api-slug: akamai-api
  description: Activate a Policy Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/policies/{policyId}/versions/{version}/activations
  tags: Cloudlets, Policies, Versions, Activations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2policiespolicyidversionsversionactivations-post-openapi.md
- name: Akamai API Get a Schema
  x-api-slug: akamai-api
  description: Get a Schema
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cloudlets/api/v2/schemas/{schemaName}
  tags: Cloudlets, Schemas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletsapiv2schemasschemaname-get-openapi.md
- name: Akamai API List Schemas per Cloudlet
  x-api-slug: akamai-api
  description: List Schemas per Cloudlet
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///cloudletCode
  tags: Cloudletcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cloudletcode-get-openapi.md
- name: Akamai API Create an Enrollment
  x-api-slug: akamai-api
  description: Create an Enrollment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments
  tags: Cps, Enrollments, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollments-post-openapi.md
- name: Akamai API List Enrollments
  x-api-slug: akamai-api
  description: List Enrollments
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments
  tags: Cps, Enrollments, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollments-get-openapi.md
- name: Akamai API Get an Enrollment
  x-api-slug: akamai-api
  description: Get an Enrollment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments/{enrollmentId}
  tags: Cps, Enrollments, Enrollment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollmentsenrollmentid-get-openapi.md
- name: Akamai API Update an Enrollment
  x-api-slug: akamai-api
  description: Update an Enrollment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments/{enrollmentId}
  tags: Cps, Enrollments, Enrollment, Deploy, Not, Before,deploy, Not, After,allow,
    Cancel, Pending, Changes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollmentsenrollmentid-put-openapi.md
- name: Akamai API Delete an Enrollment
  x-api-slug: akamai-api
  description: Delete an Enrollment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments/{enrollmentId}
  tags: Cps, Enrollments, Enrollment, Deploy, Not, Before,deploy, Not, After,allow,
    Cancel, Pending, Changes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollmentsenrollmentid-delete-openapi.md
- name: Akamai API Get Change Status
  x-api-slug: akamai-api
  description: Get Change Status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments/{enrollmentId}/changes/{changeId}
  tags: Cps, Enrollments, Enrollment, Changes, Change
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollmentsenrollmentidchangeschangeid-get-openapi.md
- name: Akamai API Cancel a Change
  x-api-slug: akamai-api
  description: Cancel a Change
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments/{enrollmentId}/changes/{changeId}
  tags: Cps, Enrollments, Enrollment, Changes, Change
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollmentsenrollmentidchangeschangeid-delete-openapi.md
- name: Akamai API Confirm a Change
  x-api-slug: akamai-api
  description: Confirm a Change
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///info
  tags: Information
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/info-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/info-get-openapi.md
- name: Akamai API Submit a Change
  x-api-slug: akamai-api
  description: Submit a Change
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///update
  tags: Update
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/update-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/update-post-openapi.md
- name: Akamai API Get a Certificate
  x-api-slug: akamai-api
  description: Get a Certificate
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/enrollments/{enrollmentId}/deployments/production
  tags: Cps, Enrollments, Enrollment, Deployments, Production
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2enrollmentsenrollmentiddeploymentsproduction-get-openapi.md
- name: Akamai API Get Sample 500 Response
  x-api-slug: akamai-api
  description: Get Sample 500 Response
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/sample&#8211;500
  tags: Samples
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2sample8211500-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2sample8211500-get-openapi.md
- name: Akamai API Get Sample 404 Response
  x-api-slug: akamai-api
  description: Get Sample 404 Response
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////cps/v2/sample&#8211;404
  tags: Samples
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2sample8211404-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cpsv2sample8211404-get-openapi.md
- name: Akamai API List Locations
  x-api-slug: akamai-api
  description: List Locations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////diagnostic-tools/v1/locations
  tags: Diagnostic, Tools, Locations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1locations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1locations-get-openapi.md
- name: Akamai API Run dig
  x-api-slug: akamai-api
  description: Run dig
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////diagnostic-tools/v1/dig
  tags: Diagnostic, Tools, Dig, Hostname,querytype,location,sourceip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1dig-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1dig-get-openapi.md
- name: Akamai API Run mtr
  x-api-slug: akamai-api
  description: Run mtr
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////diagnostic-tools/v1/mtr
  tags: Diagnostic, Tools, Mtr, Destinationdomain,location,sourceip
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1mtr-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1mtr-get-openapi.md
- name: Akamai API Translate Hostname
  x-api-slug: akamai-api
  description: Translate Hostname
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////diagnostic-tools/v1/akamaitranslator
  tags: Diagnostic, Tools, Akamaitranslator, Hostname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1akamaitranslator-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1akamaitranslator-get-openapi.md
- name: Akamai API Translate Error Code
  x-api-slug: akamai-api
  description: Translate Error Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////diagnostic-tools/v1/errortranslator
  tags: Diagnostic, Tools, Errortranslator, Errorcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1errortranslator-get-openapi.md
- name: Akamai API Get IP Geolocation Data
  x-api-slug: akamai-api
  description: Get IP Geolocation Data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////diagnostic-tools/v1/ipgeolocator
  tags: Diagnostic, Tools, Ipgeolocator, Ip
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1ipgeolocator-get-openapi.md
- name: Akamai API Is This a CDN IP
  x-api-slug: akamai-api
  description: Is This a CDN IP
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////diagnostic-tools/v1/verifycdnip
  tags: Diagnostic, Tools, Verifycdnip,IP Addresses, CDN
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/diagnostictoolsv1verifycdnip-get-openapi.md
- name: Akamai API Get a Zone
  x-api-slug: akamai-api
  description: Get a Zone
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///token
  tags: Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/token-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/token-get-openapi.md
- name: Akamai API Add or Modify a Zone
  x-api-slug: akamai-api
  description: Add or Modify a Zone
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///token
  tags: Token
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/token-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/token-post-openapi.md
- name: Akamai API Get Traffic Report
  x-api-slug: akamai-api
  description: Get Traffic Report
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////data-dns/v1/traffic/{zone}
  tags: Data, DNS, Traffic, Zone, Start,start, Time,end,end, Time,end, Time, Zone,
    Estimates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/datadnsv1trafficzone-get-openapi.md
- name: Akamai API Report Security Event Aggregation
  x-api-slug: akamai-api
  description: Report Security Event Aggregation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////etp-report/v1/configs/{configId}/threat-events/aggregate
  tags: Etp, Report, Configurationss, Configurations, Threat, Events, Aggregation,
    Starttimesec,endtimesec,dimension,filters, Aggregation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/etpreportv1configsconfigidthreateventsaggregate-get-openapi.md
- name: Akamai API Report Security Event Details
  x-api-slug: akamai-api
  description: Report Security Event Details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////etp-report/v1/configs/{configId}/threat-events/details
  tags: Etp, Report, Configurationss, Configurations, Threat, Events, Details, Starttimesec,endtimesec,dimension,filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/etpreportv1configsconfigidthreateventsdetails-get-openapi.md
- name: Akamai API Report Security Event Time Series
  x-api-slug: akamai-api
  description: Report Security Event Time Series
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////etp-report/v1/configs/{configId}/threat-events/time-series
  tags: Etp, Report, Configurationss, Configurations, Threat, Events, Time, Series,
    Starttimesec,endtimesec,dimension,filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/etpreportv1configsconfigidthreateventstimeseries-get-openapi.md
- name: Akamai API Report AUP Event Details
  x-api-slug: akamai-api
  description: Report AUP Event Details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////etp-report/v1/configs/{configId}/aup-events/details
  tags: Etp, Report, Configurationss, Configurations, Aup, Events, Details, Starttimesec,endtimesec,dimension,filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/etpreportv1configsconfigidaupeventsdetails-get-openapi.md
- name: Akamai API Report AUP Event Time Series
  x-api-slug: akamai-api
  description: Report AUP Event Time Series
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////etp-report/v1/configs/{configId}/aup-events/time-series
  tags: Etp, Report, Configurationss, Configurations, Aup, Events, Time, Series, Starttimesec,endtimesec,dimension,filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/etpreportv1configsconfigidaupeventstimeseries-get-openapi.md
- name: Akamai API Report DNS Activity Time Series
  x-api-slug: akamai-api
  description: Report DNS Activity Time Series
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////etp-report/v1/configs/{configId}/dns-activities/time-series
  tags: Etp, Report, Configurationss, Configurations, DNS, Activities, Time, Series,
    Starttimesec,endtimesec,dimension,filters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/etpreportv1configsconfigiddnsactivitiestimeseries-get-openapi.md
- name: Akamai API Report DNS Activities Totals
  x-api-slug: akamai-api
  description: Report DNS Activities Totals
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////etp-report/v1/configs/{configId}/dns-activities/aggregate
  tags: Etp, Report, Configurationss, Configurations, DNS, Activities, Aggregation,
    Starttimesec,endtimesec,dimension,filters, Aggregation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/etpreportv1configsconfigiddnsactivitiesaggregate-get-openapi.md
- name: Akamai API List Events
  x-api-slug: akamai-api
  description: List Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events
  tags: Events, Account, Events, Startrange,endrange,sortfield,sortorder,startindex,limit,customerevent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidevents-get-openapi.md
- name: Akamai API POST a New Event
  x-api-slug: akamai-api
  description: POST a New Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events
  tags: Events, Account, Events, Startrange,endrange,sortfield,sortorder,startindex,limit,customerevent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidevents-post-openapi.md
- name: Akamai API PUT a New Event
  x-api-slug: akamai-api
  description: PUT a New Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events
  tags: Events, Account, Events, Startrange,endrange,sortfield,sortorder,startindex,limit,customerevent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidevents-put-openapi.md
- name: Akamai API Remove Events
  x-api-slug: akamai-api
  description: Remove Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events
  tags: Events, Account, Events, Startrange,endrange,sortfield,sortorder,startindex,limit,customerevent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidevents-delete-openapi.md
- name: Akamai API Create a Recurring Event
  x-api-slug: akamai-api
  description: Create a Recurring Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/recurring
  tags: Events, Account, Events, Recurring, Frequency,numberoftimes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventsrecurring-post-openapi.md
- name: Akamai API Get an Event
  x-api-slug: akamai-api
  description: Get an Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}
  tags: Events, Account, Events, Event
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventid-get-openapi.md
- name: Akamai API Modify an Event, with POST
  x-api-slug: akamai-api
  description: Modify an Event, with POST
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}
  tags: Events, Account, Events, Event
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventid-post-openapi.md
- name: Akamai API Modify an Event, with PUT
  x-api-slug: akamai-api
  description: Modify an Event, with PUT
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}
  tags: Events, Account, Events, Event
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventid-put-openapi.md
- name: Akamai API Remove an Event
  x-api-slug: akamai-api
  description: Remove an Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}
  tags: Events, Account, Events, Event
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventid-delete-openapi.md
- name: Akamai API Get Event with its Services
  x-api-slug: akamai-api
  description: Get Event with its Services
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}
  tags: Events, Account, Events, Event, Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventid-get-openapi.md
- name: Akamai API List Services
  x-api-slug: akamai-api
  description: List Services
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/services
  tags: Events, Account, Events, Event, Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidservices-get-openapi.md
- name: Akamai API List Range of Events
  x-api-slug: akamai-api
  description: List Range of Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/id
  tags: Events, Account, Events, , Startrange,endrange,sortfield,sortorder,startindex,limit,customerevent
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventsid-get-openapi.md
- name: Akamai API List Events in Progress
  x-api-slug: akamai-api
  description: List Events in Progress
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/live
  tags: Events, Account, Events, Live
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventslive-get-openapi.md
- name: Akamai API List Events Current for Specific Time
  x-api-slug: akamai-api
  description: List Events Current for Specific Time
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/live/{time}
  tags: Events, Account, Events, Live, Time
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventslivetime-get-openapi.md
- name: Akamai API List Upcoming Events
  x-api-slug: akamai-api
  description: List Upcoming Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/upcoming
  tags: Events, Account, Events, Upcoming
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventsupcoming-get-openapi.md
- name: Akamai API List Impending Events
  x-api-slug: akamai-api
  description: List Impending Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/upcoming/{rangeInHours}
  tags: Events, Account, Events, Upcoming, Rangeinhours
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventsupcomingrangeinhours-get-openapi.md
- name: Akamai API List Alerts
  x-api-slug: akamai-api
  description: List Alerts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/alerts
  tags: Events, Account, Events, Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventsalerts-get-openapi.md
- name: Akamai API List Alerts per Event
  x-api-slug: akamai-api
  description: List Alerts per Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/alerts
  tags: Events, Account, Events, Event, Alerts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidalerts-get-openapi.md
- name: Akamai API Get Event Traffic Data by CP Code
  x-api-slug: akamai-api
  description: Get Event Traffic Data by CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///data
  tags: Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/data-get-openapi.md
- name: Akamai API Get Edge Bandwidth per CP Code
  x-api-slug: akamai-api
  description: Get Edge Bandwidth per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/bandwidth/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Edge, Bandwth, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeedgebandwidthcpcode-get-openapi.md
- name: Akamai API Get Event&#8217;s Edge Requests, per CP Code
  x-api-slug: akamai-api
  description: Get Event&#8217;s Edge Requests, per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/requests/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Edge, Requests, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeedgerequestscpcode-get-openapi.md
- name: Akamai API Get Event&#8217;s Status Totals
  x-api-slug: akamai-api
  description: Get Event&#8217;s Status Totals
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/status
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Edge, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeedgestatus-get-openapi.md
- name: Akamai API Get Event&#8217;s Status Totals per CP Code
  x-api-slug: akamai-api
  description: Get Event&#8217;s Status Totals per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/edge/status/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Edge, Status, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeedgestatuscpcode-get-openapi.md
- name: Akamai API Get Event&#8217;s Bandwidth Data
  x-api-slug: akamai-api
  description: Get Event&#8217;s Bandwidth Data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/bandwidth
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Origin, Bandwth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidth-get-openapi.md
- name: Akamai API Get Event&#8217;s Bandwidth Data per CP Code
  x-api-slug: akamai-api
  description: Get Event&#8217;s Bandwidth Data per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/bandwidth/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Origin, Bandwth, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidthcpcode-get-openapi.md
- name: Akamai API Get Event&#8217;s Origin Requests
  x-api-slug: akamai-api
  description: Get Event&#8217;s Origin Requests
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/requests
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Origin, Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeoriginrequests-get-openapi.md
- name: Akamai API Get Event&#8217;s Origin Requests per CP Code
  x-api-slug: akamai-api
  description: Get Event&#8217;s Origin Requests per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/requests/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Origin, Requests, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeoriginrequestscpcode-get-openapi.md
- name: Akamai API Get Event&#8217;s Origin Statuses
  x-api-slug: akamai-api
  description: Get Event&#8217;s Origin Statuses
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/status
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Origin, Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeoriginstatus-get-openapi.md
- name: Akamai API Get Event&#8217;s Origin Statuses per CP Code
  x-api-slug: akamai-api
  description: Get Event&#8217;s Origin Statuses per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/origin/status/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Origin, Status, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodeoriginstatuscpcode-get-openapi.md
- name: Akamai API Get Event&#8217;s I/O Bandwidth
  x-api-slug: akamai-api
  description: Get Event&#8217;s I/O Bandwidth
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/bandwidth
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Bandwth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodebandwidth-get-openapi.md
- name: Akamai API Get Event&#8217;s I/O Bandwidth per CP Code
  x-api-slug: akamai-api
  description: Get Event&#8217;s I/O Bandwidth per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/bandwidth/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Bandwth, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcodebandwidthcpcode-get-openapi.md
- name: Akamai API Get Event&#8217;s Requests
  x-api-slug: akamai-api
  description: Get Event&#8217;s Requests
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/requests
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Requests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcoderequests-get-openapi.md
- name: Akamai API Get Event&#8217;s Requests per CP Code
  x-api-slug: akamai-api
  description: Get Event&#8217;s Requests per CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/cpcode/requests/{cpcode}
  tags: Events, Account, Events, Event, Trafficdata, Cpcode, Requests, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatacpcoderequestscpcode-get-openapi.md
- name: Akamai API Get Entry Point Data for Flash Live Streams
  x-api-slug: akamai-api
  description: Get Entry Point Data for Flash Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/flashlive
  tags: Events, Account, Events, Event, Trafficdata, Entrypoint, Flashlive
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataentrypointflashlive-get-openapi.md
- name: Akamai API Get Entry Point Data for a Flash Live Stream
  x-api-slug: akamai-api
  description: Get Entry Point Data for a Flash Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/flashlive/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Entrypoint, Flashlive, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataentrypointflashlivestreamid-get-openapi.md
- name: Akamai API Get Entry Point Data for Universal Live Streams
  x-api-slug: akamai-api
  description: Get Entry Point Data for Universal Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/universallive
  tags: Events, Account, Events, Event, Trafficdata, Entrypoint, Universallive
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataentrypointuniversallive-get-openapi.md
- name: Akamai API Get Entry Point Data for a Universal Live Stream
  x-api-slug: akamai-api
  description: Get Entry Point Data for a Universal Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/entrypoint/universallive/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Entrypoint, Universallive, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataentrypointuniversallivestreamid-get-openapi.md
- name: Akamai API Get Aggregate Data for Flash Live Streams
  x-api-slug: akamai-api
  description: Get Aggregate Data for Flash Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressbw
  tags: Events, Account, Events, Event, Trafficdata, Fl, Egressbw, Aggregation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataflegressbw-get-openapi.md
- name: Akamai API Get Aggregate Data for a Flash Live Stream
  x-api-slug: akamai-api
  description: Get Aggregate Data for a Flash Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressbw/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Fl, Egressbw, Stream, Aggregation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataflegressbwstreamid-get-openapi.md
- name: Akamai API Get Request Data for Flash Live Streams
  x-api-slug: akamai-api
  description: Get Request Data for Flash Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressrequests
  tags: Events, Account, Events, Event, Trafficdata, Fl, Egressrequests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataflegressrequests-get-openapi.md
- name: Akamai API Get Request Data for a Flash Live Stream
  x-api-slug: akamai-api
  description: Get Request Data for a Flash Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressrequests/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Fl, Egressrequests, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataflegressrequestsstreamid-get-openapi.md
- name: Akamai API Get Viewer Data for Flash Live Streams
  x-api-slug: akamai-api
  description: Get Viewer Data for Flash Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressviewers
  tags: Events, Account, Events, Event, Trafficdata, Fl, Egressviewers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataflegressviewers-get-openapi.md
- name: Akamai API Get Viewer Data for a Flash Live Stream
  x-api-slug: akamai-api
  description: Get Viewer Data for a Flash Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/fl/egressviewers/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Fl, Egressviewers, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdataflegressviewersstreamid-get-openapi.md
- name: Akamai API Get Aggregate Data for Silverlight Live Streams
  x-api-slug: akamai-api
  description: Get Aggregate Data for Silverlight Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressbw
  tags: Events, Account, Events, Event, Trafficdata, Hdsll, Egress, Aggregation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatahdsllegressbw-get-openapi.md
- name: Akamai API Get Silverlight Live Stream
  x-api-slug: akamai-api
  description: Get Silverlight Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///streamId
  tags: Stream
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/streamid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/streamid-get-openapi.md
- name: Akamai API Get Request Data for Silverlight Live Streams
  x-api-slug: akamai-api
  description: Get Request Data for Silverlight Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressrequests
  tags: Events, Account, Events, Event, Trafficdata, Hdsll, Egressrequests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatahdsllegressrequests-get-openapi.md
- name: Akamai API Get Request Data for a Silverlight Live Stream
  x-api-slug: akamai-api
  description: Get Request Data for a Silverlight Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressrequests/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Hdsll, Egressrequests, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatahdsllegressrequestsstreamid-get-openapi.md
- name: Akamai API Get Status Data for Silverlight Live Streams
  x-api-slug: akamai-api
  description: Get Status Data for Silverlight Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressstatus
  tags: Events, Account, Events, Event, Trafficdata, Hdsll, Egressstatus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatahdsllegressstatus-get-openapi.md
- name: Akamai API Get Status Data for a Silverlight Live Stream
  x-api-slug: akamai-api
  description: Get Status Data for a Silverlight Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressstatus/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Hdsll, Egressstatus, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatahdsllegressstatusstreamid-get-openapi.md
- name: Akamai API Get Viewer Data for Silverlight Live Streams
  x-api-slug: akamai-api
  description: Get Viewer Data for Silverlight Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressviewers
  tags: Events, Account, Events, Event, Trafficdata, Hdsll, Egressviewers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatahdsllegressviewers-get-openapi.md
- name: Akamai API Get Viewer Data for a Silverlight Live Stream
  x-api-slug: akamai-api
  description: Get Viewer Data for a Silverlight Live Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/hdsll/egressviewers/{streamId}
  tags: Events, Account, Events, Event, Trafficdata, Hdsll, Egressviewers, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatahdsllegressviewersstreamid-get-openapi.md
- name: Akamai API Get SRIP Connections
  x-api-slug: akamai-api
  description: Get SRIP Connections
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/srip/connections
  tags: Events, Account, Events, Event, Trafficdata, Srip, Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatasripconnections-get-openapi.md
- name: Akamai API Get SRIP Connections per Slot
  x-api-slug: akamai-api
  description: Get SRIP Connections per Slot
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/srip/connections/{slotId}
  tags: Events, Account, Events, Event, Trafficdata, Srip, Connections, Slot
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatasripconnectionsslotid-get-openapi.md
- name: Akamai API Get SRIP Bandwidth
  x-api-slug: akamai-api
  description: Get SRIP Bandwidth
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/srip/sourcebandwidth
  tags: Events, Account, Events, Event, Trafficdata, Srip, Sourcebandwth
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatasripsourcebandwidth-get-openapi.md
- name: Akamai API Get SRIP Bandwidth per Slot
  x-api-slug: akamai-api
  description: Get SRIP Bandwidth per Slot
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/events/{eventId}/trafficdata/srip/sourcebandwidth/{slotId}
  tags: Events, Account, Events, Event, Trafficdata, Srip, Sourcebandwth, Slot
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountideventseventidtrafficdatasripsourcebandwidthslotid-get-openapi.md
- name: Akamai API Get Edge Bandwidth for Universal Live Streams
  x-api-slug: akamai-api
  description: Get Edge Bandwidth for Universal Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///deliveryFormat
  tags: Deliveryformat
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/deliveryformat-get-openapi.md
- name: Akamai API Get Audience Size
  x-api-slug: akamai-api
  description: Get Audience Size
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///timeAggInterval
  tags: Audience
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/timeagginterval-get-openapi.md
- name: Akamai API Get Report Packs
  x-api-slug: akamai-api
  description: Get Report Packs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///clientside_qos1_live
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/clientside-qos1-live-get-openapi.md
- name: Akamai API List CP Codes
  x-api-slug: akamai-api
  description: List CP Codes
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/sites/cpcodes
  tags: Events, Account, Sites, Cpcodes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidsitescpcodes-get-openapi.md
- name: Akamai API List IPA and SXL Configurations
  x-api-slug: akamai-api
  description: List IPA and SXL Configurations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/srip
  tags: Events, Account, Srip, Sortfield,sortorder,limit,startindex
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidsrip-get-openapi.md
- name: Akamai API List Flash Live Streams
  x-api-slug: akamai-api
  description: List Flash Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/streams/flashlive
  tags: Events, Account, Streams, Flashlive
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidstreamsflashlive-get-openapi.md
- name: Akamai API List Silverlight Live Streams
  x-api-slug: akamai-api
  description: List Silverlight Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/streams/silverlightlive
  tags: Events, Account, Streams, Silverlightlive
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidstreamssilverlightlive-get-openapi.md
- name: Akamai API List Universal Live Streams
  x-api-slug: akamai-api
  description: List Universal Live Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////events/v2/{accountId}/streams/universallive
  tags: Events, Account, Streams, Universallive, Sortfield,sortorder,limit,startindex
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/eventsv2accountidstreamsuniversallive-get-openapi.md
- name: Akamai API Purge a Configuration
  x-api-slug: akamai-api
  description: Purge a Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////feo/v1/purge
  tags: Feo, Purge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/feov1purge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/feov1purge-post-openapi.md
- name: Akamai API Get a Policy
  x-api-slug: akamai-api
  description: Get a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/policies/{id}
  tags: Imaging, V0, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0policiesid-get-openapi.md
- name: Akamai API Add or Modify a Policy
  x-api-slug: akamai-api
  description: Add or Modify a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/policies/{id}
  tags: Imaging, V0, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0policiesid-put-openapi.md
- name: Akamai API Remove a Policy
  x-api-slug: akamai-api
  description: Remove a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/policies/{id}
  tags: Imaging, V0, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0policiesid-delete-openapi.md
- name: Akamai API List Policies
  x-api-slug: akamai-api
  description: List Policies
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/policies
  tags: Imaging, V0, Policies
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0policies-get-openapi.md
- name: Akamai API Get Policy History
  x-api-slug: akamai-api
  description: Get Policy History
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///id
  tags: Policies, History
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/id-get-openapi.md
- name: Akamai API List Images to a Limit
  x-api-slug: akamai-api
  description: List Images to a Limit
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/images
  tags: Imaging, V0, Images, Limit
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0images-get-openapi.md
- name: Akamai API List Images Matching a URL
  x-api-slug: akamai-api
  description: List Images Matching a URL
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/images
  tags: Imaging, V0, Images, Url
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0images-get-openapi.md
- name: Akamai API Get an Image
  x-api-slug: akamai-api
  description: Get an Image
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/images/{id}
  tags: Imaging, V0, Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0imagesid-get-openapi.md
- name: Akamai API List a Policy&#8217;s Images
  x-api-slug: akamai-api
  description: List a Policy&#8217;s Images
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/images
  tags: Imaging, V0, Images, Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0images-get-openapi.md
- name: Akamai API List Image Collections
  x-api-slug: akamai-api
  description: List Image Collections
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/imagecollections
  tags: Imaging, V0, Imagecollections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0imagecollections-get-openapi.md
- name: Akamai API Get an Image Collection
  x-api-slug: akamai-api
  description: Get an Image Collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/imagecollections/{id}
  tags: Imaging, V0, Imagecollections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0imagecollectionsid-get-openapi.md
- name: Akamai API Add or Modify an Image Collection
  x-api-slug: akamai-api
  description: Add or Modify an Image Collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/imagecollections/{id}
  tags: Imaging, V0, Imagecollections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0imagecollectionsid-put-openapi.md
- name: Akamai API Remove an Image Collection
  x-api-slug: akamai-api
  description: Remove an Image Collection
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///id
  tags: Images
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/id-delete-openapi.md
- name: Akamai API List Image Collections By Tag
  x-api-slug: akamai-api
  description: List Image Collections By Tag
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/imagecollections
  tags: Imaging, V0, Imagecollections, Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0imagecollections-get-openapi.md
- name: Akamai API Get an Image Collection&#8217;s Tags
  x-api-slug: akamai-api
  description: Get an Image Collection&#8217;s Tags
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/imagecollections/tags/{id}
  tags: Imaging, V0, Imagecollections, Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0imagecollectionstagsid-get-openapi.md
- name: Akamai API Modify an Image Collection&#8217;s Tags
  x-api-slug: akamai-api
  description: Modify an Image Collection&#8217;s Tags
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////imaging/v0/imagecollections/tags/{id}
  tags: Imaging, V0, Imagecollections, Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/imagingv0imagecollectionstagsid-put-openapi.md
- name: Akamai API List Account&#8217;s Invoices
  x-api-slug: akamai-api
  description: List Account&#8217;s Invoices
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/accounts/{accountId}/invoices
  tags: Invoicing, Accounts, Account, Invoices, Year,month
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2accountsaccountidinvoices-get-openapi.md
- name: Akamai API List Contract&#8217;s Invoices
  x-api-slug: akamai-api
  description: List Contract&#8217;s Invoices
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/contracts/{contractId}/invoices
  tags: Invoicing, Contracts, Contract, Invoices, Year,month
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2contractscontractidinvoices-get-openapi.md
- name: Akamai API List Contract&#8217;s Invoice Files
  x-api-slug: akamai-api
  description: List Contract&#8217;s Invoice Files
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/contracts/{contractId}/invoices/{invoiceNumber}/files
  tags: Invoicing, Contracts, Contract, Invoices, Invoicenumber, Files
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2contractscontractidinvoicesinvoicenumberfiles-get-openapi.md
- name: Akamai API Download an Invoice File
  x-api-slug: akamai-api
  description: Download an Invoice File
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///Content-Type
  tags: Content, Type
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/contenttype-get-openapi.md
- name: Akamai API Download Geobilling Files
  x-api-slug: akamai-api
  description: Download Geobilling Files
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/contracts/{contractId}/products/{productId}/geo-billing-files
  tags: Invoicing, Contracts, Contract, Products, Product, Geo, Billing, Files, Year,month,day
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2contractscontractidproductsproductidgeobillingfiles-get-openapi.md
- name: Akamai API List Notifications
  x-api-slug: akamai-api
  description: List Notifications
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/accounts/{accountId}/notifications
  tags: Invoicing, Accounts, Account, Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2accountsaccountidnotifications-get-openapi.md
- name: Akamai API Create a Notification
  x-api-slug: akamai-api
  description: Create a Notification
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/accounts/{accountId}/notifications
  tags: Invoicing, Accounts, Account, Notifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2accountsaccountidnotifications-post-openapi.md
- name: Akamai API Get a Notification
  x-api-slug: akamai-api
  description: Get a Notification
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/accounts/{accountId}/notifications/{notificationId}
  tags: Invoicing, Accounts, Account, Notifications, Notification
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2accountsaccountidnotificationsnotificationid-get-openapi.md
- name: Akamai API Modify a Notification
  x-api-slug: akamai-api
  description: Modify a Notification
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/accounts/{accountId}/notifications/{notificationId}
  tags: Invoicing, Accounts, Account, Notifications, Notification
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2accountsaccountidnotificationsnotificationid-put-openapi.md
- name: Akamai API Remove a Notification
  x-api-slug: akamai-api
  description: Remove a Notification
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////invoicing-api/v2/accounts/{accountId}/notifications/{notificationId}
  tags: Invoicing, Accounts, Account, Notifications, Notification
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/invoicingapiv2accountsaccountidnotificationsnotificationid-delete-openapi.md
- name: Akamai API List Configurations
  x-api-slug: akamai-api
  description: List Configurations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///acgObject
  tags: Configurations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/acgobject-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/acgobject-get-openapi.md
- name: Akamai API Create a Configuration
  x-api-slug: akamai-api
  description: Create a Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///serviceId
  tags: Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-post-openapi.md
- name: Akamai API Get a Configuration
  x-api-slug: akamai-api
  description: Get a Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///serviceId
  tags: Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-get-openapi.md
- name: Akamai API Modify a Configuration
  x-api-slug: akamai-api
  description: Modify a Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///serviceId
  tags: Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-put-openapi.md
- name: Akamai API Remove a Configuration
  x-api-slug: akamai-api
  description: Remove a Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///serviceId
  tags: Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/serviceid-delete-openapi.md
- name: Akamai API Copy a Configuration
  x-api-slug: akamai-api
  description: Copy a Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///sourceServiceId
  tags: Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/sourceserviceid-post-openapi.md
- name: Akamai API Resume a Configuration
  x-api-slug: akamai-api
  description: Resume a Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////lds/v1/configurations/resume/{serviceId}
  tags: Lds, Configurationsurations, Resume, Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ldsv1configurationsresumeserviceid-post-openapi.md
- name: Akamai API List Redeliveries
  x-api-slug: akamai-api
  description: List Redeliveries
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////lds/v1/redeliveries
  tags: Lds, Redeliveries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ldsv1redeliveries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ldsv1redeliveries-get-openapi.md
- name: Akamai API Create a Redelivery
  x-api-slug: akamai-api
  description: Create a Redelivery
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////lds/v1/redeliveries
  tags: Lds, Redeliveries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ldsv1redeliveries-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ldsv1redeliveries-post-openapi.md
- name: Akamai API Get a Redelivery
  x-api-slug: akamai-api
  description: Get a Redelivery
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///redeliveryId
  tags: Redelivery
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/redeliveryid-get-openapi.md
- name: Akamai API Get a Dictionary
  x-api-slug: akamai-api
  description: Get a Dictionary
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///key
  tags: Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/key-get-openapi.md
- name: Akamai API Get Validation Context
  x-api-slug: akamai-api
  description: Get Validation Context
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////lds/v1/dictionaries/{dictionaryName}/validation/data
  tags: Lds, Dictionaries, Dictionaryname, Valation, Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/ldsv1dictionariesdictionarynamevalidationdata-get-openapi.md
- name: Akamai API List Download Delivery Dimensions
  x-api-slug: akamai-api
  description: List Download Delivery Dimensions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/download-delivery/dimensions
  tags: Media, Reports, Download, Delivery, Dimensions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1downloaddeliverydimensions-get-openapi.md
- name: Akamai API List Download Delivery Metrics
  x-api-slug: akamai-api
  description: List Download Delivery Metrics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/download-delivery/metrics
  tags: Media, Reports, Download, Delivery, Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1downloaddeliverymetrics-get-openapi.md
- name: Akamai API Get Download Delivery Data
  x-api-slug: akamai-api
  description: Get Download Delivery Data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///filterParams
  tags: Filterparams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/filterparams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/filterparams-get-openapi.md
- name: Akamai API List Object Delivery Metrics
  x-api-slug: akamai-api
  description: List Object Delivery Metrics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/object-delivery/metrics
  tags: Media, Reports, Object, Delivery, Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1objectdeliverymetrics-get-openapi.md
- name: Akamai API List Adaptive Media Delivery Metrics
  x-api-slug: akamai-api
  description: List Adaptive Media Delivery Metrics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/adaptive-media-delivery/metrics
  tags: Media, Reports, Adaptive, Media, Delivery, Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1adaptivemediadeliverymetrics-get-openapi.md
- name: Akamai API List RTMP Media Delivery Metrics
  x-api-slug: akamai-api
  description: List RTMP Media Delivery Metrics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/rtmp-media-delivery/metrics
  tags: Media, Reports, Rtmp, Media, Delivery, Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1rtmpmediadeliverymetrics-get-openapi.md
- name: Akamai API List Wholesale Delivery Metrics
  x-api-slug: akamai-api
  description: List Wholesale Delivery Metrics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/wholesale-delivery/metrics
  tags: Media, Reports, Wholesale, Delivery, Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1wholesaledeliverymetrics-get-openapi.md
- name: Akamai API List HTTP Ingest Metrics
  x-api-slug: akamai-api
  description: List HTTP Ingest Metrics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/media-services-live/http-ingest/metrics
  tags: Media, Reports, Media, Services, Live, Http, Ingest, Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1mediaserviceslivehttpingestmetrics-get-openapi.md
- name: Akamai API List RTMP Ingest Dimensions
  x-api-slug: akamai-api
  description: List RTMP Ingest Dimensions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/media-services-live/rtmp-ingest/dimensions
  tags: Media, Reports, Media, Services, Live, Rtmp, Ingest, Dimensions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1mediaserviceslivertmpingestdimensions-get-openapi.md
- name: Akamai API List RTMP Ingest Metrics
  x-api-slug: akamai-api
  description: List RTMP Ingest Metrics
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////media-reports/v1/media-services-live/rtmp-ingest/metrics
  tags: Media, Reports, Media, Services, Live, Rtmp, Ingest, Metrics
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/mediareportsv1mediaserviceslivertmpingestmetrics-get-openapi.md
- name: Akamai API List Domains
  x-api-slug: akamai-api
  description: List Domains
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live
  tags: Configurations, Media, Live, Live
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1live-get-openapi.md
- name: Akamai API Create a Domain
  x-api-slug: akamai-api
  description: Create a Domain
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live
  tags: Configurations, Media, Live, Live
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1live-post-openapi.md
- name: Akamai API Get a Domain
  x-api-slug: akamai-api
  description: Get a Domain
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}
  tags: Configurations, Media, Live, Live, Domain
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomain-get-openapi.md
- name: Akamai API Remove a Domain
  x-api-slug: akamai-api
  description: Remove a Domain
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}
  tags: Configurations, Media, Live, Live, Domain
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomain-delete-openapi.md
- name: Akamai API List Streams
  x-api-slug: akamai-api
  description: List Streams
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream
  tags: Configurations, Media, Live, Live, Domain, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstream-get-openapi.md
- name: Akamai API Create a New Stream
  x-api-slug: akamai-api
  description: Create a New Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream
  tags: Configurations, Media, Live, Live, Domain, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstream-post-openapi.md
- name: Akamai API Get a Stream
  x-api-slug: akamai-api
  description: Get a Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream/{streamId}
  tags: Configurations, Media, Live, Live, Domain, Stream, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstreamstreamid-get-openapi.md
- name: Akamai API Remove a Stream
  x-api-slug: akamai-api
  description: Remove a Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream/{streamId}
  tags: Configurations, Media, Live, Live, Domain, Stream, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstreamstreamid-delete-openapi.md
- name: Akamai API Modify a Stream
  x-api-slug: akamai-api
  description: Modify a Stream
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream/{streamId}
  tags: Configurations, Media, Live, Live, Domain, Stream, Stream
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstreamstreamid-put-openapi.md
- name: Akamai API List Events
  x-api-slug: akamai-api
  description: List Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream/{streamId}/event
  tags: Configurations, Media, Live, Live, Domain, Stream, Stream, Event
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstreamstreamidevent-get-openapi.md
- name: Akamai API Get an Event
  x-api-slug: akamai-api
  description: Get an Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream/{streamId}/event/{eventName}
  tags: Configurations, Media, Live, Live, Domain, Stream, Stream, Event, Eventname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstreamstreamideventeventname-get-openapi.md
- name: Akamai API Modify an Event
  x-api-slug: akamai-api
  description: Modify an Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream/{streamId}/event/{eventName}
  tags: Configurations, Media, Live, Live, Domain, Stream, Stream, Event, Eventname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstreamstreamideventeventname-put-openapi.md
- name: Akamai API Remove an Event
  x-api-slug: akamai-api
  description: Remove an Event
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/stream/{streamId}/event/{eventName}
  tags: Configurations, Media, Live, Live, Domain, Stream, Stream, Event, Eventname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainstreamstreamideventeventname-delete-openapi.md
- name: Akamai API Create a New Version
  x-api-slug: akamai-api
  description: Create a New Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/version
  tags: Configurations, Media, Live, Live, Domain, Version
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainversion-post-openapi.md
- name: Akamai API Get a Version
  x-api-slug: akamai-api
  description: Get a Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/version/{versionId}
  tags: Configurations, Media, Live, Live, Domain, Version
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainversionversionid-get-openapi.md
- name: Akamai API Get Activation Status
  x-api-slug: akamai-api
  description: Get Activation Status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/version/{versionId}/activation
  tags: Configurations, Media, Live, Live, Domain, Version, Activation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainversionversionidactivation-get-openapi.md
- name: Akamai API Activate a Version
  x-api-slug: akamai-api
  description: Activate a Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/{domain}/version/{versionId}/activation
  tags: Configurations, Media, Live, Live, Domain, Version, Activation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1livedomainversionversionidactivation-put-openapi.md
- name: Akamai API List Archive Locations
  x-api-slug: akamai-api
  description: List Archive Locations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/api/live/utils/archivelocation
  tags: Configurations, Media, Live, Live, Utils, Archives
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1apiliveutilsarchivelocation-get-openapi.md
- name: Akamai API List Contacts
  x-api-slug: akamai-api
  description: List Contacts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/utils/contacts
  tags: Configurations, Media, Live, Live, Utils, Contacts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1liveutilscontacts-get-openapi.md
- name: Akamai API List Countries
  x-api-slug: akamai-api
  description: List Countries
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/utils/countries
  tags: Configurations, Media, Live, Live, Utils, Countries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1liveutilscountries-get-openapi.md
- name: Akamai API List CP Codes
  x-api-slug: akamai-api
  description: List CP Codes
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/utils/cpcode
  tags: Configurations, Media, Live, Live, Utils, Cpcode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1liveutilscpcode-get-openapi.md
- name: Akamai API List Delivery Formats
  x-api-slug: akamai-api
  description: List Delivery Formats
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/utils/delivery/format
  tags: Configurations, Media, Live, Live, Utils, Delivery, Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1liveutilsdeliveryformat-get-openapi.md
- name: Akamai API List Ingest Formats
  x-api-slug: akamai-api
  description: List Ingest Formats
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-live/v1/live/utils/ingest/format
  tags: Configurations, Media, Live, Live, Utils, Ingest, Format
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmedialivev1liveutilsingestformat-get-openapi.md
- name: Akamai API List Network Lists
  x-api-slug: akamai-api
  description: List Network Lists
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists
  tags: Network, List, Network, Lists, Listtype,extended,includedeprecated,includeelements
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-lists-get-openapi.md
- name: Akamai API Create a Network List
  x-api-slug: akamai-api
  description: Create a Network List
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists
  tags: Network, List, Network, Lists, Listtype,extended,includedeprecated,includeelements
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-lists-post-openapi.md
- name: Akamai API Modify a Network List
  x-api-slug: akamai-api
  description: Modify a Network List
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}
  tags: Network, List, Network, Lists, Networklist, Extended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistid-put-openapi.md
- name: Akamai API Get a Network List
  x-api-slug: akamai-api
  description: Get a Network List
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}
  tags: Network, List, Network, Lists, Networklist, Extended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistid-get-openapi.md
- name: Akamai API Add to a Network List
  x-api-slug: akamai-api
  description: Add to a Network List
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}
  tags: Network, List, Network, Lists, Networklist, Extended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistid-post-openapi.md
- name: Akamai API Add an Element
  x-api-slug: akamai-api
  description: Add an Element
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}/element
  tags: Network, List, Network, Lists, Networklist, Element
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistidelement-put-openapi.md
- name: Akamai API Remove an Element
  x-api-slug: akamai-api
  description: Remove an Element
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}/element
  tags: Network, List, Network, Lists, Networklist, Element, Element
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistidelement-delete-openapi.md
- name: Akamai API Activate a Network List
  x-api-slug: akamai-api
  description: Activate a Network List
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}/activate
  tags: Network, List, Network, Lists, Networklist, Activate, Env
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistidactivate-post-openapi.md
- name: Akamai API Get Activation Status
  x-api-slug: akamai-api
  description: Get Activation Status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}/status
  tags: Network, List, Network, Lists, Networklist, Status, Env
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistidstatus-get-openapi.md
- name: Akamai API Get Activation Snapshot
  x-api-slug: akamai-api
  description: Get Activation Snapshot
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}/history
  tags: Network, List, Network, Lists, Networklist, History, Sync%2dpoint,extended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistidhistory-get-openapi.md
- name: Akamai API Search Network Lists
  x-api-slug: akamai-api
  description: Search Network Lists
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/search
  tags: Network, List, Network, Lists, Search, Expression,listtype,extended,includedeprecated
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listssearch-get-openapi.md
- name: Akamai API Share a Network List
  x-api-slug: akamai-api
  description: Share a Network List
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////network-list/v1/network_lists/{networkListId}/share
  tags: Network, List, Network, Lists, Networklist, Share
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/networklistv1network-listsnetworklistidshare-post-openapi.md
- name: Akamai API List Sharing Status
  x-api-slug: akamai-api
  description: List Sharing Status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///ALL
  tags: All
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/all-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/all-get-openapi.md
- name: Akamai API List Events
  x-api-slug: akamai-api
  description: List Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////prolexic-analytics/v1/events/contract/{contract}
  tags: Prolexic, Analytics, Events, Contract, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/prolexicanalyticsv1eventscontractcontract-get-openapi.md
- name: Akamai API List Critical Events
  x-api-slug: akamai-api
  description: List Critical Events
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////prolexic-analytics/v1/critical-events/contract/{contract}
  tags: Prolexic, Analytics, Critical, Events, Contract, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/prolexicanalyticsv1criticaleventscontractcontract-get-openapi.md
- name: Akamai API List Metric Types
  x-api-slug: akamai-api
  description: List Metric Types
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////prolexic-analytics/v1/metric-types
  tags: Prolexic, Analytics, Metric, Types
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/prolexicanalyticsv1metrictypes-get-openapi.md
- name: Akamai API Get Metrics Data
  x-api-slug: akamai-api
  description: Get Metrics Data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///type
  tags: Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/type-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/type-post-openapi.md
- name: Akamai API List Attack Reports
  x-api-slug: akamai-api
  description: List Attack Reports
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////prolexic-analytics/v1/attack-reports/contract/{contract}/start/{start}/end/{end}
  tags: Prolexic, Analytics, Attack, Reports, Contract, Contract, Start, Start, End,
    End
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/prolexicanalyticsv1attackreportscontractcontractstartstartendend-get-openapi.md
- name: Akamai API Get an Attack Report
  x-api-slug: akamai-api
  description: Get an Attack Report
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////prolexic-analytics/v1/attack-report/contract/{contract}/attack-id/{attackId}
  tags: Prolexic, Analytics, Attack, Report, Contract, Contract, Attack, , Attack
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/prolexicanalyticsv1attackreportcontractcontractattackidattackid-get-openapi.md
- name: Akamai API List Groups
  x-api-slug: akamai-api
  description: List Groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/groups/
  tags: Papi, V0, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0groups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0groups-get-openapi.md
- name: Akamai API List Contracts
  x-api-slug: akamai-api
  description: List Contracts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/contracts/
  tags: Papi, V0, Contracts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0contracts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0contracts-get-openapi.md
- name: Akamai API List Products
  x-api-slug: akamai-api
  description: List Products
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/products/{
  tags: Papi, V0, Products, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0products-get-openapi.md
- name: Akamai API List CP Codes
  x-api-slug: akamai-api
  description: List CP Codes
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/cpcodes/
  tags: Papi, V0, Cpcodes, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0cpcodes-get-openapi.md
- name: Akamai API Create a New CP Code
  x-api-slug: akamai-api
  description: Create a New CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/cpcodes/
  tags: Papi, V0, Cpcodes, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0cpcodes-post-openapi.md
- name: Akamai API Get a CP Code
  x-api-slug: akamai-api
  description: Get a CP Code
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/cpcodes/{cpcodeId}
  tags: Papi, V0, Cpcodes, Cpcode, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0cpcodescpcodeid-get-openapi.md
- name: Akamai API List Edge Hostnames
  x-api-slug: akamai-api
  description: List Edge Hostnames
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/edgehostnames/
  tags: Papi, V0, Edgehostnames, Contract,group,options
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0edgehostnames-get-openapi.md
- name: Akamai API Create a New Edge Hostname
  x-api-slug: akamai-api
  description: Create a New Edge Hostname
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/edgehostnames/
  tags: Papi, V0, Edgehostnames, Contract,group,options
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0edgehostnames-post-openapi.md
- name: Akamai API Get an Edge Hostname
  x-api-slug: akamai-api
  description: Get an Edge Hostname
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/edgehostnames/{edgeHostnameId}
  tags: Papi, V0, Edgehostnames, Edgehostname, Contract,group,options
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0edgehostnamesedgehostnameid-get-openapi.md
- name: Akamai API List Properties
  x-api-slug: akamai-api
  description: List Properties
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{
  tags: Papi, V0, Properties, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0properties-get-openapi.md
- name: Akamai API Create or Clone a Property
  x-api-slug: akamai-api
  description: Create or Clone a Property
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/
  tags: Papi, V0, Properties, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0properties-post-openapi.md
- name: Akamai API Get a Property
  x-api-slug: akamai-api
  description: Get a Property
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}
  tags: Papi, V0, Properties, Property, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyid-get-openapi.md
- name: Akamai API List Property Versions
  x-api-slug: akamai-api
  description: List Property Versions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions
  tags: Papi, V0, Properties, Property, Versions, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidversions-get-openapi.md
- name: Akamai API Create a New Property Version
  x-api-slug: akamai-api
  description: Create a New Property Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///createFromVersion
  tags: Versions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/createfromversion-post-openapi.md
- name: Akamai API Get a Property&#8217;s Latest Version
  x-api-slug: akamai-api
  description: Get a Property&#8217;s Latest Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions/latest
  tags: Papi, V0, Properties, Property, Versions, Latest, Contract,group,activatedon
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidversionslatest-get-openapi.md
- name: Akamai API Get a Property Version
  x-api-slug: akamai-api
  description: Get a Property Version
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: 'https://developer.akamai.com///Accept: text/xml'
  tags: Accept, Text, Xml
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/accept-textxml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/accept-textxml-get-openapi.md
- name: Akamai API List Available Criteria
  x-api-slug: akamai-api
  description: List Available Criteria
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions/{propertyVersion}/available-criteria
  tags: Papi, V0, Properties, Property, Versions, Propertyversion, Available, Criteria,
    Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidversionspropertyversionavailablecriteria-get-openapi.md
- name: Akamai API List a Property Version&#8217;s Hostnames
  x-api-slug: akamai-api
  description: List a Property Version&#8217;s Hostnames
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions/{propertyVersion}/hostnames/
  tags: Papi, V0, Properties, Property, Versions, Propertyversion, Hostnames, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidversionspropertyversionhostnames-get-openapi.md
- name: Akamai API Update a Property Version&#8217;s Hostnames
  x-api-slug: akamai-api
  description: Update a Property Version&#8217;s Hostnames
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///cnameFrom
  tags: CName, DNS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/cnamefrom-put-openapi.md
- name: Akamai API Get a Property Version&#8217;s Rule Tree
  x-api-slug: akamai-api
  description: Get a Property Version&#8217;s Rule Tree
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions/{propertyVersion}/rules/
  tags: Papi, V0, Properties, Property, Versions, Propertyversion, Rules, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidversionspropertyversionrules-get-openapi.md
- name: Akamai API Get a Rule Tree&#8217;s Digest
  x-api-slug: akamai-api
  description: Get a Rule Tree&#8217;s Digest
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions/{propertyVersion}/rules/
  tags: Papi, V0, Properties, Property, Versions, Propertyversion, Rules, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidversionspropertyversionrules-head-openapi.md
- name: Akamai API Update a Property Version&#8217;s Rule Tree
  x-api-slug: akamai-api
  description: Update a Property Version&#8217;s Rule Tree
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/versions/{propertyVersion}/rules/
  tags: Papi, V0, Properties, Property, Versions, Propertyversion, Rules, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidversionspropertyversionrules-put-openapi.md
- name: Akamai API List a Property&#8217;s Activations
  x-api-slug: akamai-api
  description: List a Property&#8217;s Activations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/properties/{propertyId}/activations/
  tags: Papi, V0, Properties, Property, Activations, Contract,group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0propertiespropertyidactivations-get-openapi.md
- name: Akamai API Create a New Activation
  x-api-slug: akamai-api
  description: Create a New Activation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///{&quot;type&quot;:&quot;/papi/v0/activation-warnings-not-acknowledged&quot;}
  tags: Activations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/quottypequotquotpapiv0activationwarningsnotacknowledgedquot-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/quottypequotquotpapiv0activationwarningsnotacknowledgedquot-post-openapi.md
- name: Akamai API Get an Activation
  x-api-slug: akamai-api
  description: Get an Activation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///Retry-After
  tags: Retry, After
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/retryafter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/retryafter-get-openapi.md
- name: Akamai API Cancel a Pending Activation
  x-api-slug: akamai-api
  description: Cancel a Pending Activation
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///status
  tags: Status
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/status-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/status-delete-openapi.md
- name: Akamai API List Available Rule Formats
  x-api-slug: akamai-api
  description: List Available Rule Formats
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/rule-formats
  tags: Papi, V0, Rule, Formats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0ruleformats-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0ruleformats-get-openapi.md
- name: Akamai API Get a Request&#8217;s JSON Schema
  x-api-slug: akamai-api
  description: Get a Request&#8217;s JSON Schema
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/schemas/request/{filename}
  tags: Papi, V0, Schemas, Request, Filename
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0schemasrequestfilename-get-openapi.md
- name: Akamai API Get a Rule Format&#8217;s JSON Schema
  x-api-slug: akamai-api
  description: Get a Rule Format&#8217;s JSON Schema
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/schemas/products/{productId}/{ruleFormat}
  tags: Papi, V0, Schemas, Products, Product, Ruleformat
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0schemasproductsproductidruleformat-get-openapi.md
- name: Akamai API Get Client Settings
  x-api-slug: akamai-api
  description: Get Client Settings
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/client-settings
  tags: Papi, V0, Client, Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0clientsettings-get-openapi.md
- name: Akamai API Update Client Settings
  x-api-slug: akamai-api
  description: Update Client Settings
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/client-settings
  tags: Papi, V0, Client, Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0clientsettings-put-openapi.md
- name: Akamai API Get Build Details
  x-api-slug: akamai-api
  description: Get Build Details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////papi/v0/build
  tags: Papi, V0, Build
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0build-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/papiv0build-get-openapi.md
- name: Akamai API List Applications
  x-api-slug: akamai-api
  description: List Applications
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/applications/
  tags: Configurations, Saas, Registration, Applications, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1applications-get-openapi.md
- name: Akamai API Create a New Application
  x-api-slug: akamai-api
  description: Create a New Application
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/applications/
  tags: Configurations, Saas, Registration, Applications, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1applications-post-openapi.md
- name: Akamai API Get an Application
  x-api-slug: akamai-api
  description: Get an Application
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/applications/{surrogateId}/
  tags: Configurations, Saas, Registration, Applications, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1applicationssurrogateid-get-openapi.md
- name: Akamai API Remove an Application
  x-api-slug: akamai-api
  description: Remove an Application
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/applications/{surrogateId}/
  tags: Configurations, Saas, Registration, Applications, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1applicationssurrogateid-delete-openapi.md
- name: Akamai API Modify an Application
  x-api-slug: akamai-api
  description: Modify an Application
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/applications/{surrogateId}/
  tags: Configurations, Saas, Registration, Applications, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1applicationssurrogateid-put-openapi.md
- name: Akamai API List Customers
  x-api-slug: akamai-api
  description: List Customers
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/customers/
  tags: Configurations, Saas, Registration, Customers, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1customers-get-openapi.md
- name: Akamai API Create a New Customer
  x-api-slug: akamai-api
  description: Create a New Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/customers/
  tags: Configurations, Saas, Registration, Customers, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1customers-post-openapi.md
- name: Akamai API Get a Customer
  x-api-slug: akamai-api
  description: Get a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/customers/{surrogateId}/
  tags: Configurations, Saas, Registration, Customers, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1customerssurrogateid-get-openapi.md
- name: Akamai API Remove a Customer
  x-api-slug: akamai-api
  description: Remove a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/customers/{surrogateId}/
  tags: Configurations, Saas, Registration, Customers, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1customerssurrogateid-delete-openapi.md
- name: Akamai API Modify a Customer
  x-api-slug: akamai-api
  description: Modify a Customer
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/customers/{surrogateId}/
  tags: Configurations, Saas, Registration, Customers, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1customerssurrogateid-put-openapi.md
- name: Akamai API List Pairs
  x-api-slug: akamai-api
  description: List Pairs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/pairs/
  tags: Configurations, Saas, Registration, Pairs, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1pairs-get-openapi.md
- name: Akamai API Create a New Pair
  x-api-slug: akamai-api
  description: Create a New Pair
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/pairs/
  tags: Configurations, Saas, Registration, Pairs, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1pairs-post-openapi.md
- name: Akamai API Get a Pair
  x-api-slug: akamai-api
  description: Get a Pair
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/pairs/{surrogateId}/
  tags: Configurations, Saas, Registration, Pairs, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1pairssurrogateid-get-openapi.md
- name: Akamai API Remove a Pair
  x-api-slug: akamai-api
  description: Remove a Pair
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/pairs/{surrogateId}/
  tags: Configurations, Saas, Registration, Pairs, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1pairssurrogateid-delete-openapi.md
- name: Akamai API Modify a Pair
  x-api-slug: akamai-api
  description: Modify a Pair
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-saas-registration/v1/pairs/{surrogateId}/
  tags: Configurations, Saas, Registration, Pairs, Surrogate, Contract
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsaasregistrationv1pairssurrogateid-put-openapi.md
- name: Akamai API List Policies
  x-api-slug: akamai-api
  description: List Policies
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security
  tags: Configurations, Media, Security, Security
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1security-get-openapi.md
- name: Akamai API Create a Policy
  x-api-slug: akamai-api
  description: Create a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security
  tags: Configurations, Media, Security, Security
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1security-post-openapi.md
- name: Akamai API Get a Policy
  x-api-slug: akamai-api
  description: Get a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}
  tags: Configurations, Media, Security, Security, Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyid-get-openapi.md
- name: Akamai API Modify a Policy
  x-api-slug: akamai-api
  description: Modify a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}
  tags: Configurations, Media, Security, Security, Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyid-put-openapi.md
- name: Akamai API Mark a Policy for Deletion
  x-api-slug: akamai-api
  description: Mark a Policy for Deletion
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}
  tags: Configurations, Media, Security, Security, Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyid-delete-openapi.md
- name: Akamai API Get Policy per Environment
  x-api-slug: akamai-api
  description: Get Policy per Environment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}/{environment}
  tags: Configurations, Media, Security, Security, Policy, Environment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyidenvironment-get-openapi.md
- name: Akamai API Clone a Policy
  x-api-slug: akamai-api
  description: Clone a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}/clonePolicy
  tags: Configurations, Media, Security, Security, Policy, Clonepolicy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyidclonepolicy-post-openapi.md
- name: Akamai API Promote a Policy
  x-api-slug: akamai-api
  description: Promote a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}/promote
  tags: Configurations, Media, Security, Security, Policy, Promote
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyidpromote-put-openapi.md
- name: Akamai API Remove a Policy
  x-api-slug: akamai-api
  description: Remove a Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}/promoteDelete
  tags: Configurations, Media, Security, Security, Policy, Promotedelete
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyidpromotedelete-delete-openapi.md
- name: Akamai API Restore a Policy Deletion
  x-api-slug: akamai-api
  description: Restore a Policy Deletion
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}/revertDelete
  tags: Configurations, Media, Security, Security, Policy, Revertdelete
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyidrevertdelete-put-openapi.md
- name: Akamai API Restore a Policy Edit
  x-api-slug: akamai-api
  description: Restore a Policy Edit
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/{policyID}/revertEdit
  tags: Configurations, Media, Security, Security, Policy, Revertedit
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitypolicyidrevertedit-put-openapi.md
- name: Akamai API Get an HD Config Policy
  x-api-slug: akamai-api
  description: Get an HD Config Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/live/{domain}/policy
  tags: Configurations, Media, Security, Security, Live, Domain, Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitylivedomainpolicy-get-openapi.md
- name: Akamai API Modify an HD Config Policy
  x-api-slug: akamai-api
  description: Modify an HD Config Policy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/live/{domain}/policy
  tags: Configurations, Media, Security, Security, Live, Domain, Policy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitylivedomainpolicy-put-openapi.md
- name: Akamai API Get an HD Config Policy per Environment
  x-api-slug: akamai-api
  description: Get an HD Config Policy per Environment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/live/{domain}/policy/{environment}
  tags: Configurations, Media, Security, Security, Live, Domain, Policy, Environment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitylivedomainpolicyenvironment-get-openapi.md
- name: Akamai API List Policy Assignments
  x-api-slug: akamai-api
  description: List Policy Assignments
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/live/{policyID}/policyassignments
  tags: Configurations, Media, Security, Security, Live, Policy, Policyassignments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitylivepolicyidpolicyassignments-get-openapi.md
- name: Akamai API Get a Policy Assignment
  x-api-slug: akamai-api
  description: Get a Policy Assignment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/live/{policyID}/policyassignments/{environment}
  tags: Configurations, Media, Security, Security, Live, Policy, Policyassignments,
    Environment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitylivepolicyidpolicyassignmentsenvironment-get-openapi.md
- name: Akamai API Promote a Policy Assignment
  x-api-slug: akamai-api
  description: Promote a Policy Assignment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/live/{policyID}/policyassignments/promote
  tags: Configurations, Media, Security, Security, Live, Policy, Policyassignments,
    Promote
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitylivepolicyidpolicyassignmentspromote-put-openapi.md
- name: Akamai API Revert a Policy Assignment Promotion
  x-api-slug: akamai-api
  description: Revert a Policy Assignment Promotion
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/live/{policyID}/policyassignments/revert
  tags: Configurations, Media, Security, Security, Live, Policy, Policyassignments,
    Revert
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitylivepolicyidpolicyassignmentsrevert-put-openapi.md
- name: Akamai API List Countries
  x-api-slug: akamai-api
  description: List Countries
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/countries
  tags: Configurations, Media, Security, Security, Countries
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitycountries-get-openapi.md
- name: Akamai API List Designated Market Areas
  x-api-slug: akamai-api
  description: List Designated Market Areas
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/dmas
  tags: Configurations, Media, Security, Security, Dmas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securitydmas-get-openapi.md
- name: Akamai API List Regions
  x-api-slug: akamai-api
  description: List Regions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/regions
  tags: Configurations, Media, Security, Security, Regions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securityregions-get-openapi.md
- name: Akamai API List Regions per Country
  x-api-slug: akamai-api
  description: List Regions per Country
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/regions/{countryCode}
  tags: Configurations, Media, Security, Security, Regions, Countrycode
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securityregionscountrycode-get-openapi.md
- name: Akamai API List Access Control Groups
  x-api-slug: akamai-api
  description: List Access Control Groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-media-security/v1/security/acgs
  tags: Configurations, Media, Security, Security, Acgs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configmediasecurityv1securityacgs-get-openapi.md
- name: Akamai API Create a Request
  x-api-slug: akamai-api
  description: Create a Request
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-secure-provisioning-service/v1/sps-requests
  tags: Configurations, Secure, Provisioning, Service, Sps, Requests, Contract,group,after,information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsecureprovisioningservicev1spsrequests-post-openapi.md
- name: Akamai API List SPS Requests
  x-api-slug: akamai-api
  description: List SPS Requests
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-secure-provisioning-service/v1/sps-requests
  tags: Configurations, Secure, Provisioning, Service, Sps, Requests, Contract,group,after,information
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configsecureprovisioningservicev1spsrequests-get-openapi.md
- name: Akamai API Create a Secure Edge Hostname
  x-api-slug: akamai-api
  description: Create a Secure Edge Hostname
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///subscriptionId
  tags: Subscription
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/subscriptionid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/subscriptionid-post-openapi.md
- name: Akamai API List Report Packs
  x-api-slug: akamai-api
  description: List Report Packs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///name
  tags: Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/name-get-openapi.md
- name: Akamai API Get a Report Pack
  x-api-slug: akamai-api
  description: Get a Report Pack
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////security-monitor/v1/report-packs/{reportPackId}
  tags: Security, Monitor, Report, Packs, Reportpack
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/securitymonitorv1reportpacksreportpackid-get-openapi.md
- name: Akamai API List Data Stores
  x-api-slug: akamai-api
  description: List Data Stores
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////security-monitor/v1/report-packs/{reportPackId}/data-stores
  tags: Security, Monitor, Report, Packs, Reportpack, Data, Stores
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/securitymonitorv1reportpacksreportpackiddatastores-get-openapi.md
- name: Akamai API Get a Data Store
  x-api-slug: akamai-api
  description: Get a Data Store
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////security-monitor/v1/report-packs/{reportPackId}/data-stores/{dataStoreId}
  tags: Security, Monitor, Report, Packs, Reportpack, Data, Stores, Datastore
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/securitymonitorv1reportpacksreportpackiddatastoresdatastoreid-get-openapi.md
- name: Akamai API List Data Sources
  x-api-slug: akamai-api
  description: List Data Sources
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////security-monitor/v1/report-packs/{reportPackId}/data-sources
  tags: Security, Monitor, Report, Packs, Reportpack, Data, Sources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/securitymonitorv1reportpacksreportpackiddatasources-get-openapi.md
- name: Akamai API List Test Configuration Quotas
  x-api-slug: akamai-api
  description: List Test Configuration Quotas
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/test-quotas
  tags: Sla, Test, Quotas
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testquotas-get-openapi.md
- name: Akamai API Create a New Test Configuration
  x-api-slug: akamai-api
  description: Create a New Test Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests
  tags: Sla, Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1tests-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1tests-post-openapi.md
- name: Akamai API List Test Configurations
  x-api-slug: akamai-api
  description: List Test Configurations
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests
  tags: Sla, Tests, Slatests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1tests-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1tests-get-openapi.md
- name: Akamai API Delete a Test Configuration
  x-api-slug: akamai-api
  description: Delete a Test Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests/{id}
  tags: Sla, Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsid-delete-openapi.md
- name: Akamai API Update a Test Configuration
  x-api-slug: akamai-api
  description: Update a Test Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests/{id}
  tags: Sla, Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsid-put-openapi.md
- name: Akamai API Get a Test Configuration
  x-api-slug: akamai-api
  description: Get a Test Configuration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests/{id}
  tags: Sla, Tests
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsid-get-openapi.md
- name: Akamai API List Agent Groups
  x-api-slug: akamai-api
  description: List Agent Groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/agent-groups
  tags: Sla, Agent, Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1agentgroups-get-openapi.md
- name: Akamai API List Performance Reports
  x-api-slug: akamai-api
  description: List Performance Reports
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests/{slaTestId}/reports/performance
  tags: Sla, Tests, Slatest, Reports, Performance, Start,end
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsslatestidreportsperformance-get-openapi.md
- name: Akamai API List Availability Reports
  x-api-slug: akamai-api
  description: List Availability Reports
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////sla-api/v1/tests/{slaTestId}/reports/availability
  tags: Sla, Tests, Slatest, Reports, Availability, Start,end
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/slaapiv1testsslatestidreportsavailability-get-openapi.md
- name: Akamai API List Maps
  x-api-slug: akamai-api
  description: List Maps
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////siteshield/v1/maps
  tags: Siteshield, Maps
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/siteshieldv1maps-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/siteshieldv1maps-get-openapi.md
- name: Akamai API Get a Map
  x-api-slug: akamai-api
  description: Get a Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////siteshield/v1/maps/{id}
  tags: Siteshield, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/siteshieldv1mapsid-get-openapi.md
- name: Akamai API Acknowledge a Map
  x-api-slug: akamai-api
  description: Acknowledge a Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////siteshield/v1/maps/{id}/acknowledge
  tags: Siteshield, Maps, , Acknowledge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/siteshieldv1mapsidacknowledge-post-openapi.md
- name: Akamai API List Domains
  x-api-slug: akamai-api
  description: List Domains
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/
  tags: Configurations, Gtm, Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domains-get-openapi.md
- name: Akamai API Get a Domain
  x-api-slug: akamai-api
  description: Get a Domain
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}
  tags: Configurations, Gtm, Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomain-get-openapi.md
- name: Akamai API Create or Update a Domain
  x-api-slug: akamai-api
  description: Create or Update a Domain
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}
  tags: Configurations, Gtm, Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomain-put-openapi.md
- name: Akamai API List Data Centers
  x-api-slug: akamai-api
  description: List Data Centers
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/datacenters
  tags: Configurations, Gtm, Domains, Datacenters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaindatacenters-get-openapi.md
- name: Akamai API Create a Data Center
  x-api-slug: akamai-api
  description: Create a Data Center
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/datacenters
  tags: Configurations, Gtm, Domains, Datacenters
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaindatacenters-post-openapi.md
- name: Akamai API Get a Data Center
  x-api-slug: akamai-api
  description: Get a Data Center
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/datacenters/{datacenterId}
  tags: Configurations, Gtm, Domains, Datacenters, Datacenter
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaindatacentersdatacenterid-get-openapi.md
- name: Akamai API Update a Data Center
  x-api-slug: akamai-api
  description: Update a Data Center
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/datacenters/{datacenterId}
  tags: Configurations, Gtm, Domains, Datacenters, Datacenter
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaindatacentersdatacenterid-put-openapi.md
- name: Akamai API Remove a Data Center
  x-api-slug: akamai-api
  description: Remove a Data Center
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/datacenters/{datacenterId}
  tags: Configurations, Gtm, Domains, Datacenters, Datacenter
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaindatacentersdatacenterid-delete-openapi.md
- name: Akamai API List Properties
  x-api-slug: akamai-api
  description: List Properties
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/properties
  tags: Configurations, Gtm, Domains, Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainproperties-get-openapi.md
- name: Akamai API Get a Property
  x-api-slug: akamai-api
  description: Get a Property
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/properties/{propertyName}
  tags: Configurations, Gtm, Domains, Properties, Propertyname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainpropertiespropertyname-get-openapi.md
- name: Akamai API Create or Update a Property
  x-api-slug: akamai-api
  description: Create or Update a Property
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/properties/{propertyName}
  tags: Configurations, Gtm, Domains, Properties, Propertyname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainpropertiespropertyname-put-openapi.md
- name: Akamai API Remove a Property
  x-api-slug: akamai-api
  description: Remove a Property
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/properties/{propertyName}
  tags: Configurations, Gtm, Domains, Properties, Propertyname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainpropertiespropertyname-delete-openapi.md
- name: Akamai API List Resources
  x-api-slug: akamai-api
  description: List Resources
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/resources
  tags: Configurations, Gtm, Domains, Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainresources-get-openapi.md
- name: Akamai API Get a Resource
  x-api-slug: akamai-api
  description: Get a Resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/resources/{resourceName}
  tags: Configurations, Gtm, Domains, Resources, Resourcename
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainresourcesresourcename-get-openapi.md
- name: Akamai API Create or Update a Resource
  x-api-slug: akamai-api
  description: Create or Update a Resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/resources/{resourceName}
  tags: Configurations, Gtm, Domains, Resources, Resourcename
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainresourcesresourcename-put-openapi.md
- name: Akamai API Remove a Resource
  x-api-slug: akamai-api
  description: Remove a Resource
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/resources/{resourceName}
  tags: Configurations, Gtm, Domains, Resources, Resourcename
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainresourcesresourcename-delete-openapi.md
- name: Akamai API List Geographic Maps
  x-api-slug: akamai-api
  description: List Geographic Maps
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/geographic-maps
  tags: Configurations, Gtm, Domains, Geographic, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaingeographicmaps-get-openapi.md
- name: Akamai API Get a Geographic Map
  x-api-slug: akamai-api
  description: Get a Geographic Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/geographic-maps/{mapName}
  tags: Configurations, Gtm, Domains, Geographic, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaingeographicmapsmapname-get-openapi.md
- name: Akamai API Create or Update a Geographic Map
  x-api-slug: akamai-api
  description: Create or Update a Geographic Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/geographic-maps/{mapName}
  tags: Configurations, Gtm, Domains, Geographic, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaingeographicmapsmapname-put-openapi.md
- name: Akamai API Remove a Geographic Map
  x-api-slug: akamai-api
  description: Remove a Geographic Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/geographic-maps/{mapName}
  tags: Configurations, Gtm, Domains, Geographic, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaingeographicmapsmapname-delete-openapi.md
- name: Akamai API List CIDR Maps
  x-api-slug: akamai-api
  description: List CIDR Maps
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/cidr-maps
  tags: Configurations, Gtm, Domains, Cr, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaincidrmaps-get-openapi.md
- name: Akamai API Get a CIDR Map
  x-api-slug: akamai-api
  description: Get a CIDR Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/cidr-maps/{mapName}
  tags: Configurations, Gtm, Domains, Cr, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaincidrmapsmapname-get-openapi.md
- name: Akamai API Create or Update a CIDR Map
  x-api-slug: akamai-api
  description: Create or Update a CIDR Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/cidr-maps/{mapName}
  tags: Configurations, Gtm, Domains, Cr, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaincidrmapsmapname-put-openapi.md
- name: Akamai API Remove a CIDR Map
  x-api-slug: akamai-api
  description: Remove a CIDR Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/cidr-maps/{mapName}
  tags: Configurations, Gtm, Domains, Cr, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomaincidrmapsmapname-delete-openapi.md
- name: Akamai API Get an AS Map
  x-api-slug: akamai-api
  description: Get an AS Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/as-maps/{mapName}
  tags: Configurations, Gtm, Domains, As, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainasmapsmapname-get-openapi.md
- name: Akamai API Create or Update an AS Map
  x-api-slug: akamai-api
  description: Create or Update an AS Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/as-maps/{mapName}
  tags: Configurations, Gtm, Domains, As, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainasmapsmapname-put-openapi.md
- name: Akamai API Remove an AS Map
  x-api-slug: akamai-api
  description: Remove an AS Map
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/as-maps/{mapName}
  tags: Configurations, Gtm, Domains, As, Maps
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainasmapsmapname-delete-openapi.md
- name: Akamai API Get Current Status
  x-api-slug: akamai-api
  description: Get Current Status
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////config-gtm/v1/domains/{domain}/status/current
  tags: Configurations, Gtm, Domains, Status, Current
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/configgtmv1domainsdomainstatuscurrent-get-openapi.md
- name: Akamai API Submit Load Data
  x-api-slug: akamai-api
  description: Submit Load Data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///region
  tags: Region
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/region-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/region-post-openapi.md
- name: Akamai API Fetch Load Data
  x-api-slug: akamai-api
  description: Fetch Load Data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///connections
  tags: Connections
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/connections-get-openapi.md
- name: Akamai API List Groups
  x-api-slug: akamai-api
  description: List Groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups
  tags: User, Admin, Accounts, Account, Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroups-get-openapi.md
- name: Akamai API List Nested Groups
  x-api-slug: akamai-api
  description: List Nested Groups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}/groups
  tags: User, Admin, Accounts, Account, Groups, Group, Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupidgroups-get-openapi.md
- name: Akamai API Get a Group
  x-api-slug: akamai-api
  description: Get a Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}
  tags: User, Admin, Accounts, Account, Groups, Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupid-get-openapi.md
- name: Akamai API Modify a Group
  x-api-slug: akamai-api
  description: Modify a Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}
  tags: User, Admin, Accounts, Account, Groups, Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupid-put-openapi.md
- name: Akamai API Create a New Group
  x-api-slug: akamai-api
  description: Create a New Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}
  tags: User, Admin, Accounts, Account, Groups, Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupid-post-openapi.md
- name: Akamai API Remove a Group
  x-api-slug: akamai-api
  description: Remove a Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}
  tags: User, Admin, Accounts, Account, Groups, Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupid-delete-openapi.md
- name: Akamai API Move a Group within Another Group
  x-api-slug: akamai-api
  description: Move a Group within Another Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/move/group/{groupId}/groups/{destinationGroupId}/
  tags: User, Admin, Accounts, Account, Move, Group, Group, Groups, Destinationgroup
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidmovegroupgroupidgroupsdestinationgroupid-post-openapi.md
- name: Akamai API List a Group&#8217;s Properties
  x-api-slug: akamai-api
  description: List a Group&#8217;s Properties
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}/properties
  tags: User, Admin, Accounts, Account, Groups, Group, Properties
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupidproperties-get-openapi.md
- name: Akamai API Get a Property
  x-api-slug: akamai-api
  description: Get a Property
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}/properties/{assetId}
  tags: User, Admin, Accounts, Account, Groups, Group, Properties, Asset
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupidpropertiesassetid-get-openapi.md
- name: Akamai API List a Property&#8217;s Users
  x-api-slug: akamai-api
  description: List a Property&#8217;s Users
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}/properties/{assetId}/users
  tags: User, Admin, Accounts, Account, Groups, Group, Properties, Asset, Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupidpropertiesassetidusers-get-openapi.md
- name: Akamai API List a User&#8217;s Property Exceptions
  x-api-slug: akamai-api
  description: List a User&#8217;s Property Exceptions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}/users/{contactId}/propertyExceptions
  tags: User, Admin, Accounts, Account, Groups, Group, Users, Contact, Propertyexceptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupiduserscontactidpropertyexceptions-get-openapi.md
- name: Akamai API Modify a User&#8217;s Set of Property Exceptions
  x-api-slug: akamai-api
  description: Modify a User&#8217;s Set of Property Exceptions
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}/users/{contactId}/propertyExceptions
  tags: User, Admin, Accounts, Account, Groups, Group, Users, Contact, Propertyexceptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupiduserscontactidpropertyexceptions-put-openapi.md
- name: Akamai API Modify a Property Exception
  x-api-slug: akamai-api
  description: Modify a Property Exception
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/groups/{groupId}/users/{contactId}/propertyExceptions/{propertyId}
  tags: User, Admin, Accounts, Account, Groups, Group, Users, Contact, Propertyexceptions,
    Property
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidgroupsgroupiduserscontactidpropertyexceptionspropertyid-put-openapi.md
- name: Akamai API Move a Property to Another Group
  x-api-slug: akamai-api
  description: Move a Property to Another Group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/properties/{propertyId}
  tags: User, Admin, Accounts, Account, Properties, Property
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidpropertiespropertyid-post-openapi.md
- name: Akamai API List Roles
  x-api-slug: akamai-api
  description: List Roles
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/roles
  tags: User, Admin, Accounts, Account, Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidroles-get-openapi.md
- name: Akamai API Create a New Role
  x-api-slug: akamai-api
  description: Create a New Role
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/roles
  tags: User, Admin, Accounts, Account, Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidroles-post-openapi.md
- name: Akamai API Modify a Role
  x-api-slug: akamai-api
  description: Modify a Role
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/roles
  tags: User, Admin, Accounts, Account, Roles
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidroles-put-openapi.md
- name: Akamai API Get a Role
  x-api-slug: akamai-api
  description: Get a Role
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/roles/{roleId}
  tags: User, Admin, Accounts, Account, Roles, Role
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidrolesroleid-get-openapi.md
- name: Akamai API Remove a Role
  x-api-slug: akamai-api
  description: Remove a Role
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/roles/{roleId}
  tags: User, Admin, Accounts, Account, Roles, Role
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidrolesroleid-delete-openapi.md
- name: Akamai API List Grantable Roles
  x-api-slug: akamai-api
  description: List Grantable Roles
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/roles/grantable
  tags: User, Admin, Accounts, Account, Roles, Grantable
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidrolesgrantable-get-openapi.md
- name: Akamai API Create a New User
  x-api-slug: akamai-api
  description: Create a New User
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/users
  tags: User, Admin, Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1users-post-openapi.md
- name: Akamai API List Users
  x-api-slug: akamai-api
  description: List Users
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/accounts/{accountId}/users
  tags: User, Admin, Accounts, Account, Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1accountsaccountidusers-get-openapi.md
- name: Akamai API List a Group&#8217;s Users
  x-api-slug: akamai-api
  description: List a Group&#8217;s Users
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/users
  tags: User, Admin, Users, Group,actions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1users-get-openapi.md
- name: Akamai API Modify a User
  x-api-slug: akamai-api
  description: Modify a User
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/users/{contactId}
  tags: User, Admin, Users, Contact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1userscontactid-put-openapi.md
- name: Akamai API Remove a User
  x-api-slug: akamai-api
  description: Remove a User
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com////user-admin/v1/users/{contactId}
  tags: User, Admin, Users, Contact
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/useradminv1userscontactid-delete-openapi.md
- name: Akamai API Reset a User&#8217;s Password
  x-api-slug: akamai-api
  description: Reset a User&#8217;s Password
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com///send_email
  tags: Send, Email
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/send-email-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/send-email-put-openapi.md
- name: Akamai API
  x-api-slug: akamai-api
  description: Akamai Technologies, Inc. is a content delivery network or CDN and
    cloud services provider headquartered in Cambridge, Massachusetts, in the United
    States. Akamais content delivery network is one of the worlds largest distributed
    computing platforms, responsible for serving between 15 and 30 percent of all
    web traffic. The company operates a network of servers around the world and rents
    capacity on these servers to customers who want their websites to work faster
    by distributing content from locations close to the user
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Akamai_Technologies,_Inc._Logo.png
  humanURL: https://akamai.com
  baseURL: https://developer.akamai.com//
  tags: Akamai
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/akamai/master/_listings/akamai/openapi.md
x-common:
- type: x-base
  url: https://api.ccu.akamai.com
- type: x-blog
  url: https://blogs.akamai.com
- type: x-blog-rss
  url: http://blogs.akamai.com/feeds.html
- type: x-crunchbase
  url: http://www.crunchbase.com/company/akamai-technologies
- type: x-developer
  url: https://developer.akamai.com/
- type: x-email
  url: open-developer@akamai.com
- type: x-github
  url: https://github.com/akamai
- type: x-twitter
  url: https://twitter.com/Akamai
- type: x-website
  url: https://akamai.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---