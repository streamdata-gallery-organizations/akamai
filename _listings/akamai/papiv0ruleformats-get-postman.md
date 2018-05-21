{
  "info": {
    "name": "Akamai API List Available Rule Formats",
    "_postman_id": "0146782b-dbf5-4033-a5d1-9cee79f03ed3",
    "description": "List Available Rule Formats",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "922741ec-14a9-4ba1-a3e0-57537e3d1a91",
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
              "id": "9379bb5d-b28f-4603-b486-5a4dc20ad9f0"
            }
          ]
        },
        {
          "id": "4b064184-fa2e-4e1d-808b-77376b82b975",
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
              "id": "af8e5534-0cd1-49fc-a7a4-f2ab87e009d9"
            }
          ]
        },
        {
          "id": "734fc899-cba4-4c1d-b726-7c283940b9f7",
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
              "id": "f84663a7-0467-4e1a-bba6-23e0b1dcb18a"
            }
          ]
        },
        {
          "id": "6eac09c0-c66e-43ea-bb6f-4077e4868692",
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
              "id": "c1ecaac8-5b54-4d78-97f2-eae88630e1f7"
            }
          ]
        },
        {
          "id": "c0c71817-4912-4ff4-9550-8804dc72ac09",
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
              "id": "a499497b-ffc6-4336-b2e6-d765472c5189"
            }
          ]
        },
        {
          "id": "875bf394-698b-4f7d-80bd-ddf505d49ca9",
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
              "id": "e0aa5361-234b-4ac8-bd2c-6ddfd546771d"
            }
          ]
        },
        {
          "id": "0d9883c1-0b5e-4035-a042-a4282a71a92d",
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
              "id": "7dc8bd1d-24a0-4118-86e3-106c405055e3"
            }
          ]
        },
        {
          "id": "cd7be785-7d38-467c-b51b-bbaa6c937af8",
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
              "id": "bea8098b-30ba-4c3d-a455-9f14349f0a29"
            }
          ]
        },
        {
          "id": "7344c934-411c-4f13-a461-27733210e28c",
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
              "id": "09114ab7-72bb-443f-a422-7df31f20867a"
            }
          ]
        },
        {
          "id": "5bc85777-1db2-41cd-b7b4-3b85a5ecf717",
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
              "id": "6ca74a5c-7f93-4b5f-a90b-711d2f69e6ce"
            }
          ]
        },
        {
          "id": "93a09bb8-07b5-4f80-8a96-fbd23d1bbadb",
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
              "id": "e7998a5b-af2b-4c7d-b88b-8300cce5a4cf"
            }
          ]
        },
        {
          "id": "b7335bc6-170d-42cc-821f-b9e4bcdce6be",
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
              "id": "6b9170a6-87ae-40ef-a72c-64ceae2b0d64"
            }
          ]
        },
        {
          "id": "2d60935a-b455-4ed9-9469-f0964ee79ba9",
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
              "id": "c8259dc9-8c4c-4067-b599-2f11353c8335"
            }
          ]
        },
        {
          "id": "115ea275-12f3-4f7a-a26f-5b74489d4edd",
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
              "id": "fa0b867e-b869-419d-986c-39eac87cf090"
            }
          ]
        },
        {
          "id": "779c99ea-0b6d-45d3-8033-29f544848439",
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
              "id": "ce7b3931-6e82-48f6-bf36-220dbb05c33f"
            }
          ]
        },
        {
          "id": "3ae28c79-81e9-4637-9d42-e98c3a6b45c5",
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
              "id": "009d4b2c-bfd4-4615-8da9-9ab26e2e12cc"
            }
          ]
        },
        {
          "id": "e780d124-5e5f-4965-9e42-a20558d51498",
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
              "id": "f4869925-64ac-4aaf-a106-2afa28903348"
            }
          ]
        },
        {
          "id": "8ec4452c-075f-43d8-a7db-be4791c5df8f",
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
              "id": "6b72577e-7705-47ad-bda7-eaaeae6cb2b6"
            }
          ]
        },
        {
          "id": "5e4651e7-a826-48d3-9a65-b297ff540f1f",
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
              "id": "8c8e0365-6994-48fe-8f8b-26eacf590785"
            }
          ]
        },
        {
          "id": "a124f9d0-3e26-42ca-8cbf-e44f8583dbbd",
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
              "id": "900b4521-72b7-4e68-a886-fac1d0444fe0"
            }
          ]
        },
        {
          "id": "cc1428a8-1119-420a-bd6a-6902deee6d0a",
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
              "id": "78318ddf-71e1-449e-b799-6be742e3b36f"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "917c5854-ac37-46cc-89f7-0934092088eb",
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
              "id": "eceb03ac-5cc4-4368-82be-92ce1721e9a1"
            }
          ]
        },
        {
          "id": "c7a21aa7-0822-467c-b578-6de0abff0597",
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
              "id": "fff2ea6f-7978-481c-a913-15a0e0e66e14"
            }
          ]
        },
        {
          "id": "1842e3dc-8086-4ffe-a593-9c85ae395e35",
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
              "id": "3e490651-2855-474b-9974-621932f3bd36"
            }
          ]
        },
        {
          "id": "e29703e6-0232-4b5c-b0dc-f06f461b59cc",
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
              "id": "69f868de-9cba-47a6-85ca-f2585b8d1a3f"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "d874b85c-2d3b-475e-94ff-ea08b1279d87",
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
              "id": "2c64c924-e961-4280-9a57-0d3abaab59ff"
            }
          ]
        },
        {
          "id": "fbc2c36a-69f8-4842-b8ab-8a9801f9ee27",
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
              "id": "f6e69042-4ad8-4520-ad63-6937da39cfdc"
            }
          ]
        },
        {
          "id": "e831c866-f09b-441b-befd-5dd084914042",
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
              "id": "b6ba1182-2667-4945-9d85-bed37aa2ec6e"
            }
          ]
        },
        {
          "id": "d54f7077-ceab-40ef-bcb3-0f8f59aa3602",
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
              "id": "bd9ff3e3-f172-4e40-a717-4ef9e402a198"
            }
          ]
        },
        {
          "id": "a7483f0c-1f66-4ad1-8a6b-9f355c4ba33b",
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
              "id": "a50f93c6-39a1-4a6a-999c-478cceda43ff"
            }
          ]
        },
        {
          "id": "717987ac-0485-44c2-836c-41ab772b5304",
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
              "id": "d48acaa8-917d-4f81-b943-eafdfde2d4b4"
            }
          ]
        },
        {
          "id": "d193b92f-6958-41a1-89a2-2491ae126983",
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
              "id": "19d3eea4-130c-4989-8574-70137b1946a4"
            }
          ]
        },
        {
          "id": "090eed71-1d37-48a3-9497-0ff9a5eb840a",
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
              "id": "050dd2c3-5b82-4c61-85c2-18e2809d4a1b"
            }
          ]
        },
        {
          "id": "b3dbc540-0731-4063-b08b-20aadc30a2ad",
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
              "id": "8961ab56-1cdf-4014-860e-c7103eedf040"
            }
          ]
        }
      ]
    },
    {
      "name": "Ccu",
      "item": [
        {
          "id": "8c33075f-1892-40f7-b3d0-bdbb4e876393",
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
              "id": "ac1dc149-8daa-4b5c-9e4a-5069d80974fb"
            }
          ]
        },
        {
          "id": "53ee18b5-9bb6-481f-90e7-9c49d4c65a7b",
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
              "id": "8a1f25cf-d1c7-429a-a654-0f4297a4e98f"
            }
          ]
        },
        {
          "id": "063d3ae8-3b0c-4172-ba65-f9edab5a1c54",
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
              "id": "e914e58e-7424-4471-99ac-0307d3801524"
            }
          ]
        },
        {
          "id": "22fe480a-99df-4e17-8ba4-9359db6082bb",
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
              "id": "30d6a585-d6d3-42a2-9fe5-d283c821dac7"
            }
          ]
        },
        {
          "id": "57e53741-e969-440f-9973-0042101757d0",
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
              "id": "e0da7e69-72d3-41d5-a2bd-e79eba15ddf9"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlet",
      "item": [
        {
          "id": "533db01d-c05a-4912-b2e2-4d1dcd3b4bf0",
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
              "id": "87ce6495-a5ac-4e3a-bb1a-8010dd6624d4"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlets",
      "item": [
        {
          "id": "2898bbdf-c691-4cd5-8c90-a53ef04bbcec",
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
              "id": "a228cb48-6680-44dd-bc36-6cba5cd1bb54"
            }
          ]
        },
        {
          "id": "704bacb5-8e87-42ed-8e11-2a41f47798a1",
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
              "id": "3c829494-f4a2-4f1c-9b2d-39e083b779ea"
            }
          ]
        },
        {
          "id": "649f89bb-090d-4d0f-8a7e-37b886627345",
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
              "id": "205a03b4-f8a7-4759-b9c9-1baca41b8942"
            }
          ]
        },
        {
          "id": "49f8a410-4661-4f9c-ab1e-bc733fa83ef0",
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
              "id": "336ce6dc-738e-4fb5-9fcf-132aa2101b83"
            }
          ]
        },
        {
          "id": "232b81a2-0789-4743-b792-e5bddaadebf4",
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
              "id": "4b0467af-9ae6-451b-8092-89f15ee37ac0"
            }
          ]
        },
        {
          "id": "8c684c86-a308-4d2a-9ea8-7886deb8097d",
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
              "id": "c7498498-86fe-470a-ad4e-ae048ff71b96"
            }
          ]
        },
        {
          "id": "7ac8cb65-4013-4c5e-ae1b-23b2d747c1df",
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
              "id": "cad5a6e8-d737-4d5e-a545-43c8423b8140"
            }
          ]
        },
        {
          "id": "42258c88-3252-4e01-8875-5018210e0a95",
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
              "id": "46f02265-3a53-4a9d-befa-562050f10892"
            }
          ]
        },
        {
          "id": "90e52550-eaf3-4b58-bace-94ea8495e3cd",
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
              "id": "486268a5-990b-4b1b-9578-d6b0e6ed8373"
            }
          ]
        },
        {
          "id": "8fa7a34b-448f-4b4e-9894-8b5881565e31",
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
              "id": "b1da9c0b-797b-4948-9000-86e4348228f9"
            }
          ]
        },
        {
          "id": "cbcde112-2885-44bb-8583-ce246acf3768",
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
              "id": "b639e7e3-671a-446e-b379-e1d70f648734"
            }
          ]
        },
        {
          "id": "669fb5ae-5621-4ec2-b106-5c95e4d8cea1",
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
              "id": "8d3f1dfe-ad98-416b-9d2b-2b236c2b695e"
            }
          ]
        },
        {
          "id": "87011dcb-2af3-43eb-b717-ae06554d8167",
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
              "id": "c49dd63a-9bb1-45b4-b4d0-86bf7d849df8"
            }
          ]
        },
        {
          "id": "cbab1729-591e-4304-a2f7-4497cae2fb85",
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
              "id": "5ce39b96-c4dd-4ca1-a36e-036eda7ebbca"
            }
          ]
        },
        {
          "id": "6882f0c2-7877-4d52-89c9-2f420513be0f",
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
              "id": "eec5b965-8fb0-4788-8b28-a35e225b9cf2"
            }
          ]
        },
        {
          "id": "4156d2bc-f583-4fd8-8d43-1efab0404f03",
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
              "id": "4f3d590f-6d55-4624-ae79-88626f00533e"
            }
          ]
        },
        {
          "id": "44808c87-2139-450b-840a-035a1565cb91",
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
              "id": "ff1bf0ed-c3ea-4e4b-bd01-8b5ea512f7b9"
            }
          ]
        },
        {
          "id": "21ed2af7-a467-456e-b714-d4a7ea883a32",
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
              "id": "9e133bd3-2f45-45cd-828c-b9f4e83f60f5"
            }
          ]
        },
        {
          "id": "11d1d54c-04ac-4d91-8f1b-f07739bf2942",
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
              "id": "3df94e31-ecf9-4940-8fc4-256ab424be09"
            }
          ]
        },
        {
          "id": "3e68c9b1-200b-413c-82b5-df8fb8ad099e",
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
              "id": "d9ffa59c-e31c-48ad-baee-aa6b3b9dbfaa"
            }
          ]
        },
        {
          "id": "91adc4fd-fc74-45d8-a25f-5d77ec32a4b5",
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
              "id": "9ccad998-76fb-4f39-9024-93d68a809e1a"
            }
          ]
        },
        {
          "id": "6dfa744a-0784-4308-a715-dc12f2760ca2",
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
              "id": "4bc71bde-b94e-414b-b59a-23bdba34d71f"
            }
          ]
        },
        {
          "id": "4d14a81a-6698-4830-89cb-7eeff590517b",
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
              "id": "0fcc7cf8-9b98-45d8-8378-bad76d8f7936"
            }
          ]
        },
        {
          "id": "f879074d-5888-4ac5-b241-a35e0a043690",
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
              "id": "e046578c-f1a5-4de9-838f-61a68ddda536"
            }
          ]
        },
        {
          "id": "f3a23075-38f2-45bf-a079-95fd0ed91954",
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
              "id": "0de59364-97c2-4174-aa20-e257095c5d73"
            }
          ]
        },
        {
          "id": "707fe32a-8692-47cd-ba93-6958d99b6eed",
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
              "id": "c62d5bdb-27ce-424f-b6e0-7d678fe2ba6d"
            }
          ]
        },
        {
          "id": "8af274db-c9c4-473d-b90d-95ccf83c00ca",
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
              "id": "b20c8cd0-ac46-4892-bd96-d8d5d7fd6b37"
            }
          ]
        },
        {
          "id": "2e303f74-ce3b-4a03-8ce6-dca8b80654cd",
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
              "id": "57b03abe-d06b-4277-9ecd-d40bfa5d58bf"
            }
          ]
        },
        {
          "id": "a341ab9a-de24-4c06-a88b-216cf0e91a0f",
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
              "id": "3b5f8ca1-b8e0-4350-9b48-25a289c52836"
            }
          ]
        },
        {
          "id": "30638de9-9d47-498a-968c-193fd9aef04c",
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
              "id": "db73113a-7f1e-447a-a182-774ce9cfece4"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudletcode",
      "item": [
        {
          "id": "dc163c10-0c09-4489-99bb-c72d761ecf43",
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
              "id": "2628ec4c-8619-4512-b356-50f688c7e710"
            }
          ]
        }
      ]
    },
    {
      "name": "Cps",
      "item": [
        {
          "id": "e508cb88-660f-40dd-9396-f70b182fac74",
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
              "id": "7d0e77da-d5c0-4754-8663-d12c4d94e795"
            }
          ]
        },
        {
          "id": "0ddafe9d-43c2-494c-ac60-caf675ab9f76",
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
              "id": "e195be29-a56d-4479-b768-95ba607ccd9d"
            }
          ]
        },
        {
          "id": "c1fc258c-b78b-47f0-9e43-1e3cf01b484f",
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
              "id": "07806ca1-819e-4c4d-b92b-af930829ef91"
            }
          ]
        },
        {
          "id": "5e0cb02c-4eae-498c-a4d1-42989154b909",
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
              "id": "276fe966-6898-4b10-8547-b7c8102d1f70"
            }
          ]
        },
        {
          "id": "e63a0487-559e-49e2-97de-d2d5a467bdc3",
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
              "id": "a3a42631-35ec-4b2a-b58d-c74280c7014a"
            }
          ]
        },
        {
          "id": "cc764bb1-7be8-4e78-9dfb-af12454e31ba",
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
              "id": "bee0a709-0d64-4ddf-aa47-ab0c989baaad"
            }
          ]
        },
        {
          "id": "fe9bb57b-2877-4229-9ae6-a625912dc993",
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
              "id": "a106dc88-c7ad-4564-8052-b999ab614018"
            }
          ]
        },
        {
          "id": "3e39a5bb-de04-4528-9358-6f24d704615b",
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
              "id": "0d9a9e5c-ba1b-45a2-913d-873cb1ec78be"
            }
          ]
        }
      ]
    },
    {
      "name": "Information",
      "item": [
        {
          "id": "2d523475-cf9b-4b6d-885e-92bf6f8b1ef8",
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
              "id": "171cf419-9c57-418d-bc5b-7073af85f9af"
            }
          ]
        }
      ]
    },
    {
      "name": "Update",
      "item": [
        {
          "id": "887520d6-e4ca-4935-9d62-d879e58ee546",
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
              "id": "31f5dd17-bc0b-41c1-81cf-298dabb87562"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "480811fa-254d-47a6-a71d-6ee9e2897a64",
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
              "id": "f40f4762-a878-4a46-ba27-2e58404a5d41"
            }
          ]
        },
        {
          "id": "83457819-3687-4cd5-a429-6c02a225047c",
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
              "id": "1b632844-4240-4720-8c38-8bda4c6e2a9f"
            }
          ]
        }
      ]
    },
    {
      "name": "Diagnostic",
      "item": [
        {
          "id": "50acf67f-bf6c-4aa9-8459-7faa89766e70",
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
              "id": "136aae7c-6cb2-4f6d-ace4-43ae5d9a6b79"
            }
          ]
        },
        {
          "id": "357551c0-a2e3-4bbc-a371-45621cde0972",
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
              "id": "4b34af3c-fa6a-4661-bd11-3760b52d754e"
            }
          ]
        },
        {
          "id": "aed4860a-6020-4cf3-a8cb-c247ce2612b5",
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
              "id": "00e4eb87-48f5-4093-8e1c-671e62c22d9e"
            }
          ]
        },
        {
          "id": "e2d83cef-9fd9-4962-b511-13bbf7ddb835",
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
              "id": "7b3d1758-8b35-426e-a9de-5c8c3594da4d"
            }
          ]
        },
        {
          "id": "13cd8e11-babc-4cee-9a33-8ee071a0b5b2",
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
              "id": "f46ab963-e7da-4ffb-a2f9-d67e3e8ad6be"
            }
          ]
        },
        {
          "id": "0ec3a1c2-7acd-4903-bf86-f006f1ab5555",
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
              "id": "9ef87ce6-26e1-469b-b665-4a4403c474dc"
            }
          ]
        },
        {
          "id": "ba2cc079-3bf9-4861-bdf5-ac0cbb8b9eec",
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
              "id": "aeb0cbd6-1892-4f33-a0b4-2ee23415d6be"
            }
          ]
        }
      ]
    },
    {
      "name": "Token",
      "item": [
        {
          "id": "d0452e38-5551-4571-be51-58aaf7988776",
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
              "id": "a37b3103-375d-4570-9a08-e25b6f490d2a"
            }
          ]
        },
        {
          "id": "b93edb71-1e00-4d8b-8214-ca8773456bda",
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
              "id": "70744d55-7701-4c1f-9e98-8e9d26035c90"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "abdb782e-61f2-40a9-855c-7497420af560",
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
              "id": "dbcd93a2-f836-4ed1-9679-0625b27f8844"
            }
          ]
        },
        {
          "id": "f54b4578-b121-4c8f-a1ef-77320acae997",
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
              "id": "c7d55968-1631-4314-b245-66d6e6208a24"
            }
          ]
        }
      ]
    },
    {
      "name": "Etp",
      "item": [
        {
          "id": "34451fb6-9ac2-4fef-9444-9f259c72dc0b",
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
              "id": "7c40229a-3e83-4a43-a9a8-ea0dbbbbc437"
            }
          ]
        },
        {
          "id": "a47f9411-94b2-4e0e-965d-82dff6c207b0",
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
              "id": "84d78bb1-31ee-4467-8053-5aea019076b3"
            }
          ]
        },
        {
          "id": "ac58f898-7c05-4595-ad16-ab3f922e1833",
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
              "id": "93026ca7-235e-4324-813e-bb6c74943504"
            }
          ]
        },
        {
          "id": "cc2db791-e131-4afa-a154-8d442424b91f",
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
              "id": "2526e128-7281-4a07-a61c-76c8a3860620"
            }
          ]
        },
        {
          "id": "065a2c5e-3e97-475b-9c93-a296b8973bda",
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
              "id": "d3cc6004-c075-4ef5-8f3b-028e14228445"
            }
          ]
        },
        {
          "id": "0a076889-9d85-484d-8431-101c1ddf70b6",
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
              "id": "3d057096-bb9f-4c78-b027-da96b41a608e"
            }
          ]
        },
        {
          "id": "04b6d867-34fe-4b15-94c0-01337d1716ad",
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
              "id": "36a0e3cc-72ba-4f76-9e45-45b13569a2f0"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "e1b34df6-7fbf-40c4-9432-1c049f378f07",
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
              "id": "d84069a8-78cb-467a-9582-0753bfcdc5a2"
            }
          ]
        },
        {
          "id": "dc25c2cd-a804-41fa-8ce2-4b5891070ee4",
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
              "id": "d4fc10bf-fcea-43fc-87f2-1a20dd6e2232"
            }
          ]
        },
        {
          "id": "aa618e3c-ff50-435d-8adf-44686b857ee4",
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
              "id": "22395a48-b700-4983-a7ff-19bc890b660f"
            }
          ]
        },
        {
          "id": "bcfc7fce-2b18-45ad-b820-ef54732d2612",
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
              "id": "8d220fd4-fc27-4ee3-8a85-d2066c156c51"
            }
          ]
        },
        {
          "id": "900559d1-94be-46ca-85db-7cc0b3b65af7",
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
              "id": "15134485-a403-4b9c-906e-ad56da96b30f"
            }
          ]
        },
        {
          "id": "69edc248-3400-4b89-b0bc-7e563be824cd",
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
              "id": "1e603fda-0cc7-4373-98e7-3fc66d261694"
            }
          ]
        },
        {
          "id": "8bf7b23c-7956-4eb0-982b-489f1f67ce3e",
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
              "id": "2b059412-1835-4aec-9b52-3f4867d8617f"
            }
          ]
        },
        {
          "id": "d3b9b114-8229-4e8a-ab15-b8651fd36271",
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
              "id": "66410dd1-2143-4631-a17d-2438b2802366"
            }
          ]
        },
        {
          "id": "745a3965-0720-4a6b-b193-5593bd64f046",
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
              "id": "fa5aaf6b-55cb-410e-a421-706591020dc2"
            }
          ]
        },
        {
          "id": "2149e7d2-2fa8-4a60-8d66-a0075de6506f",
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
              "id": "3ca8865c-d607-425e-9424-2d0527eb388d"
            }
          ]
        },
        {
          "id": "adee5a2d-03a4-4f32-9569-c783005067e8",
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
              "id": "9ef88faf-4e5e-4c5a-b6a9-f44ecbc586cc"
            }
          ]
        },
        {
          "id": "b8e38b2a-68fa-4932-8605-7eedaeb64bef",
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
              "id": "8c0146e4-ff09-43e4-afd9-722bcdbaf12b"
            }
          ]
        },
        {
          "id": "e91f843b-b770-4ce8-8439-3240ce150bdc",
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
              "id": "5dc53a1c-4d69-4dee-bd2a-4bd5758dfa31"
            }
          ]
        },
        {
          "id": "a50e7878-b4e6-406a-8eb2-83cb0044d7da",
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
              "id": "8c87d639-9a12-4d27-863c-404cad5ca4f4"
            }
          ]
        },
        {
          "id": "01017649-0601-476e-bfd7-843756e36b7b",
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
              "id": "3a11eac2-c2c3-4bbd-a94d-32f6c7079933"
            }
          ]
        },
        {
          "id": "f9147fb5-45ea-45ff-a03e-5b6eb95b78fa",
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
              "id": "3e175099-4df4-4d59-b998-68a2ef4b362d"
            }
          ]
        },
        {
          "id": "2d6840b5-e450-480b-8f86-2476a06ec68f",
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
              "id": "ad0ff262-aad5-47f5-890a-06308cf02764"
            }
          ]
        },
        {
          "id": "b2bcbb5c-223b-410d-8661-284144c93b3a",
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
              "id": "1467155b-6138-4292-bb5b-3fb673f7f227"
            }
          ]
        },
        {
          "id": "96206d9b-a3ed-4664-b8f2-a90b758b80fd",
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
              "id": "b46e97ed-f47c-417f-9cc5-a362cf8ae93e"
            }
          ]
        },
        {
          "id": "a1e55923-f041-44b7-9f90-7a5142328d75",
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
              "id": "1970c17e-3527-495d-a97b-d2b5c8c121a6"
            }
          ]
        },
        {
          "id": "7406135f-c0dc-48a3-b4d1-7a1cbcd4f620",
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
              "id": "a0c6fff9-1a2b-40ad-95dd-5b98ed2ffbc2"
            }
          ]
        },
        {
          "id": "da604711-a108-44fe-b5ce-5c8889e33aa5",
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
              "id": "cdc597a8-295c-4a8c-8e74-934bd003940a"
            }
          ]
        },
        {
          "id": "adda71ed-1173-4011-8905-ab400428b9f4",
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
              "id": "b19d6ab5-b54c-4561-9f88-59e7143f6353"
            }
          ]
        },
        {
          "id": "2e7915a7-ddd9-4aaa-901e-5258a6189d1e",
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
              "id": "2b063054-8650-4e98-b853-ccefc6763054"
            }
          ]
        },
        {
          "id": "a8afcbb5-eb19-45c8-905a-9857368ffc72",
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
              "id": "c5eed00d-57d5-4e2f-944a-89458b0ae3cd"
            }
          ]
        },
        {
          "id": "283f3694-bb04-4a8a-bdb3-5de12a47d4e3",
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
              "id": "a5318d57-fe4b-4f7d-bd6e-d6b8fb945aa4"
            }
          ]
        },
        {
          "id": "9ffe549e-86c4-4161-b03e-ccfabb2f96ed",
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
              "id": "fee0409d-7ee8-4d72-b852-c00f2aff9582"
            }
          ]
        },
        {
          "id": "2453d4a0-a17c-4875-9613-0097dfdc82be",
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
              "id": "37845782-7626-4414-b191-6556060795aa"
            }
          ]
        },
        {
          "id": "367923bf-7566-4d89-99f4-5b8cc5b3d36d",
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
              "id": "3bdc7d8a-dd95-4e99-8a8e-6832dd530a71"
            }
          ]
        },
        {
          "id": "8da52033-2022-4ae6-963d-5c8426ffe4b4",
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
              "id": "1080bf93-6fba-4635-9a41-5b1ac0713d6a"
            }
          ]
        },
        {
          "id": "2a896d36-6a1d-49a0-9ab5-65fa5bac6781",
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
              "id": "7e146fbe-6432-4887-896b-ab41bc46dcb8"
            }
          ]
        },
        {
          "id": "c946dadc-e627-440e-8ace-eefa296a9359",
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
              "id": "b98495bb-1607-4267-aa1c-64c772c6da08"
            }
          ]
        },
        {
          "id": "a643d10d-8c50-4acb-9d57-db23ee6a812f",
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
              "id": "d89ece74-cbdc-4723-933f-2b3014663d02"
            }
          ]
        },
        {
          "id": "2e35f4c3-4e9a-45e7-ac68-c2791747a1fc",
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
              "id": "6a7a4cf0-1b09-4160-9d89-e19e43a87980"
            }
          ]
        },
        {
          "id": "6ffb20ae-2d60-48bf-9647-373441b7c504",
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
              "id": "c145a57d-7973-4745-854c-925e9afcd5fd"
            }
          ]
        },
        {
          "id": "8b517a04-ceae-48c9-9f5f-80a9df604e33",
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
              "id": "c155581a-c911-47a6-b02f-ca43aa1a37aa"
            }
          ]
        },
        {
          "id": "2fcc7c24-ca41-48e4-b3c4-71dbbaebee4d",
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
              "id": "5c6835a5-5177-4c9d-9c41-9f7cfd52a0fe"
            }
          ]
        },
        {
          "id": "6b6a3a0e-3d03-4e23-b3b8-8256e2a4df83",
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
              "id": "cca3c39f-8b50-4be5-9de2-4cfa4e1b4fe4"
            }
          ]
        },
        {
          "id": "49f1a5fb-6b96-43a9-b7cf-8eef33e5c5f0",
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
              "id": "4c95e330-2d19-43bd-8dd4-c08634ef4b52"
            }
          ]
        },
        {
          "id": "c4295126-6f5d-4177-b522-d7623147bbf9",
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
              "id": "d5ac34f7-0b3e-47e0-a233-be82e07ad555"
            }
          ]
        },
        {
          "id": "a0916398-068a-400a-b678-82f364133e8e",
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
              "id": "7401e6e3-0be3-487a-9932-37a53881b51f"
            }
          ]
        },
        {
          "id": "cbad0e91-b2c0-490c-92a5-5244fd829436",
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
              "id": "1286a734-2ffc-4e31-b5b5-a7bee8a08e7c"
            }
          ]
        },
        {
          "id": "df45a549-60ae-47ba-88bc-56972c989be7",
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
              "id": "12669130-dcdc-439c-bb23-1eb6bfa127ef"
            }
          ]
        },
        {
          "id": "d789f69a-f990-40f5-af2e-0b08e3174f69",
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
              "id": "1baedf38-c23f-44fa-8215-608291cab0ff"
            }
          ]
        },
        {
          "id": "35dfc0f2-99f6-43b9-b427-e4b73035f5af",
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
              "id": "87f97058-04c0-480f-9281-427d833c9ceb"
            }
          ]
        },
        {
          "id": "89ceb50c-93cf-4dce-a7d6-5f9b5d4eadc8",
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
              "id": "0a11fff0-ff26-4b77-847c-3ba1684845aa"
            }
          ]
        },
        {
          "id": "ef329cb9-bf9a-4fbc-8dbd-0b30a4e766ea",
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
              "id": "8212a97b-6052-40b5-892c-87b29a7d63eb"
            }
          ]
        },
        {
          "id": "20be9587-86b1-438b-9c59-dd178c06d432",
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
              "id": "af4aafd2-8793-4aee-a888-94b94cf6b7c7"
            }
          ]
        },
        {
          "id": "49afd88b-4244-43a3-94ba-368e57af75ad",
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
              "id": "8235311e-9b73-41a5-9d9f-ff360aa1b0e2"
            }
          ]
        },
        {
          "id": "87e2b7b8-3420-454f-b1c9-cd3312785a77",
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
              "id": "76c0025c-69c1-4602-b834-129497680e23"
            }
          ]
        },
        {
          "id": "e2d626b4-f374-458f-ad8f-abeafd5801ec",
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
              "id": "dd93f3ce-0f34-42c3-bba6-8d64912b9fd9"
            }
          ]
        },
        {
          "id": "9a519803-48d1-41a8-8191-57bd7e77b9ee",
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
              "id": "43850385-e5c5-4528-a39f-a99d07cec518"
            }
          ]
        },
        {
          "id": "5069d698-9f4b-459b-bdd0-956833c1ec2f",
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
              "id": "98bf8c2b-d42d-465f-a75f-5067c369b75f"
            }
          ]
        },
        {
          "id": "2b9e1426-5241-495f-a1c5-1e5105127a3d",
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
              "id": "707a6766-bc6e-428a-af2f-ee7688067be8"
            }
          ]
        },
        {
          "id": "cae44f1c-d6bb-48f6-9625-e3e5953d1887",
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
              "id": "b8e5b93d-7cb8-476d-85c6-9fc2da1b2ca1"
            }
          ]
        },
        {
          "id": "a234c55c-3cd9-4494-a330-a2b80a083107",
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
              "id": "fc2fd45f-a7cc-4e04-8a96-583c08c06525"
            }
          ]
        },
        {
          "id": "c7784be2-05fc-473c-b92a-dcc952c35490",
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
              "id": "ea6dfdcc-eaf3-4ac8-bea4-3c378d8afe47"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "61393658-376b-42a0-9037-d0d6dcb3e8b7",
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
              "id": "2ff932d2-d87c-41f9-ac41-e4176103ae7e"
            }
          ]
        }
      ]
    },
    {
      "name": "Deliveryformat",
      "item": [
        {
          "id": "1d42c256-4892-441a-9256-d6dc0b003824",
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
              "id": "710dcfcb-8bde-4301-b693-e644ddf81b26"
            }
          ]
        }
      ]
    },
    {
      "name": "Audience",
      "item": [
        {
          "id": "67436771-75a1-49de-ba9d-6845fb032a49",
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
              "id": "c5602837-deb2-4dd1-a25f-f03475b49730"
            }
          ]
        }
      ]
    },
    {
      "name": "Clients",
      "item": [
        {
          "id": "d968c729-0245-4ea1-a57d-37b3f1c69fa6",
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
              "id": "97ff30db-51c1-4789-a61f-ae898df0534d"
            }
          ]
        }
      ]
    },
    {
      "name": "Feo",
      "item": [
        {
          "id": "72d2856e-f395-4a6c-9744-b26a985f054b",
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
              "id": "e321627b-7d3f-4b61-b5c0-59eba0662e0c"
            }
          ]
        }
      ]
    },
    {
      "name": "Imaging",
      "item": [
        {
          "id": "95495df5-4cd2-4821-a1d2-037673b8eee9",
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
              "id": "7183b457-03a7-4bb7-b5c3-06641e848661"
            }
          ]
        },
        {
          "id": "916f5f66-b987-4479-9bde-954cb3d2f34d",
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
              "id": "35caa872-a65d-4696-9e6c-fb273b890bc5"
            }
          ]
        },
        {
          "id": "d0d998d2-1aba-4125-888e-e9ac7acc2d46",
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
              "id": "b3d7920f-3da3-4548-870a-c8dad7396f64"
            }
          ]
        },
        {
          "id": "08945c91-0e3a-4b62-9676-4e77c16aeae5",
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
              "id": "1e00f5ac-1a42-40bb-9300-a5b16f1c9150"
            }
          ]
        },
        {
          "id": "6ea37bd4-899a-4b08-b620-37a9f6c3b2b4",
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
              "id": "171187ba-e3d2-4456-9e9c-faeb6275c3db"
            }
          ]
        },
        {
          "id": "97bfead1-ba60-4f21-bcc8-5139f517464f",
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
              "id": "198557fb-35f5-40f2-85e9-35f27b171398"
            }
          ]
        },
        {
          "id": "c45f8f93-852c-4b19-8185-9c0704ef49bc",
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
              "id": "a5ed49b3-90d1-4461-88f9-c1528758ef3a"
            }
          ]
        },
        {
          "id": "2502b41c-134c-43d5-88a7-fed44bfb198f",
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
              "id": "3451ac96-5c00-4901-ad32-4abf73149e85"
            }
          ]
        },
        {
          "id": "34453a0a-07e8-4908-a110-bb0866eb7bfe",
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
              "id": "5c5389c5-2f13-45bb-9403-67de3c2bcad0"
            }
          ]
        },
        {
          "id": "e21747a5-9ee6-4ffd-8ff7-90bf0d7eda88",
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
              "id": "486fc3ec-9e91-463d-8b6a-71eb47a03755"
            }
          ]
        },
        {
          "id": "35eba343-901a-4b67-85cc-27d264c50d5b",
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
              "id": "6d52c20b-2ed2-4961-8f88-45bee09724ef"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "3f2acd31-55cf-4643-a003-f68599f26a92",
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
              "id": "fbe8afda-770a-4d79-97bd-647c82fdffaa"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "4b75f58c-fb6d-4dd0-b092-3cbe37576909",
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
              "id": "df6a0e82-00d6-4d9d-b146-61a3c95377ee"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoicing",
      "item": [
        {
          "id": "1b05ad14-2b9c-4f7e-a47b-1f051552a3ad",
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
              "id": "80b770c9-081c-4492-9a78-e5880097c0b7"
            }
          ]
        },
        {
          "id": "213b2da2-056d-4fad-94db-b7faa37618b7",
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
              "id": "9033a594-13f5-48d7-b8fb-e8f216aef82b"
            }
          ]
        },
        {
          "id": "390b540d-b968-41fa-b303-d0254851809d",
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
              "id": "0317734a-f5e6-4674-8297-4d071e1bb480"
            }
          ]
        },
        {
          "id": "8affe93d-1e17-4712-bf28-6a45a2d95a4b",
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
              "id": "5d4806a6-fcc4-46b4-a89d-cfd96e9d4067"
            }
          ]
        },
        {
          "id": "75bf11dc-20f3-4f20-bcc7-a4ca9201b1f7",
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
              "id": "5332bb71-bce0-4634-a62d-5b11a6d5de9e"
            }
          ]
        },
        {
          "id": "9e27d21c-ad58-4210-82d7-bf7472526c29",
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
              "id": "f74cfa98-5dc9-4a7b-a197-094511839446"
            }
          ]
        },
        {
          "id": "e83e307f-16cb-4b44-bd78-9c098cd02927",
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
              "id": "61b573f1-1204-414f-a1d7-4f4265ba53b1"
            }
          ]
        },
        {
          "id": "10684974-1b84-4379-9402-9c663031b859",
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
              "id": "40b40c17-b864-434b-9cc5-588d40e3fe91"
            }
          ]
        },
        {
          "id": "e5dcdd5b-7bc8-4a8c-976f-6e86f8618c3a",
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
              "id": "a5b33faf-5cb8-4dcf-be1c-3140c19b764d"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "ffc64365-69ab-4a46-a8fd-ea394d49b47b",
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
              "id": "f7e565da-1e6c-44eb-ad97-4a86a44f1c0c"
            }
          ]
        }
      ]
    },
    {
      "name": "Configurations",
      "item": [
        {
          "id": "2f2bb436-5fd8-49ad-8d3a-e26c787f0ffe",
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
              "id": "ac90dd98-5070-45ca-8eb2-9002cc9ef9e0"
            }
          ]
        },
        {
          "id": "b77616b9-5edb-4e2d-9668-f89be426674c",
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
              "id": "3a5d232a-5d4f-4f64-bee8-200b66b929f9"
            }
          ]
        },
        {
          "id": "fe6239d4-27a6-4ca4-9879-6148c5f1658a",
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
              "id": "2489de8b-40e8-41aa-b262-8fa35db7f378"
            }
          ]
        },
        {
          "id": "b53734f5-11fd-4dd8-80f8-dfd718a476a2",
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
              "id": "46994afc-da0a-427f-928c-9f241a390fc4"
            }
          ]
        },
        {
          "id": "4433621e-bd91-42d5-995e-71d722bc003d",
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
              "id": "e7327c55-bc02-4e16-8bbe-7755a38db302"
            }
          ]
        },
        {
          "id": "953c8fda-9140-4fb2-8481-8621b708a4a4",
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
              "id": "0f535098-f0ef-47cb-93cd-22c0834a961d"
            }
          ]
        },
        {
          "id": "aaceee24-d103-46fc-bb30-ace4c64e9f77",
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
              "id": "1705b28c-6b10-4858-8754-3ae366627166"
            }
          ]
        },
        {
          "id": "0ae0a33f-a25d-4344-956b-27218e0f3ec4",
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
              "id": "4c863f29-0f49-46db-b882-80817d036c34"
            }
          ]
        },
        {
          "id": "19e78dc6-a951-495b-8f92-558a1c6dff78",
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
              "id": "93cd4fb8-be4e-47b9-9797-d6cdf4e79813"
            }
          ]
        },
        {
          "id": "b46fcd68-fb0f-434a-af06-4aadc9153296",
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
              "id": "ef4a5273-6328-4010-9109-7373d7984346"
            }
          ]
        },
        {
          "id": "3db706fb-45f1-4ad8-ae98-7c6b3f318cf8",
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
              "id": "265e9645-d356-4def-be0f-d7b97223399a"
            }
          ]
        },
        {
          "id": "a21b6728-c17b-441b-829d-a5e4d5ba8371",
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
              "id": "7e0f2cf8-8b9f-4984-a0c1-14ed543a5c19"
            }
          ]
        },
        {
          "id": "b722ea09-bf95-4a42-b442-4d6eaa809b0b",
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
              "id": "8f8edbef-9866-48c2-a99c-cf94e32802c9"
            }
          ]
        },
        {
          "id": "8f45680b-02a3-4616-9192-ccebccc30a3c",
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
              "id": "543e258c-9f05-4cc9-b2ba-9d1240afa88f"
            }
          ]
        },
        {
          "id": "c17dde85-47ad-4121-916a-c9c9532b560a",
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
              "id": "ee343d5a-c20e-493a-90fa-29fd5b284c35"
            }
          ]
        },
        {
          "id": "280905bf-88e2-4505-99e8-11ac435e1269",
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
              "id": "24814303-d5a5-4adf-8cbc-06a9d70ed3b3"
            }
          ]
        },
        {
          "id": "606c8f1f-1a5b-4943-87ca-2163ab74ac8a",
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
              "id": "3396839a-3efd-481b-8c22-dc8924e5b7b4"
            }
          ]
        },
        {
          "id": "6d71bb6e-90a1-4e04-9f39-1a9e51559100",
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
              "id": "68ea01b7-4468-4e63-b5ed-c0b9c49a8cd0"
            }
          ]
        },
        {
          "id": "b9e774f5-28cd-4284-b1f0-af07aa4c8364",
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
              "id": "245cc197-1e24-4b74-8170-1ff8c880d826"
            }
          ]
        },
        {
          "id": "6afbf031-4ac7-46bc-b048-906f305d7614",
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
              "id": "946d09e7-4c30-4ada-8cdf-b8479e95992e"
            }
          ]
        },
        {
          "id": "87c4fc09-8f8e-4fb2-acb2-c75da12356be",
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
              "id": "40f958ea-6add-49c2-a56e-41dbc9846a17"
            }
          ]
        },
        {
          "id": "5a0bd501-32c9-49ac-92ce-26cddd8edb8c",
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
              "id": "d0a1a392-4241-4c53-ac7b-0ddfe8c084af"
            }
          ]
        },
        {
          "id": "a6fe57d9-2298-4bf3-b528-f862c3a4d42b",
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
              "id": "182aad56-d608-4d3b-a596-b2213db34c41"
            }
          ]
        },
        {
          "id": "ac441867-a81a-4117-98bf-a104b04e9105",
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
              "id": "3e45ab98-8d52-4b2e-a497-49da8604fb8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Service",
      "item": [
        {
          "id": "6ee9ccbb-8fbd-4730-8e62-5d9cc9a378f5",
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
              "id": "2bc31f09-55e8-45be-8b6c-53f3b0b19c03"
            }
          ]
        },
        {
          "id": "fc37c21d-4a3e-4555-b46e-2dbd4d227dde",
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
              "id": "7c8a3f63-3c3c-4989-8b48-53111c060138"
            }
          ]
        },
        {
          "id": "6c0695e2-77a0-4d46-804e-6352f3087249",
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
              "id": "0b1bf1bf-2604-4c3a-b1f6-39681fb8f5c7"
            }
          ]
        },
        {
          "id": "08b75dd0-b1f2-4270-adf5-3e7300e21dc0",
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
              "id": "97fc480a-8d0d-4ec6-bfd4-af2736fb6b16"
            }
          ]
        }
      ]
    },
    {
      "name": "Services",
      "item": [
        {
          "id": "f473f552-01cd-4a6d-bb0d-201e2e3f3c7b",
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
              "id": "0b06da75-1c93-44d4-b175-8f18bf53acdd"
            }
          ]
        }
      ]
    },
    {
      "name": "Lds",
      "item": [
        {
          "id": "04423503-c5a0-4065-a9e7-d1697d27b0d3",
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
              "id": "f7ad198a-c53e-484c-b0f3-668fef6e9054"
            }
          ]
        },
        {
          "id": "3a4d7fd1-2b74-46c5-8c81-aa67c3b49265",
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
              "id": "7353b1b1-f4a9-4b73-8ffe-85b2f76f84d6"
            }
          ]
        },
        {
          "id": "fa640901-01af-4fa4-83fb-233a52f6c7fe",
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
              "id": "8b605ebc-aa74-4a15-97c6-335f972f8d44"
            }
          ]
        },
        {
          "id": "a621512e-8035-43c8-ba21-247165895c55",
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
              "id": "6204a2f7-e4fd-4cb7-9485-88660b9a54a0"
            }
          ]
        }
      ]
    },
    {
      "name": "Redelivery",
      "item": [
        {
          "id": "7d8b2229-6ed7-49cc-83f2-7cc19d11a1e5",
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
              "id": "a9c8248d-2b6c-4c2b-99d7-e224fbf9b3de"
            }
          ]
        }
      ]
    },
    {
      "name": "Key",
      "item": [
        {
          "id": "4114280a-0c5b-45f5-837c-d7c6818d6380",
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
              "id": "d599afca-bb7e-452e-919d-94ffc8076296"
            }
          ]
        }
      ]
    },
    {
      "name": "Media",
      "item": [
        {
          "id": "2d49fea2-6221-42f4-944f-feb0a7214a5c",
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
              "id": "85cf337b-2d5d-426a-949d-ee14ad07ee5b"
            }
          ]
        },
        {
          "id": "af9da7ad-a1ae-41aa-bb62-2ea7c4d0f8eb",
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
              "id": "9b2fe3bf-4635-407c-8bbd-cb9023477dcc"
            }
          ]
        },
        {
          "id": "67a39dab-93eb-4d49-9420-b138c28499a8",
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
              "id": "50a1b2bd-af68-4ecb-898e-b78019f39b81"
            }
          ]
        },
        {
          "id": "b42e4ff4-3373-495d-a5a7-36b7172b4701",
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
              "id": "bcee3c5a-5d68-4b1a-b10b-9e53deb44971"
            }
          ]
        },
        {
          "id": "1de667bd-08c0-4c34-ad90-dae6d37df7a4",
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
              "id": "b03458e3-ec42-463e-96e2-1cd1c0ce8c96"
            }
          ]
        },
        {
          "id": "49242bcb-bf18-4e6a-9d26-da1f2addc9d0",
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
              "id": "6d6ff93e-d676-4c76-af55-dad43cd9b020"
            }
          ]
        },
        {
          "id": "cca4cfb9-d670-40f3-9b2b-0f8b74255f51",
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
              "id": "96fa521c-b20a-4876-baf4-282e6ef5900e"
            }
          ]
        },
        {
          "id": "44f2cc06-e453-4392-a1cd-6da30deb194e",
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
              "id": "dd4bc7bb-c12e-47a0-96a0-2e36eafc3ae2"
            }
          ]
        },
        {
          "id": "786f5153-2dff-4e64-b428-94e5dfa46846",
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
              "id": "2bcd7add-b53c-460e-a5e9-28eeef8ec8e5"
            }
          ]
        }
      ]
    },
    {
      "name": "Filterparams",
      "item": [
        {
          "id": "68eb3130-2555-4817-9e66-d84b36b27de3",
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
              "id": "a16032b4-fb19-4fd0-9b61-3197561409c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "366525fd-3521-4cc9-8001-89a7d775ddee",
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
              "id": "4855bb91-278c-46e2-87db-621c5b51da3c"
            }
          ]
        },
        {
          "id": "46d3bf5d-2905-437e-856c-435c3902dd67",
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
              "id": "1e50f3c8-57b5-4b7f-938d-4f27e89912a2"
            }
          ]
        },
        {
          "id": "29029139-47b8-4a48-9c20-aefeea496287",
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
              "id": "7a0b4d8d-6287-4138-ae24-72b38c176310"
            }
          ]
        },
        {
          "id": "c68f454f-3566-4c7f-964f-50726e6d7809",
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
              "id": "aabb5232-b300-4faa-ae63-89b8183d8e02"
            }
          ]
        },
        {
          "id": "f4e459bd-06f0-450f-a864-7a34598c66ee",
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
              "id": "5f0d6077-2a7d-4f14-8dd7-5b3a9b2613e3"
            }
          ]
        },
        {
          "id": "b9751e5e-d407-48b0-be76-ec8b2d42b214",
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
              "id": "3b4912de-d7db-443b-bbf7-307d506ee32a"
            }
          ]
        },
        {
          "id": "b6b3658d-22c2-45b3-b09a-1cedd46153f9",
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
              "id": "a580109e-baa3-4236-9fdc-11564b61844c"
            }
          ]
        },
        {
          "id": "541c08ec-de00-4fbb-8bae-9e2c0f9a23e7",
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
              "id": "ce9dff83-8eff-42b9-a828-32214bdb3ac5"
            }
          ]
        },
        {
          "id": "986af62c-49ac-4441-9a93-a6d1899b2517",
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
              "id": "5398b722-aedb-44dc-902e-dc5bed018d11"
            }
          ]
        },
        {
          "id": "b0148278-f00b-4813-91e3-f1e36ea51a8e",
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
              "id": "4ba91bad-5e09-47f4-94f3-0b156194dab9"
            }
          ]
        },
        {
          "id": "c309fa9c-57b5-4d6a-bc30-3e60ad036e94",
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
              "id": "85722d87-7297-4124-9dec-40bc3bb1c373"
            }
          ]
        },
        {
          "id": "7bd84893-51b3-41f7-90e7-38489242f96f",
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
              "id": "e29e2758-2448-45a7-828d-a9b7164b0798"
            }
          ]
        }
      ]
    },
    {
      "name": "All",
      "item": [
        {
          "id": "2ce0292a-203f-41c7-9fd8-c17e802e168c",
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
              "id": "04c3a8c4-4990-495a-9fbc-dcfe07c742c3"
            }
          ]
        }
      ]
    },
    {
      "name": "Prolexic",
      "item": [
        {
          "id": "28ef5a45-999f-474a-bff0-487ecc0b5738",
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
              "id": "47a4d4af-5f2b-462a-b304-271df754883a"
            }
          ]
        },
        {
          "id": "1b71c129-f796-476f-b4b2-5517adf28922",
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
              "id": "85a4db21-e293-419e-a1bf-90796c825b70"
            }
          ]
        },
        {
          "id": "81dcfe2a-d2a5-4e5e-9d50-de38ae88377d",
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
              "id": "36a5c914-eada-40ee-9658-6dfed909a1a4"
            }
          ]
        },
        {
          "id": "a802c37e-10ce-4188-aa1e-e33734296348",
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
              "id": "32d14094-3543-4948-823c-3175bd88b17d"
            }
          ]
        },
        {
          "id": "33cfb0f5-e73b-4023-a34b-98597dbfc0b5",
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
              "id": "16b93581-65e2-4e98-9482-78491f039bba"
            }
          ]
        }
      ]
    },
    {
      "name": "Type",
      "item": [
        {
          "id": "74c4be59-a966-476b-a437-61b6d870b491",
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
              "id": "2801dad5-711a-4444-a84c-a11dc7aa08ae"
            }
          ]
        }
      ]
    },
    {
      "name": "Papi",
      "item": [
        {
          "id": "014bb547-25ca-4026-8480-b71df31d18a1",
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
              "id": "901ccd07-74bf-4c38-9585-971b68d61d16"
            }
          ]
        },
        {
          "id": "40601fb9-007a-4850-9d89-8f8f0e628a66",
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
              "id": "bacb7ef4-cad4-4506-b712-c2c27d0524a4"
            }
          ]
        },
        {
          "id": "0b5030a6-354c-4d9d-bbd6-c76b79fdd609",
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
              "id": "f9eaeec1-bfa1-43fb-9754-6e91dbe40cfc"
            }
          ]
        },
        {
          "id": "9598cc47-0c87-4d38-b500-266ff838a9dd",
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
              "id": "edbfe759-c90d-4713-96a4-f350a601ec64"
            }
          ]
        },
        {
          "id": "b9e8eddd-6739-4269-be9d-b6c4806d2b11",
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
              "id": "e0a2cb91-7051-40cb-b409-5566feb08dbe"
            }
          ]
        },
        {
          "id": "f8687321-87d0-4c34-89a4-ca2e31be8cf6",
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
              "id": "edce882b-30f4-4707-9287-199800522e1d"
            }
          ]
        },
        {
          "id": "e08d4e2f-8569-4655-978b-0edb4724686e",
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
              "id": "83c2a212-7f1b-485d-ad6e-47465aa7cf01"
            }
          ]
        },
        {
          "id": "5bc1602a-f45e-4351-b68e-651a3f71ce62",
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
              "id": "0d7cb75b-ec5f-4452-8c2d-708b904ae903"
            }
          ]
        },
        {
          "id": "c48d7877-5ba5-47b8-9f2d-2b9be172d609",
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
              "id": "749d97eb-3eab-4eb5-9e72-bbb3f5fdb3b5"
            }
          ]
        },
        {
          "id": "8d8db540-9917-4fb5-ba4e-c9782ce90fdf",
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
              "id": "b730d3d0-ec7a-48e4-b90f-037157199ee2"
            }
          ]
        },
        {
          "id": "e2db8fd0-08e3-4d0e-8a1e-e213821ffdab",
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
              "id": "363b69c0-2520-49d9-8999-a915270c569d"
            }
          ]
        },
        {
          "id": "4b9e8aa9-6787-431e-834f-1aa0068157a4",
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
              "id": "83ba21b7-f393-4aa8-aee1-3ae3d728431b"
            }
          ]
        },
        {
          "id": "9343668e-d9ce-421b-8e0e-c905a8a48bcb",
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
              "id": "a98456b7-355b-48fb-a1e9-9928a55cd0fa"
            }
          ]
        },
        {
          "id": "f0d8a3fb-b612-4b2a-be41-4f6154a2a49a",
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
              "id": "fdaeb0df-dc95-4452-9c1c-e42d0d783744"
            }
          ]
        },
        {
          "id": "66fbcfd6-44ec-402e-a2af-ad4f596ec9bd",
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
              "id": "ea1df632-7390-459e-a556-fef1b3ffbc00"
            }
          ]
        },
        {
          "id": "e13491c4-ab5c-45f7-ae54-5f85b485c208",
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
              "id": "bf46a2b6-2dc7-40c7-9265-fe6f8ac3cc23"
            }
          ]
        },
        {
          "id": "7f6f697c-5203-4efa-adab-fb2ed3e8e780",
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
              "id": "187ee41d-ab49-4293-b05b-b8d65825920d"
            }
          ]
        },
        {
          "id": "4864266d-3bd8-462b-af0c-4a71ef00e82d",
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
              "id": "930bdebc-8113-4016-a881-272870869fe5"
            }
          ]
        },
        {
          "id": "7d303906-fd3a-44a2-82e9-7cba6d7cd92b",
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
              "id": "ea3ec4f7-dff9-4259-bac0-31ebb2899e55"
            }
          ]
        },
        {
          "id": "a7617a52-6e3b-4d04-9935-29e2a1745f79",
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
              "id": "e7752af6-5284-4f91-8bc0-e7392b494581"
            }
          ]
        }
      ]
    },
    {
      "name": "Versions",
      "item": [
        {
          "id": "9565228e-ae1e-4da9-8ca1-2d53ee0c1cd4",
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
              "id": "450b2e15-786e-4f87-bbb1-a55d8489e38d"
            }
          ]
        }
      ]
    },
    {
      "name": "Accept",
      "item": [
        {
          "id": "46d34f9a-10c0-4c70-96bc-3d6858eca07f",
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
              "id": "72b10f1a-83ea-4f61-bca2-df4976dfbbcc"
            }
          ]
        }
      ]
    },
    {
      "name": "CName",
      "item": [
        {
          "id": "2e23b034-6899-44d6-825d-d156bce719d3",
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
              "id": "4092393c-c8f7-480e-8e17-db7750e29080"
            }
          ]
        }
      ]
    },
    {
      "name": "Activations",
      "item": [
        {
          "id": "d4ca1070-e111-4fec-bc7f-09201ca5c927",
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
              "id": "e9c9f8ab-fefc-432f-99df-c02b694e3f32"
            }
          ]
        }
      ]
    },
    {
      "name": "Retry",
      "item": [
        {
          "id": "f3830e29-a445-4c4c-98cd-263e21c7dfcb",
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
              "id": "714a2e23-e027-41a5-9988-d65575818788"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "0b810eeb-4b47-4680-a373-4bad074485eb",
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
              "id": "aacde636-fd9d-49c6-8ee0-b92d685ed53b"
            }
          ]
        }
      ]
    }
  ]
}