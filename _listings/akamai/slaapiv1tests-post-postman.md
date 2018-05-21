{
  "info": {
    "name": "Akamai API Create a New Test Configuration",
    "_postman_id": "41451ce1-4bff-4304-9dd6-66449125eb9b",
    "description": "Create a New Test Configuration",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "bfb4ce79-4205-44c8-8661-b33c1a5bfd84",
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
              "id": "aff80666-9bd4-41c5-9e9e-55fbd0e323fe"
            }
          ]
        },
        {
          "id": "caf1c485-0302-4bb2-ae42-3c5b8f50c477",
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
              "id": "16651e18-df1f-4ad9-b9a2-0d4d665aa6f1"
            }
          ]
        },
        {
          "id": "e72f1cb4-ce3f-4ee6-8828-9ed095d8e7fc",
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
              "id": "ac12de83-5477-4037-ac0c-73be789e909c"
            }
          ]
        },
        {
          "id": "0e7e3aa7-1e2b-4f67-bd38-9cc409530a1d",
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
              "id": "d0b2905a-6bfc-4719-88bb-2fdd94f64fac"
            }
          ]
        },
        {
          "id": "6ea7c63f-7718-44eb-9f01-169f7bc7608c",
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
              "id": "0f5c983a-f51f-462c-b8c5-d67110a6d3b5"
            }
          ]
        },
        {
          "id": "7c5f514e-e1ae-45f3-86cb-e0b9489259b3",
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
              "id": "5e8b21e3-78bd-432e-b11d-c9b7bce85074"
            }
          ]
        },
        {
          "id": "99655945-3a27-45d1-8d88-cbf861116098",
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
              "id": "57d966d6-7ebb-4b4e-9ff6-d152053feb5d"
            }
          ]
        },
        {
          "id": "5f7f1e88-e7ba-4159-b461-aa1945be7e13",
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
              "id": "535e9c47-a6e1-451a-86f7-43630a1b3837"
            }
          ]
        },
        {
          "id": "58d474a3-2d14-4dd6-94c4-636a7215efd0",
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
              "id": "b3e0ab25-b221-4c85-acea-8854d9ee975d"
            }
          ]
        },
        {
          "id": "3e7a7475-ac71-44f8-a068-317508b63d2c",
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
              "id": "e374df8b-87aa-431f-b705-af0baaa31778"
            }
          ]
        },
        {
          "id": "15c40a73-a768-4f81-9c02-3aa694f831c0",
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
              "id": "a8a9d4c6-f5d0-48ae-8853-23f2b5b05f9f"
            }
          ]
        },
        {
          "id": "910ee75e-45dd-4d37-8c0f-d2765c397e1f",
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
              "id": "df55c39a-1037-4178-87f4-ed4b2e49c38c"
            }
          ]
        },
        {
          "id": "ad9efb6a-bd38-4494-8e16-ca35dcde3b67",
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
              "id": "538c71bd-ab09-435e-a8a2-3d9627dcc39b"
            }
          ]
        },
        {
          "id": "4e108772-1ab0-447a-b40f-07e232087b7d",
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
              "id": "7d89171b-95ce-42e2-82e1-da85b1612577"
            }
          ]
        },
        {
          "id": "ffbd033d-1f49-4ed2-8c45-4f142a6013e9",
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
              "id": "de8b0310-ada5-4ebd-a7e1-1611c22fb526"
            }
          ]
        },
        {
          "id": "c4fbf784-fc04-40d9-9840-6b27a5581a81",
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
              "id": "417580de-9109-4562-9d0c-fa1d79fe96de"
            }
          ]
        },
        {
          "id": "45929a7b-e3cc-4ff3-b909-8fd183e2d294",
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
              "id": "87323f6a-4f84-43d8-8655-3725bba067ba"
            }
          ]
        },
        {
          "id": "0591da3a-fa68-4271-8903-46877c7ec0a0",
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
              "id": "ee3972c5-591d-4885-b2d5-0d731fc57e25"
            }
          ]
        },
        {
          "id": "439d48b3-9a3f-4889-bbb2-f8454fe5a69e",
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
              "id": "d4aaa8af-8156-4966-b031-5ad2d4048776"
            }
          ]
        },
        {
          "id": "0ea76132-6ce3-4a02-8388-c283170a406e",
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
              "id": "e0d1c0d3-1f7f-4095-9244-db64b11181d0"
            }
          ]
        },
        {
          "id": "33b0cd2d-c41f-4933-8925-3c8652fd9d4b",
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
              "id": "8bdec4e2-d0c6-4e42-b05f-6a1789537a9f"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "f90799ca-33d6-4cc8-9a5c-9f4c3a7f9000",
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
              "id": "b49bb3ec-663c-4e59-8e02-23d37adc4626"
            }
          ]
        },
        {
          "id": "6559638d-17ae-485d-b36d-a281e6b1e1a9",
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
              "id": "92219d89-e0f9-4d46-9a72-3246d052ad48"
            }
          ]
        },
        {
          "id": "69dcd67b-bab3-49af-8152-cc039af261ef",
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
              "id": "ee454ed5-60ff-40ab-b1f8-bb9e6dd697cd"
            }
          ]
        },
        {
          "id": "1f814c5f-8595-42a9-9daa-5ba9d11cacc7",
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
              "id": "d67668fd-fddf-4014-bc34-88a4e96d5bd6"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "adce2ee2-7675-4f32-b046-9f49609437e5",
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
              "id": "91ede3ce-3d8a-4a75-bc26-01947de0a918"
            }
          ]
        },
        {
          "id": "18407d92-b16a-4339-8f7a-8331c1537a88",
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
              "id": "f4b59dcb-f9cc-48fd-a5d1-b2b625ea4c4d"
            }
          ]
        },
        {
          "id": "2ae624e2-a9d2-4548-bb27-00fe4d2b6758",
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
              "id": "46821805-b86f-4707-baa5-c6494d396ed5"
            }
          ]
        },
        {
          "id": "cc68ae80-6d3a-4eda-803c-c4c63ae6e9bd",
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
              "id": "de76bda7-b6bd-4ffe-bee9-8e6d35bec70c"
            }
          ]
        },
        {
          "id": "ee7051d1-274b-410b-99bd-4299dd33ee83",
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
              "id": "5dd60e97-a2b7-43bf-bcb5-3ee3c9db8339"
            }
          ]
        },
        {
          "id": "310784f7-116e-4df7-b0b8-b2c2ce77afee",
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
              "id": "e2dd365d-43ed-4de9-bbc9-dc4714f076f7"
            }
          ]
        },
        {
          "id": "9dc132d2-44b1-4aba-b229-ea9839570e09",
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
              "id": "2444c9dd-f230-4ccf-8303-0e7f354c53c8"
            }
          ]
        },
        {
          "id": "86429e8f-e32d-4a5e-992c-b10ad2489c2b",
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
              "id": "be45cb13-4c37-40d6-abe6-3b68edccceb7"
            }
          ]
        },
        {
          "id": "42b74ebc-d968-470d-a38c-1d88d29dce4e",
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
              "id": "a70d1b71-f40d-42a1-886e-b5ecc3ef3036"
            }
          ]
        }
      ]
    },
    {
      "name": "Ccu",
      "item": [
        {
          "id": "b00b09fe-5a79-4e94-a347-f2f035bdc796",
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
              "id": "40d87f65-1357-4b36-95a5-468f07f3c733"
            }
          ]
        },
        {
          "id": "8e509e95-f54c-43e0-9a45-728ddc180d70",
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
              "id": "6fd7ca77-2eab-40f7-84ae-2375e2aa2afb"
            }
          ]
        },
        {
          "id": "ba4a4b91-dd1a-4bb6-b67d-915ba96dd70d",
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
              "id": "87713d78-689d-42fb-94de-acb35c7204cd"
            }
          ]
        },
        {
          "id": "c3931242-c09a-41f4-8832-62e578b858eb",
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
              "id": "3508c97a-38cc-4c50-8182-c0b128c1de21"
            }
          ]
        },
        {
          "id": "06ced0bf-afe4-4abb-8ef5-827fae3448a3",
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
              "id": "160b94c4-aca4-4d8c-842a-d62304a06390"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlet",
      "item": [
        {
          "id": "de640f42-c870-4db0-8f00-f3fd905d980b",
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
              "id": "021d3029-3210-449a-a030-9e8f6f15d96c"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlets",
      "item": [
        {
          "id": "d5f1e62b-aa10-419e-bf87-b674c308d41f",
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
              "id": "13669722-d714-4d37-bfda-11983f9c74fe"
            }
          ]
        },
        {
          "id": "41f37188-d11d-4efb-9a22-c9d8ec1d3c70",
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
              "id": "f486ab17-497b-40d3-842a-2693cccd0348"
            }
          ]
        },
        {
          "id": "e7f2d81c-5d5c-4e16-a2cd-fa3dcacd43cd",
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
              "id": "bce7acb0-66c1-4d2c-9355-9f7640a3742b"
            }
          ]
        },
        {
          "id": "4e5e2e64-97ad-45f0-b8be-d45bcacd6f34",
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
              "id": "4da01e11-3681-4bec-af6a-8e872a6f74cd"
            }
          ]
        },
        {
          "id": "dcb8d673-0c97-4bdc-b5e4-6ace97458bc7",
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
              "id": "547c5f5d-7d18-4367-a1b9-4cd134ef5978"
            }
          ]
        },
        {
          "id": "22348206-83bd-4ef0-ba66-e2170769ef9c",
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
              "id": "37589d13-f19b-4773-8a52-e7bc13816174"
            }
          ]
        },
        {
          "id": "badeff4f-226b-4823-8310-37f650570954",
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
              "id": "fe8f5e49-7436-4647-8973-1354655e29fa"
            }
          ]
        },
        {
          "id": "1dfa276e-1864-48bd-8724-8a1e25bfb607",
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
              "id": "23c4b75f-3dd8-4a38-818b-0ff0b3a699b0"
            }
          ]
        },
        {
          "id": "ee373594-6387-49c8-9d42-568d7da322cc",
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
              "id": "35a42f24-9fd6-4d7f-8c96-9c09bb6ba240"
            }
          ]
        },
        {
          "id": "c3effa10-8752-4f6a-a632-6ab833b16b67",
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
              "id": "a89407eb-384f-43d9-88cb-3d3c2eb1f600"
            }
          ]
        },
        {
          "id": "3657d5b7-e17b-4de8-abf1-7b862014f45f",
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
              "id": "c35313af-bc91-4672-b581-e2493fb6ce4d"
            }
          ]
        },
        {
          "id": "777b4f9e-eea2-46f0-a441-5d48ff4aa8ca",
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
              "id": "eec583dc-af6a-487e-8ab1-567ebaacc379"
            }
          ]
        },
        {
          "id": "1f7f257f-15e5-4836-a8d6-34b7f4c9917f",
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
              "id": "13d47f60-cb83-4902-a2d0-6c7c6bd7f4a7"
            }
          ]
        },
        {
          "id": "b08af9ca-2b91-4865-9efc-7347a7c331af",
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
              "id": "b385bc3d-8b46-42d3-bc44-f3ad651af189"
            }
          ]
        },
        {
          "id": "c3635406-7739-4c91-ac77-0d87a808923e",
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
              "id": "02e8d113-f479-4d6c-b525-72134e5446e5"
            }
          ]
        },
        {
          "id": "6734e492-5f7d-4e53-b386-728d68ecb216",
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
              "id": "47217e9d-12e5-4ce2-b786-ac4853d36a79"
            }
          ]
        },
        {
          "id": "8a34876e-2f5a-476e-8864-da7cbe0803c0",
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
              "id": "fdd3fa4c-8032-4c8b-864c-23a76efe25ca"
            }
          ]
        },
        {
          "id": "7a3dac12-2e94-4f2c-b81e-28ea78650525",
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
              "id": "795769c3-a1cb-445f-9bdd-95ec6f456618"
            }
          ]
        },
        {
          "id": "45748fcf-2b38-43d5-b2a7-f7ae649572da",
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
              "id": "dcc4b32d-b3fb-47ad-a059-ff02d8707199"
            }
          ]
        },
        {
          "id": "3b6f250f-0b12-4d32-a2d0-fb3f76ca8684",
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
              "id": "f675e9f9-8b18-4751-b5d5-491f13938974"
            }
          ]
        },
        {
          "id": "35fd0c04-f13f-4504-82a9-d0725e8347c0",
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
              "id": "96416bff-6a1d-47f2-b123-16bccd13a477"
            }
          ]
        },
        {
          "id": "8253fc60-d06d-466a-b73d-c22fa531d27f",
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
              "id": "d846f7a4-ee13-4372-a855-3d6b5f72a262"
            }
          ]
        },
        {
          "id": "cfe789f3-33dd-4b99-b04c-1bb161e64d10",
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
              "id": "a022d224-94ea-441f-aa65-01dfcc240387"
            }
          ]
        },
        {
          "id": "c4ebc6d2-99a1-4d88-9558-66be054d0c25",
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
              "id": "338c8d09-7943-4c6c-be4e-f52ad9982c35"
            }
          ]
        },
        {
          "id": "7a550c3b-070b-4ac3-ad9d-9fa6a60f818b",
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
              "id": "056387a9-4c9b-4e97-972e-bd08a03576ad"
            }
          ]
        },
        {
          "id": "87a8300e-ea59-4fd3-b020-27515ccad387",
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
              "id": "caf15278-30a6-45c0-9f22-400ca749aff2"
            }
          ]
        },
        {
          "id": "d6bae570-bc4d-44f8-b0c3-d06964a4843b",
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
              "id": "509190c4-c9f8-40b7-8697-c25bccbd189f"
            }
          ]
        },
        {
          "id": "197debe5-e72a-4851-bd9e-26422e07a349",
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
              "id": "a5b10b9d-a9b6-4b11-ac1f-27e6f242e984"
            }
          ]
        },
        {
          "id": "d8a0820a-b395-48e1-abfc-311498cbb96c",
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
              "id": "429fe495-d7ae-4132-bd2c-7fc6830539ca"
            }
          ]
        },
        {
          "id": "4c494293-b591-426a-95cc-ae2744f84500",
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
              "id": "095497fe-2e69-49fc-adc0-b237fe720a2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudletcode",
      "item": [
        {
          "id": "d92fac91-b791-4095-bd6c-ebd7e8e1bcf2",
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
              "id": "e1e56c2b-8b24-452a-80bc-4316fd1d3fa5"
            }
          ]
        }
      ]
    },
    {
      "name": "Cps",
      "item": [
        {
          "id": "45e59d89-4f5d-4585-baa8-ceb41500ee40",
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
              "id": "ac5248f7-0a6c-4e3c-81e1-ea4079fcad9a"
            }
          ]
        },
        {
          "id": "821f148d-ed53-443b-bf80-7407bb5cda74",
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
              "id": "4a103329-aeb6-403c-8dbd-99b3f309154a"
            }
          ]
        },
        {
          "id": "c3ba888a-a33e-47d3-8cce-ac5fb4bd7352",
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
              "id": "7b25e509-ebba-4b01-9a66-338acecdd942"
            }
          ]
        },
        {
          "id": "d3acf638-5b64-45b4-86a8-40a2cdefe0fc",
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
              "id": "1e7c9545-9086-41c6-9afd-d3f02932d911"
            }
          ]
        },
        {
          "id": "60eccd2b-60e2-472a-b779-bad496afb0a4",
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
              "id": "5a8d85fc-eece-4db1-a275-7941b1cf05c9"
            }
          ]
        },
        {
          "id": "fe505e80-860b-4f39-ad15-84995b07fff8",
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
              "id": "bdb5ccfc-9325-419e-94ef-0c6405cb1aab"
            }
          ]
        },
        {
          "id": "e94cb71d-c8eb-40f7-91f7-6a74e8737982",
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
              "id": "3d4b132a-e59a-4d3f-b659-b2a497fc9640"
            }
          ]
        },
        {
          "id": "cbcd5e14-935b-4a75-9648-b8c6d04fd66f",
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
              "id": "0c952829-ff16-4f5f-9941-7fa7614ada5e"
            }
          ]
        }
      ]
    },
    {
      "name": "Information",
      "item": [
        {
          "id": "42b45191-d297-4a8f-8029-7d9037f40a7a",
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
              "id": "58e48b35-b6e1-43b0-a6ab-cc352e40a251"
            }
          ]
        }
      ]
    },
    {
      "name": "Update",
      "item": [
        {
          "id": "59e2fffd-d4bd-42fa-a2b0-e20e9ff476ff",
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
              "id": "f79e2f94-d6d0-43f8-9d25-e4a61d2154a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "b7d544dc-4a3b-4851-8f1a-61c4690ef9b7",
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
              "id": "519a0ad7-3d7a-4e5f-9614-644564e84cc9"
            }
          ]
        },
        {
          "id": "8c95ec8e-39f4-416d-8db2-0e781181b2b2",
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
              "id": "fe7d03e9-c677-49f7-97bb-f76b782413cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Diagnostic",
      "item": [
        {
          "id": "a3a42395-d05c-42f6-9211-4b1e377ea312",
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
              "id": "41a46a83-3731-443f-9d8a-e7ac116e9cea"
            }
          ]
        },
        {
          "id": "c29c6861-07ba-4143-a17d-00c99a21804a",
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
              "id": "ca81699e-3b00-4088-b7aa-868a92d2f17f"
            }
          ]
        },
        {
          "id": "ec98f524-5f44-4f99-bc8b-d184aa02ddca",
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
              "id": "76938b99-8416-4dd3-9b53-1197381eed91"
            }
          ]
        },
        {
          "id": "26a93d41-9559-43a9-a0a2-9f7e9214149e",
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
              "id": "37dd9f55-e0fc-4305-abe7-79c866cbcf9f"
            }
          ]
        },
        {
          "id": "76b1cfdf-22d7-4794-b286-a1be380a4ddb",
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
              "id": "509792d0-de72-4795-a4a9-e2c536bd3edb"
            }
          ]
        },
        {
          "id": "93d8444b-270a-43b6-b75d-3a60f91d8c80",
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
              "id": "22e54079-df3e-4a61-b553-6bba887394bf"
            }
          ]
        },
        {
          "id": "46bc5bb0-a762-430d-a2ef-1584adc20a29",
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
              "id": "093b82ad-b43e-42c6-89a9-0a6340be2eb3"
            }
          ]
        }
      ]
    },
    {
      "name": "Token",
      "item": [
        {
          "id": "d2d9babc-7666-4650-b323-3ceef39fb16c",
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
              "id": "9b1fbada-3f08-4d41-a249-c6a320c1f9b7"
            }
          ]
        },
        {
          "id": "5429a696-4b93-41b8-b6ef-495c22068c3e",
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
              "id": "516124be-3e70-456d-ad5f-3bf5f65ffcd8"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "a242de48-ab57-479e-9de4-a1ad95d4720e",
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
              "id": "efd327c6-3dca-4209-a05c-26b3b51f463d"
            }
          ]
        },
        {
          "id": "2f6d7df1-b06a-4904-a0cb-218acf1e077e",
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
              "id": "7825f427-e7ae-4b99-8a8e-f2b3bcbbcd99"
            }
          ]
        }
      ]
    },
    {
      "name": "Etp",
      "item": [
        {
          "id": "cfb6f98a-a8a5-4755-8f43-6a2b719cbe0c",
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
              "id": "af2705f0-5076-4341-9ce4-39f61d889ad5"
            }
          ]
        },
        {
          "id": "f974d2e8-f181-4c3e-ae0e-8b26b05bfdf2",
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
              "id": "96eca8e3-c084-402b-8803-6d09e1bc1e4b"
            }
          ]
        },
        {
          "id": "cc40f6a6-8b74-40fe-bf1e-a35fe3a02205",
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
              "id": "7b2c05d1-551c-4379-8a93-cce04c2df948"
            }
          ]
        },
        {
          "id": "5ecac26b-f5cf-42bd-a9b4-fe33a9c3d8ae",
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
              "id": "114fb5b8-5fd4-4f36-9da8-d2f0540070c1"
            }
          ]
        },
        {
          "id": "2a043629-c1eb-45cb-a779-b6826f05f559",
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
              "id": "6870c619-d8da-4298-935f-5b0b9e2437bb"
            }
          ]
        },
        {
          "id": "101727fa-ce5b-47ad-aaa5-d5ceaf8f5475",
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
              "id": "13cb0700-4b66-47f5-af30-1fd71641f37d"
            }
          ]
        },
        {
          "id": "10fac094-c945-4bd7-96c4-1df8541e40a1",
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
              "id": "287d4ac8-c1b2-4096-a5f7-97567dca0d1e"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "d0b44d8f-c814-4b03-b435-938333d0ffca",
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
              "id": "86d8c7d0-176f-4feb-9a72-410bc4ed0cb5"
            }
          ]
        },
        {
          "id": "1736f1ce-1f64-4159-95e8-0903737485ba",
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
              "id": "266983f5-6027-4091-95b7-0aa338769432"
            }
          ]
        },
        {
          "id": "f15bb617-37cc-4873-b343-db97c223dd96",
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
              "id": "cd0234ef-5b05-4015-bdcc-b3e07c964d1a"
            }
          ]
        },
        {
          "id": "81ea540c-125f-4c4d-871d-2798ec0438ae",
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
              "id": "d5de0ed0-3000-4c17-a2f9-b735f09e24a2"
            }
          ]
        },
        {
          "id": "5e6504dc-aaac-4431-a667-d1439f0c64e7",
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
              "id": "83468feb-7108-44d4-9a25-bc685bed00b3"
            }
          ]
        },
        {
          "id": "67cbdfe5-f27a-46ab-8a81-0376f7f8d51b",
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
              "id": "a4cff125-ec58-4a81-a367-e20550833aa3"
            }
          ]
        },
        {
          "id": "42c37ae0-5daf-4387-8584-4401dee616d0",
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
              "id": "aa9376d2-cdc0-4e69-8f7a-868cc69ff11b"
            }
          ]
        },
        {
          "id": "b1a1d5ca-1e56-4c06-bb70-e639ea794194",
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
              "id": "64c028b2-76ef-41ec-b04b-40240d9f32ed"
            }
          ]
        },
        {
          "id": "c3b12675-6018-44cf-b2b8-d95a627ed926",
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
              "id": "89c8ac2d-ba4e-464c-8891-041f88d40a8d"
            }
          ]
        },
        {
          "id": "25ea8c4b-8564-4589-a13f-3d126438c7aa",
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
              "id": "55cfcb02-3b51-4b0c-8083-4fb39320d22e"
            }
          ]
        },
        {
          "id": "e9ad6372-c62a-42c2-9a5a-e71617bd503a",
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
              "id": "0fc7f7d4-2f92-4071-a86e-498f7def6a0f"
            }
          ]
        },
        {
          "id": "9e9a37f4-f345-4d99-8b46-fc2009163925",
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
              "id": "b793c0f9-bad2-4673-8281-4b2fdf65b5b2"
            }
          ]
        },
        {
          "id": "f84024f9-857d-409f-8013-69c673450d1e",
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
              "id": "9bf4bfe6-94b3-4690-873f-3bef9fbc3f7e"
            }
          ]
        },
        {
          "id": "92ad5e7c-0dc1-4426-bfd0-04758891215e",
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
              "id": "5d9b50b5-245e-4579-8120-0619b0ae20d8"
            }
          ]
        },
        {
          "id": "c616c7b3-b2e9-45d4-830e-4b704a51afbb",
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
              "id": "a079fe8f-d418-4f15-8542-2f4c63f3fd66"
            }
          ]
        },
        {
          "id": "73bc28f8-e87d-496b-85c5-24c30b1a2e75",
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
              "id": "fb736dc0-0c4e-496d-9971-8982e8b155c1"
            }
          ]
        },
        {
          "id": "6c4f924e-d398-463e-b3d2-88f17991d695",
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
              "id": "f1b0fc8d-5260-4b7a-a264-36d8f7627c4d"
            }
          ]
        },
        {
          "id": "108946f7-e1de-4e23-ae31-024c2d47cb60",
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
              "id": "e1c645e3-eea4-4969-b0db-a4f730becf93"
            }
          ]
        },
        {
          "id": "7914dccc-369d-4765-b207-4a63cb9dc546",
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
              "id": "475c8a27-f711-4373-b11d-2990a9f67b06"
            }
          ]
        },
        {
          "id": "6981fea4-4c20-4029-b79b-378122eb24ce",
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
              "id": "91b6e88b-53cd-463e-8c63-c2619bb81df2"
            }
          ]
        },
        {
          "id": "8e58db79-b535-42dc-9024-7cebb60b3d25",
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
              "id": "c815bcfb-ce62-4018-a5d3-3a7a8bd2a60f"
            }
          ]
        },
        {
          "id": "4614ffd9-42a3-48c2-bdc9-906501968949",
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
              "id": "936f49ba-4d93-42e0-9559-2fbdf7307ac3"
            }
          ]
        },
        {
          "id": "5e068243-a2b4-4b41-b7fb-05c7b5fac522",
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
              "id": "33ca4a7e-c585-4078-b1ac-49cee0101254"
            }
          ]
        },
        {
          "id": "2e5b59b5-e690-4de9-88a6-5ae553dfa2b1",
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
              "id": "fa6de1d6-f820-4111-bd16-306b29dba810"
            }
          ]
        },
        {
          "id": "f0b8d1ca-5390-4b9e-bd5d-139c78c079e9",
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
              "id": "1d3d532e-04b1-4736-a506-86f01353296e"
            }
          ]
        },
        {
          "id": "235e888a-9b6b-4ccf-9c0f-3b0a7276295b",
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
              "id": "f71e2477-215a-4905-90a7-84963d2634ea"
            }
          ]
        },
        {
          "id": "0cf50a27-1e69-4fcc-b98e-d44f0386dcc4",
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
              "id": "d29d41a3-b56a-4db4-a890-595e4a6b217e"
            }
          ]
        },
        {
          "id": "1427aa6d-1169-4da2-806a-3b76a8148d6c",
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
              "id": "99dace37-bc6b-4764-bb12-2871fc81498d"
            }
          ]
        },
        {
          "id": "743cc9c9-5605-4aae-ab8a-eb32d54c769f",
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
              "id": "c9641178-4367-4a57-89b1-b00ee3c29397"
            }
          ]
        },
        {
          "id": "361f3a6a-3c83-4f4e-8588-401a5bac92c5",
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
              "id": "2e84ef1f-27eb-4150-8375-38666ea32f76"
            }
          ]
        },
        {
          "id": "8de10ffc-cf23-44b0-a212-a068fdc2dd71",
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
              "id": "1d4cb956-0547-4266-b581-fb22b0533b98"
            }
          ]
        },
        {
          "id": "c33ffd40-60e2-495a-bc17-09157357c1e1",
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
              "id": "f84d4095-73d8-420b-b8a6-ec27f6fed41f"
            }
          ]
        },
        {
          "id": "809a9354-68fe-4366-9979-45674b8e54e7",
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
              "id": "3cc03808-f4e8-4166-8f68-c1a4db4b6311"
            }
          ]
        },
        {
          "id": "4eca4771-16f8-4384-a47f-dddd751ccb92",
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
              "id": "92fa1f45-c430-4e24-9f81-bd61d01aa4cb"
            }
          ]
        },
        {
          "id": "19af3c56-84ef-4faa-a3bf-f26c032c4f3e",
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
              "id": "df02359b-4e6d-4963-b155-2d4da10f4f00"
            }
          ]
        },
        {
          "id": "4503ff56-06fe-4dd6-b2be-49e47b8e7a4b",
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
              "id": "12c7c96b-c658-476a-9d9b-b35c1df6d660"
            }
          ]
        },
        {
          "id": "9c8f977d-18df-41c7-90e9-b397bb29a66c",
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
              "id": "2d744246-26f2-4a29-b8d1-4fdef679fb0c"
            }
          ]
        },
        {
          "id": "770d25c2-11e4-4984-a515-858e73afe29b",
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
              "id": "104360bb-24de-4253-817a-9e9865c17bfb"
            }
          ]
        },
        {
          "id": "8ba70a3c-eedb-4f85-a9fb-c13613fa7c81",
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
              "id": "063d15d0-2a5b-4e2f-b8d9-9ab29ab63a1d"
            }
          ]
        },
        {
          "id": "4fd856ca-a973-4d4d-9800-45fe17654740",
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
              "id": "3ac8d3a5-d017-4ae1-bb9e-dc4d215f1813"
            }
          ]
        },
        {
          "id": "5aeccb2a-3e3a-493f-8ac4-a494fe8249b6",
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
              "id": "dd88644d-a7c2-4a03-9763-ba9295c0c9a8"
            }
          ]
        },
        {
          "id": "5ef90888-fad2-40e4-b1e1-479e83934268",
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
              "id": "be816178-37b1-4b47-9a82-0413107a0c61"
            }
          ]
        },
        {
          "id": "5635f449-2880-433a-a54f-9607bf46fe72",
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
              "id": "babb79b4-3df6-489a-a534-8530d41bbe27"
            }
          ]
        },
        {
          "id": "5c3b64cb-7886-4bb5-9cfd-0bbf4c9a2f56",
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
              "id": "66ca9e3f-f873-47f6-a45f-aad09f8294e7"
            }
          ]
        },
        {
          "id": "4da80115-4cfd-47f0-8a31-e636745975a5",
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
              "id": "814b52b2-83ce-44d1-bb91-29c1567d8801"
            }
          ]
        },
        {
          "id": "af9cfe09-4a49-457f-8bcc-fb4b78df520e",
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
              "id": "d41fe20a-dfa8-412c-b4e6-e30b861f0d2d"
            }
          ]
        },
        {
          "id": "29b99208-8e63-4a13-bdcc-55e9d4c3f9e2",
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
              "id": "1da666e9-4b90-4a9f-aaa4-539c805beaaf"
            }
          ]
        },
        {
          "id": "23859ce8-1545-4fae-82ac-e975b7591c5f",
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
              "id": "0c3d7bbc-0b51-4c8c-beb5-89879565ac2b"
            }
          ]
        },
        {
          "id": "ea343a90-51cd-4c8c-a195-f701fd8bb2a0",
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
              "id": "22d8d528-a457-441b-b63f-b67f346769b0"
            }
          ]
        },
        {
          "id": "898459a2-0aad-41b8-8f44-95222e4a3b5b",
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
              "id": "076828da-0c49-410a-8960-0d10f4060bef"
            }
          ]
        },
        {
          "id": "935fd260-5241-4cdc-b49b-ca4e247b9012",
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
              "id": "ee980e39-1814-4521-8e88-073647a76d3c"
            }
          ]
        },
        {
          "id": "de0bd9e9-356e-4dcc-be11-756c30b04ed0",
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
              "id": "4dfdf38a-df59-431a-81a9-f79b47fdf894"
            }
          ]
        },
        {
          "id": "16c2b268-2f2a-4c1f-9eed-42cd3fbcf767",
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
              "id": "414a53c5-81d7-4c6a-9076-11f61dd9d9cd"
            }
          ]
        },
        {
          "id": "77ab8cf7-8cd2-4aa7-8379-cf90119fa167",
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
              "id": "3e2fba11-a435-42be-8631-8ea23d2cb685"
            }
          ]
        },
        {
          "id": "8fe0b25a-ffb3-4586-a6e6-0c59ad41cc38",
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
              "id": "a78c9025-6d47-4c7d-8aa5-908a4aaa58f2"
            }
          ]
        },
        {
          "id": "72bdf80c-df74-49f9-8a41-d4dd05efe40f",
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
              "id": "da513cbc-efb7-423e-bc23-307659b6cdef"
            }
          ]
        },
        {
          "id": "ee1a053b-e4e5-4dfc-b1dd-95c1cf51ea2c",
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
              "id": "7f135c76-cd04-4137-91ee-3056af34ee7b"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "4befe975-fb5d-458e-9bf0-0ead3f78a0b8",
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
              "id": "81de67da-6805-4b6c-bcca-b1b0e2203120"
            }
          ]
        }
      ]
    },
    {
      "name": "Deliveryformat",
      "item": [
        {
          "id": "4ce86ada-c14b-464e-a799-f7b8c163aa09",
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
              "id": "8cbf809c-ccbd-47b4-a2b8-4f3bad577f90"
            }
          ]
        }
      ]
    },
    {
      "name": "Audience",
      "item": [
        {
          "id": "e41fe5b4-b839-423e-8516-1aac83f29180",
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
              "id": "0163e2cf-783e-40a1-9a4a-e602c5c067c9"
            }
          ]
        }
      ]
    },
    {
      "name": "Clients",
      "item": [
        {
          "id": "7a9e929c-cd38-443a-8d7f-e99848f9715c",
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
              "id": "785a69ac-844a-426c-a173-258291fe7e32"
            }
          ]
        }
      ]
    },
    {
      "name": "Feo",
      "item": [
        {
          "id": "bcbd78f3-73bb-440e-89ab-93fce0315650",
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
              "id": "b41fca22-27c8-403e-851d-36144ee04984"
            }
          ]
        }
      ]
    },
    {
      "name": "Imaging",
      "item": [
        {
          "id": "dc494c03-1f8e-45b6-9a63-7a91cd6b6fc5",
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
              "id": "8a2baf30-0f16-4687-be82-be71c43572e7"
            }
          ]
        },
        {
          "id": "3a6f9754-af11-447e-9cb6-17ea95c85fc7",
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
              "id": "d79cbf43-dfef-44d0-9c27-004f5130fa37"
            }
          ]
        },
        {
          "id": "6879aa42-6e08-49c3-8783-57d53d089a9e",
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
              "id": "b1d2d43f-10cd-460e-a9d3-95e8526e1ef3"
            }
          ]
        },
        {
          "id": "574240fc-49c3-4e78-8f3b-d7ee0e1ef467",
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
              "id": "e5b6261b-c1fd-4c3f-acdc-6ff5926ce829"
            }
          ]
        },
        {
          "id": "9d951d58-4670-4049-99d4-a73756e2582c",
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
              "id": "ab6902af-fd3f-483b-b157-18342a010804"
            }
          ]
        },
        {
          "id": "7fc5a31b-3a93-4f68-97ec-a3d2b1dc9279",
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
              "id": "3d0b54cc-46d4-495d-8e00-e5e9a1b3e084"
            }
          ]
        },
        {
          "id": "7f2f4b8b-3f18-4584-bd5c-6557b6cff89b",
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
              "id": "adec7c44-0546-4118-9ace-d896f651448b"
            }
          ]
        },
        {
          "id": "62815dc9-02d7-49df-9c90-8433131afc85",
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
              "id": "0fdf9b6c-3f78-4feb-96d9-47032daca539"
            }
          ]
        },
        {
          "id": "4374bff5-38f3-496b-9e4a-99b1f8bc1a97",
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
              "id": "f1858ea8-e772-412c-b5de-7eba355c50a6"
            }
          ]
        },
        {
          "id": "defcf90a-043c-4e1f-928c-2d5469775f2d",
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
              "id": "b4fed7c0-e8dc-4758-bcb9-4c4a8805fa6b"
            }
          ]
        },
        {
          "id": "9cdfd997-e4d2-42f6-b333-2dd399a03e00",
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
              "id": "923f544f-026b-42c1-84ac-8931ea83468b"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "685c8c85-4fe3-46c5-958d-807420025729",
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
              "id": "79890ff7-4313-403c-8db5-4d9d8170bbed"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "05ac03f9-999e-4074-b21a-bfc80be858b0",
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
              "id": "be3bbad8-22ef-4944-9f35-e15a86d2ef7f"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoicing",
      "item": [
        {
          "id": "188cfbaa-3375-467a-ae68-117c1123c6e9",
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
              "id": "8308829d-a9ac-44a3-86dd-8a01be3533ba"
            }
          ]
        },
        {
          "id": "e99a5058-8af0-4fd1-9f52-4d725d4dde61",
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
              "id": "446c03e6-f58e-4798-bdb9-f8fe7d85b3de"
            }
          ]
        },
        {
          "id": "4a06d9b5-e945-4b84-b57f-61729962bcfd",
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
              "id": "385151e8-2c09-499c-8309-2e59546be9f0"
            }
          ]
        },
        {
          "id": "f45130b7-01ae-4e8a-b112-02454ac95294",
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
              "id": "fbfd40df-1602-48db-a58d-61a099ebe5a4"
            }
          ]
        },
        {
          "id": "05cbc4b0-31cb-4e8f-813e-07ed30d77aeb",
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
              "id": "00783db9-b68d-4c32-a52b-911f42cf8f93"
            }
          ]
        },
        {
          "id": "7f2d2df6-6010-4ae8-b1cf-ba06b14fb3d0",
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
              "id": "e574c39a-b591-4f3d-8d4c-f92c4f48860b"
            }
          ]
        },
        {
          "id": "1e0af7ce-3b6c-4fe1-9248-b37f40b896f6",
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
              "id": "207fa98e-7279-4901-b379-46ea8a3769f8"
            }
          ]
        },
        {
          "id": "fedaa900-1479-4b6e-b8bf-b480bbb3ef97",
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
              "id": "1e586dab-8ecd-4305-9677-f18525ed5bfb"
            }
          ]
        },
        {
          "id": "1048b326-f0aa-4c3c-ad19-c8fccf357331",
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
              "id": "a7985c6e-d715-4e30-a91d-08eb5803f079"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "018aeb9e-1369-4c50-bd21-8ae574a574cc",
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
              "id": "e8342b24-2bd5-4068-9710-f0a6ca1823b6"
            }
          ]
        }
      ]
    },
    {
      "name": "Configurations",
      "item": [
        {
          "id": "923e4f3c-c53c-48a3-bc9d-27103851b097",
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
              "id": "9d2aeb3e-c0ca-4208-9fdf-30bdc1c2236e"
            }
          ]
        },
        {
          "id": "78cb12b8-ce7f-41d0-bc93-8d19bc1c08ab",
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
              "id": "5af646cd-d663-4c05-981a-b10a0bd185c4"
            }
          ]
        },
        {
          "id": "22a060a4-e419-4538-9c5a-fe11ee54aafe",
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
              "id": "a304b7e8-ac7f-4271-a9c7-3ee879cca7dc"
            }
          ]
        },
        {
          "id": "ccc29cbe-2590-44d9-82b4-7b3c1bfe4693",
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
              "id": "38040919-7272-4663-b7cf-7483495d9e2e"
            }
          ]
        },
        {
          "id": "ca1d5e80-0209-411e-bdf6-2ee0ff906774",
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
              "id": "412ec73c-a30e-47f5-a811-7141a3265220"
            }
          ]
        },
        {
          "id": "353abd63-eec3-48a3-9545-c7da61a7af71",
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
              "id": "f786b9d9-7e3e-41c0-9dab-b161c82e6244"
            }
          ]
        },
        {
          "id": "9bbb54c8-a20e-4a42-af64-1810eb2c2d23",
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
              "id": "e0f3a647-1b14-410c-a2b2-0df7173fc333"
            }
          ]
        },
        {
          "id": "88f4332d-20bc-4e06-a094-3703b6d5a01d",
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
              "id": "f0ab3687-ed82-4ccf-9f89-caefee76251f"
            }
          ]
        },
        {
          "id": "8d275fd5-db90-4212-b356-a894dc788674",
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
              "id": "bf20aec6-fb8d-4bc0-b4f0-87356da6861c"
            }
          ]
        },
        {
          "id": "6a718cb8-0cb4-4b81-9a81-33435962aaa0",
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
              "id": "2c5fb86a-bd79-464b-aa9b-76930e3da196"
            }
          ]
        },
        {
          "id": "e235e30d-6f8a-4f58-bf53-a46038933ccf",
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
              "id": "82dec876-25ab-47ec-94b7-a1de98d9f159"
            }
          ]
        },
        {
          "id": "aed15066-87cf-4428-abfe-6fff7f1cef3f",
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
              "id": "6b988ad1-8ec2-45f7-af11-2fd871776a47"
            }
          ]
        },
        {
          "id": "c1d542dc-8ea4-44cd-9033-4d9857234bcf",
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
              "id": "7ee35935-c9e7-401b-bacd-318c25f9f20a"
            }
          ]
        },
        {
          "id": "4a6b2b35-9e52-4731-afdb-882346f58879",
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
              "id": "225ababe-b18c-43c7-beaa-d7f573222a5e"
            }
          ]
        },
        {
          "id": "7aec9c84-57a1-4439-9ab3-bc36fea72ba3",
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
              "id": "ec063aa2-5db8-4d00-8397-7323e53c7667"
            }
          ]
        },
        {
          "id": "bb134668-97b7-4038-aaa6-1f56dfd8223f",
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
              "id": "6535f2e6-116c-43fc-bfce-bcca61933696"
            }
          ]
        },
        {
          "id": "9ed80b5c-ac72-46de-a642-8553e834f917",
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
              "id": "b4bd3c34-a401-414d-9f69-d2c4ed34f53d"
            }
          ]
        },
        {
          "id": "41fefedb-7fe9-4fbd-b518-86d4b9b1e8c1",
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
              "id": "5be2f4d0-da6d-480c-ad58-d154c4455013"
            }
          ]
        },
        {
          "id": "252f8e15-01a4-42e2-977c-e545e5159570",
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
              "id": "e3e9dce4-4a09-47bf-9b81-7580b62d51d2"
            }
          ]
        },
        {
          "id": "268063e1-200d-4b01-877c-3a67229cd764",
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
              "id": "ee377ac4-68a3-4d56-a425-619001e028b4"
            }
          ]
        },
        {
          "id": "7eb2e459-efc8-4740-b2a8-0e6a16129421",
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
              "id": "f568e85d-e59f-4306-93f6-de7615d89537"
            }
          ]
        },
        {
          "id": "4671df6d-40e5-4d05-b6f5-60b862974d77",
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
              "id": "0d8b48c4-b103-4512-abe8-2cd31998e551"
            }
          ]
        },
        {
          "id": "1e822ece-e415-406d-b81b-203c00c6d59c",
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
              "id": "cfaada34-35f9-4c13-be3b-1ab321072bd3"
            }
          ]
        },
        {
          "id": "ea3ff079-4d3a-4588-b7d0-39e9045fa297",
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
              "id": "8049668e-a198-420b-a4dc-2f5c8cb1fbcb"
            }
          ]
        },
        {
          "id": "1bee0ef1-bc6c-47a8-9663-325c25389e9a",
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
              "id": "ec3cc8af-2bc8-48b0-8f81-fb92c747c1fd"
            }
          ]
        },
        {
          "id": "6466ab17-7f28-4cf3-a521-114ad4307475",
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
              "id": "06d591a6-011a-4704-9d8a-cc5c97bb2e83"
            }
          ]
        },
        {
          "id": "042e55db-1ed2-4975-9f1c-171db036b399",
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
              "id": "befea53b-aa1d-4035-8055-8684600f07fa"
            }
          ]
        },
        {
          "id": "97301762-5232-45c9-8bac-9de22143f5f7",
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
              "id": "4cf504f9-aa2c-4029-9007-400d002246fa"
            }
          ]
        },
        {
          "id": "c5ff60ba-238d-43a2-a1b8-a4a91a80ad72",
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
              "id": "05b2c6a7-29e6-42c8-99a5-aea5abe8f255"
            }
          ]
        },
        {
          "id": "a1ab21c3-c625-45c9-8ca1-5cc91901d33d",
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
              "id": "017d277f-4429-4ba1-8761-bd9f4ff39c66"
            }
          ]
        },
        {
          "id": "e6448bb9-721a-43af-bb89-7e47544e9a0c",
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
              "id": "105821e6-51ec-49e8-85f8-2ee6839904b0"
            }
          ]
        },
        {
          "id": "06e73023-9a05-4865-b741-fdb25c9a7c00",
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
              "id": "87dbaba1-9c15-4f69-a3c3-dcba747ff5f6"
            }
          ]
        },
        {
          "id": "e10b2881-9805-4f9f-8494-27bf15aa38f7",
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
              "id": "980923f0-d8a0-49d2-af2c-d625b7d8344e"
            }
          ]
        },
        {
          "id": "ecea0c83-f56c-477f-9d13-233862fa15d1",
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
              "id": "077fa672-67c2-4445-be32-e73fa9388e1a"
            }
          ]
        },
        {
          "id": "c3d1a263-e801-46e6-972e-40b9d42bc740",
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
              "id": "8c2a88f3-8069-4186-96bb-1a83aabd97ae"
            }
          ]
        },
        {
          "id": "be08c430-5c7c-4a57-9270-4eadcd63838c",
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
              "id": "e913380e-8976-4b3b-a7a8-510c3afcd729"
            }
          ]
        },
        {
          "id": "b59a3006-b87f-479c-9b67-f00b58fa6a8d",
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
              "id": "f7b85381-a228-4367-9ff0-5646d95d2006"
            }
          ]
        },
        {
          "id": "aec5cee7-5263-4e5d-81d4-db17e055ced6",
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
              "id": "44ff3a3b-66b5-4d89-881a-387ec374b179"
            }
          ]
        },
        {
          "id": "d5cb2856-d004-4ee8-93eb-744c1cea9b02",
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
              "id": "0c654988-9d3b-4ee4-8a30-0a0360a53760"
            }
          ]
        },
        {
          "id": "713aa7fe-b4c1-4608-8277-6b1fcff2a293",
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
              "id": "314bbd4f-f23d-47b8-b9af-b554f3184a77"
            }
          ]
        },
        {
          "id": "58c3e2fd-55b5-4b81-a74d-22df637a6e82",
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
              "id": "e1192a5a-4e0c-4c5d-b99c-ee560dd47da0"
            }
          ]
        },
        {
          "id": "2c567781-978b-4de8-bd04-79a58b8252b0",
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
              "id": "23d88a2c-7c19-4d97-b393-fa442f7756f7"
            }
          ]
        },
        {
          "id": "11c2b92f-ec1d-4d43-a821-aff21dc5c9c8",
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
              "id": "693aa24c-00a7-4e5f-a657-5f3aae4366e2"
            }
          ]
        },
        {
          "id": "524bbf6a-ad6b-4977-b538-482f57c79f0d",
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
              "id": "e9f51d80-b9f6-451b-96c9-87356736630e"
            }
          ]
        },
        {
          "id": "87e1f5fa-c2fd-43ad-8350-e5ff60353dfb",
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
              "id": "0f7c4c41-9541-4d31-a9e1-082a217a995e"
            }
          ]
        },
        {
          "id": "041c1c68-b5b6-434e-8516-c2d02e28177e",
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
              "id": "67feafad-dd55-4db9-8cc4-72dd6f5fd361"
            }
          ]
        },
        {
          "id": "67d59e75-2ffe-4961-a998-eee03649c12d",
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
              "id": "9d16f2be-f97e-46f9-a2cf-7314e646cae8"
            }
          ]
        },
        {
          "id": "53a29b6a-49c0-4605-adff-6bd983ddcd2b",
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
              "id": "d3804f79-4b16-4570-aa6a-3721e782c7cf"
            }
          ]
        },
        {
          "id": "0f232eb2-6922-4871-ab43-eb97771048ce",
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
              "id": "cc20d246-b9ed-4353-9c6a-18ae4559e488"
            }
          ]
        },
        {
          "id": "f41623d9-1b10-4e26-949e-8c55d5654daf",
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
              "id": "62d0c3dd-b65b-49eb-bd2c-604825b72b2f"
            }
          ]
        },
        {
          "id": "86b1dff8-92db-48b2-8014-15a324b91db5",
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
              "id": "c52ff355-cbcc-4141-9944-c5c0a69650c8"
            }
          ]
        },
        {
          "id": "d6b846b4-535b-4bf5-8f81-6cd08a58b09e",
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
              "id": "c7537ef6-80e0-400d-86dd-4de8dd2e582b"
            }
          ]
        },
        {
          "id": "ae16cfa8-7056-4bc0-89ee-a2a85e719501",
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
              "id": "487186d6-877f-4575-b9cb-95659db6cac2"
            }
          ]
        },
        {
          "id": "f82d3108-390f-4084-bbad-b8cbc5eee82a",
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
              "id": "16730a50-930a-4947-b48e-af8afaff3a3a"
            }
          ]
        },
        {
          "id": "73a5470d-1760-4aa8-9ffb-98ad5af7ded9",
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
              "id": "6de2f34b-2650-441d-b6b3-1f6ffafe778c"
            }
          ]
        },
        {
          "id": "c76630d0-0459-4260-8530-82b6cb2973fb",
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
              "id": "9c3917f5-eaeb-4f1d-a44f-461205070559"
            }
          ]
        },
        {
          "id": "1f9e504d-8177-4194-9f7a-8ae2aad2eab2",
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
              "id": "b377331e-fa54-4941-9735-ed295d8ea1b8"
            }
          ]
        },
        {
          "id": "1aab9455-3806-4984-9566-cf4585d22e44",
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
              "id": "69b8f126-c2c6-4143-9d66-31a4c7434d83"
            }
          ]
        },
        {
          "id": "ee9e1d29-6bd5-4bc9-975f-61aa830ea87f",
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
              "id": "2fac137c-004e-4292-bbad-8db63f8e1371"
            }
          ]
        },
        {
          "id": "88fdefaa-3b22-43cc-a39d-837dd6de44bd",
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
              "id": "b9c9875c-6b37-436c-9988-95d21ad6f743"
            }
          ]
        },
        {
          "id": "b1278ea7-d768-4297-80f9-d8990f9d1077",
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
              "id": "33bd62bb-b19c-42c7-b4b0-b01ee8313b22"
            }
          ]
        },
        {
          "id": "1d2b7723-11e0-4115-9f21-b617a72b37aa",
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
              "id": "dfa4d42d-577d-464c-b6a6-43b4b70fbfd2"
            }
          ]
        },
        {
          "id": "240fa587-91d7-408f-aa8d-7a2d147ab32c",
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
              "id": "9f0420ec-2c48-4c1f-8620-b247f93baa19"
            }
          ]
        },
        {
          "id": "8ea7983e-31ee-4687-a2db-6a82a435c314",
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
              "id": "7449f2e8-4e9d-4a84-b868-32374b847b14"
            }
          ]
        }
      ]
    },
    {
      "name": "Service",
      "item": [
        {
          "id": "2debf1d0-ae32-4b8a-bd44-44bc8ef66379",
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
              "id": "0270c9f7-935b-4324-870a-9ae15ec85418"
            }
          ]
        },
        {
          "id": "f259eca6-542c-4c84-b792-2a413d127958",
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
              "id": "5edaa935-770b-4b78-a6ae-774ec7af9340"
            }
          ]
        },
        {
          "id": "f9979f68-1b3b-4ecd-a271-580705dc8063",
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
              "id": "446e7f6b-5c93-4452-840d-515aa675f284"
            }
          ]
        },
        {
          "id": "4127869d-8b5c-4357-9af0-66e9fedab077",
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
              "id": "ed5bd1ed-3bb7-494e-bb5a-2391cc4ffacd"
            }
          ]
        }
      ]
    },
    {
      "name": "Services",
      "item": [
        {
          "id": "37408f21-1ad5-4215-81a0-8849f80eb3ba",
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
              "id": "cc90a9bb-5bef-46c5-b45c-f99dc4fadc62"
            }
          ]
        }
      ]
    },
    {
      "name": "Lds",
      "item": [
        {
          "id": "19b82c27-b7e8-467e-9a4b-feb5c28b27c6",
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
              "id": "b95c1fd5-90af-4ab6-9abc-272339851be8"
            }
          ]
        },
        {
          "id": "742fd001-6213-48a4-964d-39d7dda66c18",
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
              "id": "3958f0ec-1f33-4c20-80a4-fc2118240980"
            }
          ]
        },
        {
          "id": "99c1b3b5-f3a5-4e6a-9761-865ea352083d",
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
              "id": "edf7f78e-dd69-41f5-87de-33c3d899f1c7"
            }
          ]
        },
        {
          "id": "b9a365ec-8a55-418c-8a43-043937159d64",
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
              "id": "d7c4473f-5651-478e-bd9c-2383a273170e"
            }
          ]
        }
      ]
    },
    {
      "name": "Redelivery",
      "item": [
        {
          "id": "e7804766-c1d1-417b-b20f-e79e6c821dcd",
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
              "id": "d6d9b5fb-4c7e-4f42-ad3c-56a7ba530fda"
            }
          ]
        }
      ]
    },
    {
      "name": "Key",
      "item": [
        {
          "id": "c4c5873e-5ddd-45cf-b7b7-122b70a59be7",
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
              "id": "2ed69136-b29f-4c2f-b44b-804366249560"
            }
          ]
        }
      ]
    },
    {
      "name": "Media",
      "item": [
        {
          "id": "d07f6fa2-c47a-4e8e-83ec-8b6d31f63460",
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
              "id": "2b73da88-e9ad-494f-8f4b-e9c08e6c23d3"
            }
          ]
        },
        {
          "id": "66a8152a-08ef-4643-a8d7-4261bbcb7f3c",
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
              "id": "af16388a-e832-4a4e-893e-71d9ef7579f0"
            }
          ]
        },
        {
          "id": "e27c707b-9b04-464d-a5d2-5c66577495d2",
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
              "id": "6a51f12f-9b0b-4e7d-8835-fa2b0f7ce519"
            }
          ]
        },
        {
          "id": "5fd86870-0afa-44c7-bea2-b37a710419bf",
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
              "id": "eec4d6dc-5c36-44d2-89dc-ad62da3ea4d0"
            }
          ]
        },
        {
          "id": "c56fcf43-ce6b-4197-89de-0b3ce5f21bc3",
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
              "id": "d36672ec-0d53-41f0-9f9c-89315bf266a9"
            }
          ]
        },
        {
          "id": "a902d592-8627-4f18-939d-e3f3ee083e16",
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
              "id": "aa3b5977-4beb-4b56-8f70-5924d9ce56a8"
            }
          ]
        },
        {
          "id": "35095dcb-c5e0-4ff1-8d54-fccba5a1ba5a",
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
              "id": "fa9a968c-538e-41f9-9afa-e8563d1dfc6e"
            }
          ]
        },
        {
          "id": "2306e4bb-3103-46e5-b0e4-d99d37834a1e",
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
              "id": "5208e100-3687-4227-bc4e-8dfdd90299bc"
            }
          ]
        },
        {
          "id": "a9cae1a2-bd41-4d7b-af6d-58b6f6ba26ab",
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
              "id": "da3251c6-2e7d-4d6e-ac04-96937c6e762b"
            }
          ]
        }
      ]
    },
    {
      "name": "Filterparams",
      "item": [
        {
          "id": "433cafd5-3453-4418-bb5f-b4dc3d512c75",
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
              "id": "ad51819a-e321-42bc-ad3e-90fd810f36a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "726726d0-7149-49de-831f-9b7f97daa236",
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
              "id": "c42e0389-cc08-403e-9459-3fe606b65c55"
            }
          ]
        },
        {
          "id": "e47e8276-6257-4889-9328-7d0b5f2b2885",
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
              "id": "284b932a-be98-489f-b610-31ec9a48c963"
            }
          ]
        },
        {
          "id": "cad5bba4-a96f-4ce0-8d0f-27a85f3696cc",
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
              "id": "e38b4bfa-b5c0-4e50-a553-7c988d74dd47"
            }
          ]
        },
        {
          "id": "c1db1828-44ff-436c-8c4b-04b84dbc4240",
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
              "id": "2573a900-d4ce-4c0d-aad4-fdbb78f78266"
            }
          ]
        },
        {
          "id": "4ad582cb-08da-43c3-9f6c-7a8bd890b293",
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
              "id": "c17b8015-1418-44cf-8789-04e8c9ae0a8e"
            }
          ]
        },
        {
          "id": "1092a7f2-2040-4d34-be5c-b07a59973aa5",
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
              "id": "3f60e407-08ec-4f67-a037-3a71bbe6e194"
            }
          ]
        },
        {
          "id": "4dd2af28-8bde-41da-ab07-6caf37a08577",
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
              "id": "bfa48c6e-5c63-4a81-8224-78cd63d45259"
            }
          ]
        },
        {
          "id": "ae51b98e-d867-40e2-8409-4b50d62e6242",
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
              "id": "019b372c-088d-439b-ad05-f690e01260f6"
            }
          ]
        },
        {
          "id": "84c88aac-c06e-4e44-a785-86a20552e396",
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
              "id": "bbf110fb-04b5-47ee-8fe5-78fda297007c"
            }
          ]
        },
        {
          "id": "34f6bff2-028a-44ec-a575-99fe67790001",
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
              "id": "013a5046-d316-4d58-8935-1759736d6ecf"
            }
          ]
        },
        {
          "id": "3fdf7c8a-34f5-42af-a664-f624d149f1a2",
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
              "id": "b519ff64-dfe5-4a9a-8732-1429b7941760"
            }
          ]
        },
        {
          "id": "7a0b24eb-5c9d-47d2-a106-b385d3eb6488",
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
              "id": "2ca8f2d5-5ffd-445d-94a2-96f84655bf09"
            }
          ]
        }
      ]
    },
    {
      "name": "All",
      "item": [
        {
          "id": "0b01fc49-1ba1-4137-8a9f-fae5f06e0b4d",
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
              "id": "9d20ccfe-9f86-4ed6-919f-312eb650041c"
            }
          ]
        }
      ]
    },
    {
      "name": "Prolexic",
      "item": [
        {
          "id": "abe91b34-6756-4c2e-a313-92d51e6f16c7",
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
              "id": "a5947638-dd84-4414-9886-7dbc8f4d2c4d"
            }
          ]
        },
        {
          "id": "f7999e85-50fd-42ae-8a09-89fa109c676d",
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
              "id": "0cab4be4-9694-4a36-a188-bda3c2a4f9cb"
            }
          ]
        },
        {
          "id": "834fafce-888c-48e1-b6d9-96498d636cfb",
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
              "id": "ea8a8d40-3b53-481e-85f6-6f9a67549aee"
            }
          ]
        },
        {
          "id": "f1ff922f-f033-47d8-a5cf-073bd80c4a0f",
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
              "id": "2668174a-1ac8-4e1f-bca6-aaa4e9f992d2"
            }
          ]
        },
        {
          "id": "3aaffc92-515d-43da-b4a9-5d1ed8bb3f39",
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
              "id": "2468e81d-2c94-4806-9ad7-2c3ff6792f90"
            }
          ]
        }
      ]
    },
    {
      "name": "Type",
      "item": [
        {
          "id": "82101a1d-bde9-4ed3-bf05-51e8137b40d7",
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
              "id": "2b653993-a3d5-43e5-9d0b-79e5b78b7881"
            }
          ]
        }
      ]
    },
    {
      "name": "Papi",
      "item": [
        {
          "id": "31a04b42-49a2-4fa9-8bb2-b386679b505b",
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
              "id": "893d1246-0419-4bab-b44c-306cbaaac13a"
            }
          ]
        },
        {
          "id": "f3ba1807-4fef-4c92-8f5b-3cfd6eb3e5a7",
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
              "id": "4529a739-1a03-4a9d-9160-8739e17f60f6"
            }
          ]
        },
        {
          "id": "c1fb0fe2-80d8-4249-be86-19bd8ab3ae17",
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
              "id": "34c7f127-f5ed-49f7-b035-d674d4eb1715"
            }
          ]
        },
        {
          "id": "8ce14152-9f19-4c86-8552-c8f1af5e790b",
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
              "id": "d34b9c58-769e-4ebf-9f42-e64e6fbee068"
            }
          ]
        },
        {
          "id": "b4c905fa-2203-4bbd-a3aa-38902575089f",
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
              "id": "d3f607ed-ee14-4e86-bbc5-8d777fb16fc4"
            }
          ]
        },
        {
          "id": "4521feec-292e-4501-a383-41ecf3e11c05",
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
              "id": "2b7c82d3-26be-420e-b731-41b458f5409b"
            }
          ]
        },
        {
          "id": "015af720-bed4-43d4-9913-7d8f5081e581",
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
              "id": "8ca10512-daed-4fb2-9f90-361595102dd9"
            }
          ]
        },
        {
          "id": "cf06e3d8-50ad-4f4a-8fd4-82dbe4c6a8a1",
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
              "id": "a02dde00-14ec-46eb-9e37-cd8250eeec0b"
            }
          ]
        },
        {
          "id": "8d2afb61-3232-4ae0-8147-af643d31249f",
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
              "id": "eb72aee2-bd3f-4168-94bb-6462d765f31b"
            }
          ]
        },
        {
          "id": "1c49fd9a-7598-4a99-9bd5-3de071c02abf",
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
              "id": "70fa31a5-9987-475f-b7ca-a09a7f7eccaa"
            }
          ]
        },
        {
          "id": "4929a573-870e-471c-95de-10164a3b0981",
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
              "id": "7ba8cf29-55fe-4a56-a21c-e327d6806223"
            }
          ]
        },
        {
          "id": "ff498dec-1b45-4024-8f8f-c5f298f9676c",
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
              "id": "8e60e7d8-e034-497b-8d9f-6b4a7f22146f"
            }
          ]
        },
        {
          "id": "98c889c1-73ae-4f4c-9f3a-8e76a24b7875",
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
              "id": "8c686638-81eb-4468-9d10-af2f37592324"
            }
          ]
        },
        {
          "id": "01cdc6f7-5da9-4869-9ac7-a21176ab0686",
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
              "id": "5aba910b-a516-48a8-a35e-d09397a4b017"
            }
          ]
        },
        {
          "id": "2d21d0cf-a304-4b9c-a184-fc35830ab832",
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
              "id": "7d4189cc-bd01-4e6d-b24b-8a5b69233639"
            }
          ]
        },
        {
          "id": "17facf68-0e3a-4b0d-97f9-e47dba2aef8a",
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
              "id": "01201da2-b833-483e-9905-50ba6a667b04"
            }
          ]
        },
        {
          "id": "9983285b-3247-4e81-964e-6f880aa9df46",
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
              "id": "6f54959e-153f-4799-a01b-f41cea88f30b"
            }
          ]
        },
        {
          "id": "b470f3e1-10c7-43a9-acad-ccf1a8d5e2f6",
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
              "id": "f4797456-9272-48bd-9e39-1bee2f7b4507"
            }
          ]
        },
        {
          "id": "6ca17d8d-eafc-4ecf-b191-9c7cd4925327",
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
              "id": "625e951d-03d3-4904-adbe-f50f858cb480"
            }
          ]
        },
        {
          "id": "d6851965-0ba8-44ee-a578-a0011f30e365",
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
              "id": "3bf98c4e-e0de-49e5-bbba-a6f60189daa7"
            }
          ]
        },
        {
          "id": "9be791eb-2b94-4d63-8683-6a457f8ed28e",
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
              "id": "baddbab0-d2d6-42f4-a206-f857ddfa285d"
            }
          ]
        },
        {
          "id": "e5c3653f-cbc4-4ab7-a512-d76223d0da30",
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
              "id": "d06c6ad2-54f7-4982-bfd8-b2163f95e586"
            }
          ]
        },
        {
          "id": "07a9e0d0-934f-411d-8011-7af2d671674a",
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
              "id": "2467dba0-ef25-47c9-9297-7716ff66878d"
            }
          ]
        },
        {
          "id": "77f109e8-3c99-4cdc-a911-5466e955561b",
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
              "id": "d1fe5c15-f575-4cf6-aa9b-0a2660f59c9e"
            }
          ]
        },
        {
          "id": "c9564566-8217-4497-970f-c6f0c04d4a39",
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
              "id": "2d63d8cd-4161-4208-97e3-0159e9f351b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Versions",
      "item": [
        {
          "id": "853b18ba-3637-4fa6-b305-4b625d558835",
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
              "id": "2b114c7f-13f2-4429-8c5d-e359a7559f9a"
            }
          ]
        }
      ]
    },
    {
      "name": "Accept",
      "item": [
        {
          "id": "90d58c17-924a-4a4c-b108-57869e0eab3c",
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
              "id": "18f22845-3f87-4e19-9545-ef41c85a2c49"
            }
          ]
        }
      ]
    },
    {
      "name": "CName",
      "item": [
        {
          "id": "f4c9ee8a-28f8-473b-aa12-a85a2929c793",
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
              "id": "2ae8f13e-f241-4f75-843a-16ec2106b3c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Activations",
      "item": [
        {
          "id": "12c2520f-fbb6-492f-9a5f-0009a7b47d7a",
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
              "id": "4cf95e6c-4e70-40d1-9cc1-2b67baa9d899"
            }
          ]
        }
      ]
    },
    {
      "name": "Retry",
      "item": [
        {
          "id": "cf762821-4cbc-4cec-b0bc-a9f0a7b90a30",
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
              "id": "451f8eea-6f65-4695-8f40-699a00c23d3a"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "58b792d2-db2e-493c-84fc-bb6808728de0",
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
              "id": "0f69d0b4-1b15-48c1-878f-3b2e5211f292"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscription",
      "item": [
        {
          "id": "9f9052dc-c018-4d29-adc0-26a42ca214cf",
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
              "id": "321924a9-2d58-48db-8fbd-7987e5e5e4b5"
            }
          ]
        }
      ]
    },
    {
      "name": "Name",
      "item": [
        {
          "id": "c6eb77c1-8f4d-433d-9a1f-843989201f51",
          "name": "name",
          "request": {
            "url": "http://developer.akamai.com/name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Report Packs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f51c193-2cb5-4173-802f-16c4ae4b56dd"
            }
          ]
        }
      ]
    },
    {
      "name": "Security",
      "item": [
        {
          "id": "18e0fbb2-0318-40eb-897e-8bce6d61fd70",
          "name": "securitymonitorv1reportpacksreportpackid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "security-monitor/v1/report-packs/:reportPackId"
              ],
              "variable": [
                {
                  "id": "reportPackId",
                  "value": "reportPackId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Report Pack"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4eae4868-bc22-48c0-bf15-c6d9329f6cd2"
            }
          ]
        },
        {
          "id": "5e9c4e61-ab9c-4772-98b8-72cdd1e78fd4",
          "name": "securitymonitorv1reportpacksreportpackiddatastores",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "security-monitor/v1/report-packs/:reportPackId/data-stores"
              ],
              "variable": [
                {
                  "id": "reportPackId",
                  "value": "reportPackId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Data Stores"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8904f9c-1dd6-436b-87f3-7851fd584dd2"
            }
          ]
        },
        {
          "id": "8ac18229-527f-40dd-b1a1-8ba204667234",
          "name": "securitymonitorv1reportpacksreportpackiddatastoresdatastoreid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "security-monitor/v1/report-packs/:reportPackId/data-stores/:dataStoreId"
              ],
              "variable": [
                {
                  "id": "dataStoreId",
                  "value": "dataStoreId",
                  "type": "string"
                },
                {
                  "id": "reportPackId",
                  "value": "reportPackId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Data Store"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d7a5e7ec-dcd9-4b45-a553-9d46de600575"
            }
          ]
        },
        {
          "id": "45a9f05a-6e3e-47f2-a3c8-79d017e1d294",
          "name": "securitymonitorv1reportpacksreportpackiddatasources",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "security-monitor/v1/report-packs/:reportPackId/data-sources"
              ],
              "variable": [
                {
                  "id": "reportPackId",
                  "value": "reportPackId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Data Sources"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6c16f679-fa1c-481d-a1fb-30403cd298d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Sla",
      "item": [
        {
          "id": "7e985e2d-ba61-4bef-be1e-737b85cb9540",
          "name": "slaapiv1testquotas",
          "request": {
            "url": "http://developer.akamai.com/sla-api/v1/test-quotas",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Test Configuration Quotas"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f8614956-6adc-470f-8cf0-8674959e35c0"
            }
          ]
        },
        {
          "id": "5302a923-f8b5-40a2-bab3-337a74850c48",
          "name": "slaapiv1tests",
          "request": {
            "url": "http://developer.akamai.com/sla-api/v1/tests",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Test Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "479f15aa-7f00-458c-a030-58770810121b"
            }
          ]
        }
      ]
    }
  ]
}