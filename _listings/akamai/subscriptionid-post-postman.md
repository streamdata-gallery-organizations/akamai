{
  "info": {
    "name": "Akamai API Create a Secure Edge Hostname",
    "_postman_id": "ca144134-ec69-4c00-a9c8-7ee2a44600c7",
    "description": "Create a Secure Edge Hostname",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "6ee5f57a-42df-4537-9c3e-29ca3262221a",
          "name": "galaxyv1customersincludedeleteddebug",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/customers?debug=debug&includeDeleted=includeDeleted",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Customers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "faf7f169-30d9-4bdf-9268-76b0219acfa8"
            }
          ]
        },
        {
          "id": "4f70b759-72e8-4797-9ab1-9ee496227207",
          "name": "galaxyv1customers",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/customers?akamaiCustomerId=akamaiCustomerId&debug=debug",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91ee2598-1ba8-426a-9795-5356c835d4fe"
            }
          ]
        },
        {
          "id": "ca471856-a6d7-4f9b-9058-53ee27d651e2",
          "name": "galaxyv1customersakamaicustomerid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5a1789b-547a-466a-9a89-16ecd4c7189a"
            }
          ]
        },
        {
          "id": "d2d0d44f-a3f9-4d8e-b72e-9d258e50abdf",
          "name": "galaxyv1customersakamaicustomerid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ced9eed0-c744-4aa8-ba13-9060deca290d"
            }
          ]
        },
        {
          "id": "1b8ae13e-b652-43d6-bca6-c3d6cf86ebac",
          "name": "galaxyv1customersakamaicustomeridopdeactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId/op/deactivate"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivate a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6047c9c7-7c25-4b11-abd4-80310db8dd39"
            }
          ]
        },
        {
          "id": "9060cd50-4f28-4d1f-8664-5ea887cb8e4f",
          "name": "galaxyv1customersakamaicustomeridopreactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:akamaiCustomerId/op/reactivate"
              ],
              "variable": [
                {
                  "id": "akamaiCustomerId",
                  "value": "akamaiCustomerId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Reactivate a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa6c4f56-1b59-46a9-bede-cc03e1ab9750"
            }
          ]
        },
        {
          "id": "0bf9224f-e7f1-48fc-be50-030a3ac11ed2",
          "name": "galaxyv1clientsincludedeleteddebugself",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/clients?debug=debug&includeDeleted=includeDeleted&self=self",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Clients"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e1238c0-e29e-40dc-8faa-debfc009c2f4"
            }
          ]
        },
        {
          "id": "970f1805-b212-47af-9e31-977ce2d9196a",
          "name": "galaxyv1clients",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/clients?clientId=clientId&debug=debug",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee42432e-6479-47eb-b444-f526477c4d60"
            }
          ]
        },
        {
          "id": "6def4311-63e6-4b45-beb6-72a55bb09675",
          "name": "galaxyv1clientsclientid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/clients/:clientId"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86306292-9261-4889-bdb8-1d14e10966ea"
            }
          ]
        },
        {
          "id": "cb5feab5-29d6-4763-b774-092ba6024d65",
          "name": "galaxyv1clientsclientid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/clients/:clientId"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "750a7049-8f07-4f39-8a30-5138e5d00969"
            }
          ]
        },
        {
          "id": "dd41f845-41f9-44d9-8f1c-32fe2b31de6a",
          "name": "galaxyv1customersclientidopdeactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:clientId/op/deactivate"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivate a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b88c7020-0b91-4f1b-8f5a-de11aa0d9525"
            }
          ]
        },
        {
          "id": "2361ef32-db59-42f6-953b-1772aaeded20",
          "name": "galaxyv1customersclientidopreactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/customers/:clientId/op/reactivate"
              ],
              "variable": [
                {
                  "id": "clientId",
                  "value": "clientId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Reactivate a Client"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "592a1dba-9319-4617-a90f-9dde8ea49591"
            }
          ]
        },
        {
          "id": "c198c4b8-4b00-440c-b58a-fa6c8cf3d7f5",
          "name": "galaxyv1client-groupsincludedeleteddebugself",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/client_groups?debug=debug&includeDeleted=includeDeleted",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Client Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "541cdc4e-887d-4fdb-a627-c0c617c44c9a"
            }
          ]
        },
        {
          "id": "2db58bad-8297-4f06-8ea6-5975d0aee14d",
          "name": "galaxyv1client-groups",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/client_groups?debug=debug&includeDeleted=includeDeleted",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Associate Multiple Activation Files for a DPC"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f802f7e-75e1-41e0-9978-a2f681feb984"
            }
          ]
        },
        {
          "id": "99252d6a-0361-4cc0-b172-e2a55699ac54",
          "name": "galaxyv1devicesdeviceiddebug",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "query": [
                {
                  "key": "debug",
                  "value": "debug",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfa98d7f-62ed-450c-9cf7-5abf73c46a04"
            }
          ]
        },
        {
          "id": "1a317f58-7ee5-4cdb-ade0-c1e97119fd4a",
          "name": "galaxyv1devicesdeviceid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bdab7b53-bd67-4cec-bbb7-b3edebfd877a"
            }
          ]
        },
        {
          "id": "f2894d9a-5c62-4d84-b9cb-98ea56d745a3",
          "name": "galaxyv1devicesdeviceid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4700cae-300f-4303-8cc8-4493c3e876e8"
            }
          ]
        },
        {
          "id": "db576866-3dcb-4360-a75d-7ea57cb55dc5",
          "name": "galaxyv1devicesdeviceid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f2b043c-e61b-48ae-ae7b-bfa814e4f93f"
            }
          ]
        },
        {
          "id": "25c47a62-32b7-4d70-978c-06a0b68ee973",
          "name": "galaxyv1devicesdeviceidopdeactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId/op/deactivate"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Deactivate a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d39cb3a-989d-4bdd-91e5-423217513c3d"
            }
          ]
        },
        {
          "id": "f72f6832-9fcb-4ca7-a980-c98a37552f5d",
          "name": "galaxyv1devicesdeviceidopreactivate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "galaxy/v1/devices/:deviceId/op/reactivate"
              ],
              "variable": [
                {
                  "id": "deviceId",
                  "value": "deviceId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Reactivate a Device"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be924342-8178-4378-a74c-2507788d6dc2"
            }
          ]
        },
        {
          "id": "d4ffd073-ec86-46f3-86a1-477f35673493",
          "name": "galaxyv1build",
          "request": {
            "url": "http://developer.akamai.com/galaxy/v1/build",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Build Information"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bc81d057-ebf1-4741-9237-abffb4b9534d"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "7605bb93-a6db-4342-a547-ef7061c1cbe1",
          "name": "billingcenterapiv2contractscontractidproductsproductidstatisticsyearmonthfromyearfrommonthtoyeartomo",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/contracts/:contractId/products/:productId/statistics"
              ],
              "query": [
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "contractId",
                  "value": "contractId",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Statistics per Contract"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cf92a40-1f0c-45a7-a867-15c0c9116206"
            }
          ]
        },
        {
          "id": "2e0f3899-ddb2-429b-806d-6c74750e707c",
          "name": "billingcenterapiv2contractscontractidproductsproductidmeasuresyearmonthfromyearfrommonthtoyeartomont",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/contracts/:contractId/products/:productId/measures"
              ],
              "query": [
                {
                  "key": "billingDayOnly",
                  "value": "billingDayOnly",
                  "disabled": false
                },
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "statisticName",
                  "value": "statisticName",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "contractId",
                  "value": "contractId",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Usage per Contract"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4ee4e9f-6673-4d3c-a57c-7a3519d562be"
            }
          ]
        },
        {
          "id": "91abba74-ce5e-4f53-bca3-bf8db3063279",
          "name": "billingcenterapiv2reportinggroupsreportinggroupidproductsproductidstatisticsyearmonthfromyearfrommon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/reporting-groups/:reportingGroupId/products/:productId/statistics"
              ],
              "query": [
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                },
                {
                  "id": "reportingGroupId",
                  "value": "reportingGroupId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Statistics per Reporting Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e5ffa0c-52a7-474b-b428-4c40616ebf9c"
            }
          ]
        },
        {
          "id": "6f2a0a25-bc0b-4407-bf2e-91ccf6dcd29e",
          "name": "billingcenterapiv2reportinggroupsreportinggroupidproductsproductidmeasuresyearmonthfromyearfrommonth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "billing-center-api/v2/reporting-groups/:reportingGroupId/products/:productId/measures"
              ],
              "query": [
                {
                  "key": "billingDayOnly",
                  "value": "billingDayOnly",
                  "disabled": false
                },
                {
                  "key": "fromMonth",
                  "value": "fromMonth",
                  "disabled": false
                },
                {
                  "key": "fromYear",
                  "value": "fromYear",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "statisticName",
                  "value": "statisticName",
                  "disabled": false
                },
                {
                  "key": "toMonth",
                  "value": "toMonth",
                  "disabled": false
                },
                {
                  "key": "toYear",
                  "value": "toYear",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                },
                {
                  "id": "reportingGroupId",
                  "value": "reportingGroupId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Usage per Reporting Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "414d58e0-d0ee-4d6b-80cb-b0835afaf5f9"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "378c877e-8538-4813-be32-033c06b2777f",
          "name": "casesv1category",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/:category"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "category",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cases per Category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2518546-8f3d-4295-86aa-212d783624f8"
            }
          ]
        },
        {
          "id": "44401448-ac52-443f-9700-b1e96a3487ea",
          "name": "casesv1category",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/:category"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "category",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa2ca490-f6d1-4bd0-8793-74c0aef99075"
            }
          ]
        },
        {
          "id": "08d16a86-c8e5-494c-a2f2-e4a873f596fa",
          "name": "casesv1ps",
          "request": {
            "url": "http://developer.akamai.com/cases/v1/PS",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Professional Services Cases"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "488f8bc9-46b9-4568-a225-90823496fa7d"
            }
          ]
        },
        {
          "id": "cfd980b2-a40b-4fd8-b933-c4206c393f12",
          "name": "casesv1ps",
          "request": {
            "url": "http://developer.akamai.com/cases/v1/PS",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Professional Services Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ebf214b6-8fe3-4982-8406-963075893095"
            }
          ]
        },
        {
          "id": "8f0f539d-6b9f-4a1e-bc03-c4017ba7ceb2",
          "name": "casesv1portaluserstatustypecategory",
          "request": {
            "url": "http://developer.akamai.com/cases/v1/portal-user?category=category&status=status&type=type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cases"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f5f50829-82aa-4c7f-9709-c083c607e041"
            }
          ]
        },
        {
          "id": "32efc9c2-74c8-4108-b805-1146c7583331",
          "name": "casesv1portalusercasecaseid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36100e0f-ba23-41a1-bd9e-64a78532da37"
            }
          ]
        },
        {
          "id": "c8eef054-084a-4a39-9f85-cd0359ad37f3",
          "name": "casesv1portalusercasecaseidnotes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId/notes"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Comment on a Case"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2d67326-a9d6-4785-b3b2-dbffe1cd46c2"
            }
          ]
        },
        {
          "id": "56091543-2fe1-4aa4-947f-25d8adb4512a",
          "name": "casesv1portalusercasecaseidfiles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId/files"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Upload a File Attachment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b127c412-b464-472c-82e2-c6c3a19a849d"
            }
          ]
        },
        {
          "id": "81a98669-a394-4e4c-bd87-ff14d17bdf38",
          "name": "casesv1portalusercasecaseidrequestclose",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cases/v1/portal-user/case/:caseId/request-close"
              ],
              "variable": [
                {
                  "id": "caseId",
                  "value": "caseId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Close a Request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa661eb5-0e21-4569-8082-fb91b3803b6a"
            }
          ]
        }
      ]
    },
    {
      "name": "Ccu",
      "item": [
        {
          "id": "41c6fe33-8707-4f40-8997-97613bd6cd94",
          "name": "ccuv3invalidateurlnetwork",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v3/invalidate/url/:network"
              ],
              "variable": [
                {
                  "id": "network",
                  "value": "network",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Invalidate by URL"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54b46ce4-8111-47b8-94ec-f9321206993c"
            }
          ]
        },
        {
          "id": "7e0adc70-b5d9-4d7f-bbe1-89ff02f92387",
          "name": "ccuv3deleteurlnetwork",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v3/delete/url/:network"
              ],
              "variable": [
                {
                  "id": "network",
                  "value": "network",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Delete by URL"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c88a5d2-cf02-41ac-9b98-d849f4a31a67"
            }
          ]
        },
        {
          "id": "d22b6c1d-f482-4656-a726-a281bea07073",
          "name": "ccuv2queuesqueuename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v2/queues/:queueName"
              ],
              "variable": [
                {
                  "id": "queueName",
                  "value": "queueName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Current Queue Size"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e011a06f-8bd9-40c2-8f52-089aff4af917"
            }
          ]
        },
        {
          "id": "06b87953-0ab0-4bac-8a07-c04090c7f7c8",
          "name": "ccuv2queuesqueuename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v2/queues/:queueName"
              ],
              "variable": [
                {
                  "id": "queueName",
                  "value": "queueName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0589735-aea7-4a6e-ac0d-4cda1a4e7327"
            }
          ]
        },
        {
          "id": "62f6182d-befa-47d0-a427-b81149d9e9ce",
          "name": "ccuv2purgespurgeid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "ccu/v2/purges/:purgeId"
              ],
              "variable": [
                {
                  "id": "purgeId",
                  "value": "purgeId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Purge Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9d8c3456-6ef5-4c14-beec-8f3b309c0ac8"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlet",
      "item": [
        {
          "id": "32aaadfb-af7d-4b01-a202-2dea1ce1abdd",
          "name": "cloudletid",
          "request": {
            "url": "http://developer.akamai.com/cloudletId?cloudletId=cloudletId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cloudlets"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bad4fce6-b8c5-4f65-af16-988050f3bc78"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlets",
      "item": [
        {
          "id": "8470efa8-e233-4f86-8d44-aa2964db29e8",
          "name": "cloudletsapiv2groupinfo",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/group-info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f161190-ce09-4393-89aa-013cbada8bb3"
            }
          ]
        },
        {
          "id": "723213a1-443b-4939-9417-5caa649f1446",
          "name": "cloudletsapiv2groupinfogroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/group-info/:groupId"
              ],
              "variable": [
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "494611aa-eefe-4da3-b8b1-61cd8fedbd49"
            }
          ]
        },
        {
          "id": "6f21494d-7b52-419e-95da-44b06742cadf",
          "name": "cloudletsapiv2policiesgidincludedeletedcloudletid",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/policies?cloudletId=cloudletId&gid=gid&includeDeleted=includeDeleted",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11797eef-b6a9-4a07-b941-322a2d17da0a"
            }
          ]
        },
        {
          "id": "d2e645e7-b874-42db-8190-d8cfa5559e8d",
          "name": "cloudletsapiv2policiesclonepolicyidversion",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/policies?clonePolicyId=clonePolicyId&version=version",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1f67d7c-801b-4e21-a639-d6ae9e407632"
            }
          ]
        },
        {
          "id": "9334e839-4515-439a-af19-cd523aa69541",
          "name": "cloudletsapiv2policiespolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be8fc2c3-7a16-4142-8e61-79eed60652bb"
            }
          ]
        },
        {
          "id": "fb24dbca-4e5d-440e-aeec-48bad9db481f",
          "name": "cloudletsapiv2policiespolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "905cb171-ab6e-40f0-a1df-948a0bc9c1a3"
            }
          ]
        },
        {
          "id": "30be6737-0777-4bb3-b4a2-be2613820cec",
          "name": "cloudletsapiv2policiespolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ff540db-7b56-4d02-a8e3-6a042cb220f8"
            }
          ]
        },
        {
          "id": "dbe9a7e7-2ddf-49ad-876b-c0283f44172f",
          "name": "cloudletsapiv2policiespolicyidversionsincluderulesmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions"
              ],
              "query": [
                {
                  "key": "includeRules",
                  "value": "includeRules",
                  "disabled": false
                },
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policy Versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "121353fd-ede0-4f60-ac82-8d0128f47ed9"
            }
          ]
        },
        {
          "id": "29be15ef-cad7-43bb-b475-98a1e2550bef",
          "name": "cloudletsapiv2policiespolicyidversionsmatchruleformatcloneversion",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions"
              ],
              "query": [
                {
                  "key": "cloneVersion",
                  "value": "cloneVersion",
                  "disabled": false
                },
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb9d2751-84a9-46cb-a32f-54e32ef99978"
            }
          ]
        },
        {
          "id": "66501913-1154-4b7a-be1c-2850de4716b8",
          "name": "cloudletsapiv2policiespolicyidversionsversionomitrulesmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version"
              ],
              "query": [
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                },
                {
                  "key": "omitRules",
                  "value": "omitRules",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cef4f173-54e8-4d80-9604-4b04acea913c"
            }
          ]
        },
        {
          "id": "42cd4f69-6d0b-40a0-94af-fae61f5eb86f",
          "name": "cloudletsapiv2policiespolicyidversionsversionmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version"
              ],
              "query": [
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d62044f3-8945-4635-9b0c-b14569a862e2"
            }
          ]
        },
        {
          "id": "679622fd-8d3c-4514-9179-ffa8cc74d88a",
          "name": "cloudletsapiv2policiespolicyidversionsversionomitrulesmatchruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version"
              ],
              "query": [
                {
                  "key": "matchRuleFormat",
                  "value": "matchRuleFormat",
                  "disabled": false
                },
                {
                  "key": "omitRules",
                  "value": "omitRules",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c222863-b5fd-42af-8e2d-54bf7f1f6a00"
            }
          ]
        },
        {
          "id": "701a4d26-cd33-49ce-b636-49d03f6fd026",
          "name": "cloudletsapiv2policiespolicyidversionsversionrulesindex",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version/rules"
              ],
              "query": [
                {
                  "key": "index",
                  "value": "index",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add a Version Rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5bc14b43-c13a-4e97-9cab-b822a968f0db"
            }
          ]
        },
        {
          "id": "365443a5-1b42-487c-9880-8ff2882da344",
          "name": "cloudletsapiv2policiespolicyidversionsversionrulesakaruleid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version/rules/:akaRuleId"
              ],
              "variable": [
                {
                  "id": "akaRuleId",
                  "value": "akaRuleId",
                  "type": "string"
                },
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Version Rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e12ece3-8ce7-457a-845a-50ac5aa6f120"
            }
          ]
        },
        {
          "id": "313f0526-89de-4b98-8866-c33b49a0d7bb",
          "name": "cloudletsapiv2policiespolicyidversionsversionrulesakaruleid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version/rules/:akaRuleId"
              ],
              "variable": [
                {
                  "id": "akaRuleId",
                  "value": "akaRuleId",
                  "type": "string"
                },
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Version Rule"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27d71578-0ddb-43b7-9074-e78fe2acc22a"
            }
          ]
        },
        {
          "id": "d50949ad-a7f4-49c1-9de9-8beda50b0e88",
          "name": "cloudletsapiv2properties",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/properties",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Associated Properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a310d080-9402-4d9b-a887-d36e3f21bedb"
            }
          ]
        },
        {
          "id": "48b4979a-d699-4f9f-b616-c8a2483798dc",
          "name": "cloudletsapiv2policyidproperties",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/:policyId/properties"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Associated Properties for a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0abde26b-8d92-4a5b-94da-e19b806af463"
            }
          ]
        },
        {
          "id": "bd568ad2-3cf6-489e-891a-ee9e1cd656ed",
          "name": "cloudletsapiv2originstype",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/origins?type=type",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cloudlets Origins"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f90a18cb-5931-4922-8998-7abdbeb11b4b"
            }
          ]
        },
        {
          "id": "170f202d-93b5-4c17-add7-f179f9e5d081",
          "name": "cloudletsapiv2originsoriginid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Cloudlets Origin"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d983b61-d134-46d7-a275-5e4a38da0bfd"
            }
          ]
        },
        {
          "id": "8aee895a-51cc-4893-ad10-51a1076cbfab",
          "name": "cloudletsapiv2originsoriginid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Cloudlets Origin"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "913daeec-d6aa-4539-911b-c6d43d688e43"
            }
          ]
        },
        {
          "id": "19843cc8-b8c6-4e23-828a-a9895ae05e94",
          "name": "cloudletsapiv2originsoriginidversions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/versions"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Cloudlets Origin Versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0d5016c8-2999-4aef-96b9-c9fdb8914781"
            }
          ]
        },
        {
          "id": "02053cfb-9297-4a3a-aad7-2d3c78674422",
          "name": "cloudletsapiv2originsoriginidversions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/versions"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Cloudlets Origin Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad10588e-1d7d-4b40-a9e6-bd269a3d9607"
            }
          ]
        },
        {
          "id": "7ddc6beb-4c1b-4f17-854b-99813ad445b9",
          "name": "cloudletsapiv2originsoriginidversionsversionvalidate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/versions/:version"
              ],
              "query": [
                {
                  "key": "validate",
                  "value": "validate",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Cloudlets Origin Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "848331ee-84eb-408a-95c1-80b570b8e9df"
            }
          ]
        },
        {
          "id": "6fd16bb3-932e-4434-adc1-eb15332bbb48",
          "name": "cloudletsapiv2originsoriginidversionsversionvalidate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/versions/:version"
              ],
              "query": [
                {
                  "key": "validate",
                  "value": "validate",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Cloudlets Origin Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30809ed4-5082-4140-ae8a-9f5607e5ed58"
            }
          ]
        },
        {
          "id": "7d2b6d2b-eb1d-48dd-94cf-7d30b4b45a8b",
          "name": "cloudletsapiv2originscurrentactivations",
          "request": {
            "url": "http://developer.akamai.com/cloudlets/api/v2/origins/currentActivations",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Current Cloudlets Origin Activations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60344701-adc3-48a8-9b96-f9bc4ed7b36f"
            }
          ]
        },
        {
          "id": "4aacae7b-e2fe-4ebc-a5b6-ae85551acc17",
          "name": "cloudletsapiv2originsoriginidactivations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/activations"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Activations for a Cloudlets Origin"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60519b83-ae5d-48d0-96ef-750bae0ead5c"
            }
          ]
        },
        {
          "id": "cae728b8-a93f-4697-b449-c666fa2916a5",
          "name": "cloudletsapiv2originsoriginidactivations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/origins/:originId/activations"
              ],
              "variable": [
                {
                  "id": "originId",
                  "value": "originId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Activate a Cloudlets Origin Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3864046f-7e73-42dc-be3c-3ca09b8440a4"
            }
          ]
        },
        {
          "id": "c47d772f-b7a0-495e-a225-31b2f7d16dd2",
          "name": "cloudletsapiv2policiespolicyidactivationsnetworkpropertyname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/activations"
              ],
              "query": [
                {
                  "key": "network",
                  "value": "network",
                  "disabled": false
                },
                {
                  "key": "propertyName",
                  "value": "propertyName",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policy Activations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "535457ee-bfb4-400e-8ccd-028b14c29704"
            }
          ]
        },
        {
          "id": "c8f1728f-87fd-4f11-a7b0-5d987cfecd27",
          "name": "cloudletsapiv2policiespolicyidversionsversionactivations",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/policies/:policyId/versions/:version/activations"
              ],
              "variable": [
                {
                  "id": "policyId",
                  "value": "policyId",
                  "type": "string"
                },
                {
                  "id": "version",
                  "value": "version",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Activate a Policy Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7968227c-3cb9-44cf-bd14-0b3fd8318205"
            }
          ]
        },
        {
          "id": "c5beb011-307d-4fb5-96ce-fa36683ccc3a",
          "name": "cloudletsapiv2schemasschemaname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cloudlets/api/v2/schemas/:schemaName"
              ],
              "variable": [
                {
                  "id": "schemaName",
                  "value": "schemaName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Schema"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b95497fe-e696-42b5-a838-59cd7fd95d3d"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudletcode",
      "item": [
        {
          "id": "f380c4a4-82c5-4a4b-8b58-8ae230a7cd68",
          "name": "cloudletcode",
          "request": {
            "url": "http://developer.akamai.com/cloudletCode?cloudletType=cloudletType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Schemas per Cloudlet"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ee825b5d-9816-4171-8c63-b079acd3ba44"
            }
          ]
        }
      ]
    },
    {
      "name": "Cps",
      "item": [
        {
          "id": "5ecae392-4a21-4c88-b7dc-e76be2bb8485",
          "name": "cpsv2enrollmentscontractid",
          "request": {
            "url": "http://developer.akamai.com/cps/v2/enrollments?contractId=contractId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Enrollments"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "083b38da-7e2e-4d04-ae30-30f8f4870e36"
            }
          ]
        },
        {
          "id": "7ebb0829-075a-4a0a-9a5b-75d50d9d526e",
          "name": "cpsv2enrollmentscontractid",
          "request": {
            "url": "http://developer.akamai.com/cps/v2/enrollments?contractId=contractId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create an Enrollment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f326ef20-6242-4f13-9847-6208c64b295f"
            }
          ]
        },
        {
          "id": "071edcbf-5cd1-41a4-b65d-b9e6b193e102",
          "name": "cpsv2enrollmentsenrollmentid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cps/v2/enrollments/:enrollmentId"
              ],
              "variable": [
                {
                  "id": "enrollmentId",
                  "value": "enrollmentId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Enrollment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cafe3ef6-7f32-437d-a752-a1359d821cfa"
            }
          ]
        },
        {
          "id": "6dfcd7c9-13db-48d9-9cde-55799e715a00",
          "name": "cpsv2enrollmentsenrollmentiddeploynotbeforedeploynotafterallowcancelpendingchanges",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cps/v2/enrollments/:enrollmentId"
              ],
              "query": [
                {
                  "key": "allow-cancel-pending-changes",
                  "value": "allow-cancel-pending-changes",
                  "disabled": false
                },
                {
                  "key": "deploy-not-after",
                  "value": "deploy-not-after",
                  "disabled": false
                },
                {
                  "key": "deploy-not-before",
                  "value": "deploy-not-before",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "enrollmentId",
                  "value": "enrollmentId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update an Enrollment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "937a0f2b-a3db-4b89-9f3b-dff06bf7421a"
            }
          ]
        },
        {
          "id": "bfb262a1-d2a6-45bb-8c9e-c29309aad0c9",
          "name": "cpsv2enrollmentsenrollmentiddeploynotbeforedeploynotafterallowcancelpendingchanges",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cps/v2/enrollments/:enrollmentId"
              ],
              "query": [
                {
                  "key": "allow-cancel-pending-changes",
                  "value": "allow-cancel-pending-changes",
                  "disabled": false
                },
                {
                  "key": "deploy-not-after",
                  "value": "deploy-not-after",
                  "disabled": false
                },
                {
                  "key": "deploy-not-before",
                  "value": "deploy-not-before",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "enrollmentId",
                  "value": "enrollmentId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete an Enrollment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcb87daa-6384-4a50-a6de-e5692365391a"
            }
          ]
        },
        {
          "id": "0b767a93-c8f6-4cd4-8598-d923aa0e24db",
          "name": "cpsv2enrollmentsenrollmentidchangeschangeid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cps/v2/enrollments/:enrollmentId/changes/:changeId"
              ],
              "variable": [
                {
                  "id": "changeId",
                  "value": "changeId",
                  "type": "string"
                },
                {
                  "id": "enrollmentId",
                  "value": "enrollmentId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Change Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6254e657-484b-4f9d-bd09-1c6d9671fe19"
            }
          ]
        },
        {
          "id": "0815d7c6-3112-45a5-a61b-b15f20bd602d",
          "name": "cpsv2enrollmentsenrollmentidchangeschangeid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cps/v2/enrollments/:enrollmentId/changes/:changeId"
              ],
              "variable": [
                {
                  "id": "changeId",
                  "value": "changeId",
                  "type": "string"
                },
                {
                  "id": "enrollmentId",
                  "value": "enrollmentId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Cancel a Change"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "feb3ce69-4122-4e3d-99ef-200fe2c94f86"
            }
          ]
        },
        {
          "id": "484d91ca-676b-42e0-9a65-47a91d507def",
          "name": "cpsv2enrollmentsenrollmentiddeploymentsproduction",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "cps/v2/enrollments/:enrollmentId/deployments/production"
              ],
              "variable": [
                {
                  "id": "enrollmentId",
                  "value": "enrollmentId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Certificate"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6901efc6-c039-4fe5-b507-54c5c655e16d"
            }
          ]
        }
      ]
    },
    {
      "name": "Information",
      "item": [
        {
          "id": "36209edb-8b71-408e-a7de-2b15d5ef444b",
          "name": "info",
          "request": {
            "url": "http://developer.akamai.com/info?changeId=changeId&enrollmentId=enrollmentId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Confirm a Change"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c697fd75-f290-41f0-840b-fe034769f573"
            }
          ]
        }
      ]
    },
    {
      "name": "Update",
      "item": [
        {
          "id": "65e00188-3f41-45bb-ad45-7e33231dc1f8",
          "name": "update",
          "request": {
            "url": "http://developer.akamai.com/update?changeId=changeId&enrollmentId=enrollmentId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Submit a Change"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e62ab47f-1b62-4bc5-ac28-47d973b80bc8"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "697ed36d-8a80-42aa-8c79-3c35741a2f02",
          "name": "cpsv2sample8211500",
          "request": {
            "url": "http://developer.akamai.com/cps/v2/sample&#8211;500",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Sample 500 Response"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09b1361f-8cae-4389-970d-733d8126821c"
            }
          ]
        },
        {
          "id": "66b648f9-6873-4a1f-acd3-ecad6b6ef620",
          "name": "cpsv2sample8211404",
          "request": {
            "url": "http://developer.akamai.com/cps/v2/sample&#8211;404",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Sample 404 Response"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e9da9b0-e93a-41e6-8499-94b2a55a176f"
            }
          ]
        }
      ]
    },
    {
      "name": "Diagnostic",
      "item": [
        {
          "id": "3ce9cf2f-486c-4058-879c-e26e066c41fe",
          "name": "diagnostictoolsv1locations",
          "request": {
            "url": "http://developer.akamai.com/diagnostic-tools/v1/locations",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Locations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2a70a494-2ff7-4d06-ba86-110728ab560c"
            }
          ]
        },
        {
          "id": "06e03577-88b8-43af-b0c8-5c92ff2b6059",
          "name": "diagnostictoolsv1dighostnamequerytypelocationsourceip",
          "request": {
            "url": "http://developer.akamai.com/diagnostic-tools/v1/dig?hostname=hostname&location=location&queryType=queryType&sourceIp=sourceIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Run dig"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b05b0df-7623-4a86-b570-8e12bc3724bb"
            }
          ]
        },
        {
          "id": "49af8f32-62db-4aed-82c2-568873864336",
          "name": "diagnostictoolsv1mtrdestinationdomainlocationsourceip",
          "request": {
            "url": "http://developer.akamai.com/diagnostic-tools/v1/mtr?destinationDomain=destinationDomain&location=location&sourceIp=sourceIp",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Run mtr"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd4fd2ee-e2f7-4d2e-9159-6c09e16fe28b"
            }
          ]
        },
        {
          "id": "6ca55ef1-b0df-4dae-ab52-6431108ff1e7",
          "name": "diagnostictoolsv1akamaitranslatorhostname",
          "request": {
            "url": "http://developer.akamai.com/diagnostic-tools/v1/akamaitranslator?hostname=hostname",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Translate Hostname"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9943fe96-a940-43de-82f3-d7b67ca81d55"
            }
          ]
        },
        {
          "id": "14a625d8-a382-4fbc-ab50-77e19e4fc0f9",
          "name": "diagnostictoolsv1errortranslatorerrorcode",
          "request": {
            "url": "http://developer.akamai.com/diagnostic-tools/v1/errortranslator?errorCode=errorCode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Translate Error Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ada454a-d8a3-4be0-8060-af23bfb9df28"
            }
          ]
        },
        {
          "id": "fa2db0b1-d3cb-4776-bbf6-088494753f67",
          "name": "diagnostictoolsv1ipgeolocatorip",
          "request": {
            "url": "http://developer.akamai.com/diagnostic-tools/v1/ipgeolocator?ip=ip",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get IP Geolocation Data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e56ecba4-74a4-44e2-8821-07bcc17c6959"
            }
          ]
        },
        {
          "id": "524fbefa-9945-4f64-8893-3548e117da2a",
          "name": "diagnostictoolsv1verifycdnipip",
          "request": {
            "url": "http://developer.akamai.com/diagnostic-tools/v1/verifycdnip?ip=ip",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Is This a CDN IP"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80d967c7-7ff6-4b25-b4aa-ee1868366494"
            }
          ]
        }
      ]
    },
    {
      "name": "Token",
      "item": [
        {
          "id": "dd134949-8765-4839-bdcd-fa8e452d21f6",
          "name": "token",
          "request": {
            "url": "http://developer.akamai.com/token?zone=zone",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Zone"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ae060b54-8d09-48a6-9e0a-5f2306f3d425"
            }
          ]
        },
        {
          "id": "c43d2201-7662-4320-8312-da3ca5440230",
          "name": "token",
          "request": {
            "url": "http://developer.akamai.com/token?zone=zone",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add or Modify a Zone"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "573dbb5b-131d-4cae-b00a-4a60a9c613c4"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "e6c261b5-4a59-4270-831f-cd1b32755442",
          "name": "datadnsv1trafficzonestartstart-timeendend-timeend-timetime-zoneinclude-estimates",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "data-dns/v1/traffic/:zone"
              ],
              "query": [
                {
                  "key": "end",
                  "value": "end",
                  "disabled": false
                },
                {
                  "key": "end_time",
                  "value": "end_time",
                  "disabled": false
                },
                {
                  "key": "include_estimates",
                  "value": "include_estimates",
                  "disabled": false
                },
                {
                  "key": "start",
                  "value": "start",
                  "disabled": false
                },
                {
                  "key": "start_time",
                  "value": "start_time",
                  "disabled": false
                },
                {
                  "key": "time_zone",
                  "value": "time_zone",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "zone",
                  "value": "zone",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Traffic Report"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8a275e9-d6a3-4573-9020-7fd5d8c86052"
            }
          ]
        },
        {
          "id": "f538f172-d2b0-4fbd-acfd-36884784aa5a",
          "name": "data",
          "request": {
            "url": "http://developer.akamai.com/data?accountId=accountId&eventId=eventId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event Traffic Data by CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "851143b6-ebf5-4b46-b9f6-bae53a2f0477"
            }
          ]
        }
      ]
    },
    {
      "name": "Etp",
      "item": [
        {
          "id": "c17b7ea9-84c6-4a0b-9b0c-6739c4b4e249",
          "name": "etpreportv1configsconfigidthreateventsaggregatestarttimesecendtimesecdimensionfilters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "etp-report/v1/configs/:configId/threat-events/aggregate"
              ],
              "query": [
                {
                  "key": "dimension",
                  "value": "dimension",
                  "disabled": false
                },
                {
                  "key": "endTimeSec",
                  "value": "endTimeSec",
                  "disabled": false
                },
                {
                  "key": "filters",
                  "value": "filters",
                  "disabled": false
                },
                {
                  "key": "startTimeSec",
                  "value": "startTimeSec",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "configId",
                  "value": "configId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Report Security Event Aggregation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "564eee22-4484-473a-b8a7-50a4b5bac038"
            }
          ]
        },
        {
          "id": "b878888b-14df-4588-b345-7fc67afed851",
          "name": "etpreportv1configsconfigidthreateventsdetailsstarttimesecendtimesecdimensionfilters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "etp-report/v1/configs/:configId/threat-events/details"
              ],
              "query": [
                {
                  "key": "dimension",
                  "value": "dimension",
                  "disabled": false
                },
                {
                  "key": "endTimeSec",
                  "value": "endTimeSec",
                  "disabled": false
                },
                {
                  "key": "filters",
                  "value": "filters",
                  "disabled": false
                },
                {
                  "key": "startTimeSec",
                  "value": "startTimeSec",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "configId",
                  "value": "configId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Report Security Event Details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34f0c2c7-a151-4216-bebb-a9c0f94dadb0"
            }
          ]
        },
        {
          "id": "85983ade-2492-4c6f-a925-8e8b7821f7b6",
          "name": "etpreportv1configsconfigidthreateventstimeseriesstarttimesecendtimesecdimensionfilters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "etp-report/v1/configs/:configId/threat-events/time-series"
              ],
              "query": [
                {
                  "key": "dimension",
                  "value": "dimension",
                  "disabled": false
                },
                {
                  "key": "endTimeSec",
                  "value": "endTimeSec",
                  "disabled": false
                },
                {
                  "key": "filters",
                  "value": "filters",
                  "disabled": false
                },
                {
                  "key": "startTimeSec",
                  "value": "startTimeSec",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "configId",
                  "value": "configId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Report Security Event Time Series"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89da6388-3733-4fbe-a6e0-13bd435c0112"
            }
          ]
        },
        {
          "id": "5228fc7b-9247-4cbf-a794-c99942c57201",
          "name": "etpreportv1configsconfigidaupeventsdetailsstarttimesecendtimesecdimensionfilters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "etp-report/v1/configs/:configId/aup-events/details"
              ],
              "query": [
                {
                  "key": "dimension",
                  "value": "dimension",
                  "disabled": false
                },
                {
                  "key": "endTimeSec",
                  "value": "endTimeSec",
                  "disabled": false
                },
                {
                  "key": "filters",
                  "value": "filters",
                  "disabled": false
                },
                {
                  "key": "startTimeSec",
                  "value": "startTimeSec",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "configId",
                  "value": "configId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Report AUP Event Details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d127c5f6-301e-4a4e-9a3a-ac0d481f49ae"
            }
          ]
        },
        {
          "id": "cd340f05-444f-46d1-abc8-b0bfe31eaba6",
          "name": "etpreportv1configsconfigidaupeventstimeseriesstarttimesecendtimesecdimensionfilters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "etp-report/v1/configs/:configId/aup-events/time-series"
              ],
              "query": [
                {
                  "key": "dimension",
                  "value": "dimension",
                  "disabled": false
                },
                {
                  "key": "endTimeSec",
                  "value": "endTimeSec",
                  "disabled": false
                },
                {
                  "key": "filters",
                  "value": "filters",
                  "disabled": false
                },
                {
                  "key": "startTimeSec",
                  "value": "startTimeSec",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "configId",
                  "value": "configId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Report AUP Event Time Series"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "393530a4-0af6-4660-ba13-bc2f43e12889"
            }
          ]
        },
        {
          "id": "7fdff33b-6c0b-497c-ac08-14b488a92794",
          "name": "etpreportv1configsconfigiddnsactivitiestimeseriesstarttimesecendtimesecdimensionfilters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "etp-report/v1/configs/:configId/dns-activities/time-series"
              ],
              "query": [
                {
                  "key": "dimension",
                  "value": "dimension",
                  "disabled": false
                },
                {
                  "key": "endTimeSec",
                  "value": "endTimeSec",
                  "disabled": false
                },
                {
                  "key": "filters",
                  "value": "filters",
                  "disabled": false
                },
                {
                  "key": "startTimeSec",
                  "value": "startTimeSec",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "configId",
                  "value": "configId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Report DNS Activity Time Series"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5af4844e-cfb3-4f99-ab7f-199dae5b3178"
            }
          ]
        },
        {
          "id": "0b20cfba-1513-436e-bc0d-7545c4b52dc1",
          "name": "etpreportv1configsconfigiddnsactivitiesaggregatestarttimesecendtimesecdimensionfilters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "etp-report/v1/configs/:configId/dns-activities/aggregate"
              ],
              "query": [
                {
                  "key": "dimension",
                  "value": "dimension",
                  "disabled": false
                },
                {
                  "key": "endTimeSec",
                  "value": "endTimeSec",
                  "disabled": false
                },
                {
                  "key": "filters",
                  "value": "filters",
                  "disabled": false
                },
                {
                  "key": "startTimeSec",
                  "value": "startTimeSec",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "configId",
                  "value": "configId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Report DNS Activities Totals"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0f4280f3-33bf-43a4-9f08-34af4fb5f900"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "7d7e2104-ac3d-473b-95b1-0c2c04913bba",
          "name": "eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events"
              ],
              "query": [
                {
                  "key": "customerEventId",
                  "value": "customerEventId",
                  "disabled": false
                },
                {
                  "key": "endRange",
                  "value": "endRange",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "sortField",
                  "value": "sortField",
                  "disabled": false
                },
                {
                  "key": "sortOrder",
                  "value": "sortOrder",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "startIndex",
                  "disabled": false
                },
                {
                  "key": "startRange",
                  "value": "startRange",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d554ed6-ad4b-4b91-a398-8035203e2463"
            }
          ]
        },
        {
          "id": "cbb01baa-c308-4796-9712-061facb37ddd",
          "name": "eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events"
              ],
              "query": [
                {
                  "key": "customerEventId",
                  "value": "customerEventId",
                  "disabled": false
                },
                {
                  "key": "endRange",
                  "value": "endRange",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "sortField",
                  "value": "sortField",
                  "disabled": false
                },
                {
                  "key": "sortOrder",
                  "value": "sortOrder",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "startIndex",
                  "disabled": false
                },
                {
                  "key": "startRange",
                  "value": "startRange",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "PUT a New Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19b064b7-5255-4aaf-9c32-ae3b9e29c63b"
            }
          ]
        },
        {
          "id": "b3c16b92-9030-4e12-b799-8104d9c48d04",
          "name": "eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events"
              ],
              "query": [
                {
                  "key": "customerEventId",
                  "value": "customerEventId",
                  "disabled": false
                },
                {
                  "key": "endRange",
                  "value": "endRange",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "sortField",
                  "value": "sortField",
                  "disabled": false
                },
                {
                  "key": "sortOrder",
                  "value": "sortOrder",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "startIndex",
                  "disabled": false
                },
                {
                  "key": "startRange",
                  "value": "startRange",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "POST a New Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b177ed6-423b-4c37-ad91-ea70da20244e"
            }
          ]
        },
        {
          "id": "7f924084-9c67-494e-9519-3f1f2d546540",
          "name": "eventsv2accountideventsstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events"
              ],
              "query": [
                {
                  "key": "customerEventId",
                  "value": "customerEventId",
                  "disabled": false
                },
                {
                  "key": "endRange",
                  "value": "endRange",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "sortField",
                  "value": "sortField",
                  "disabled": false
                },
                {
                  "key": "sortOrder",
                  "value": "sortOrder",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "startIndex",
                  "disabled": false
                },
                {
                  "key": "startRange",
                  "value": "startRange",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6bf8d865-1523-499a-867d-0fbbb459a648"
            }
          ]
        },
        {
          "id": "172a9101-2664-4567-b887-3e6b126f0f5a",
          "name": "eventsv2accountideventsrecurringfrequencynumberoftimes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/recurring"
              ],
              "query": [
                {
                  "key": "frequency",
                  "value": "frequency",
                  "disabled": false
                },
                {
                  "key": "numberOfTimes",
                  "value": "numberOfTimes",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Recurring Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c615610-76a5-409e-8e60-5c146a8c516d"
            }
          ]
        },
        {
          "id": "09a3667f-234f-4566-8c3f-de880f07a0a7",
          "name": "eventsv2accountideventseventidservices",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId"
              ],
              "query": [
                {
                  "key": "services",
                  "value": "services",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event with its Services"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f37f255-1d9b-49d1-aa08-a5ac612ae272"
            }
          ]
        },
        {
          "id": "83917e5d-c0ac-4045-a908-47633a3c045a",
          "name": "eventsv2accountideventseventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify an Event, with PUT"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d4c81103-3cab-41ff-a56c-00826aae2587"
            }
          ]
        },
        {
          "id": "129abf04-97cf-4719-b96f-532afc6bda12",
          "name": "eventsv2accountideventseventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Modify an Event, with POST"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7338805a-5877-4811-8c09-353661b7c8e9"
            }
          ]
        },
        {
          "id": "c7f339e2-18f1-4f5d-91eb-1c6da465b464",
          "name": "eventsv2accountideventseventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove an Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a7fc0ee-1a39-4fab-96e4-7e18a51dadee"
            }
          ]
        },
        {
          "id": "39eeb963-4c45-4954-a371-09acc8955dda",
          "name": "eventsv2accountideventseventidservices",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/services"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Services"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "725f901e-8bfb-4725-bb5f-681c101c5ed0"
            }
          ]
        },
        {
          "id": "524b4217-1bd0-4fcd-a5ef-18ddbbf3c293",
          "name": "eventsv2accountideventsidstartrangeendrangesortfieldsortorderstartindexlimitcustomereventid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/id"
              ],
              "query": [
                {
                  "key": "customerEventId",
                  "value": "customerEventId",
                  "disabled": false
                },
                {
                  "key": "endRange",
                  "value": "endRange",
                  "disabled": false
                },
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "sortField",
                  "value": "sortField",
                  "disabled": false
                },
                {
                  "key": "sortOrder",
                  "value": "sortOrder",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "startIndex",
                  "disabled": false
                },
                {
                  "key": "startRange",
                  "value": "startRange",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Range of Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4f038231-e151-4daa-a0a9-c9e9d204ba54"
            }
          ]
        },
        {
          "id": "cc8e944e-f7aa-4ca4-9d3d-ca28a60aab42",
          "name": "eventsv2accountideventslive",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/live"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Events in Progress"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16d145ab-988c-4d15-b950-919ecb6c18df"
            }
          ]
        },
        {
          "id": "dada5468-c508-49fb-9fc6-151fcfa44f9b",
          "name": "eventsv2accountideventslivetime",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/live/:time"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "time",
                  "value": "time",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Events Current for Specific Time"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1976d5d-8d1c-4d08-8125-8df7057c1b3f"
            }
          ]
        },
        {
          "id": "571e8505-731d-43f8-b36c-c1d6d0de395c",
          "name": "eventsv2accountideventsupcoming",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/upcoming"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Upcoming Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f73936da-490f-420d-84bc-15a264230645"
            }
          ]
        },
        {
          "id": "7f185718-a378-400e-b2e9-a83db449aac8",
          "name": "eventsv2accountideventsupcomingrangeinhours",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/upcoming/:rangeInHours"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "rangeInHours",
                  "value": "rangeInHours",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Impending Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7149b0db-6037-4919-aa24-4e7cfba9214a"
            }
          ]
        },
        {
          "id": "68e01d56-80b7-43a8-9e56-266cee5800c0",
          "name": "eventsv2accountideventsalerts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/alerts"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Alerts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6301630-b636-4913-8935-7bb59e2f7aad"
            }
          ]
        },
        {
          "id": "c656470f-ff9c-476e-aa71-a9c5b9bc3d5d",
          "name": "eventsv2accountideventseventidalerts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/alerts"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Alerts per Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea57a2ff-8113-4cdc-97ea-d5b3f8cc775b"
            }
          ]
        },
        {
          "id": "fcc612e4-95db-42ed-8b0c-fd16822b5422",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeedgebandwidthcpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/edge/bandwidth/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Edge Bandwidth per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80120c99-2db1-40d7-ba0f-5755903fb6a1"
            }
          ]
        },
        {
          "id": "be8fd004-62b3-4126-9cd5-464249e36e4e",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeedgerequestscpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/edge/requests/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Edge Requests, per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e520f0f9-11d0-4589-8a87-1e7b58a8e67d"
            }
          ]
        },
        {
          "id": "ea348e3a-cb4d-42b5-8282-08fb015d8053",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeedgestatus",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/edge/status"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Status Totals"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32b6b7b6-256c-4e6f-9c05-620acf604d32"
            }
          ]
        },
        {
          "id": "9dec0276-9e43-41b3-b632-5e379750a791",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeedgestatuscpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/edge/status/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Status Totals per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d924bb82-2eca-4bdd-88df-59247ac4bbcd"
            }
          ]
        },
        {
          "id": "334ba7a8-cea4-4ae5-a65b-b6e2644c62fb",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/origin/bandwidth"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Bandwidth Data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c82e2371-c326-4453-a23e-75f891418516"
            }
          ]
        },
        {
          "id": "a04c2d48-995e-46a3-b343-43d7b0861bc5",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeoriginbandwidthcpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/origin/bandwidth/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Bandwidth Data per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f30e4951-335b-4ece-9a70-280004e96e95"
            }
          ]
        },
        {
          "id": "f770831f-cf87-40be-8100-d4229001ded1",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeoriginrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/origin/requests"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Origin Requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1c75e32-68de-453c-8648-5f8e07cbc03b"
            }
          ]
        },
        {
          "id": "d8789a94-5821-4f34-9bca-c18e616f1dcd",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeoriginrequestscpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/origin/requests/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Origin Requests per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "14247133-f8b5-4510-a08a-18339a742357"
            }
          ]
        },
        {
          "id": "0b041dca-8e12-4fa9-af2a-03144726aab4",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeoriginstatus",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/origin/status"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Origin Statuses"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e3440e90-0adf-4626-91e9-88f4ca1b36f1"
            }
          ]
        },
        {
          "id": "0011009c-c288-4977-b616-d044e1cfbcae",
          "name": "eventsv2accountideventseventidtrafficdatacpcodeoriginstatuscpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/origin/status/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Origin Statuses per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd925eb9-5bfb-4fb3-9622-d8b4bb20e890"
            }
          ]
        },
        {
          "id": "c31c5861-f440-4eae-89ca-80e4ebab7e0b",
          "name": "eventsv2accountideventseventidtrafficdatacpcodebandwidth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/bandwidth"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s I/O Bandwidth"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6161e71-22aa-40f2-a64c-25dc6ba44926"
            }
          ]
        },
        {
          "id": "81a5908f-49bf-41a8-961f-7aa816262a5d",
          "name": "eventsv2accountideventseventidtrafficdatacpcodebandwidthcpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/bandwidth/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s I/O Bandwidth per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "956e35d3-804a-474f-88a2-5d9e3e955b8c"
            }
          ]
        },
        {
          "id": "f710e8e5-6b96-4d46-82ca-c986c450ad3d",
          "name": "eventsv2accountideventseventidtrafficdatacpcoderequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/requests"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43f26fe9-8f76-442f-85a7-3c6a98ff6112"
            }
          ]
        },
        {
          "id": "5c570208-d34e-4463-bcc6-4b58ba9bf349",
          "name": "eventsv2accountideventseventidtrafficdatacpcoderequestscpcode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/cpcode/requests/:cpcode"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "cpcode",
                  "value": "cpcode",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Event&#8217;s Requests per CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0636e227-5216-41d6-ac77-6fae2ca4c43f"
            }
          ]
        },
        {
          "id": "d0f93684-2c10-4950-b46f-75b2aa91ac16",
          "name": "eventsv2accountideventseventidtrafficdataentrypointflashlive",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/entrypoint/flashlive"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Entry Point Data for Flash Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e65f5a4-0a0e-4756-9f7e-e6e60c55c95e"
            }
          ]
        },
        {
          "id": "f092ffe8-cf59-4edf-9da0-8eff97c6761c",
          "name": "eventsv2accountideventseventidtrafficdataentrypointflashlivestreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/entrypoint/flashlive/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Entry Point Data for a Flash Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ba4f580-ddfe-4528-b815-9309ea0614c6"
            }
          ]
        },
        {
          "id": "10a7f268-0da3-4295-8048-670cb496dbb4",
          "name": "eventsv2accountideventseventidtrafficdataentrypointuniversallive",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/entrypoint/universallive"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Entry Point Data for Universal Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9f57d09-2b24-4176-bee4-c5905959ac0b"
            }
          ]
        },
        {
          "id": "86a52197-1531-43c0-a4d0-f69b3a8267cd",
          "name": "eventsv2accountideventseventidtrafficdataentrypointuniversallivestreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/entrypoint/universallive/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Entry Point Data for a Universal Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b34c6e34-b0cf-474d-bbd5-edd10b6502bb"
            }
          ]
        },
        {
          "id": "95bb66e6-f989-4413-8904-9b58dd76deae",
          "name": "eventsv2accountideventseventidtrafficdataflegressbw",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/fl/egressbw"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Aggregate Data for Flash Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79cf567d-cbe5-4e2a-b32b-2a284ed3f118"
            }
          ]
        },
        {
          "id": "35b57733-3ce4-47e0-b39e-54d350688b87",
          "name": "eventsv2accountideventseventidtrafficdataflegressbwstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/fl/egressbw/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Aggregate Data for a Flash Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d43caa94-1c5f-4e6c-bbac-28868cde9d3e"
            }
          ]
        },
        {
          "id": "ffaa78a7-7391-424c-8fa2-788aacfe3a19",
          "name": "eventsv2accountideventseventidtrafficdataflegressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/fl/egressrequests"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Request Data for Flash Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "205b0abd-3c46-4ee1-9ae0-48eadbb57e29"
            }
          ]
        },
        {
          "id": "0258ee2b-66d1-4337-8ccc-b0f71ffab5c9",
          "name": "eventsv2accountideventseventidtrafficdataflegressrequestsstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/fl/egressrequests/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Request Data for a Flash Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8434748-5147-438f-8df3-c1931faba956"
            }
          ]
        },
        {
          "id": "32632fb0-95b7-48d5-a181-67c48e26830e",
          "name": "eventsv2accountideventseventidtrafficdataflegressviewers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/fl/egressviewers"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Viewer Data for Flash Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d76f1e49-33c5-4d56-8515-dc0fde9a167d"
            }
          ]
        },
        {
          "id": "1fb1627a-2340-481b-b3f1-5e1140e70da5",
          "name": "eventsv2accountideventseventidtrafficdataflegressviewersstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/fl/egressviewers/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Viewer Data for a Flash Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c8fe1b7-ffb5-44ea-b4ba-228871352bc1"
            }
          ]
        },
        {
          "id": "5078050a-3359-4c08-834d-bf69dfe329aa",
          "name": "eventsv2accountideventseventidtrafficdatahdsllegressbw",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/hdsll/egressbw"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Aggregate Data for Silverlight Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d11f78d7-af9d-46fd-9dde-fcc5a0f1dadd"
            }
          ]
        },
        {
          "id": "14f99ee2-4c00-48cd-9ed8-2e676cf2d109",
          "name": "eventsv2accountideventseventidtrafficdatahdsllegressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/hdsll/egressrequests"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Request Data for Silverlight Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b6eb1f56-c661-4f2e-91e4-0a397c68c160"
            }
          ]
        },
        {
          "id": "7eb74509-7a0d-40cc-8001-b847632dcd4d",
          "name": "eventsv2accountideventseventidtrafficdatahdsllegressrequestsstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/hdsll/egressrequests/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Request Data for a Silverlight Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfea8aba-f506-4c6f-ac0a-4f14f034e6a5"
            }
          ]
        },
        {
          "id": "19c4984e-ee7c-442a-82da-3cf52f8de0cb",
          "name": "eventsv2accountideventseventidtrafficdatahdsllegressstatus",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/hdsll/egressstatus"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Status Data for Silverlight Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9cc2a48d-d1a8-486a-abb7-a7060c220632"
            }
          ]
        },
        {
          "id": "ac2598d9-58f1-40b5-9252-b525e4d530eb",
          "name": "eventsv2accountideventseventidtrafficdatahdsllegressstatusstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/hdsll/egressstatus/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Status Data for a Silverlight Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8efc683e-1032-495f-a32a-892af506eecb"
            }
          ]
        },
        {
          "id": "2f8adc4d-8cca-4537-bc7f-6719bd8fac6d",
          "name": "eventsv2accountideventseventidtrafficdatahdsllegressviewers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/hdsll/egressviewers"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Viewer Data for Silverlight Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9000483-e768-4aaa-8536-528d8bfed5b2"
            }
          ]
        },
        {
          "id": "c0766a9a-fec1-402f-8cef-935d2f954287",
          "name": "eventsv2accountideventseventidtrafficdatahdsllegressviewersstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/hdsll/egressviewers/:streamId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Viewer Data for a Silverlight Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12e8e112-654c-402b-a44a-d99eb145fd3d"
            }
          ]
        },
        {
          "id": "0aaf3283-2aa0-4e28-b7c5-575a2c18644c",
          "name": "eventsv2accountideventseventidtrafficdatasripconnections",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/srip/connections"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get SRIP Connections"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3d0e10a-6a65-46f3-a568-b0eff5142066"
            }
          ]
        },
        {
          "id": "7971668a-b434-4734-8fa3-bcf80ff3f410",
          "name": "eventsv2accountideventseventidtrafficdatasripconnectionsslotid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/srip/connections/:slotId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "slotId",
                  "value": "slotId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get SRIP Connections per Slot"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "480226bf-7f66-4485-956c-fad6d0f6531d"
            }
          ]
        },
        {
          "id": "6aeab155-a91a-4e25-ac7b-af376d78a710",
          "name": "eventsv2accountideventseventidtrafficdatasripsourcebandwidth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/srip/sourcebandwidth"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get SRIP Bandwidth"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b57d359-d81b-442c-963f-bace35c10b59"
            }
          ]
        },
        {
          "id": "2f046583-54ab-420d-9e57-d1cf69a4c99f",
          "name": "eventsv2accountideventseventidtrafficdatasripsourcebandwidthslotid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/events/:eventId/trafficdata/srip/sourcebandwidth/:slotId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "eventId",
                  "value": "eventId",
                  "type": "string"
                },
                {
                  "id": "slotId",
                  "value": "slotId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get SRIP Bandwidth per Slot"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "248a87e7-0577-4114-a233-031971d5db93"
            }
          ]
        },
        {
          "id": "9a52ea34-dab2-4171-b294-5a8197a0a311",
          "name": "eventsv2accountidsitescpcodes",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/sites/cpcodes"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List CP Codes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1166834-50d1-4d9a-9f6b-bccefc27c1f0"
            }
          ]
        },
        {
          "id": "149f5893-5c6a-42f1-95bc-7c29dab200f9",
          "name": "eventsv2accountidsripsortfieldsortorderlimitstartindex",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/srip"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "sortField",
                  "value": "sortField",
                  "disabled": false
                },
                {
                  "key": "sortOrder",
                  "value": "sortOrder",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "startIndex",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List IPA and SXL Configurations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df74668c-02f5-4463-8e16-cb746c2d6ddf"
            }
          ]
        },
        {
          "id": "0d728e92-f4d7-425f-9420-ad27fdc2b6c8",
          "name": "eventsv2accountidstreamsflashlive",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/streams/flashlive"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Flash Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da3af0d7-c94b-4953-a069-abae140fd255"
            }
          ]
        },
        {
          "id": "c35bd3b5-f6ad-4bee-924c-878f343fc667",
          "name": "eventsv2accountidstreamssilverlightlive",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/streams/silverlightlive"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Silverlight Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1408f27a-9fd9-459d-8ea1-aa6e873711bb"
            }
          ]
        },
        {
          "id": "d9cd2ba0-d74c-4b39-a36e-f3aa65a65ac0",
          "name": "eventsv2accountidstreamsuniversallivesortfieldsortorderlimitstartindex",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "events/v2/:accountId/streams/universallive"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "limit",
                  "disabled": false
                },
                {
                  "key": "sortField",
                  "value": "sortField",
                  "disabled": false
                },
                {
                  "key": "sortOrder",
                  "value": "sortOrder",
                  "disabled": false
                },
                {
                  "key": "startIndex",
                  "value": "startIndex",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Universal Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6cd2d0cc-c603-4de7-a5bd-1b3ac088b129"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "8c5f4415-d2a4-4f28-9e06-e295ea6beebc",
          "name": "streamid",
          "request": {
            "url": "http://developer.akamai.com/streamId?accountId=accountId&eventId=eventId&streamId=streamId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Silverlight Live Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5373872f-8f27-4a2c-991a-942df3246ef1"
            }
          ]
        }
      ]
    },
    {
      "name": "Deliveryformat",
      "item": [
        {
          "id": "c78ca241-f8b7-4634-a5d2-28ed940d872b",
          "name": "deliveryformat",
          "request": {
            "url": "http://developer.akamai.com/deliveryFormat?accountId=accountId&deliveryFormat=deliveryFormat&eventId=eventId&range=range&streamId=streamId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Edge Bandwidth for Universal Live Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ffacaef-39af-434a-967d-07e382439241"
            }
          ]
        }
      ]
    },
    {
      "name": "Audience",
      "item": [
        {
          "id": "18e38371-c22d-4339-af49-d5de6a7d4093",
          "name": "timeagginterval",
          "request": {
            "url": "http://developer.akamai.com/timeAggInterval?accountId=accountId&endDate=endDate&eventId=eventId&reportPackID=reportPackID&startDate=startDate&timeAggInterval=timeAggInterval",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Audience Size"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "96ca4eee-c1f1-4193-b4c5-d543ec1ee4e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Clients",
      "item": [
        {
          "id": "4cdea489-7725-4138-a114-a94a47f4d36a",
          "name": "clientside-qos1-live",
          "request": {
            "url": "http://developer.akamai.com/clientside_qos1_live?accountId=accountId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Report Packs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68a601a5-3f9c-47a9-89db-844f9af21444"
            }
          ]
        }
      ]
    },
    {
      "name": "Feo",
      "item": [
        {
          "id": "40ee47d9-2e51-404f-b8ef-9f180054fd77",
          "name": "feov1purge",
          "request": {
            "url": "http://developer.akamai.com/feo/v1/purge",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Purge a Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41896863-40dd-4b4a-8f8a-efcd10c45c54"
            }
          ]
        }
      ]
    },
    {
      "name": "Imaging",
      "item": [
        {
          "id": "76c4cb60-ca69-468c-a42d-fa68360b5282",
          "name": "imagingv0policiesid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/policies/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb153ebf-2513-424f-8dde-bdc8c6ea9cd2"
            }
          ]
        },
        {
          "id": "a3dd3444-d983-42d8-8650-9435418ed6cd",
          "name": "imagingv0policiesid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/policies/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Add or Modify a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30ba3865-deef-45a3-a91b-0333e783b165"
            }
          ]
        },
        {
          "id": "0cb9bd9f-7f0d-4b39-99d3-cb425570d057",
          "name": "imagingv0policiesid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/policies/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb1f5ac6-fdcb-4c69-9c13-c8e93d4b5ea3"
            }
          ]
        },
        {
          "id": "b8dc3626-89e4-4979-95d9-bd932679a57e",
          "name": "imagingv0policies",
          "request": {
            "url": "http://developer.akamai.com/imaging/v0/policies",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27fdb5da-99c7-46a1-bead-a656c7f6ec52"
            }
          ]
        },
        {
          "id": "2dae6cca-333b-404a-8127-9d3a6b41502c",
          "name": "imagingv0imagespolicyid",
          "request": {
            "url": "http://developer.akamai.com/imaging/v0/images?policyId=policyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List a Policy&#8217;s Images"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2ec22e47-2c0a-40f2-9849-500fd066d7b5"
            }
          ]
        },
        {
          "id": "a4832a8e-da5e-4c64-a771-3a4b78f79a9b",
          "name": "imagingv0imagesid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/images/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Image"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6b9f29f0-7b6b-4897-87bf-dd55724294c9"
            }
          ]
        },
        {
          "id": "b6615904-9d19-4f6e-8880-2f4226a89cca",
          "name": "imagingv0imagecollectionstag",
          "request": {
            "url": "http://developer.akamai.com/imaging/v0/imagecollections?tag=tag",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Image Collections By Tag"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc1442d1-0265-4d1e-87fa-76c4453651e0"
            }
          ]
        },
        {
          "id": "6748c787-6187-4c97-ba47-7b119e148085",
          "name": "imagingv0imagecollectionsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/imagecollections/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Image Collection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59550515-a281-47d7-ba53-915121649ba6"
            }
          ]
        },
        {
          "id": "4157e237-7b2b-4efb-846a-68da2f8a5d4b",
          "name": "imagingv0imagecollectionsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/imagecollections/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Add or Modify an Image Collection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b8a5d474-953c-490c-86eb-211d4c5f4fc1"
            }
          ]
        },
        {
          "id": "ebca7c90-ced2-4b65-861b-2ce0dc9130ce",
          "name": "imagingv0imagecollectionstagsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/imagecollections/tags/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Image Collection&#8217;s Tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "342f9d57-9b95-4ef6-a585-66456a2f159c"
            }
          ]
        },
        {
          "id": "ec33b55e-f34a-4af4-8293-07255e0c83a0",
          "name": "imagingv0imagecollectionstagsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "imaging/v0/imagecollections/tags/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify an Image Collection&#8217;s Tags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb2ec47c-1a58-4106-954a-73b37a6b7779"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "7a951fdf-d682-44c9-83e8-55a30edb2c66",
          "name": "id",
          "request": {
            "url": "http://developer.akamai.com/id?id=id",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Policy History"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6c148ef-e98d-456e-8cf2-1c45ff7d9731"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "aaa6c151-5130-47ae-bd0c-e3f804eab47a",
          "name": "id",
          "request": {
            "url": "http://developer.akamai.com/id?id=id",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove an Image Collection"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4455302a-0545-4375-a07e-689551b74e3f"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoicing",
      "item": [
        {
          "id": "0ce89c92-d26b-483b-b8ba-51d8488c83e4",
          "name": "invoicingapiv2accountsaccountidinvoicesyearmonth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/accounts/:accountId/invoices"
              ],
              "query": [
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Account&#8217;s Invoices"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8cb3dbb0-bd2b-4cc5-9411-0ca0231c9fe5"
            }
          ]
        },
        {
          "id": "2dd72cca-01fe-485d-8bd7-c2bf4e39c58f",
          "name": "invoicingapiv2contractscontractidinvoicesyearmonth",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/contracts/:contractId/invoices"
              ],
              "query": [
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "contractId",
                  "value": "contractId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Contract&#8217;s Invoices"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19c7bd3d-1f7b-4b20-940b-461482e27259"
            }
          ]
        },
        {
          "id": "56cadb76-3730-4c7d-88e8-f8534b7d0bc0",
          "name": "invoicingapiv2contractscontractidinvoicesinvoicenumberfiles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/contracts/:contractId/invoices/:invoiceNumber/files"
              ],
              "variable": [
                {
                  "id": "contractId",
                  "value": "contractId",
                  "type": "string"
                },
                {
                  "id": "invoiceNumber",
                  "value": "invoiceNumber",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Contract&#8217;s Invoice Files"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34d8480b-866c-45f9-a023-55c96c5f31a5"
            }
          ]
        },
        {
          "id": "bb4af45f-c617-4446-94b0-d3f778666919",
          "name": "invoicingapiv2contractscontractidproductsproductidgeobillingfilesyearmonthday",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/contracts/:contractId/products/:productId/geo-billing-files"
              ],
              "query": [
                {
                  "key": "day",
                  "value": "day",
                  "disabled": false
                },
                {
                  "key": "month",
                  "value": "month",
                  "disabled": false
                },
                {
                  "key": "year",
                  "value": "year",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "contractId",
                  "value": "contractId",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download Geobilling Files"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5fd6f08c-3a0c-463a-83ee-28c304542918"
            }
          ]
        },
        {
          "id": "92763a39-4f7f-4207-b38e-50fde0065139",
          "name": "invoicingapiv2accountsaccountidnotifications",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/accounts/:accountId/notifications"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Notifications"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f985336-7a29-44c8-962b-c5bffb5324de"
            }
          ]
        },
        {
          "id": "0efc9a25-af3e-4f3d-a1ac-54b4dab12028",
          "name": "invoicingapiv2accountsaccountidnotifications",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/accounts/:accountId/notifications"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Notification"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0606c64f-81d7-4ced-9154-d4a7445ee870"
            }
          ]
        },
        {
          "id": "b894b920-475b-40a4-8559-71e5f1a318e5",
          "name": "invoicingapiv2accountsaccountidnotificationsnotificationid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/accounts/:accountId/notifications/:notificationId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "notificationId",
                  "value": "notificationId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Notification"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4adb252c-aa24-4ece-aaf0-1d91c17f87c2"
            }
          ]
        },
        {
          "id": "26611d6d-e23a-424d-a91b-8b1d4010a01d",
          "name": "invoicingapiv2accountsaccountidnotificationsnotificationid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/accounts/:accountId/notifications/:notificationId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "notificationId",
                  "value": "notificationId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Notification"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5a80c63d-5cd7-498e-821d-40bea2af0992"
            }
          ]
        },
        {
          "id": "507b343f-3853-435c-8e3f-a1440896691f",
          "name": "invoicingapiv2accountsaccountidnotificationsnotificationid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "invoicing-api/v2/accounts/:accountId/notifications/:notificationId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "notificationId",
                  "value": "notificationId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Notification"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27358fc6-16c7-447c-bdff-3b01a3f8b2ff"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "d25cfe36-d68c-4f17-8631-8219ffa8cb31",
          "name": "contenttype",
          "request": {
            "url": "http://developer.akamai.com/Content-Type?contractId=contractId&filename=filename&invoiceNumber=invoiceNumber",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download an Invoice File"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84dafe4a-134b-45bf-86ab-aa5631c80b18"
            }
          ]
        }
      ]
    },
    {
      "name": "Configurations",
      "item": [
        {
          "id": "cfd1ddaf-1359-4258-9203-9a6941d23e62",
          "name": "acgobject",
          "request": {
            "url": "http://developer.akamai.com/acgObject",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Configurations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbb5b333-a761-4e23-90d9-e8dcd4199321"
            }
          ]
        },
        {
          "id": "15543227-0b7c-4da2-b513-add5724ee94d",
          "name": "configmedialivev1live",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/live",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Domains"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d0f85d48-d69b-4929-9e0a-469fba5e8e97"
            }
          ]
        },
        {
          "id": "b8651d5c-b2b7-40be-8759-a000f0706513",
          "name": "configmedialivev1live",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/live",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Domain"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23f1df68-b34d-40ef-a7d8-f1dff7336b13"
            }
          ]
        },
        {
          "id": "a7069fa6-b7e7-4d48-ad53-fed40be10f4d",
          "name": "configmedialivev1livedomain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Domain"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ecc2cc47-d6a8-4adf-b356-b2f872b269e4"
            }
          ]
        },
        {
          "id": "cd173b79-da92-4fd3-b259-4fe9e786e1be",
          "name": "configmedialivev1livedomain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Domain"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bbdbd341-8e93-4ff6-bd56-319066a13cab"
            }
          ]
        },
        {
          "id": "7292158b-2b3d-4866-b2d0-14f700c99e2a",
          "name": "configmedialivev1livedomainstream",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Streams"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a01a6cb2-c784-4966-be32-94cf4221a0c5"
            }
          ]
        },
        {
          "id": "c5f4d2cc-823e-461e-9c66-380c89f93f1e",
          "name": "configmedialivev1livedomainstream",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb385e8e-9612-4425-bffc-92e4cd7fc93b"
            }
          ]
        },
        {
          "id": "3efd7d46-1ef6-4cb4-82bf-729146655934",
          "name": "configmedialivev1livedomainstreamstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream/:streamId"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e658077f-6ee8-47bd-83af-9bf1ba4aceb2"
            }
          ]
        },
        {
          "id": "bedfda28-7da8-4f52-8262-4e5269ba88ec",
          "name": "configmedialivev1livedomainstreamstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream/:streamId"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4d144e4-61e1-47c9-ad0d-70b34719d2e8"
            }
          ]
        },
        {
          "id": "709ed960-be0e-4442-8212-f3eb717e192a",
          "name": "configmedialivev1livedomainstreamstreamid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream/:streamId"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Stream"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "286f0780-b539-424d-97aa-28c639738d1e"
            }
          ]
        },
        {
          "id": "b7dcd658-5410-4491-b448-ea60091e70b4",
          "name": "configmedialivev1livedomainstreamstreamidevent",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream/:streamId/event"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f33635e3-cf20-46b3-a57c-ab3522a5a4e3"
            }
          ]
        },
        {
          "id": "62ee407d-6381-4ffe-840f-b42daee1bec2",
          "name": "configmedialivev1livedomainstreamstreamideventeventname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream/:streamId/event/:eventName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "eventName",
                  "value": "eventName",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5729f9ba-5aed-4519-a170-77669abf070d"
            }
          ]
        },
        {
          "id": "e6b04aeb-c1f4-42ca-bb03-f651ed254456",
          "name": "configmedialivev1livedomainstreamstreamideventeventname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream/:streamId/event/:eventName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "eventName",
                  "value": "eventName",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify an Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cadcf0ab-c78b-45d9-8f3b-6c59684ae54f"
            }
          ]
        },
        {
          "id": "6bc1ee87-e9bb-494e-8f3e-8867de74460b",
          "name": "configmedialivev1livedomainstreamstreamideventeventname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/stream/:streamId/event/:eventName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "eventName",
                  "value": "eventName",
                  "type": "string"
                },
                {
                  "id": "streamId",
                  "value": "streamId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove an Event"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff6ee498-4ed8-42ac-82a8-20aafb8617f1"
            }
          ]
        },
        {
          "id": "7caef929-c0b4-4761-8fb1-0107dbab97f6",
          "name": "configmedialivev1livedomainversion",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/version"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6fdc394-6a6f-436e-a3ae-08bdfd80b1e2"
            }
          ]
        },
        {
          "id": "2b7d0c45-0bbf-4f02-89ea-0c1853ab165c",
          "name": "configmedialivev1livedomainversionversionid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/version/:versionId"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "versionId",
                  "value": "versionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66911a2f-5557-41e1-807f-1a2241885a34"
            }
          ]
        },
        {
          "id": "606704c2-1e0b-42f8-90f6-f2e81233bcdd",
          "name": "configmedialivev1livedomainversionversionidactivation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/version/:versionId/activation"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "versionId",
                  "value": "versionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Activation Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59df00e4-5216-4199-918c-f90851163041"
            }
          ]
        },
        {
          "id": "677d60fb-0f57-425f-bf5f-a2bdcf1f00fc",
          "name": "configmedialivev1livedomainversionversionidactivation",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-live/v1/live/:domain/version/:versionId/activation"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "versionId",
                  "value": "versionId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Activate a Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c3f9e14-8a29-4386-bad7-f09ebed8a7e0"
            }
          ]
        },
        {
          "id": "c19b366c-f9e3-41c5-8986-6a4d3eba72a6",
          "name": "configmedialivev1apiliveutilsarchivelocation",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/api/live/utils/archivelocation",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Archive Locations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dcf27b2a-33ff-46b7-9db6-fbeb33cee84d"
            }
          ]
        },
        {
          "id": "f52e0fb1-d4f1-4454-978a-96de5da658a3",
          "name": "configmedialivev1liveutilscontacts",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/live/utils/contacts",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Contacts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7397e648-bcca-48b4-a61b-b2022a49ceed"
            }
          ]
        },
        {
          "id": "47d201b8-e1bd-4b49-94f4-ff6e189dac28",
          "name": "configmedialivev1liveutilscountries",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/live/utils/countries",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Countries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eae7d4ad-29cf-494b-acfa-83ec79af24e4"
            }
          ]
        },
        {
          "id": "e7f5e556-10ed-4e04-a31a-7a3b3bab149e",
          "name": "configmedialivev1liveutilscpcode",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/live/utils/cpcode",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List CP Codes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aacc23db-1c74-46dc-8a3d-21af00f4c598"
            }
          ]
        },
        {
          "id": "007da650-9864-4e81-9e77-525f33ed53b6",
          "name": "configmedialivev1liveutilsdeliveryformat",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/live/utils/delivery/format",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Delivery Formats"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acccbb95-b380-4a7f-b504-078b4ca80e78"
            }
          ]
        },
        {
          "id": "111450a7-c8ba-4d0a-8152-ce7b90f8d306",
          "name": "configmedialivev1liveutilsingestformat",
          "request": {
            "url": "http://developer.akamai.com/config-media-live/v1/live/utils/ingest/format",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Ingest Formats"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f1fa7ba8-4eaa-45ac-9e82-1292b300274e"
            }
          ]
        },
        {
          "id": "2e96dfea-b756-4c83-94ef-60f5a5d2c3c3",
          "name": "configsaasregistrationv1applicationscontractid",
          "request": {
            "url": "http://developer.akamai.com/config-saas-registration/v1/applications/?contractId=contractId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Applications"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe6411b0-009d-409f-b95b-479754bc5408"
            }
          ]
        },
        {
          "id": "dacff72e-fbbf-4618-be03-c0bb02038c94",
          "name": "configsaasregistrationv1applicationscontractid",
          "request": {
            "url": "http://developer.akamai.com/config-saas-registration/v1/applications/?contractId=contractId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Application"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c08a3800-300e-466e-955a-bfcf01d48089"
            }
          ]
        },
        {
          "id": "69811225-da6c-43e7-8f58-02ca02385622",
          "name": "configsaasregistrationv1applicationssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/applications/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Application"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b09c6a6-7b4c-4b42-9932-0ba9b683176d"
            }
          ]
        },
        {
          "id": "af915518-a3c6-40f0-b22b-c3d30846a8f6",
          "name": "configsaasregistrationv1applicationssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/applications/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify an Application"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "996094a5-1d2d-4b20-abb9-5351d874bece"
            }
          ]
        },
        {
          "id": "b8130103-f988-4dc6-a8c2-ecec73f2248e",
          "name": "configsaasregistrationv1applicationssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/applications/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove an Application"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94f2c3c7-7418-453d-8e3d-a220eeae18bf"
            }
          ]
        },
        {
          "id": "d777fa60-b254-4abd-94f4-5e31af4cc341",
          "name": "configsaasregistrationv1customerscontractid",
          "request": {
            "url": "http://developer.akamai.com/config-saas-registration/v1/customers/?contractId=contractId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Customers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb0621f7-9cd4-4e0f-aa7a-46a70cdcd5d8"
            }
          ]
        },
        {
          "id": "c9cd7ee8-79d5-4ebb-8822-46d03b79e2f6",
          "name": "configsaasregistrationv1customerscontractid",
          "request": {
            "url": "http://developer.akamai.com/config-saas-registration/v1/customers/?contractId=contractId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b520128c-9aa3-4df0-b2d9-3ec27c793458"
            }
          ]
        },
        {
          "id": "367bd210-e7ca-47a6-9186-5561779ee078",
          "name": "configsaasregistrationv1customerssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/customers/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3c7c57e-ec62-46e0-8098-ec3aad49ba3a"
            }
          ]
        },
        {
          "id": "2b0a8b4d-daca-42b7-b05b-a37283b53fc2",
          "name": "configsaasregistrationv1customerssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/customers/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc96b68d-9601-44ca-847f-8598b8a1c078"
            }
          ]
        },
        {
          "id": "57576874-6650-479b-89a6-0e1bc557c443",
          "name": "configsaasregistrationv1customerssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/customers/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Customer"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5542c745-6761-4755-9231-51d2841d398d"
            }
          ]
        },
        {
          "id": "e10e85f9-ff5c-4263-9d86-262290c780c0",
          "name": "configsaasregistrationv1pairscontractid",
          "request": {
            "url": "http://developer.akamai.com/config-saas-registration/v1/pairs/?contractId=contractId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Pairs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0c4471b1-1734-4131-a23d-8a67f1a23df6"
            }
          ]
        },
        {
          "id": "06518ef6-3cdd-4315-a6d2-060aa8cf61ec",
          "name": "configsaasregistrationv1pairscontractid",
          "request": {
            "url": "http://developer.akamai.com/config-saas-registration/v1/pairs/?contractId=contractId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Pair"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "254bdf34-b0b7-42b8-b82d-c0d4f4fe59ae"
            }
          ]
        },
        {
          "id": "70e2fdbb-adc3-446f-88e0-6ee41a323764",
          "name": "configsaasregistrationv1pairssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/pairs/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Pair"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "37c7df91-3652-4fea-8fb3-7f2198ba9512"
            }
          ]
        },
        {
          "id": "cd211084-7c59-40b2-9911-fbb0af2230de",
          "name": "configsaasregistrationv1pairssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/pairs/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Pair"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c890d6b5-eaec-49da-9c96-f135d662db6e"
            }
          ]
        },
        {
          "id": "616d2abb-910a-4db0-b62d-4677e730e328",
          "name": "configsaasregistrationv1pairssurrogateidcontractid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-saas-registration/v1/pairs/:surrogateId/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "surrogateId",
                  "value": "surrogateId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Pair"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b0f6282-c5b9-49c6-8b68-1ee63f36d9ff"
            }
          ]
        },
        {
          "id": "7d275cc4-cf58-460f-b5bd-894104eccd8c",
          "name": "configmediasecurityv1security",
          "request": {
            "url": "http://developer.akamai.com/config-media-security/v1/security",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policies"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3946bc82-5337-4635-886e-dca89f078145"
            }
          ]
        },
        {
          "id": "e43f4155-3a37-4266-b2b9-fa04cb6070e1",
          "name": "configmediasecurityv1security",
          "request": {
            "url": "http://developer.akamai.com/config-media-security/v1/security",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7fad3cd-7935-4644-b03f-0d05e040218e"
            }
          ]
        },
        {
          "id": "67c98c8a-6935-4b3c-b7ec-6c3ec290ddfe",
          "name": "configmediasecurityv1securitypolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e763184f-fcca-4ecd-b41f-1e8e0af62adb"
            }
          ]
        },
        {
          "id": "fe6615d2-5286-43e9-a7c6-19ab1058126f",
          "name": "configmediasecurityv1securitypolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c433bbdf-0309-4de7-b2f7-30ddb0a13c89"
            }
          ]
        },
        {
          "id": "1155025d-ed61-41a7-a741-beee26033d43",
          "name": "configmediasecurityv1securitypolicyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Mark a Policy for Deletion"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ab689664-daa9-4515-9c59-0c4b48d5df07"
            }
          ]
        },
        {
          "id": "44311654-9dd2-4f3a-b147-51e0ddc75d94",
          "name": "configmediasecurityv1securitypolicyidenvironment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID/:environment"
              ],
              "variable": [
                {
                  "id": "environment",
                  "value": "environment",
                  "type": "string"
                },
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Policy per Environment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d50ecdb-b97d-496c-a162-aa16b2152623"
            }
          ]
        },
        {
          "id": "2480b949-8b53-4cf0-b3df-1d5f492815a6",
          "name": "configmediasecurityv1securitypolicyidclonepolicy",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID/clonePolicy"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Clone a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63281c3b-0c09-4671-a83d-b30713b6ffd0"
            }
          ]
        },
        {
          "id": "7261afa1-0c9d-4b2c-8b64-dbda19695230",
          "name": "configmediasecurityv1securitypolicyidpromote",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID/promote"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Promote a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12ebc5c8-a033-4a38-ac29-b7d01122901c"
            }
          ]
        },
        {
          "id": "5edbf25d-e87f-4a82-b4b6-15a02c80f9bc",
          "name": "configmediasecurityv1securitypolicyidpromotedelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID/promoteDelete"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d399f80a-adc6-4233-8beb-17bb90a90c81"
            }
          ]
        },
        {
          "id": "35d7daa8-bd8b-41e5-8675-f2ab45d1985f",
          "name": "configmediasecurityv1securitypolicyidrevertdelete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID/revertDelete"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Restore a Policy Deletion"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e596f1c4-2964-4e34-bd59-5fa02ac84252"
            }
          ]
        },
        {
          "id": "112c1b33-399e-4c3c-827e-b83e28ae3534",
          "name": "configmediasecurityv1securitypolicyidrevertedit",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/:policyID/revertEdit"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Restore a Policy Edit"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "035763c5-dede-418e-90f6-9596330e1305"
            }
          ]
        },
        {
          "id": "6f3c0911-a8ae-46cf-b3c8-f39b00de25df",
          "name": "configmediasecurityv1securitylivedomainpolicy",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/live/:domain/policy"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an HD Config Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d59792d-3095-4477-9c21-59f274bce50f"
            }
          ]
        },
        {
          "id": "54f73eb4-f44b-43b9-8d60-4d21494afea6",
          "name": "configmediasecurityv1securitylivedomainpolicy",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/live/:domain/policy"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify an HD Config Policy"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58297f35-19f7-4c88-af0e-e925eed3cc9d"
            }
          ]
        },
        {
          "id": "7ea078df-5550-483b-b774-3a2f86e405ee",
          "name": "configmediasecurityv1securitylivedomainpolicyenvironment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/live/:domain/policy/:environment"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "environment",
                  "value": "environment",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an HD Config Policy per Environment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e57753a0-5da8-458a-acc5-42aea829c773"
            }
          ]
        },
        {
          "id": "eca9bb79-2135-4729-b0ae-c7c7bfdbeaf9",
          "name": "configmediasecurityv1securitylivepolicyidpolicyassignments",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/live/:policyID/policyassignments"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Policy Assignments"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8dd0d076-b6be-4c70-bfb8-d507226f4505"
            }
          ]
        },
        {
          "id": "5c5c5620-e3de-4070-a801-f2c2c9f591a1",
          "name": "configmediasecurityv1securitylivepolicyidpolicyassignmentsenvironment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/live/:policyID/policyassignments/:environment"
              ],
              "variable": [
                {
                  "id": "environment",
                  "value": "environment",
                  "type": "string"
                },
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Policy Assignment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "894af1b1-4f24-45d7-b739-34f7ea898451"
            }
          ]
        },
        {
          "id": "8c7d3a3c-fabf-4326-9e5e-c8976b709edb",
          "name": "configmediasecurityv1securitylivepolicyidpolicyassignmentspromote",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/live/:policyID/policyassignments/promote"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Promote a Policy Assignment"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f2b2dce-e627-48c4-a099-1246359beebb"
            }
          ]
        },
        {
          "id": "76b24c36-e9fa-4c4e-82f6-23ebb77f7eb1",
          "name": "configmediasecurityv1securitylivepolicyidpolicyassignmentsrevert",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/live/:policyID/policyassignments/revert"
              ],
              "variable": [
                {
                  "id": "policyID",
                  "value": "policyID",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Revert a Policy Assignment Promotion"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a0d3fb6-e2cf-4732-8f14-25e8ae8f2d6c"
            }
          ]
        },
        {
          "id": "4fa8a00b-7d89-412c-8b73-1555db4cabbe",
          "name": "configmediasecurityv1securitycountries",
          "request": {
            "url": "http://developer.akamai.com/config-media-security/v1/security/countries",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Countries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a6640ace-1b39-4a97-a571-0eec6210f01b"
            }
          ]
        },
        {
          "id": "f287dcb7-7cf3-4484-a8c9-78d0660df520",
          "name": "configmediasecurityv1securitydmas",
          "request": {
            "url": "http://developer.akamai.com/config-media-security/v1/security/dmas",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Designated Market Areas"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "70be0e37-c8fc-404f-8c0b-56528d33ae41"
            }
          ]
        },
        {
          "id": "e95ed30e-71f9-47c0-8e5c-9d8298dd7b31",
          "name": "configmediasecurityv1securityregions",
          "request": {
            "url": "http://developer.akamai.com/config-media-security/v1/security/regions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Regions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8a7f33f4-85f7-42b2-96cc-f1f15be9ecd8"
            }
          ]
        },
        {
          "id": "c49d4035-ef0e-47a2-8301-7e606b604750",
          "name": "configmediasecurityv1securityregionscountrycode",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-media-security/v1/security/regions/:countryCode"
              ],
              "variable": [
                {
                  "id": "countryCode",
                  "value": "countryCode",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Regions per Country"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5555463-3b8f-4ce9-8aaf-68fe4a553286"
            }
          ]
        },
        {
          "id": "2cd40ae4-ef84-4bd9-8326-b5e6e91322fd",
          "name": "configmediasecurityv1securityacgs",
          "request": {
            "url": "http://developer.akamai.com/config-media-security/v1/security/acgs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Access Control Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1ab7244-48c4-491b-929f-9ddfbcf7a74e"
            }
          ]
        },
        {
          "id": "e9a4619b-169a-4dd8-857c-f88dec2ac20d",
          "name": "configsecureprovisioningservicev1spsrequestscontractidgroupidafterinformation",
          "request": {
            "url": "http://developer.akamai.com/config-secure-provisioning-service/v1/sps-requests?after=after&contractId=contractId&groupId=groupId&information=information",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List SPS Requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87044bcd-31de-4595-8fad-723f59310699"
            }
          ]
        },
        {
          "id": "e5ad7e4b-1e94-4d09-848b-84b9c99c220a",
          "name": "configsecureprovisioningservicev1spsrequestscontractidgroupidafterinformation",
          "request": {
            "url": "http://developer.akamai.com/config-secure-provisioning-service/v1/sps-requests?after=after&contractId=contractId&groupId=groupId&information=information",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a64cf972-bbe6-43c8-9607-ae61cbfb4b77"
            }
          ]
        }
      ]
    },
    {
      "name": "Service",
      "item": [
        {
          "id": "d2c89db1-a9ad-4237-ab79-c8e772148959",
          "name": "serviceid",
          "request": {
            "url": "http://developer.akamai.com/serviceId?serviceId=serviceId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc0e6260-520d-4960-ad23-66938ecd7ea1"
            }
          ]
        },
        {
          "id": "ed44d240-c62f-44f4-89b2-1a9f3689d1a4",
          "name": "serviceid",
          "request": {
            "url": "http://developer.akamai.com/serviceId?serviceId=serviceId",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c541d7dc-34ca-49e7-a131-f37e8b7efbaa"
            }
          ]
        },
        {
          "id": "54cef0de-c225-4e37-90c5-128cd11f7461",
          "name": "serviceid",
          "request": {
            "url": "http://developer.akamai.com/serviceId?serviceId=serviceId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d015d055-a587-46bc-ac26-9d1f80848108"
            }
          ]
        },
        {
          "id": "aa961e49-31c2-450c-a50d-2554cdda1b77",
          "name": "serviceid",
          "request": {
            "url": "http://developer.akamai.com/serviceId?serviceId=serviceId",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6eb7fde8-2423-4b0c-8b03-f39944c404c7"
            }
          ]
        }
      ]
    },
    {
      "name": "Services",
      "item": [
        {
          "id": "5718cf9a-96c8-49b6-ae29-d8d036780980",
          "name": "sourceserviceid",
          "request": {
            "url": "http://developer.akamai.com/sourceServiceId?sourceServiceId=sourceServiceId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Copy a Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1a3dfcc-eb6e-4a08-b2d9-4ea641eea264"
            }
          ]
        }
      ]
    },
    {
      "name": "Lds",
      "item": [
        {
          "id": "6d97b116-f5c3-4682-bd2c-463ea8fe666c",
          "name": "ldsv1configurationsresumeserviceid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "lds/v1/configurations/resume/:serviceId"
              ],
              "variable": [
                {
                  "id": "serviceId",
                  "value": "serviceId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Resume a Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4827c051-b28b-45a1-a433-915456294a67"
            }
          ]
        },
        {
          "id": "7eb9b2e2-a87b-4d3f-a6e4-64b71ce544de",
          "name": "ldsv1redeliveries",
          "request": {
            "url": "http://developer.akamai.com/lds/v1/redeliveries",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Redeliveries"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "10e2cb9e-d51c-4c80-8a8e-7fb9c3287df7"
            }
          ]
        },
        {
          "id": "62eb3440-d9a3-4681-8b18-697953a0c932",
          "name": "ldsv1redeliveries",
          "request": {
            "url": "http://developer.akamai.com/lds/v1/redeliveries",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Redelivery"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7851f288-a819-4ad1-b1db-ab8db8b4488b"
            }
          ]
        },
        {
          "id": "68a73bc1-594c-4579-bc83-2031dc463420",
          "name": "ldsv1dictionariesdictionarynamevalidationdata",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "lds/v1/dictionaries/:dictionaryName/validation/data"
              ],
              "variable": [
                {
                  "id": "dictionaryName",
                  "value": "dictionaryName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Validation Context"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "848a7cfd-969a-4e79-9c8b-413bd29c9f7f"
            }
          ]
        }
      ]
    },
    {
      "name": "Redelivery",
      "item": [
        {
          "id": "6aba5458-600e-4b2c-a5de-6ed8b645b3eb",
          "name": "redeliveryid",
          "request": {
            "url": "http://developer.akamai.com/redeliveryId?redeliveryId=redeliveryId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Redelivery"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87371054-89b8-418f-834a-3e46c5d377c0"
            }
          ]
        }
      ]
    },
    {
      "name": "Key",
      "item": [
        {
          "id": "d33291c0-5642-4a26-bff2-cec0bcc98ac7",
          "name": "key",
          "request": {
            "url": "http://developer.akamai.com/key?currentValueKey=currentValueKey&dictionaryName=dictionaryName&objectId=objectId&objectType=objectType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Dictionary"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9172d524-94f9-435c-9d9d-3e54ac990f66"
            }
          ]
        }
      ]
    },
    {
      "name": "Media",
      "item": [
        {
          "id": "c9611c79-1d88-4924-9450-4a2c5bdae102",
          "name": "mediareportsv1downloaddeliverydimensions",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/download-delivery/dimensions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Download Delivery Dimensions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f479d8fd-81b0-4739-9fdf-1d77994c5ad9"
            }
          ]
        },
        {
          "id": "72c00457-eb2a-49e7-976f-46aeb940a047",
          "name": "mediareportsv1downloaddeliverymetrics",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/download-delivery/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Download Delivery Metrics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0735547e-67f4-4219-ad91-81ed2d7e005c"
            }
          ]
        },
        {
          "id": "1f3e2493-cb79-4e56-a6b5-964e77896a4b",
          "name": "mediareportsv1objectdeliverymetrics",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/object-delivery/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Object Delivery Metrics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "916ae40a-95be-4401-a8ec-b7c711941abc"
            }
          ]
        },
        {
          "id": "777d9fcd-417e-428f-9e0f-ebaa8df30f51",
          "name": "mediareportsv1adaptivemediadeliverymetrics",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/adaptive-media-delivery/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Adaptive Media Delivery Metrics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e427408-9348-49cb-b34c-7078525c0238"
            }
          ]
        },
        {
          "id": "b3fbfbd1-fccc-4086-a000-9ba9a2254ccc",
          "name": "mediareportsv1rtmpmediadeliverymetrics",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/rtmp-media-delivery/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List RTMP Media Delivery Metrics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d4e29cd-0c58-4c35-b418-58600352903b"
            }
          ]
        },
        {
          "id": "aa5af6f3-c43a-44bd-8b28-83d81bf4e538",
          "name": "mediareportsv1wholesaledeliverymetrics",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/wholesale-delivery/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Wholesale Delivery Metrics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "61e9b667-f393-485f-885e-2cc41ac306c0"
            }
          ]
        },
        {
          "id": "f64d77dc-6169-40ef-8f67-01ad3c5b52b6",
          "name": "mediareportsv1mediaserviceslivehttpingestmetrics",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/media-services-live/http-ingest/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List HTTP Ingest Metrics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "55296bae-7e1b-44ee-ab29-8c9cc769ef3a"
            }
          ]
        },
        {
          "id": "3ef299d6-cf5e-416f-b46a-8c4aa9a388fa",
          "name": "mediareportsv1mediaserviceslivertmpingestdimensions",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/media-services-live/rtmp-ingest/dimensions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List RTMP Ingest Dimensions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63cf4f2f-6fbb-4dab-b367-0e5f2cbbff12"
            }
          ]
        },
        {
          "id": "eb2e4196-0528-46b1-8671-296b12a01adb",
          "name": "mediareportsv1mediaserviceslivertmpingestmetrics",
          "request": {
            "url": "http://developer.akamai.com/media-reports/v1/media-services-live/rtmp-ingest/metrics",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List RTMP Ingest Metrics"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "389a9dcd-6020-40ba-9b20-b7435e50c811"
            }
          ]
        }
      ]
    },
    {
      "name": "Filterparams",
      "item": [
        {
          "id": "ad8073d5-6736-43fd-982d-4145afbeb1ca",
          "name": "filterparams",
          "request": {
            "url": "http://developer.akamai.com/filterParams?aggregation=aggregation&cpcodes=cpcodes&deliveryFormat=deliveryFormat&deliveryOption=deliveryOption&deliveryType=deliveryType&dimensions=dimensions&endDate=endDate&filterParams=filterParams&ipVersion=ipVersion&limit=limit&metrics=metrics&offset=offset&sortParams=sortParams&startDate=startDate&streams=streams",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Download Delivery Data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "300e9c0c-d1fe-4adc-8521-9b665e59ef22"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "b2b1191f-2486-4e6e-9b25-df2f86c41d05",
          "name": "networklistv1network-listslisttypeextendedincludedeprecatedincludeelements",
          "request": {
            "url": "http://developer.akamai.com/network-list/v1/network_lists?extended=extended&includeDeprecated=includeDeprecated&includeElements=includeElements&listType=listType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Network Lists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93d2b177-54e3-4ae5-9460-4957c5f541f2"
            }
          ]
        },
        {
          "id": "84b284d2-0350-4fa4-bf46-92a2f9c899c1",
          "name": "networklistv1network-listslisttypeextendedincludedeprecatedincludeelements",
          "request": {
            "url": "http://developer.akamai.com/network-list/v1/network_lists?extended=extended&includeDeprecated=includeDeprecated&includeElements=includeElements&listType=listType",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Network List"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1501e35f-65ce-43c0-a781-4a45d26a512d"
            }
          ]
        },
        {
          "id": "d0a4bc13-7013-42fa-bc83-d86666791049",
          "name": "networklistv1network-listsnetworklistidextended",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId"
              ],
              "query": [
                {
                  "key": "extended",
                  "value": "extended",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Network List"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6c7f963a-7c30-4113-a4da-b9aa3ed21bf2"
            }
          ]
        },
        {
          "id": "c9253413-faef-4aca-a367-8dd3707e83c7",
          "name": "networklistv1network-listsnetworklistidextended",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId"
              ],
              "query": [
                {
                  "key": "extended",
                  "value": "extended",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Network List"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "93cb10c7-7aa0-41c0-ae9a-735af056d869"
            }
          ]
        },
        {
          "id": "8472911f-6a4f-423b-8185-a26b361340ab",
          "name": "networklistv1network-listsnetworklistidextended",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId"
              ],
              "query": [
                {
                  "key": "extended",
                  "value": "extended",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Add to a Network List"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b450c827-a461-472f-9704-66b2df27bf77"
            }
          ]
        },
        {
          "id": "8addc666-c010-484c-8d7c-7ea595d07f11",
          "name": "networklistv1network-listsnetworklistidelement",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId/element"
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Add an Element"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45383ace-de8f-4a43-8597-c78991fc42e6"
            }
          ]
        },
        {
          "id": "4b8cc9e4-1589-4687-b598-f1516bcae466",
          "name": "networklistv1network-listsnetworklistidelementelement",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId/element"
              ],
              "query": [
                {
                  "key": "element",
                  "value": "element",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove an Element"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59c7ccef-29b5-425c-8db4-7ae4d67ae082"
            }
          ]
        },
        {
          "id": "2f46f1cd-ff51-41ae-90f1-67f4ce003d8a",
          "name": "networklistv1network-listsnetworklistidactivateenv",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId/activate"
              ],
              "query": [
                {
                  "key": "env",
                  "value": "env",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Activate a Network List"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29cd467b-1b87-497e-b967-143044141aa1"
            }
          ]
        },
        {
          "id": "acf47788-2004-4249-b7e0-35656b5f4f10",
          "name": "networklistv1network-listsnetworklistidstatusenv",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId/status"
              ],
              "query": [
                {
                  "key": "env",
                  "value": "env",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Activation Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21820457-9be0-4569-a60c-102ef64a0735"
            }
          ]
        },
        {
          "id": "10e94059-bad6-447a-ae50-23f7a336df6e",
          "name": "networklistv1network-listsnetworklistidhistorysync2dpointextended",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId/history"
              ],
              "query": [
                {
                  "key": "extended",
                  "value": "extended",
                  "disabled": false
                },
                {
                  "key": "sync%2dpoint",
                  "value": "sync%252dpoint",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Activation Snapshot"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e2142d2-f9ff-4769-9d7c-3bbd405fd88c"
            }
          ]
        },
        {
          "id": "1d51f0fe-4643-492c-9100-88f9bf1b2504",
          "name": "networklistv1network-listssearchexpressionlisttypeextendedincludedeprecated",
          "request": {
            "url": "http://developer.akamai.com/network-list/v1/network_lists/search?expression=expression&extended=extended&includeDeprecated=includeDeprecated&listType=listType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Search Network Lists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be4e62fd-8566-43d1-907e-afe2eeb1fedf"
            }
          ]
        },
        {
          "id": "409e31ad-0b20-4938-9628-86baa2858050",
          "name": "networklistv1network-listsnetworklistidshare",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "network-list/v1/network_lists/:networkListId/share"
              ],
              "variable": [
                {
                  "id": "networkListId",
                  "value": "networkListId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Share a Network List"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b7cf04d2-4f6d-48bb-b20b-08c424138632"
            }
          ]
        }
      ]
    },
    {
      "name": "All",
      "item": [
        {
          "id": "f2085a18-4e26-4d4e-a4a6-7f050d645ec7",
          "name": "all",
          "request": {
            "url": "http://developer.akamai.com/ALL?networkListId=networkListId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Sharing Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe79b36e-91a9-4f77-aab4-6c06e1452580"
            }
          ]
        }
      ]
    },
    {
      "name": "Prolexic",
      "item": [
        {
          "id": "a0b8b0dc-39a8-4560-85f9-b13a023ae32e",
          "name": "prolexicanalyticsv1eventscontractcontract",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "prolexic-analytics/v1/events/contract/:contract"
              ],
              "variable": [
                {
                  "id": "contract",
                  "value": "contract",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bf827779-3742-4031-86f8-cb1804e391b5"
            }
          ]
        },
        {
          "id": "cfc9a653-a487-4949-a25b-daa2ac2e2fcb",
          "name": "prolexicanalyticsv1criticaleventscontractcontract",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "prolexic-analytics/v1/critical-events/contract/:contract"
              ],
              "variable": [
                {
                  "id": "contract",
                  "value": "contract",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Critical Events"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5223f2d7-fb5c-4739-b87e-771772b22652"
            }
          ]
        },
        {
          "id": "9a057045-1342-4215-8a7b-5a52fafd49ba",
          "name": "prolexicanalyticsv1metrictypes",
          "request": {
            "url": "http://developer.akamai.com/prolexic-analytics/v1/metric-types",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Metric Types"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e8052e6-c2bb-4b44-8c0b-9b7056e73449"
            }
          ]
        },
        {
          "id": "d5739689-f1bb-4156-8a95-27ba70dbc222",
          "name": "prolexicanalyticsv1attackreportscontractcontractstartstartendend",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "prolexic-analytics/v1/attack-reports/contract/:contract/start/:start/end/:end"
              ],
              "variable": [
                {
                  "id": "contract",
                  "value": "contract",
                  "type": "string"
                },
                {
                  "id": "end",
                  "value": "end",
                  "type": "string"
                },
                {
                  "id": "start",
                  "value": "start",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Attack Reports"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d32e3214-3f46-4b75-b1e2-944cd325522d"
            }
          ]
        },
        {
          "id": "b1b489c5-11d9-4638-8a52-92308221d434",
          "name": "prolexicanalyticsv1attackreportcontractcontractattackidattackid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "prolexic-analytics/v1/attack-report/contract/:contract/attack-id/:attackId"
              ],
              "variable": [
                {
                  "id": "attackId",
                  "value": "attackId",
                  "type": "string"
                },
                {
                  "id": "contract",
                  "value": "contract",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Attack Report"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50840c99-d8a7-4756-8f0d-55e5a1160afa"
            }
          ]
        }
      ]
    },
    {
      "name": "Type",
      "item": [
        {
          "id": "103f1cea-b2cd-413d-9035-93ed2e937ad0",
          "name": "type",
          "request": {
            "url": "http://developer.akamai.com/type",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Get Metrics Data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a295fa06-29ac-4ae6-b3aa-2f47aea58a11"
            }
          ]
        }
      ]
    },
    {
      "name": "Papi",
      "item": [
        {
          "id": "f0c498e5-dca7-4c9f-bb72-f95d59d0b889",
          "name": "papiv0groups",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/groups/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de0fa569-506b-41e2-b49b-8c42837b66f8"
            }
          ]
        },
        {
          "id": "719e337e-64f2-43df-a41b-8a7301eaa244",
          "name": "papiv0contracts",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/contracts/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Contracts"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85ea4ea3-d002-4e70-8f04-2f0809791483"
            }
          ]
        },
        {
          "id": "32e41292-dd5f-47dd-835b-10117954d34c",
          "name": "papiv0productscontractid",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/products/{?contractId=contractId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Products"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9459a5af-67fe-4c18-a242-4c0f1415b3bd"
            }
          ]
        },
        {
          "id": "89da3446-cb40-4ebd-81d3-16aaef15bfb1",
          "name": "papiv0cpcodescontractidgroupid",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/cpcodes/?contractId=contractId&groupId=groupId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List CP Codes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "89ea5734-df83-480c-a193-debd68d07005"
            }
          ]
        },
        {
          "id": "82a89765-a91d-4fab-8e10-688bef25c3f5",
          "name": "papiv0cpcodescontractidgroupid",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/cpcodes/?contractId=contractId&groupId=groupId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea9048cc-bb78-40ce-854d-81c0289dad24"
            }
          ]
        },
        {
          "id": "172ad740-6ece-4a91-8bf2-739b314724ce",
          "name": "papiv0cpcodescpcodeidcontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/cpcodes/:cpcodeId"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "cpcodeId",
                  "value": "cpcodeId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a CP Code"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dc158a8e-32b7-4a0f-b9de-2a494e08d2b2"
            }
          ]
        },
        {
          "id": "c5b60767-d554-4e15-bb79-42135095d347",
          "name": "papiv0edgehostnamescontractidgroupidoptions",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/edgehostnames/?contractId=contractId&groupId=groupId&options=options",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Edge Hostnames"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6e55c14c-952f-4045-a4a7-9c2fbed6e369"
            }
          ]
        },
        {
          "id": "0817730d-61ff-45bd-80d6-e6f763b0858c",
          "name": "papiv0edgehostnamescontractidgroupidoptions",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/edgehostnames/?contractId=contractId&groupId=groupId&options=options",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Edge Hostname"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ee4db29-844a-4860-803b-7e17b7060cc7"
            }
          ]
        },
        {
          "id": "850724fe-e958-4e9b-bf37-90e65c40a9ea",
          "name": "papiv0edgehostnamesedgehostnameidcontractidgroupidoptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/edgehostnames/:edgeHostnameId"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                },
                {
                  "key": "options",
                  "value": "options",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "edgeHostnameId",
                  "value": "edgeHostnameId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Edge Hostname"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07005b05-3961-4c76-9d07-0b73ef956287"
            }
          ]
        },
        {
          "id": "e2c05da6-9b53-4027-8b61-d4c5a717d9c5",
          "name": "papiv0propertiescontractidgroupid",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/properties/{?contractId=contractId&groupId=groupId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f0035b18-4126-47b7-8d55-70dd6b66cdd0"
            }
          ]
        },
        {
          "id": "2bdbe49b-bb6f-4c50-b9f1-ee0d4117ffad",
          "name": "papiv0propertiescontractidgroupid",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/properties/?contractId=contractId&groupId=groupId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create or Clone a Property"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c766a51-ff8c-4dd6-814d-2e6171775a6b"
            }
          ]
        },
        {
          "id": "f614bf28-3238-4a05-aa19-614c46128c26",
          "name": "papiv0propertiespropertyidcontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Property"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54644feb-b4f4-4598-8976-2be640792f27"
            }
          ]
        },
        {
          "id": "e22e68c3-4cc7-42af-a1a7-568fca18c0cd",
          "name": "papiv0propertiespropertyidversionscontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/versions"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Property Versions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9db7aaf0-7f7f-4657-b91a-18fc62217d99"
            }
          ]
        },
        {
          "id": "97715289-77af-4064-a6e8-139f3cbb40e4",
          "name": "papiv0propertiespropertyidversionslatestcontractidgroupidactivatedon",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/versions/latest"
              ],
              "query": [
                {
                  "key": "activatedOn",
                  "value": "activatedOn",
                  "disabled": false
                },
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Property&#8217;s Latest Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d79dbda8-d92f-4f88-a59c-cdbc5671c780"
            }
          ]
        },
        {
          "id": "e3cdad46-0bc6-424a-a681-ea470e7deed5",
          "name": "papiv0propertiespropertyidversionspropertyversionavailablecriteriacontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/versions/:propertyVersion/available-criteria"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                },
                {
                  "id": "propertyVersion",
                  "value": "propertyVersion",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Available Criteria"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f705fa4-e246-4785-82ca-26f7ac7379a0"
            }
          ]
        },
        {
          "id": "e2ce471e-03ff-4c65-8a18-03a3292fd716",
          "name": "papiv0propertiespropertyidversionspropertyversionhostnamescontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/versions/:propertyVersion/hostnames/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                },
                {
                  "id": "propertyVersion",
                  "value": "propertyVersion",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List a Property Version&#8217;s Hostnames"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf270415-975f-4d80-9d06-515b432fdb08"
            }
          ]
        },
        {
          "id": "8d82624d-453f-4d30-a6e8-c0afc8a4c906",
          "name": "papiv0propertiespropertyidversionspropertyversionrulescontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/versions/:propertyVersion/rules/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                },
                {
                  "id": "propertyVersion",
                  "value": "propertyVersion",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Property Version&#8217;s Rule Tree"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13fc89b8-3149-4f32-ac0a-267899e0c0a6"
            }
          ]
        },
        {
          "id": "c27a8a3c-139d-4067-afed-92fe93be4089",
          "name": "papiv0propertiespropertyidversionspropertyversionrulescontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/versions/:propertyVersion/rules/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                },
                {
                  "id": "propertyVersion",
                  "value": "propertyVersion",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Property Version&#8217;s Rule Tree"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83567786-971c-40b5-9e5b-0c61cedfdd70"
            }
          ]
        },
        {
          "id": "e9e76ea0-2e3f-4600-968d-84de5edc18d5",
          "name": "papiv0propertiespropertyidactivationscontractidgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/properties/:propertyId/activations/"
              ],
              "query": [
                {
                  "key": "contractId",
                  "value": "contractId",
                  "disabled": false
                },
                {
                  "key": "groupId",
                  "value": "groupId",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List a Property&#8217;s Activations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be9a5235-c0bc-4545-ba05-420bbcb8b0cd"
            }
          ]
        },
        {
          "id": "51b9d888-0d58-4247-8151-145f9339e574",
          "name": "papiv0ruleformats",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/rule-formats",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Available Rule Formats"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad0248e3-006d-4566-a356-c10c97d8ea86"
            }
          ]
        },
        {
          "id": "40c1b5dd-f226-4587-9831-403fdb802f59",
          "name": "papiv0schemasrequestfilename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/schemas/request/:filename"
              ],
              "variable": [
                {
                  "id": "filename",
                  "value": "filename",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Request&#8217;s JSON Schema"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0858fd77-5b81-47a5-95f8-e20e96ff92ad"
            }
          ]
        },
        {
          "id": "7704f793-bc27-4015-82cd-969b3090dde8",
          "name": "papiv0schemasproductsproductidruleformat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "papi/v0/schemas/products/:productId/:ruleFormat"
              ],
              "variable": [
                {
                  "id": "productId",
                  "value": "productId",
                  "type": "string"
                },
                {
                  "id": "ruleFormat",
                  "value": "ruleFormat",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Rule Format&#8217;s JSON Schema"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7072a8c8-1e7b-4df4-97fc-1877a1f6d5d2"
            }
          ]
        },
        {
          "id": "6e67719e-189d-44b8-90a4-cd5aed286943",
          "name": "papiv0clientsettings",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/client-settings",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Client Settings"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34911fb2-e1d4-4bfb-b7c4-eb470d51046c"
            }
          ]
        },
        {
          "id": "be04e498-d126-41bc-b81f-2841a6b1c3cc",
          "name": "papiv0clientsettings",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/client-settings",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update Client Settings"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c643ad74-ffbb-4872-8303-b8e375673cbc"
            }
          ]
        },
        {
          "id": "1ac37a94-cd41-44d9-893f-5fcce1206678",
          "name": "papiv0build",
          "request": {
            "url": "http://developer.akamai.com/papi/v0/build",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Build Details"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad22e2d8-ac9a-4665-aaed-273b228a4b1b"
            }
          ]
        }
      ]
    },
    {
      "name": "Versions",
      "item": [
        {
          "id": "4c1710f6-3fff-45ac-b679-db6da5c52b1b",
          "name": "createfromversion",
          "request": {
            "url": "http://developer.akamai.com/createFromVersion?contractId=contractId&groupId=groupId&propertyId=propertyId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Property Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2c6a2fd2-7a36-41fb-8920-952434df5882"
            }
          ]
        }
      ]
    },
    {
      "name": "Accept",
      "item": [
        {
          "id": "fdaf8ef3-838c-4360-bd70-3929114f4645",
          "name": "accept-textxml",
          "request": {
            "url": "http://developer.akamai.com/Accept: text/xml?contractId=contractId&groupId=groupId&propertyId=propertyId&propertyVersion=propertyVersion",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Property Version"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "854c5138-d2f0-4ef4-aaba-9e6089ee0ea8"
            }
          ]
        }
      ]
    },
    {
      "name": "CName",
      "item": [
        {
          "id": "cf7b6f06-1763-4f4a-8ead-bf4af2d70549",
          "name": "cnamefrom",
          "request": {
            "url": "http://developer.akamai.com/cnameFrom?contractId=contractId&groupId=groupId&propertyId=propertyId&propertyVersion=propertyVersion",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Update a Property Version&#8217;s Hostnames"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7d6a8efa-583d-4d24-b4f4-191f6989d5fc"
            }
          ]
        }
      ]
    },
    {
      "name": "Activations",
      "item": [
        {
          "id": "2e756321-e976-4591-92a3-3f20c9b0a028",
          "name": "createNewActvation",
          "request": {
            "url": "http://developer.akamai.com/{&quot;type&quot;:&quot;/papi/v0/activation-warnings-not-acknowledged&quot;}?contractId=contractId&groupId=groupId&propertyId=propertyId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Activation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1b91ba4-64bf-4f1e-919a-827637660f50"
            }
          ]
        }
      ]
    },
    {
      "name": "Retry",
      "item": [
        {
          "id": "d5c14a39-de48-4f23-a600-f3818f377365",
          "name": "retryafter",
          "request": {
            "url": "http://developer.akamai.com/Retry-After?activationId=activationId&contractId=contractId&groupId=groupId&propertyId=propertyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an Activation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9caa296-8e5a-42b2-bbb0-40b7c19f0cc8"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "b4b7d7ff-a242-4172-b375-b0777a203dad",
          "name": "status",
          "request": {
            "url": "http://developer.akamai.com/status?activationId=activationId&contractId=contractId&groupId=groupId&propertyId=propertyId",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Cancel a Pending Activation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "17939215-ff53-4b47-986e-dd0bdf072330"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscription",
      "item": [
        {
          "id": "c5dfa2df-1ca8-4fe2-881f-57d455d50a0c",
          "name": "subscriptionid",
          "request": {
            "url": "http://developer.akamai.com/subscriptionId?contractId=contractId&groupId=groupId",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a Secure Edge Hostname"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1dade5a-2f45-43f5-8706-3d6c19f9335a"
            }
          ]
        }
      ]
    }
  ]
}