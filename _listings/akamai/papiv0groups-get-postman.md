{
  "info": {
    "name": "Akamai API List Groups",
    "_postman_id": "013ecc57-7109-4fd1-a534-8342cd657d09",
    "description": "List Groups",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "56c9bd17-e0ed-4d45-8385-41651c618ac4",
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
              "id": "5f49d419-0861-4166-8252-3e07ba0615de"
            }
          ]
        },
        {
          "id": "f08d0b49-c859-4122-9b6f-db6c2a57da4f",
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
              "id": "17f30052-c78a-4866-a045-da90243f53d4"
            }
          ]
        },
        {
          "id": "bf3ab562-f0de-4952-b34c-848488a25247",
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
              "id": "97abe19e-c656-452e-a792-cdde664c42fa"
            }
          ]
        },
        {
          "id": "1964e139-d5b3-4c22-bd98-c070cca44209",
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
              "id": "e479346f-9211-4bbb-87be-bdae1d68cf1b"
            }
          ]
        },
        {
          "id": "5ee0a587-4028-4d6e-bf26-1bf1f9b1d80b",
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
              "id": "89fb5790-8bef-4f29-99a1-73e01d64a101"
            }
          ]
        },
        {
          "id": "d681bc0d-6a33-4abd-815b-6245bf39d597",
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
              "id": "8d832a33-567a-4662-a7af-d5e062d6a94a"
            }
          ]
        },
        {
          "id": "403fa4ed-c7e8-4970-8053-b6b5261766f0",
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
              "id": "c565d1ee-9d58-4434-907a-3a802b395be3"
            }
          ]
        },
        {
          "id": "e6bc16eb-8900-4362-a2b3-e3ad0334e88f",
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
              "id": "8d9d78fc-494f-4557-9070-484b37b46253"
            }
          ]
        },
        {
          "id": "1b4b1a9c-dec9-48a6-bd31-b5a42788d5f0",
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
              "id": "27c2c92b-c433-412e-80b0-b60405c634da"
            }
          ]
        },
        {
          "id": "9dd7ee0d-09cc-4497-b081-4adc19ff0e42",
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
              "id": "bedc4a92-bbe4-40dd-b508-5a944b64bb86"
            }
          ]
        },
        {
          "id": "70fe21b8-bcbf-4876-ab6b-61675b0a8a0e",
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
              "id": "a9e93602-b743-450f-a2aa-7d9e59535c04"
            }
          ]
        },
        {
          "id": "9f28a07a-9d5e-4241-b65e-eb1dd073db23",
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
              "id": "b319c5bd-6610-4bb0-abc3-2760089dc6a7"
            }
          ]
        },
        {
          "id": "aa0527b7-8973-462f-b36d-adeec6bcf37b",
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
              "id": "fbe6843e-c688-4d8e-a797-e4233876019f"
            }
          ]
        },
        {
          "id": "ac496ed6-449f-4adb-ab24-9e25a4d5caf2",
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
              "id": "09b38456-c207-4c52-bb71-ea84dfcd264e"
            }
          ]
        },
        {
          "id": "7f0fbbb3-e8a9-493f-a1e7-24dc68533622",
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
              "id": "e88858b3-32c7-4ba3-9d56-9a4066f94048"
            }
          ]
        },
        {
          "id": "5e8bf6d1-8b31-4183-976a-3ccce7f3bb76",
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
              "id": "af297b5c-de74-46b9-96c6-466ecdbef65d"
            }
          ]
        },
        {
          "id": "0fe3bfd8-e093-4a0e-bb17-b8cc7e3095e5",
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
              "id": "ae812487-0f2a-41a9-983c-879793d80493"
            }
          ]
        },
        {
          "id": "5ef30c10-ada9-44b6-a63e-95ed584af67d",
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
              "id": "79fc0fb9-e513-448a-b124-1a70b1869de9"
            }
          ]
        },
        {
          "id": "dc720f13-5e3f-4746-bf26-1449fa5736da",
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
              "id": "3596b9fd-c5bb-47da-a889-321a87286121"
            }
          ]
        },
        {
          "id": "274e411d-aac2-4a74-a627-3040bd81143b",
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
              "id": "bc6f8a44-8793-4926-b04d-9a1ea9b0848a"
            }
          ]
        },
        {
          "id": "1b72bf8c-42f9-4c0a-a415-694e5e966f6c",
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
              "id": "97d323d4-96fd-4149-8be0-d8a21b5efb22"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "defd486b-ca45-486a-9ed5-acc0ab965a0d",
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
              "id": "a4d178eb-3a8e-4642-8f84-8f06ca8749ef"
            }
          ]
        },
        {
          "id": "d04ad365-9e95-4fa0-b687-5ee4832b3372",
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
              "id": "85891d09-b3f9-4990-b817-6692af380759"
            }
          ]
        },
        {
          "id": "cfd59ab2-9de9-47e3-87a6-445b9a40912f",
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
              "id": "ae8c2438-bf54-4560-a5b6-6a6437ac935b"
            }
          ]
        },
        {
          "id": "490e3125-26ae-4e4d-839b-0547cde131fc",
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
              "id": "f5f04ae4-1e03-488e-abcd-d99939c6c731"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "a3e18376-c661-4ceb-b2bd-9818bf2f62ec",
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
              "id": "b87ef9d2-093c-40bc-aa7e-e187f1ff048d"
            }
          ]
        },
        {
          "id": "487947a3-14b2-43f7-bbd3-b8b9663fcf77",
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
              "id": "1a625ffd-c70d-46ff-b98a-90c9b0eb95a2"
            }
          ]
        },
        {
          "id": "b0ad0f53-a3e9-4a05-b406-b28b86f64130",
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
              "id": "039e8540-1f3f-42cd-a53c-d87efc4abcc7"
            }
          ]
        },
        {
          "id": "ddcdde6c-e31f-485b-a6c3-8ab1ca831445",
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
              "id": "ec87accb-2181-4ccb-bb50-d9d4b5592400"
            }
          ]
        },
        {
          "id": "cc9c0fdc-7fa8-4b0d-b7ef-662049c35496",
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
              "id": "85120c32-3d15-4a3b-8173-77dc57b5461c"
            }
          ]
        },
        {
          "id": "206556c6-7235-46a3-b9ab-5d4cd2f376dc",
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
              "id": "456f341f-1c50-4e4f-83a9-867fcfae7ece"
            }
          ]
        },
        {
          "id": "23567b5f-dbdc-4177-8b16-15a7b3211528",
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
              "id": "a8844a5d-2078-4320-8897-3ef2c717e04c"
            }
          ]
        },
        {
          "id": "86bc687c-0472-4b5d-9f24-2c065f383422",
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
              "id": "ea6ae275-8a31-4444-b19b-c3a02d7dd491"
            }
          ]
        },
        {
          "id": "a3127137-6488-48a8-9415-4c716c889617",
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
              "id": "f0508764-2d8a-4581-8bd9-0a0618934c9a"
            }
          ]
        }
      ]
    },
    {
      "name": "Ccu",
      "item": [
        {
          "id": "f1d4a4af-ef51-4c32-bdbc-9679759824cc",
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
              "id": "9d3077b2-6ea2-473b-bed1-c5515380bde3"
            }
          ]
        },
        {
          "id": "1c97471f-ea35-4886-a616-624e61c26b6c",
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
              "id": "5a76d6bc-7568-47e5-80f8-208452b0275b"
            }
          ]
        },
        {
          "id": "5df73230-2c98-4393-b177-a8fae6063878",
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
              "id": "b17bf4fc-6ccb-4233-a72d-5b9e2a892b75"
            }
          ]
        },
        {
          "id": "582a5265-241e-401f-9088-ed62ebb5f746",
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
              "id": "80f22ebb-5bbd-47fa-9a43-de1ec3b537c9"
            }
          ]
        },
        {
          "id": "aa6f0f48-177e-4ea0-90ea-42895ab24faf",
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
              "id": "159047b5-11b7-4d91-8473-f4ceaa6795d9"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlet",
      "item": [
        {
          "id": "e3eec970-e1ad-428c-a5b0-67c8e842e8ad",
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
              "id": "a3d013f0-9d2b-416a-ac93-0d6eb50cf8f6"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlets",
      "item": [
        {
          "id": "55fbf1b9-8d2e-446d-ad8c-2d21719cd040",
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
              "id": "26423caa-fca9-4973-a319-26c24f7f254b"
            }
          ]
        },
        {
          "id": "3a15e496-3408-49b0-be0a-7fa7e66fe5ee",
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
              "id": "1fa0a382-193b-43b3-a933-27cdc32e6bdf"
            }
          ]
        },
        {
          "id": "5a405624-d5ca-4ed9-acdd-9c09d471a0fb",
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
              "id": "6c27c3b5-3356-4223-9c01-cffe6bfa7189"
            }
          ]
        },
        {
          "id": "d7773fdd-d79a-459f-b1d9-23acb853a4dc",
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
              "id": "7f992427-f35a-4130-9ee5-bf807d32ebcb"
            }
          ]
        },
        {
          "id": "05fb6f67-9a8f-45e9-91d7-b658b5748f97",
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
              "id": "855f9e03-0f31-435c-aa5e-8f549089a4d3"
            }
          ]
        },
        {
          "id": "e5005c79-c543-40b5-9567-a8d5b136eb08",
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
              "id": "93434d5b-9292-4348-a8e2-9337ae0339c1"
            }
          ]
        },
        {
          "id": "ad525cf0-76eb-4441-a45c-bae995448e44",
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
              "id": "095895e5-fe7a-4afb-96b0-b5f8a3dfd152"
            }
          ]
        },
        {
          "id": "04e0f06a-7986-454c-98b5-d637d3af8498",
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
              "id": "aa03a63b-85b9-420e-86f8-dc7e6a5f6015"
            }
          ]
        },
        {
          "id": "1dc22a81-2f95-4514-8bfa-81132af13302",
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
              "id": "ee81bba6-a920-4022-bfc7-f761ef2cbe5d"
            }
          ]
        },
        {
          "id": "779da67f-29e0-4ae0-a409-e247d5546900",
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
              "id": "f481d4fc-b361-4186-8bc0-b5f3387e324c"
            }
          ]
        },
        {
          "id": "2777f4ee-7482-4c4d-806b-17063ea9f28c",
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
              "id": "d4291238-1239-4598-9329-a3eb5aaf7f70"
            }
          ]
        },
        {
          "id": "354fd91e-b2a7-4207-a1ff-d8036e31442d",
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
              "id": "480bec90-9700-424b-bd06-987bb370c312"
            }
          ]
        },
        {
          "id": "aa0c2dd3-e239-48da-93e4-9875358d7ab3",
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
              "id": "f97672c3-f83c-4baf-8334-a3c0cd57426d"
            }
          ]
        },
        {
          "id": "afc47644-3899-47cc-be67-fbd08e1cec01",
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
              "id": "3477ea7a-f167-4b78-a03f-fd01497a8506"
            }
          ]
        },
        {
          "id": "490205be-0dd1-4dd7-9766-5516b6a77a8f",
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
              "id": "78bb25f7-3071-47df-881f-db2472595d20"
            }
          ]
        },
        {
          "id": "eb6fb4c5-0719-416c-9183-044dd5aa451d",
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
              "id": "54914a7e-f2e7-4d7f-9ef5-f0f9b61fefe1"
            }
          ]
        },
        {
          "id": "3f168859-a032-412f-bb2e-1cb1dc04a932",
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
              "id": "400b8b66-fe94-4699-9c69-10b2f42e7a4a"
            }
          ]
        },
        {
          "id": "c1d8e1da-a999-4e6d-82b7-eca2113adae4",
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
              "id": "a91bd1a2-8437-45e7-b386-b2df094ce618"
            }
          ]
        },
        {
          "id": "d5f4d108-0261-4b22-97e8-e21ea554db98",
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
              "id": "ed21c541-c5e6-4631-a9c0-adcea778badf"
            }
          ]
        },
        {
          "id": "4ded8ef4-0e4b-4faa-80db-5c589beb9c59",
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
              "id": "1c75f63f-aa60-4283-b90b-47083d193681"
            }
          ]
        },
        {
          "id": "c12d3634-2e66-4420-94d8-ebdf480cd39a",
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
              "id": "2ce3eaf7-4871-4ccf-b145-5fb9801a890f"
            }
          ]
        },
        {
          "id": "66222ec6-cea9-440a-b45f-b81cdc9f6008",
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
              "id": "a2dd4e75-0a2b-480f-b9fb-eb2501cdce31"
            }
          ]
        },
        {
          "id": "c9c970d7-5937-450d-a242-e0428d33e74a",
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
              "id": "4757fcdf-55ef-4ff6-b10e-8f8a56fec641"
            }
          ]
        },
        {
          "id": "894efaff-b9e2-4da5-a1fa-48f23b7c5b8d",
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
              "id": "455fb4b1-5336-4db8-af9e-a71c4523179d"
            }
          ]
        },
        {
          "id": "93a73a9d-8d7f-4282-a818-99bb3850841e",
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
              "id": "2be47b3f-ee2f-4d68-a06b-6106e3406bfb"
            }
          ]
        },
        {
          "id": "13828ee6-21ee-4f3a-84b8-be9dff83bd27",
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
              "id": "e4164177-157d-4426-875a-b690f67eed90"
            }
          ]
        },
        {
          "id": "de146f9d-8e09-40b9-9a54-308fe36e4f7f",
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
              "id": "1accb974-1c89-41ec-9609-54e46d04b756"
            }
          ]
        },
        {
          "id": "9b0c3517-d6dd-494c-89fa-43e52b70477e",
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
              "id": "25123643-a2c2-47b9-a378-2168084c2254"
            }
          ]
        },
        {
          "id": "54fbb8fa-34f8-49f8-82d8-f7916e48d332",
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
              "id": "673b89d2-8f3b-461d-9729-d541d4b95f30"
            }
          ]
        },
        {
          "id": "5270e98d-75df-4dfc-bed1-dce50d4c6867",
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
              "id": "d7fdcddf-ee8f-4ddc-b71c-12e2f8936251"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudletcode",
      "item": [
        {
          "id": "b17e82ac-84b0-4424-bfdc-5ee4ed4c1719",
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
              "id": "40a1766a-0680-4f41-842a-db242fef6cba"
            }
          ]
        }
      ]
    },
    {
      "name": "Cps",
      "item": [
        {
          "id": "135f29a0-e46b-4e20-ac14-4ae92068e662",
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
              "id": "afcc0e39-7b65-4a50-9512-e7a36479df75"
            }
          ]
        },
        {
          "id": "7c22ba69-d6cb-460a-b400-4e3e6838a257",
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
              "id": "74334f54-dcb1-474a-bd37-b14711423439"
            }
          ]
        },
        {
          "id": "9b95b099-a667-4fc4-b978-4cf1e6c39da9",
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
              "id": "9d186ebe-4186-4310-bfad-baadda812ec1"
            }
          ]
        },
        {
          "id": "42c78880-d257-41fc-8e0c-5286987aa643",
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
              "id": "2d973f33-141e-4c83-bfbc-44288e4c443f"
            }
          ]
        },
        {
          "id": "8c7f05f3-9b3a-4dae-8ad0-d4415b4b9a65",
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
              "id": "f62e5ca3-e18e-4433-9ff1-74e1c106f556"
            }
          ]
        },
        {
          "id": "96dc3c89-b2ef-4d7b-a4aa-86a14751dc76",
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
              "id": "cf8af5a3-992d-4368-9050-cfbc0b807366"
            }
          ]
        },
        {
          "id": "7bbf94e2-893d-45bf-9fe6-f5adafb8cafc",
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
              "id": "10c420df-ba7b-460d-a32e-207e61a4c940"
            }
          ]
        },
        {
          "id": "92c58873-519d-41f9-9eeb-b4ca2c535496",
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
              "id": "87584849-b82a-4f73-9212-e0cbc6685ef5"
            }
          ]
        }
      ]
    },
    {
      "name": "Information",
      "item": [
        {
          "id": "23621be8-7bde-492d-abb9-2043bbbe9b49",
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
              "id": "47544985-0b1a-428d-9dd7-da287a0b44c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Update",
      "item": [
        {
          "id": "8e9bb039-a45e-4ddd-a8db-4e767c244e66",
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
              "id": "cf58f0a3-4c7a-4fec-b254-8adb710e5b50"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "80e1b1d3-5edd-4649-bdf9-5a94a1b4082c",
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
              "id": "3321a9eb-07f6-4b72-b818-06701411053e"
            }
          ]
        },
        {
          "id": "53a21b2e-f749-4dc9-9e49-c9c23c66e7a4",
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
              "id": "bf8a3b00-f95d-4f90-8fd8-260b808a8398"
            }
          ]
        }
      ]
    },
    {
      "name": "Diagnostic",
      "item": [
        {
          "id": "9a4c2472-b40f-4533-bc3c-8e56bb793d1c",
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
              "id": "7c393530-5f07-4382-807c-eeaf51f6738e"
            }
          ]
        },
        {
          "id": "6c0bedf8-d731-4feb-9409-76df298d7874",
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
              "id": "95909729-8505-4fc3-b0aa-0dcda22e71b1"
            }
          ]
        },
        {
          "id": "74d6475d-19ca-4e80-81df-e7c832823e79",
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
              "id": "40b054e3-8a52-47ed-8919-097e03437dff"
            }
          ]
        },
        {
          "id": "e700f9a7-15ed-48f5-ab76-efef080901ab",
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
              "id": "97a49b4e-5175-462c-b822-1551cc752ebf"
            }
          ]
        },
        {
          "id": "23b2d180-f739-4fac-b748-8461724abb88",
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
              "id": "4ca92680-eac4-4746-8c4e-28b90c9c986a"
            }
          ]
        },
        {
          "id": "6b6681d3-6c67-4f39-8ddf-7ac91e42051d",
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
              "id": "67a35423-2f4a-4ef1-bc08-73cbf2a7c785"
            }
          ]
        },
        {
          "id": "f796a6bb-cf84-47c1-abdc-26e23dac748c",
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
              "id": "defb9c2d-fc80-450b-a8c1-0522f14ea2a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Token",
      "item": [
        {
          "id": "45b950e6-5154-43f6-9db1-6e049aec58db",
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
              "id": "da9c2ce5-3606-4981-8ef7-2f5d6320ca8d"
            }
          ]
        },
        {
          "id": "627dedca-037a-4fec-8db9-24aac2e2005b",
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
              "id": "4e82acc7-403e-4088-a2c3-a707817f8379"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "b8df76d1-5bec-49e2-b8d6-29fcf6670927",
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
              "id": "339687aa-94de-4fb3-ae24-df79d115dfe6"
            }
          ]
        },
        {
          "id": "be84201a-415e-4fa3-8bae-d81a6a20fac0",
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
              "id": "f4093882-36c5-458a-bbc6-1a58afd96d3a"
            }
          ]
        }
      ]
    },
    {
      "name": "Etp",
      "item": [
        {
          "id": "fb9b5a01-a2c4-438b-8685-97de25c22d20",
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
              "id": "d2b8400e-5081-4ca8-bb0c-8c4357392405"
            }
          ]
        },
        {
          "id": "1bfa7724-24a5-40ce-a14f-bfbcb0e96f9c",
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
              "id": "188f4193-2d5f-482e-96d5-7ca0629c53d2"
            }
          ]
        },
        {
          "id": "cbceca59-7fd0-40ae-a523-ca41f2e4ed08",
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
              "id": "18cee38b-6674-46e1-808d-81b690fc80a6"
            }
          ]
        },
        {
          "id": "18d0b4c5-8608-4f42-898e-3ba39165a678",
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
              "id": "d32c515b-afec-4d63-81c7-78109aa28924"
            }
          ]
        },
        {
          "id": "9b6b4e6e-8bc8-45b8-b13b-05ea68e4defc",
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
              "id": "b79a20cd-ed07-4994-acea-ae15f87cb9e4"
            }
          ]
        },
        {
          "id": "83d9c3c1-a205-4c1f-827e-5cdbbe382e12",
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
              "id": "9e972d09-d326-42bc-a47b-ed199906f6a8"
            }
          ]
        },
        {
          "id": "d1dce79f-94fa-4e61-b0e8-b22f7c8d6006",
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
              "id": "ea5f38be-cd3b-4bde-9e93-2deeecb53896"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "cabeed6c-33e3-4344-b3fd-6b45338e5fef",
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
              "id": "5dc4b217-65f2-4db5-93f0-80de521e697b"
            }
          ]
        },
        {
          "id": "b46222f3-8a20-44b0-bb1b-5cf93cf88b60",
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
              "id": "76f13913-fe1a-4b44-baa4-71d1b0ef3f11"
            }
          ]
        },
        {
          "id": "e86d48b1-1e65-4d97-a6dd-a07eb22afa11",
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
              "id": "2216cf30-c1de-4e59-9a8f-031162a103af"
            }
          ]
        },
        {
          "id": "60663f88-f1cb-4161-ae01-2522ab6ab6aa",
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
              "id": "2b22f02e-4f91-446a-aff6-1920a0e9f5e1"
            }
          ]
        },
        {
          "id": "f806106a-7606-4ba6-a475-5bfa2b584acb",
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
              "id": "58cb2de0-0035-4bd1-82d1-f68929394f06"
            }
          ]
        },
        {
          "id": "f4372ffc-b95c-492b-9bfc-25e867edcdf2",
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
              "id": "91828eb9-58fa-4589-a593-db1c18fc1da4"
            }
          ]
        },
        {
          "id": "2dc4df77-dd2d-403a-97a9-6bcbea4ec3b8",
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
              "id": "0665838d-a0c9-4e32-8e0c-a6ade9ca5edb"
            }
          ]
        },
        {
          "id": "49bea37b-0db7-4f36-8766-d56f9d4b1557",
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
              "id": "3492e19f-e178-49ab-ba65-3e2c1f5feff3"
            }
          ]
        },
        {
          "id": "cd31b04f-7b69-4a2d-8000-4cf39d44d7bf",
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
              "id": "27c0ca1a-33f9-46d9-908d-d7af9ef812cf"
            }
          ]
        },
        {
          "id": "9d487b9f-a530-4bcd-9840-aa577b117c20",
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
              "id": "a946fe4e-36ac-419e-b4f1-27f01088ae17"
            }
          ]
        },
        {
          "id": "cd37a4a6-3d1e-4b10-a0dc-d4db976832be",
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
              "id": "60688ee8-cd42-413e-9809-7965d905185f"
            }
          ]
        },
        {
          "id": "bd23d15a-a629-41aa-b07d-4d08305954f5",
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
              "id": "8ea5409d-a730-4855-9a09-8630b211efbb"
            }
          ]
        },
        {
          "id": "657f5a4f-eb34-4e70-af89-bc8bd8663cc9",
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
              "id": "a86b1c8b-ea16-425c-be28-276162344ded"
            }
          ]
        },
        {
          "id": "607f5cd2-d3bd-4640-b8b2-1c971068bf99",
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
              "id": "0053c4b7-cc14-4488-886b-889b0fcb32cc"
            }
          ]
        },
        {
          "id": "32a4180a-7fff-4809-8cab-6e05e02cb6d1",
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
              "id": "036fa03d-0d0e-4e1c-8dbe-48fb3e82a617"
            }
          ]
        },
        {
          "id": "c2168886-9bc1-4381-8768-906d5974afb5",
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
              "id": "293876a4-5f6e-4636-967b-518a96a55c86"
            }
          ]
        },
        {
          "id": "671d7ad9-3ab6-48e6-a021-00e6874d616c",
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
              "id": "4a70e0a4-6fcc-4762-9231-37cc0277bab9"
            }
          ]
        },
        {
          "id": "5f46f34e-c7c8-4f9e-a3df-1e557f3335e1",
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
              "id": "c0631348-0fa3-4d5f-9ffe-370ad6083e31"
            }
          ]
        },
        {
          "id": "ee15302d-8cab-4265-95d3-8be8ffe6a2dc",
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
              "id": "676d671b-ff03-42e8-87c2-a2ce13199dde"
            }
          ]
        },
        {
          "id": "233dbbb4-5f4f-4724-afaf-6c06b541e91c",
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
              "id": "e9ce1b2b-969f-4230-983c-ed8838cd0b7e"
            }
          ]
        },
        {
          "id": "f51e7a63-a5f4-4509-8c44-c744c389d2c6",
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
              "id": "dcf13617-3eda-4ac0-b123-eb2e8a5387a2"
            }
          ]
        },
        {
          "id": "24a5d140-8337-464f-a762-805bc865c469",
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
              "id": "640ab6c6-ba5d-4590-963a-12b361b78e4f"
            }
          ]
        },
        {
          "id": "bfc655cc-a5ee-4dab-a7a7-e0703e286dc9",
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
              "id": "0c1ad0fe-e134-4911-9b8e-439fe0ca0852"
            }
          ]
        },
        {
          "id": "9bf9ed9d-16ac-463c-ad7e-bb1ae1ce3715",
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
              "id": "fc446761-93d4-40a3-9a7f-d36f75dd564f"
            }
          ]
        },
        {
          "id": "e48865dd-7bd6-4e7f-bce2-ccae58f65e07",
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
              "id": "7119dab0-a6ef-43ed-a8ef-22a1cf537ad5"
            }
          ]
        },
        {
          "id": "16678902-56cb-4f87-bdf3-d1df880eb680",
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
              "id": "e404e1cf-fb23-4b8c-9e11-cb819c02d486"
            }
          ]
        },
        {
          "id": "4fd36bf2-2e50-4c69-8623-b511e1840a5a",
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
              "id": "46fcf0da-3e30-4826-b8c3-1ed95ab7c7a1"
            }
          ]
        },
        {
          "id": "dc97c307-0fcf-4ddc-97d6-dfe1e2eef9ac",
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
              "id": "f3ecb007-5454-412c-93ca-41a2ef00c60b"
            }
          ]
        },
        {
          "id": "9709f6e7-7d6e-433f-b507-5ab4cd3b98b3",
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
              "id": "d546a1b2-73ba-481e-ba04-b9e777ae124f"
            }
          ]
        },
        {
          "id": "73754567-58af-49c7-a1ca-c9d6c7fbefb9",
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
              "id": "fe4d9238-8abe-46d4-ba91-d29ae1307fcb"
            }
          ]
        },
        {
          "id": "88c52a54-c668-4755-b6a1-4fa0856333f7",
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
              "id": "d12465ed-d335-4d60-95d2-2bc3a6abdf45"
            }
          ]
        },
        {
          "id": "94d56cce-449a-4ad8-9335-d281eebb3e6f",
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
              "id": "4f320069-6780-4212-818b-b66708dacb80"
            }
          ]
        },
        {
          "id": "daf91093-1a5a-4799-930d-521fbb2ffeb3",
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
              "id": "9cec8f9b-e752-405c-958c-b7e5aefd595a"
            }
          ]
        },
        {
          "id": "33f12920-b6e9-4695-b5a3-77896fe0c678",
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
              "id": "8389426c-d930-472a-a6ab-80d7b28cd791"
            }
          ]
        },
        {
          "id": "aa8fa0ba-b20d-42f3-a602-dcbbe38c5729",
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
              "id": "2bd1274b-bc8c-4493-a82e-2efe28e1b0d4"
            }
          ]
        },
        {
          "id": "375d62c8-66be-4c13-a374-3b1714045eaa",
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
              "id": "0963ba70-8fbc-4a9a-8136-64d2de018836"
            }
          ]
        },
        {
          "id": "fa71da13-a075-47df-aaf5-7f85c6a4c01d",
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
              "id": "fb70cf9e-7636-479a-ba28-5f67cdfbb2b7"
            }
          ]
        },
        {
          "id": "1805dffc-8ea8-43e2-a1f6-18c083a02fba",
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
              "id": "c1d77079-f432-4276-a01c-1ba77aed1ff6"
            }
          ]
        },
        {
          "id": "394fe2d4-14ca-4713-be08-d15e736ced80",
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
              "id": "2d66164e-1ccf-4c27-b4d2-1008b3b7c861"
            }
          ]
        },
        {
          "id": "8726fcbb-0120-4cce-965c-88b9085b7ce1",
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
              "id": "13f137ea-5c92-4ff6-b9b7-a525ff2b3bdd"
            }
          ]
        },
        {
          "id": "bd1b4bf4-c54b-4991-9a87-8a87b4c08b6f",
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
              "id": "04aec5cd-dbf2-4f44-b351-3b389eacc248"
            }
          ]
        },
        {
          "id": "2c4b8de4-39ba-4f4b-8bc0-0c7c47b931de",
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
              "id": "fb992734-14f5-4abe-8507-1b2aca8ab322"
            }
          ]
        },
        {
          "id": "e70229e3-7bcb-44a3-a386-52d45601e517",
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
              "id": "1a336021-6413-450f-bf4b-746d48a5710d"
            }
          ]
        },
        {
          "id": "ad7c9664-7b39-4b36-af9f-b4981bcc1db8",
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
              "id": "d3e13810-c053-4058-804d-b3de974ad39f"
            }
          ]
        },
        {
          "id": "8f64b4df-9176-48b2-aa65-bf1d631c2c44",
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
              "id": "79893509-a5f4-4b34-9da8-ddb6a94b505e"
            }
          ]
        },
        {
          "id": "a352f810-6002-4585-8de9-237536adaecd",
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
              "id": "ccee413b-d86c-410c-98a9-90a9e1f8dbe1"
            }
          ]
        },
        {
          "id": "f9b82e05-8fc0-4b26-bf99-8558ba32fdda",
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
              "id": "c88f7ef4-d5ed-4e6e-85da-f8f619dd2495"
            }
          ]
        },
        {
          "id": "11d5b234-f159-457a-a9d3-12749d7b4232",
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
              "id": "90496859-07ca-416a-8330-3b5bbcd02e18"
            }
          ]
        },
        {
          "id": "d7854084-ad71-483b-b914-5eefed2b4d5a",
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
              "id": "2efb9546-6b0b-4f5e-9e1f-ad3ec799da99"
            }
          ]
        },
        {
          "id": "fc83d672-f66b-46bc-9aed-4d1eb2ac232f",
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
              "id": "888242ce-3e07-42e4-b9de-5a4f68207239"
            }
          ]
        },
        {
          "id": "1b4f715c-0021-4cea-90ba-0c913ddb42c2",
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
              "id": "1e180c81-0291-4344-8b55-c9688d3e93e8"
            }
          ]
        },
        {
          "id": "abf5cdc8-b6e2-4496-965b-3a27852d0659",
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
              "id": "534c40b1-40b8-47ef-8a65-7bfeb87038dd"
            }
          ]
        },
        {
          "id": "70e201dd-5f47-4f34-aa01-d594e6ae240a",
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
              "id": "a2d7273c-8828-481f-9f15-1ed9157da291"
            }
          ]
        },
        {
          "id": "75b5da7c-72e6-49da-9539-f6f8953e8b9c",
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
              "id": "470f3146-f275-4563-b60a-50e1070d345b"
            }
          ]
        },
        {
          "id": "328b6282-d78b-427e-a645-1285245e71ec",
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
              "id": "9d50ceaf-e0a9-4343-b36a-68370e8bfdc8"
            }
          ]
        },
        {
          "id": "c1219fd4-1024-48fb-8a0e-48b4a3232f77",
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
              "id": "4c2ae459-531c-41da-9412-dae96ca2032d"
            }
          ]
        },
        {
          "id": "2bcf1b79-6eda-4abb-9062-8b386b437d46",
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
              "id": "f1bee4c4-54b6-4cd4-867f-42cfa1a5c0f2"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "79c0801a-b5e6-47b2-aa16-a693281269be",
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
              "id": "cab3d4bf-42e7-45e5-a3c6-11fd23a24d89"
            }
          ]
        }
      ]
    },
    {
      "name": "Deliveryformat",
      "item": [
        {
          "id": "0efb9b29-72b9-4567-9e9c-55e16b7108e3",
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
              "id": "40d90b98-e2e3-4c05-aa74-51fdb1798fc0"
            }
          ]
        }
      ]
    },
    {
      "name": "Audience",
      "item": [
        {
          "id": "e700032c-1636-4e13-a044-61f2f25f5bcb",
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
              "id": "9fc69282-3a80-434e-a3de-96f4aeef4cb0"
            }
          ]
        }
      ]
    },
    {
      "name": "Clients",
      "item": [
        {
          "id": "f043df39-fcbe-4f5d-a2c2-50b96f5b47c9",
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
              "id": "77b4775a-82fb-4028-b6b5-14611d29aac2"
            }
          ]
        }
      ]
    },
    {
      "name": "Feo",
      "item": [
        {
          "id": "a10fb86b-09ba-4218-b367-1152e8036530",
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
              "id": "ced7a391-a097-4282-8957-8fb67d3d1035"
            }
          ]
        }
      ]
    },
    {
      "name": "Imaging",
      "item": [
        {
          "id": "a3b0f0df-6ab0-4dbc-85dc-92ff27b4bdec",
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
              "id": "04587afc-383c-4305-90f3-b46048f8a630"
            }
          ]
        },
        {
          "id": "6f1e9b98-8611-4424-8d17-338eaffcc065",
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
              "id": "b384b2e7-0a6e-4bc5-a42f-379444f1f56a"
            }
          ]
        },
        {
          "id": "74bf7141-6fed-453b-8623-6ac9fd12ff14",
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
              "id": "181198fc-add5-4691-9841-1efd5b72b1b5"
            }
          ]
        },
        {
          "id": "5cd579be-cee1-4729-a939-b8c4d0776757",
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
              "id": "6fea32d3-1548-4506-b628-cf953e0aace1"
            }
          ]
        },
        {
          "id": "1796310f-2372-48f2-932a-7669d063524d",
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
              "id": "6cd94ca3-3dbd-4897-83e2-876378bfadcf"
            }
          ]
        },
        {
          "id": "57c387ae-e6cb-427d-8863-1d364989aa4f",
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
              "id": "6d298c63-3e40-4dbc-94de-a663d1e022e4"
            }
          ]
        },
        {
          "id": "18774e8e-1a02-4ff9-af51-7c6d23c337fc",
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
              "id": "88447e32-5026-4640-bc29-166db5073396"
            }
          ]
        },
        {
          "id": "6c405f6a-a396-4225-a277-9c37adf700a8",
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
              "id": "edc12ec8-b17f-46b3-8123-7f7473d542c2"
            }
          ]
        },
        {
          "id": "59d39fa7-a75c-4e34-8f1c-5c085a29a25a",
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
              "id": "823498a6-eca2-4f7b-a8ba-25612f8ec48f"
            }
          ]
        },
        {
          "id": "59d239d8-76fa-4e09-8fa7-9c29adbe31b3",
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
              "id": "bb6129a3-4654-43bb-9aeb-fdd662aeb97d"
            }
          ]
        },
        {
          "id": "946eeb32-4f7a-4dc8-a6e3-d897a9ca5d08",
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
              "id": "81f373f6-dd0e-436b-9e8c-a895b5e038c5"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "80deb2a1-9337-4ef9-bf70-2885bf47d6b1",
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
              "id": "a44c67cd-d463-421d-a0b6-852e977d8a64"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "532c23be-3048-404c-aa2c-736cdabe3944",
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
              "id": "5a000026-2912-4eca-9f55-386ec3a52b9d"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoicing",
      "item": [
        {
          "id": "7a88a0f8-9ba4-4484-bbe3-2173fd422383",
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
              "id": "a4e9f786-b94f-44d4-b408-72138b6f5dcf"
            }
          ]
        },
        {
          "id": "a563dc47-8162-4944-bf3e-c09d14d490ad",
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
              "id": "48042aa2-9795-4ee8-9537-fa82b014cbd4"
            }
          ]
        },
        {
          "id": "319c469a-3394-4a76-bf66-e929408c21fd",
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
              "id": "a1f50163-e05f-48e2-809d-ffb10c388821"
            }
          ]
        },
        {
          "id": "b278eba5-0c01-4b04-9946-45f6a2c8f90f",
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
              "id": "20b80170-08b2-4a9b-b8e8-94ac8d091a6a"
            }
          ]
        },
        {
          "id": "72539208-c3cd-4ccd-8206-16499d4d711c",
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
              "id": "7d25081b-6312-4a18-ac4b-ddb52622f149"
            }
          ]
        },
        {
          "id": "162d6a8a-d4bf-4204-bb88-3d5d11cb6893",
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
              "id": "a4c90af1-bd0e-4e16-adda-051e0e6f2fcd"
            }
          ]
        },
        {
          "id": "d021db87-527a-463f-be49-809df43efae5",
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
              "id": "ec572990-4ca5-4668-9fd1-0a3d4bce18b8"
            }
          ]
        },
        {
          "id": "332b1c2d-ca85-42c9-8905-d0e8cb842d66",
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
              "id": "6e30f419-42aa-45af-b972-38176513c2e2"
            }
          ]
        },
        {
          "id": "e26f7865-d11d-4e57-a36e-6dd65bd72089",
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
              "id": "359f3d3d-c95c-498a-a4aa-3ae0e252cd09"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "fc7748cf-aa8d-4c2c-b77b-b89fdf2725be",
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
              "id": "b9b8512d-7055-4fe5-98f0-386f20f72d2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Configurations",
      "item": [
        {
          "id": "e7b3c8b4-f1f5-43fb-a40a-a17f206d17c9",
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
              "id": "84a6293c-cdb9-4ed0-89b5-d99a10a7719a"
            }
          ]
        },
        {
          "id": "efc0db5c-54f4-4d0f-8cf1-57f3bbbce0b5",
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
              "id": "decb6dc9-f4bd-4c28-9ba4-3882b0c5159a"
            }
          ]
        },
        {
          "id": "0b07b661-0d6f-49d4-a1d2-7bad0ab7c094",
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
              "id": "734a24db-4b90-43f0-81eb-3dc87cf5e640"
            }
          ]
        },
        {
          "id": "330a41ca-e409-4f76-8d60-a7e9ea0789df",
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
              "id": "85df8ac7-8788-4520-93d0-00f2e7b4f940"
            }
          ]
        },
        {
          "id": "e1990139-3b3f-4a72-b326-5530f3b2e091",
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
              "id": "43cad46e-1a70-43fe-989a-bb7a9efc1d94"
            }
          ]
        },
        {
          "id": "33b7663b-3cc9-40ef-acda-91e745face87",
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
              "id": "28e8c2ae-d7f8-4489-9f4e-95f062699b2f"
            }
          ]
        },
        {
          "id": "ac160998-6064-4363-9131-1d495c24bfcb",
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
              "id": "5e8a85ce-4053-436f-a05d-691417c29803"
            }
          ]
        },
        {
          "id": "5c0d4041-1705-44fb-9889-e80990a7f3eb",
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
              "id": "19097170-0d40-4840-a22f-e6e3d93410ad"
            }
          ]
        },
        {
          "id": "d2ddba0f-adab-4b3a-875c-e4648155b67a",
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
              "id": "5711fd6d-42bf-4e67-941a-8ec7f00b1132"
            }
          ]
        },
        {
          "id": "9de311cb-af45-456f-a1f1-720feaef6b94",
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
              "id": "f5c61d01-8b23-4add-93b3-185cfb519d5f"
            }
          ]
        },
        {
          "id": "bf141518-2bd1-49ec-b89e-c2941e1228b0",
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
              "id": "ec9f174c-6f6a-4c73-b47b-3d68dba76908"
            }
          ]
        },
        {
          "id": "68281bc1-2c2c-4b9e-b99d-0f1311771f49",
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
              "id": "1588266a-dd7c-4861-93d0-d93e86166d02"
            }
          ]
        },
        {
          "id": "2996231a-fc53-41bc-ae35-0bc0dda6bca3",
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
              "id": "81c0ac6c-775e-4ca7-acd6-e948e74f936e"
            }
          ]
        },
        {
          "id": "8c1bf89e-fc9d-40d7-90e8-8c00d191e44e",
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
              "id": "e878acdc-4613-4529-8655-425fd3ff73cf"
            }
          ]
        },
        {
          "id": "8ce338e0-352e-4e9e-9912-5e1f68a0296f",
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
              "id": "c5636edc-9ddc-4d1b-830b-42afc6968baa"
            }
          ]
        },
        {
          "id": "3314e2e2-8bc3-468e-96f2-b85d18977e14",
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
              "id": "2264600b-827f-4cf6-b4a4-34eb422919b5"
            }
          ]
        },
        {
          "id": "af156ba9-616d-479b-8e24-c59982707b89",
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
              "id": "29ecb0ca-2228-44a4-a147-695d9c66f838"
            }
          ]
        },
        {
          "id": "663861f0-44fc-4d4f-ac77-bbb356a79153",
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
              "id": "e2fbf6bc-35fd-4c2b-90ba-2b57ef57e437"
            }
          ]
        },
        {
          "id": "f7d57980-bfe1-41db-81ce-9bc40a13b73e",
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
              "id": "3765a339-d31d-4360-b857-aeb72bff48fa"
            }
          ]
        },
        {
          "id": "de7b4562-219d-4c1d-bb3d-506f556d0ee1",
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
              "id": "23ec5045-c895-4767-a3d4-f827499f7139"
            }
          ]
        },
        {
          "id": "7e3b18b7-f8f2-46a6-bf5d-6d1795b2c5d9",
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
              "id": "7d8fab60-0cf3-4a63-81cc-0f0582e0715c"
            }
          ]
        },
        {
          "id": "4debf960-bcfc-4928-b232-c97e2e3be532",
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
              "id": "89d8f842-e8e3-4863-9ac7-4c4a257d9b36"
            }
          ]
        },
        {
          "id": "38a064d3-1aa2-437b-8481-1909d12ee80a",
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
              "id": "01931de7-14df-44e5-9340-6974a21600e9"
            }
          ]
        },
        {
          "id": "e26667ab-eb30-4cd6-b490-05c2c52a1ae2",
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
              "id": "f64a0171-3654-4c7f-a80d-add74e1b1914"
            }
          ]
        }
      ]
    },
    {
      "name": "Service",
      "item": [
        {
          "id": "eec7d467-fad5-4a35-a3c4-9d816411fb2d",
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
              "id": "c898f8dc-00e3-4469-a48a-30f59148fd12"
            }
          ]
        },
        {
          "id": "0b84399e-928b-467a-81aa-9bb185546c33",
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
              "id": "9720e84b-498a-46e6-a847-a468985dde20"
            }
          ]
        },
        {
          "id": "73487eef-5494-4c85-b770-9aff11a39dec",
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
              "id": "653941b9-3569-466a-8acb-5a7ae7f65503"
            }
          ]
        },
        {
          "id": "ec51f45d-732b-402b-bfff-0cd1717f3a00",
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
              "id": "0ac0db11-a35c-439b-a0b6-8e06ebdef4be"
            }
          ]
        }
      ]
    },
    {
      "name": "Services",
      "item": [
        {
          "id": "d06df258-2f0d-4edb-a4a4-d6dd973c59bf",
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
              "id": "0fd77df1-f2d4-4b50-8783-2b7586eb0881"
            }
          ]
        }
      ]
    },
    {
      "name": "Lds",
      "item": [
        {
          "id": "ce68f67a-e051-4937-b348-7b2cca910fcb",
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
              "id": "95c47bc4-10cf-44ae-ac91-b75f02f3857d"
            }
          ]
        },
        {
          "id": "3d58d81b-8038-4e0f-9cc0-4c72b54c828d",
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
              "id": "bba1ceb9-1062-45b4-8473-8ff4cbbdb122"
            }
          ]
        },
        {
          "id": "27305856-4fc7-4056-bfc1-cae8e2964079",
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
              "id": "139d4f58-36f8-4655-adcf-a3b783bae5a5"
            }
          ]
        },
        {
          "id": "eafc2e86-9e03-46d2-a2f1-87ccb732d872",
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
              "id": "5e16be27-406f-4a66-b363-6f134753d918"
            }
          ]
        }
      ]
    },
    {
      "name": "Redelivery",
      "item": [
        {
          "id": "abaf1d19-6cc1-4476-8011-7499a1ab7be7",
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
              "id": "fc309113-e104-4258-9532-01c4dc18846e"
            }
          ]
        }
      ]
    },
    {
      "name": "Key",
      "item": [
        {
          "id": "93942e91-a564-4de6-8949-3b31bcc2cf1d",
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
              "id": "15c62875-9ce3-4f91-8ed4-71f2179af3f4"
            }
          ]
        }
      ]
    },
    {
      "name": "Media",
      "item": [
        {
          "id": "348b4252-2e0b-42e6-a5b1-8396048704f8",
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
              "id": "e753720c-51d2-4d37-a59e-22dd80a1291f"
            }
          ]
        },
        {
          "id": "c38d64ea-acce-4b69-9a7e-a5afc0acf55b",
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
              "id": "7c17a0ad-6422-49bb-b5d5-eca4b6044d09"
            }
          ]
        },
        {
          "id": "9356ea9e-eeb5-4e76-9edc-fe2bc66898f1",
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
              "id": "f240b89a-369d-4cd0-bbd3-2ecf88665c71"
            }
          ]
        },
        {
          "id": "93adc2f2-a6af-4353-9c00-b842e6798287",
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
              "id": "2d21d0db-9070-42cf-87f6-e991a0c2e97b"
            }
          ]
        },
        {
          "id": "97e3635c-0535-4426-ac67-d51ca147da96",
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
              "id": "6bc1f396-f68d-43fb-a8ad-dc13816614cb"
            }
          ]
        },
        {
          "id": "a977fea3-6900-4c60-94e9-a62caf9b9d7f",
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
              "id": "828eb492-da8c-4a32-8de7-3b7e163fb09a"
            }
          ]
        },
        {
          "id": "fd6cfd02-2885-4c1f-bf23-1953f1094cd0",
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
              "id": "d8d9dcc3-ce2a-496c-a0d4-51201561dbd8"
            }
          ]
        },
        {
          "id": "3ab13455-88f7-46d1-b119-80f85578708c",
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
              "id": "907e50c2-311f-41c5-aff8-0f2f687309e8"
            }
          ]
        },
        {
          "id": "7fe610c6-3b4e-4ca3-ba04-3362096992f2",
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
              "id": "c38007d6-dc69-4c3b-98ca-47624f51d511"
            }
          ]
        }
      ]
    },
    {
      "name": "Filterparams",
      "item": [
        {
          "id": "18226c86-4dd6-4651-81a2-df131d0f43ec",
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
              "id": "d8cb2c9d-1ac4-42a6-b2ae-71bbe1449923"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "d241b2d4-b4ec-4510-a32f-4ec22ac4faab",
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
              "id": "2ee0a2ca-bdcd-42c7-b532-e091dcdfa8b5"
            }
          ]
        },
        {
          "id": "dd3f68bd-548e-453f-998f-63b5162a1c50",
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
              "id": "caa6aff3-6715-4811-976f-89efb3396da7"
            }
          ]
        },
        {
          "id": "5b80660b-45e7-4ae3-8241-647d9d258cd4",
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
              "id": "2b7103b7-2ca5-4e87-a51d-a0db6e958055"
            }
          ]
        },
        {
          "id": "8fa16d11-b313-4d53-96a0-271c47fb696f",
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
              "id": "86acab0f-7b71-4d66-bf5b-0f6493940e93"
            }
          ]
        },
        {
          "id": "0ccc3323-3e60-4e64-9ccc-3569d8ffda9b",
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
              "id": "4dd7f1ed-43df-4d79-b7fd-259427c2970f"
            }
          ]
        },
        {
          "id": "98a95302-bf32-49c3-ae6b-ada453f45ccb",
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
              "id": "17783ac1-d891-4f29-b21f-0bd5b1149a49"
            }
          ]
        },
        {
          "id": "a8b83eea-52a3-4b79-9ddf-ffdf4a19703e",
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
              "id": "b8784dab-6b78-4bc6-a997-b6229307a061"
            }
          ]
        },
        {
          "id": "eb69710a-c68c-424e-9e7f-293388a0c287",
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
              "id": "bfc668ab-11f1-4a8d-bc1a-dd3748dba453"
            }
          ]
        },
        {
          "id": "5398cc7c-df26-477f-b377-42612ef6683f",
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
              "id": "d67f01ca-a98a-4dd4-8f71-1f94fb91b30b"
            }
          ]
        },
        {
          "id": "193d9b4b-e9fc-4e28-91e2-31bbd4ecdc93",
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
              "id": "1e985771-c14b-4469-8dbc-b34d5968fa50"
            }
          ]
        },
        {
          "id": "75c545cf-759b-4313-9e08-d92384d303c9",
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
              "id": "c9c3c7c0-bb81-4a9f-9235-35b03487874e"
            }
          ]
        },
        {
          "id": "65e7085e-5532-4a1c-b3e0-7bd26695183e",
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
              "id": "079b93a9-8592-4d5a-b827-9db4cd4d8097"
            }
          ]
        }
      ]
    },
    {
      "name": "All",
      "item": [
        {
          "id": "2eeecac6-4303-4de0-9b06-e47e1b271090",
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
              "id": "b8265e81-ecee-4c46-9241-7d0bf44fe358"
            }
          ]
        }
      ]
    },
    {
      "name": "Prolexic",
      "item": [
        {
          "id": "5b1dfa0a-1e63-4abf-b456-e8b79eb090a1",
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
              "id": "e1375489-364f-481e-9937-92c54f096fba"
            }
          ]
        },
        {
          "id": "e802c19a-b218-4b52-b1e5-858dfb8d8fee",
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
              "id": "22688896-1080-41be-9673-7ef5ba5ae3d0"
            }
          ]
        },
        {
          "id": "b5a36a03-541f-430c-bfe7-77505e3dd422",
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
              "id": "619de6d6-c463-451e-a8a8-99dc5c2fd98d"
            }
          ]
        },
        {
          "id": "e04f1963-3e98-4e0a-8635-03c67b0b106f",
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
              "id": "e16e795b-6069-48ba-a263-ca3d1caac8d9"
            }
          ]
        },
        {
          "id": "260dd609-8ef3-4e61-bd1c-308a56fd48fb",
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
              "id": "eb0cf333-c0d4-4eeb-82fd-8331d4db4468"
            }
          ]
        }
      ]
    },
    {
      "name": "Type",
      "item": [
        {
          "id": "1631ae41-f194-4d8f-8615-28533802a86e",
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
              "id": "bbb3f880-d6e8-42ff-8ba3-2fcb98b3347c"
            }
          ]
        }
      ]
    },
    {
      "name": "Papi",
      "item": [
        {
          "id": "88ad6b64-024d-40ef-b977-b63c925265b6",
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
              "id": "e7860580-9571-4efe-832a-9510d75e3994"
            }
          ]
        }
      ]
    }
  ]
}