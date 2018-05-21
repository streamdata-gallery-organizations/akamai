{
  "info": {
    "name": "Akamai API List Professional Services Cases",
    "_postman_id": "3df4b38d-f8d4-476d-a771-b9d12b8a8bb3",
    "description": "List Professional Services Cases",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "d9b8a482-d35d-45b2-ba18-c5beb9f92e6c",
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
              "id": "b95d0864-2d9c-46fe-8ebc-fa400e2fa3a8"
            }
          ]
        },
        {
          "id": "6c61ae05-1453-4826-9632-92377f54fead",
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
              "id": "1c185cf5-25f7-4013-bb9e-16bbfc5f71e4"
            }
          ]
        },
        {
          "id": "080fda11-4150-4718-a8e0-62b74cbbd2f3",
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
              "id": "05223d58-7f96-4e3d-a600-587ac444b81b"
            }
          ]
        },
        {
          "id": "c54f5d01-6d5e-480d-803e-44b916bf76a5",
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
              "id": "b7325efa-4803-4ce7-9975-da10b8423015"
            }
          ]
        },
        {
          "id": "5edbf9f9-1d70-44e3-ab9f-a237450c06ec",
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
              "id": "fc65e032-4d4b-4e07-895d-f402b4482c15"
            }
          ]
        },
        {
          "id": "b89b5a72-50e5-4ced-9f43-27b300aca6b6",
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
              "id": "9726a142-cf20-400e-a3b9-c274a702ff4f"
            }
          ]
        },
        {
          "id": "5eaa1695-5d1b-4990-899b-3ec58d921304",
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
              "id": "d9fb51ff-ecb7-4964-b0a0-72f4ab8db67a"
            }
          ]
        },
        {
          "id": "81f6d230-4f2f-4d1a-ab13-919092cc67f8",
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
              "id": "72db9cc9-b43e-4cf4-85a2-f5433364982f"
            }
          ]
        },
        {
          "id": "a4133fe7-4a31-48cc-a428-a76163cd32e2",
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
              "id": "d20b8758-b088-4bb5-8360-4f0b6bcb5388"
            }
          ]
        },
        {
          "id": "e940b6ad-915a-4aff-a0c6-5270e13929e3",
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
              "id": "d8f495e9-0004-4d1e-a3f6-22e8c89baa9e"
            }
          ]
        },
        {
          "id": "2a8978bb-abd3-4886-822e-d4aeaec2900a",
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
              "id": "26ab9976-35d7-478c-bed3-dcb6d342b07b"
            }
          ]
        },
        {
          "id": "7b8af608-8441-4b70-95e7-9812157fd353",
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
              "id": "454b6765-d64c-4259-9742-a734f0e26a5f"
            }
          ]
        },
        {
          "id": "7bc9980d-2e86-471f-82f6-f0120cee7a9f",
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
              "id": "e8632a0b-3afa-4988-ab90-fd8fb669a1c7"
            }
          ]
        },
        {
          "id": "354aac29-52fc-4331-8df1-41aaff8ec0de",
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
              "id": "a8717a5f-ac05-4bf1-96ee-24629e45bd0f"
            }
          ]
        },
        {
          "id": "2e041ac3-91c5-4edc-a3bc-9b5761b47d3b",
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
              "id": "d7262e4b-44dc-4bb4-962d-de002a4bd95b"
            }
          ]
        },
        {
          "id": "dfbfbf21-b443-4862-95da-cb84a60da05c",
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
              "id": "2705383d-99e1-4883-9c6d-8ec31659091a"
            }
          ]
        },
        {
          "id": "5e4788bb-cc93-4d33-b594-7f3757e2cb32",
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
              "id": "4e564d2c-a3c4-44f3-b07f-c44c4b703c70"
            }
          ]
        },
        {
          "id": "6c030874-feb3-45d6-af15-0f8a18ed4592",
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
              "id": "8f802be9-1527-4230-ac59-a220b6b5c0cf"
            }
          ]
        },
        {
          "id": "18244f9f-590b-43cf-afe4-0bd039415f2c",
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
              "id": "6e6ba03f-8b5f-4cbc-8588-48f5b6548b4a"
            }
          ]
        },
        {
          "id": "1e7c8f43-5b1d-4f31-a3f9-0e87d9decf9b",
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
              "id": "ce08dea4-dddb-4849-a5b9-bbfeedb9833f"
            }
          ]
        },
        {
          "id": "0d433c61-d52d-447f-8f76-ec3e3261868d",
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
              "id": "54596648-af51-43f0-8e42-6d6d40f9ab36"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "a5322bf0-4bfa-489d-8775-f9ab99a8e486",
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
              "id": "a432bd7c-e95d-4820-8e88-cfd4f7f3c9c5"
            }
          ]
        },
        {
          "id": "2fca7704-5536-4833-932c-f1cf129d75a1",
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
              "id": "9a5c0dcb-4ca1-4bf6-a1bd-40d19cecf2d3"
            }
          ]
        },
        {
          "id": "d5b8c967-d4f2-4c94-a84d-d25a848d4ff5",
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
              "id": "0926facd-e911-410e-a12e-bb0863e1287b"
            }
          ]
        },
        {
          "id": "3c6f377c-78f3-48b6-9e48-1a09e91ae724",
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
              "id": "b9edb4bd-2729-42ad-96bd-3301b1303b62"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "4cba8a79-0d53-4ca4-8c29-e3163d5fbc95",
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
              "id": "bf038b24-2780-4002-81ed-6ede4428208c"
            }
          ]
        },
        {
          "id": "3e352bff-ec22-4d67-911c-f4c7cf6a00a7",
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
              "id": "e0a1717f-260c-483d-aca2-d444412ee2c9"
            }
          ]
        },
        {
          "id": "f5f22ec5-004a-4d67-9c8e-81fe883f31d6",
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
              "id": "db3ff190-8662-4e6e-a5b9-74515a9c12bb"
            }
          ]
        }
      ]
    }
  ]
}