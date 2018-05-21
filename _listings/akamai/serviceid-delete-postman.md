{
  "info": {
    "name": "Akamai API Remove a Configuration",
    "_postman_id": "939ed16a-948f-4b99-8aa1-608185d4aa04",
    "description": "Remove a Configuration",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "57608c08-41c3-4941-89f0-9a599d6b55ec",
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
              "id": "624e3cd1-82c2-4cb5-bdb7-3a990775275b"
            }
          ]
        },
        {
          "id": "13c93699-8807-481b-9f6c-b0c5e65dec8b",
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
              "id": "5d694086-bc80-4942-9e81-6f24eba58793"
            }
          ]
        },
        {
          "id": "516c9264-5a5b-4e1a-99bf-2b386e4e3ba9",
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
              "id": "1c8e92aa-dda4-41fa-9e35-d12c8af6e96c"
            }
          ]
        },
        {
          "id": "2b1bf9b6-00ce-4709-9bd6-2ed2071028be",
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
              "id": "17690613-01eb-4b51-a1b8-5643b0a43c84"
            }
          ]
        },
        {
          "id": "23549bdc-af47-47c0-9409-a103ba498d95",
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
              "id": "51269a0f-dfcd-4637-8d89-f2e6a719c4b4"
            }
          ]
        },
        {
          "id": "15334ba1-4fd2-4011-b033-25e74b9b80e6",
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
              "id": "40cb1e0d-bf04-4e61-8bec-d15ca7a993e9"
            }
          ]
        },
        {
          "id": "e9f9ef20-6837-4024-b35f-dc5c9718c072",
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
              "id": "32809ed9-d5fb-44e9-86b3-5379b663495d"
            }
          ]
        },
        {
          "id": "516b5ce0-c351-4563-af6f-f238ffe4ba18",
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
              "id": "265aa6a1-14be-4e0e-9e71-ebfd9058625b"
            }
          ]
        },
        {
          "id": "0988b47b-19e9-402b-be61-a2a1222fc801",
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
              "id": "96e1be03-d805-492e-aae5-28f3d1fbcad9"
            }
          ]
        },
        {
          "id": "6f4a06a6-77e2-46e3-9180-b8b4c0e16959",
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
              "id": "c00b9a92-628d-4591-9389-056ca51fa5d7"
            }
          ]
        },
        {
          "id": "db22ddf3-34d2-4f04-ad62-0c1f9f270891",
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
              "id": "bb0ed6b8-bc20-4740-8c39-423769bc0f6f"
            }
          ]
        },
        {
          "id": "54b26ecc-0fe9-400b-8dc1-3c2995b7503f",
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
              "id": "2a786679-0f64-4a4a-b013-6fbad4fdd380"
            }
          ]
        },
        {
          "id": "4c6f2728-05c1-491f-b508-2d83a4acafb3",
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
              "id": "52cc708f-cac0-489f-b87c-0e3ecfba3431"
            }
          ]
        },
        {
          "id": "574b1207-65dc-4ac1-98c9-82c61354facb",
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
              "id": "2553aa47-6be5-4531-9ca5-928c905a50db"
            }
          ]
        },
        {
          "id": "aba157be-9a72-4e65-a067-38f34c72bd69",
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
              "id": "f37a0e23-3dc9-4cb2-8646-0e8037e4887b"
            }
          ]
        },
        {
          "id": "1055fa31-925e-4e16-acf3-f7685979ee05",
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
              "id": "6d02dff8-f80f-4ea0-8262-664e70b21ed3"
            }
          ]
        },
        {
          "id": "e8334d64-50ac-4777-b3f9-5dc8e17760f9",
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
              "id": "385bac37-a0fd-496b-a3ef-0a2de7f8bade"
            }
          ]
        },
        {
          "id": "bd1b3d4f-7473-4930-bc4d-e32dab994f69",
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
              "id": "b16ac7b2-592b-4006-bf87-dcddc4165cc6"
            }
          ]
        },
        {
          "id": "152371ae-14ff-457c-86cb-295c8089cafc",
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
              "id": "1bf265ff-e6d8-4f55-a1d9-035ce26ccc31"
            }
          ]
        },
        {
          "id": "b64222fb-68b7-4a72-8ad2-1fb77c5350c5",
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
              "id": "1c8030a7-b8db-4f5f-a08f-77222d784908"
            }
          ]
        },
        {
          "id": "b3176a88-8434-4ac1-9947-85fba517ec69",
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
              "id": "86b313fa-2a06-4a14-9629-7bd386b999b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "69480ed5-acc5-4f4c-84ad-28a8cad9a1cf",
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
              "id": "18255869-e7e4-4a27-ab09-c73ab446ef46"
            }
          ]
        },
        {
          "id": "06aaca2e-0e47-4276-8118-cfef86ba4aed",
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
              "id": "b31be308-b043-4cee-bfbb-375b6c6cee57"
            }
          ]
        },
        {
          "id": "d4fd2d05-3800-4923-bf20-2a7186ecf924",
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
              "id": "b1f7b4b3-79ee-48eb-970d-dc9081b908fb"
            }
          ]
        },
        {
          "id": "5c7f9f9b-925f-4aee-bc7f-b8da353e0919",
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
              "id": "b984563c-ce60-45d3-a500-deaa6add6d8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "dbafcb1a-c75a-45e4-94e7-5f5ba75a95fd",
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
              "id": "5aa76ff5-ffc6-45fb-b32f-d784cdec795a"
            }
          ]
        },
        {
          "id": "747ee1df-b46b-4bab-b77c-b7ceba77e04d",
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
              "id": "123a3de5-5078-4243-a1a3-96cabb4a0057"
            }
          ]
        },
        {
          "id": "f007ade0-6439-44bb-99f8-1fdafbc09f37",
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
              "id": "fac12ba6-6a08-4468-a919-f18de6d3dda4"
            }
          ]
        },
        {
          "id": "840f0a01-eff7-4601-b11f-d2916305e0c2",
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
              "id": "fb1cdcf8-b6be-4fb7-9db1-318bd80160d8"
            }
          ]
        },
        {
          "id": "99d5d5db-6111-415d-bddc-867e93745f18",
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
              "id": "66a1d111-8521-4640-8127-14d328038ff7"
            }
          ]
        },
        {
          "id": "60227da9-d225-4055-aeb6-c4530b03da75",
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
              "id": "ff83c7d9-7ccf-48fa-a05d-8e59b0ce93d7"
            }
          ]
        },
        {
          "id": "77993a22-3caa-4bec-9217-5d07c3606da6",
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
              "id": "363af5b1-39ac-40e0-93b5-5f5ee7774606"
            }
          ]
        },
        {
          "id": "82a49c61-81f9-447e-8e79-91ef6de0a5ff",
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
              "id": "6ec0bc13-8c86-4c95-963c-6eab8505bc59"
            }
          ]
        },
        {
          "id": "b31a5300-d06b-4af7-ae6b-0fba066393fa",
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
              "id": "4bac8ae9-7325-4c48-bf43-eea9e00af215"
            }
          ]
        }
      ]
    },
    {
      "name": "Ccu",
      "item": [
        {
          "id": "6221e60f-f75f-4911-a256-7ceb69d3c249",
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
              "id": "66455c0b-5808-48f2-a49f-1be275f4de99"
            }
          ]
        },
        {
          "id": "3a271440-8bc1-42e3-83d2-7483e92a019e",
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
              "id": "a8c558b8-04b5-4af3-84b3-c61686866c0b"
            }
          ]
        },
        {
          "id": "ea9a8bdd-571b-4c29-884f-d050cbe12ea7",
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
              "id": "bc661c1c-074c-4201-8323-4f54c138f5f7"
            }
          ]
        },
        {
          "id": "06fac70d-e3cf-427a-a7f1-59ed913f2647",
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
              "id": "238084c1-3c83-464c-a686-9830523aed04"
            }
          ]
        },
        {
          "id": "e85f320a-5d1d-4d67-95e6-27a1aaa184ec",
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
              "id": "58db6347-5ce1-435f-9b9e-4af20a223aac"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlet",
      "item": [
        {
          "id": "37a2602b-cee9-43b6-b229-e5996e7b9038",
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
              "id": "34e7f8d1-5604-4ff9-825a-3e022aa87249"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlets",
      "item": [
        {
          "id": "16ddcc0d-821c-41e6-ab16-ac2cebcb7706",
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
              "id": "1beab40a-1f8a-4789-b25a-1882040d95b9"
            }
          ]
        },
        {
          "id": "a99bd2a1-6db0-45c1-81fa-28ac45911284",
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
              "id": "50cebe67-6e71-4019-a228-8cd0067f2fd1"
            }
          ]
        },
        {
          "id": "f30c214e-1e1c-4e03-bde6-526646573dec",
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
              "id": "4649d80d-0fd1-4568-89ea-158a5e3d97ee"
            }
          ]
        },
        {
          "id": "cf96efde-8734-4ec0-9cc6-346ff42ccef3",
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
              "id": "e156c592-987c-47c1-befb-a8db903b93ee"
            }
          ]
        },
        {
          "id": "ca2bcb8f-d746-4ef3-a82e-7805bc2255aa",
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
              "id": "64807b1a-61da-4a1c-a918-0a3ca2db32f3"
            }
          ]
        },
        {
          "id": "998b1f6c-cb6c-4c8a-809e-aad468c54b60",
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
              "id": "7bf68aaa-feaa-444d-99c9-d73e47468e28"
            }
          ]
        },
        {
          "id": "043e7158-3cf8-499d-9a0c-c1c55ba0ac79",
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
              "id": "01e48fa2-9cfe-4db6-932e-6b97df3852d4"
            }
          ]
        },
        {
          "id": "9d1d7012-497a-4f6a-8175-9518ff049904",
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
              "id": "dbe9a61c-5a7c-4998-8632-b6f1474f4115"
            }
          ]
        },
        {
          "id": "27d44f50-b264-4bac-bdc3-e1fa9a9aae4d",
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
              "id": "26bd1bc1-799d-441d-9a63-3504f02d1d90"
            }
          ]
        },
        {
          "id": "80e7d17c-eb2f-4608-a7ef-6d80dbdc8b6b",
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
              "id": "89dfdb7c-6ef4-43cc-9df2-8a06286714fc"
            }
          ]
        },
        {
          "id": "a1b3f107-08f9-4792-91ba-d07168a7387d",
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
              "id": "c583d843-5351-47f9-8801-7e0ae7b5419d"
            }
          ]
        },
        {
          "id": "4925edad-73a0-4095-b35f-fc7889d9f06a",
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
              "id": "4d02bddd-26f3-4de5-86db-1d6bee0c880a"
            }
          ]
        },
        {
          "id": "a9f84bc4-e1b2-4c26-8446-22133087aaa2",
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
              "id": "6aa36a85-630c-4c44-a630-a849852ae889"
            }
          ]
        },
        {
          "id": "b9b8ea74-5187-4642-982e-078fba28e061",
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
              "id": "45a3b2d7-e504-443b-903e-d5e6eaee643e"
            }
          ]
        },
        {
          "id": "2758130f-2e1c-43c7-ac4d-6a6c40c726d3",
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
              "id": "cf50e373-de28-4964-827f-54327eff5c2b"
            }
          ]
        },
        {
          "id": "dc1c847f-b4a0-4773-9a50-a19a10c3e4bb",
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
              "id": "714188c1-12d0-4653-ab06-4e60f611afa3"
            }
          ]
        },
        {
          "id": "ad7090cf-2b9c-497d-9e38-dde339514075",
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
              "id": "7c1c0690-d91c-485f-9e3b-f6b0a143d324"
            }
          ]
        },
        {
          "id": "4d568233-9a9e-48fd-aa08-c3bfb6dcf5c0",
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
              "id": "3781a7ac-9a3c-4632-ade2-23e9356dce0e"
            }
          ]
        },
        {
          "id": "320bddf5-b539-4895-ad51-f5678327b68a",
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
              "id": "755be87c-fa9c-4fab-aaf8-0d084235a390"
            }
          ]
        },
        {
          "id": "734206e6-80f1-4ca6-981c-e68907904cdf",
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
              "id": "97322694-97e3-4716-9dd0-88a4c03b142e"
            }
          ]
        },
        {
          "id": "0abba911-b877-4de8-a85a-46ec2e749f89",
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
              "id": "22a2fe45-bcb2-438f-bf44-04d80601cc9e"
            }
          ]
        },
        {
          "id": "29710f66-bdce-4441-a500-5d6c89c4500a",
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
              "id": "604035c2-32e8-4206-a020-b17ea6c8cf76"
            }
          ]
        },
        {
          "id": "22619397-5838-4d52-afd1-d4b1c0bedb03",
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
              "id": "517df604-6c02-48c7-b3b6-10eed8ce75fd"
            }
          ]
        },
        {
          "id": "7adf08c7-9672-4cf4-96a4-e54db16aebed",
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
              "id": "48129b62-03ad-4432-990e-25802f2cf4bb"
            }
          ]
        },
        {
          "id": "94c602bb-7027-4347-a690-c6cfefb25093",
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
              "id": "3e1ac2e4-db06-48c6-8615-6cd0462e5a83"
            }
          ]
        },
        {
          "id": "35b4bfc8-c71c-40e1-b873-e5596c3b2f47",
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
              "id": "f690b757-23f8-42e2-a7e6-45010018c2ef"
            }
          ]
        },
        {
          "id": "a478980f-9f42-4622-9eea-95fd293a788f",
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
              "id": "ec4e6bcb-4837-4cf5-b287-e6cf5d1645f0"
            }
          ]
        },
        {
          "id": "35241868-425a-40e9-9294-387cc729bba4",
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
              "id": "8c33a757-bf66-4d91-b0af-3f82b2d2d165"
            }
          ]
        },
        {
          "id": "6259b9a9-ecf6-456f-b294-303dea183ca2",
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
              "id": "d75d34fa-5373-4ff5-a0c1-ef1a1015f447"
            }
          ]
        },
        {
          "id": "56fd75f9-bf66-477c-887f-90721177c7b7",
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
              "id": "9b655455-327e-412f-80db-bab06519ced3"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudletcode",
      "item": [
        {
          "id": "f269109e-281f-468b-ac31-22a3964a363e",
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
              "id": "4f8dc7b1-36d3-4ad0-a1ed-62d0d183ba1b"
            }
          ]
        }
      ]
    },
    {
      "name": "Cps",
      "item": [
        {
          "id": "55ce24b2-b894-4694-995a-3dd19e933b86",
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
              "id": "23b24da7-f1ab-48e0-b978-21c605a7447e"
            }
          ]
        },
        {
          "id": "fd5babe8-1b4f-4b42-92da-72660698bbbf",
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
              "id": "c5b539c0-ffac-474c-9e2b-72a78fa412a2"
            }
          ]
        },
        {
          "id": "77dfd743-d980-4157-a3e1-5d25497e4697",
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
              "id": "5fde745c-2777-4586-9a61-56822f1ce51e"
            }
          ]
        },
        {
          "id": "5120105f-8ec1-4847-9002-7dc8d0745ed6",
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
              "id": "a86cf98d-c5b6-4d1c-86a6-2115dd012a9c"
            }
          ]
        },
        {
          "id": "cc8947c4-23cb-4cd8-9eb1-5638a41a504c",
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
              "id": "2ee1ace8-448a-4e0b-83ce-bdb26ae16409"
            }
          ]
        },
        {
          "id": "aba89b19-8006-4360-85fb-49460425e0aa",
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
              "id": "3b25a95e-7742-4eab-a497-06533649078f"
            }
          ]
        },
        {
          "id": "2b089dd4-da63-4cdb-af39-dd014032b12e",
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
              "id": "98e14115-b6ad-47d8-88b3-ffd459ea0e9c"
            }
          ]
        },
        {
          "id": "bb0de9a1-a60d-45e4-bb74-7ae18b1c578e",
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
              "id": "cbee4dc9-c880-43d8-870a-5ea976497e88"
            }
          ]
        }
      ]
    },
    {
      "name": "Information",
      "item": [
        {
          "id": "851c40d6-07b0-4c6b-b244-c303b2e36c6c",
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
              "id": "78195191-1fe0-48ec-84cb-91fc269a8cad"
            }
          ]
        }
      ]
    },
    {
      "name": "Update",
      "item": [
        {
          "id": "cb10d27e-9b7f-4545-9613-23276f87821e",
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
              "id": "53062fa4-f95a-497f-a20c-be69a282d1c2"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "9ac86d49-77dd-4638-8a32-3d57c72c905f",
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
              "id": "3502973e-7a96-4eab-a739-c2efb1caa1fc"
            }
          ]
        },
        {
          "id": "80462aa8-8a0c-44b2-83ee-5a28f6662596",
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
              "id": "2b971c42-7f8c-4b92-9d13-9609f7a8c533"
            }
          ]
        }
      ]
    },
    {
      "name": "Diagnostic",
      "item": [
        {
          "id": "63581c44-d4ba-487b-90cb-a6153dc996b2",
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
              "id": "ce3cfaed-f3f5-469a-9d37-6b2b7f4469de"
            }
          ]
        },
        {
          "id": "ab44aea5-944f-4fda-885d-272e5d850f53",
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
              "id": "eb6f1fc1-38a5-4d35-b17f-ec811a10b8cb"
            }
          ]
        },
        {
          "id": "5cab0c0a-5719-47ca-a248-7a1d0a3d8063",
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
              "id": "22f8291c-b814-422c-a4fa-e6c0cb9a179f"
            }
          ]
        },
        {
          "id": "a2fa3d61-fe81-448a-915f-115b86c8c6ef",
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
              "id": "da4685f1-eab5-41a7-a343-070f9649fa1f"
            }
          ]
        },
        {
          "id": "8e61c74d-7bf4-4fd9-9abe-5fabc467f976",
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
              "id": "30e61430-65bb-4aa4-b202-f10aeea51be3"
            }
          ]
        },
        {
          "id": "b2a0e8f3-0e27-4d22-9236-123dae537f11",
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
              "id": "52196fdc-e5c3-4327-b377-0602b0220585"
            }
          ]
        },
        {
          "id": "9e133a24-839a-4cec-9bda-babbe1eab098",
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
              "id": "5937f49b-b149-4b30-94bd-bc1f8e97ceb1"
            }
          ]
        }
      ]
    },
    {
      "name": "Token",
      "item": [
        {
          "id": "e6a279de-a1bc-4052-b04e-96152b2b89d7",
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
              "id": "62dd0518-cc0b-4735-89e9-be0b123ae921"
            }
          ]
        },
        {
          "id": "f5da0c8a-0592-4a16-84ee-4c626b7a48b4",
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
              "id": "271e9980-5aa5-4ba4-9ad9-b5aaf8f02e22"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "f4a71f8e-740e-4ec7-9210-e2da60563fcf",
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
              "id": "538c47a2-a5fa-4d4d-8b9f-59bbacc51daa"
            }
          ]
        },
        {
          "id": "d86e0cda-71fe-4bee-806d-a2090f96c8e7",
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
              "id": "3e310353-5b39-402d-9d89-6bc6e84b5cd0"
            }
          ]
        }
      ]
    },
    {
      "name": "Etp",
      "item": [
        {
          "id": "00afd2f2-2074-47ec-bca6-a003409e0d71",
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
              "id": "6bf00267-72c7-4267-ae0f-4b4679a16080"
            }
          ]
        },
        {
          "id": "4afac0d2-8346-4e7d-a0e3-211a2ca5b18b",
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
              "id": "389c4002-fbe7-4017-a5e9-132a007d48af"
            }
          ]
        },
        {
          "id": "91c849e7-95c9-4355-a900-fb7767077545",
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
              "id": "f014d66d-3a63-43fa-9e25-c81951b2a90c"
            }
          ]
        },
        {
          "id": "7c79180c-f0f5-4f03-b44d-ec8c0c3f2c42",
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
              "id": "97a4f424-dc0a-4668-a8aa-bcb921b4e91d"
            }
          ]
        },
        {
          "id": "d123b0b2-e9f6-4296-be38-8e592bd8a831",
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
              "id": "38f32a3e-7446-4e68-bb61-78a596fb6bf3"
            }
          ]
        },
        {
          "id": "582a8505-2c33-4586-9ba8-cc82e0d66dd8",
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
              "id": "34783d92-fe4a-45be-9811-7b5632844028"
            }
          ]
        },
        {
          "id": "8b959156-3cf4-454c-9500-31d7c3d87ace",
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
              "id": "c98276e5-85ef-4006-9cfa-6473e8835880"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "624ab61d-bf0c-4120-9e0e-a9fdaf9c33a2",
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
              "id": "4c874be6-cac8-459f-8b3d-0ef2bc713356"
            }
          ]
        },
        {
          "id": "50e93d75-5554-4dcc-9dc5-c05933272a5d",
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
              "id": "77bfe53f-9db4-4c50-bc7c-89c77f4ec3a0"
            }
          ]
        },
        {
          "id": "f94c6a41-e037-4fbe-add3-ae3b9f905b16",
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
              "id": "ac9e1ace-73f2-4956-ab3f-08129751ad65"
            }
          ]
        },
        {
          "id": "1b51dd07-b04d-4470-9abf-91e44649bd96",
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
              "id": "4ef595e5-2e25-47fc-87d0-514f4b7e9863"
            }
          ]
        },
        {
          "id": "91655661-fad7-489e-b3a8-e0b4db32631f",
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
              "id": "6babe791-f493-4326-8673-d0b40e520cb7"
            }
          ]
        },
        {
          "id": "26bd75b2-3e53-4a54-abe0-9375803ed669",
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
              "id": "c4a2e2a6-dddb-4e0f-85d7-5bb962bb9dec"
            }
          ]
        },
        {
          "id": "81984ac6-378e-470a-9708-a38adc741368",
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
              "id": "b4b8f5c9-27d6-4d90-ba08-7371c84978a8"
            }
          ]
        },
        {
          "id": "fea76ec4-dede-409f-8600-56a9dfc26477",
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
              "id": "bd027004-913b-410a-b473-b805d4d93677"
            }
          ]
        },
        {
          "id": "71eb208c-c89d-4265-8e15-41d45cde01ec",
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
              "id": "5511533a-dce1-4882-8949-e33ce039ed65"
            }
          ]
        },
        {
          "id": "c223c348-cf52-4a6d-9261-012fbb08a521",
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
              "id": "9c939ea1-bacd-4b81-99e4-fe2fda3dfb69"
            }
          ]
        },
        {
          "id": "77393d3c-5526-4d9a-8782-b3abf16e6cb3",
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
              "id": "81d675ea-a987-4d6a-8c02-41d199751d7e"
            }
          ]
        },
        {
          "id": "d01d8ba3-6be2-4f72-bb08-2717ba0e0ff8",
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
              "id": "63b26b25-9a36-4c40-b633-640dd03a4905"
            }
          ]
        },
        {
          "id": "e1c34fa7-7683-462a-827b-6c0c89c40ed5",
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
              "id": "1b1b7aed-9cf2-4c52-8fe2-a75e2252932b"
            }
          ]
        },
        {
          "id": "86078116-2a7c-46b2-aaaf-4fe3022d536c",
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
              "id": "1fd4eced-748c-4964-a762-4050dff9d1c1"
            }
          ]
        },
        {
          "id": "0aea0d5a-30b3-4ef5-a3eb-e58b3e9de19c",
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
              "id": "704b87b9-c307-41f9-b986-1981b2b92fd5"
            }
          ]
        },
        {
          "id": "c002633d-d1cb-4738-adea-14d45d47b31b",
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
              "id": "27b88af0-6e3b-4e2a-857e-052c6580e2d8"
            }
          ]
        },
        {
          "id": "c5b1d869-1add-4e1a-b957-977ee1ece9fc",
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
              "id": "21f9995d-b721-4733-9485-d5a166a8a2ce"
            }
          ]
        },
        {
          "id": "d8e5f684-bfb4-4ac3-b5ac-938249187b69",
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
              "id": "3224d534-16a0-4313-ac29-26888eb6280e"
            }
          ]
        },
        {
          "id": "908b61c8-b2bf-4997-89ae-5b6413f61f2e",
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
              "id": "24621eb4-6b7c-465c-891a-9bc9315cbe19"
            }
          ]
        },
        {
          "id": "a0240fe8-943e-4eb2-9c5a-9f9d5ee0f193",
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
              "id": "37b33863-da17-46e1-a75c-33cd199f574d"
            }
          ]
        },
        {
          "id": "eaffc882-32d1-49c3-a9b1-4aaff7387368",
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
              "id": "bed96035-4605-4470-ba3a-62c67bc5e785"
            }
          ]
        },
        {
          "id": "e876892d-6e79-4e1a-9bd0-eba9c77da261",
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
              "id": "4685dc27-d03a-449f-944d-860e32be2a05"
            }
          ]
        },
        {
          "id": "b1a90285-451d-44ca-b736-9941eccd8be8",
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
              "id": "2c966e23-1afb-4402-965f-a346b3c9b1bf"
            }
          ]
        },
        {
          "id": "cb853e00-f2d8-429f-aecf-6e4f523332d7",
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
              "id": "f885b6a7-8002-4553-a12d-cfdd3a53d90b"
            }
          ]
        },
        {
          "id": "bffdabe9-a561-4b91-b085-3713d23699fb",
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
              "id": "852acdaa-8413-4d61-88df-05b78f5ad3d4"
            }
          ]
        },
        {
          "id": "c90057fd-05c1-4a28-8d50-36087e16fbc2",
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
              "id": "77085490-f19c-4743-84c3-9ed8babbfa5a"
            }
          ]
        },
        {
          "id": "fee27e4d-a644-40d8-8d76-3024cae86a1f",
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
              "id": "28c951d8-2b9e-4600-bdea-35991830e7cb"
            }
          ]
        },
        {
          "id": "f69bd159-bb6c-42c6-adaa-bb9d93691b1b",
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
              "id": "6cb30e57-ceb1-4261-95ec-9c0d76e46ecf"
            }
          ]
        },
        {
          "id": "2ae1de68-b6c3-4c0b-892e-383a0c94f5b5",
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
              "id": "127d6fb0-1654-4677-9549-44a0c234203c"
            }
          ]
        },
        {
          "id": "bcc62edd-ed29-412e-8290-65420f5259ba",
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
              "id": "96b29778-4e04-4805-870f-01e5b3dfd313"
            }
          ]
        },
        {
          "id": "886398cb-7141-4a56-99fa-6bf74f9cf5d7",
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
              "id": "13925c9d-1589-4d04-9d6a-0bb1bcfa8364"
            }
          ]
        },
        {
          "id": "22fb9f05-44c5-4439-99eb-41e77efe1bb7",
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
              "id": "cdf3a046-c0bc-4eed-9510-137d8277c1d8"
            }
          ]
        },
        {
          "id": "8955297b-6a87-4da7-834b-b482b2f0c002",
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
              "id": "ebe9f077-d7ea-41d3-97a6-3939f3d7d482"
            }
          ]
        },
        {
          "id": "dbeaf4fe-db6c-4d5f-a75e-b1bffb40156f",
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
              "id": "4779765f-57e2-4b18-9401-9f1248c6330c"
            }
          ]
        },
        {
          "id": "3665aaa0-22bd-4f4c-b6f8-b8d8c908ef6f",
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
              "id": "70710905-00a8-485d-bb88-ee667694b4dd"
            }
          ]
        },
        {
          "id": "67b9c9fb-e787-49c6-ab65-98d416649214",
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
              "id": "171ab14d-bb2f-4ea8-b978-8e5fdb473e29"
            }
          ]
        },
        {
          "id": "8dd1c5aa-f52a-40cb-86e6-82958dd01c3a",
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
              "id": "80e56fcb-197f-4ddb-a939-c90eca58279f"
            }
          ]
        },
        {
          "id": "d0fcc8b3-506e-4967-99bc-2f1d07d15548",
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
              "id": "dc34c6a1-b90c-4505-8845-a0472c27e186"
            }
          ]
        },
        {
          "id": "15018979-6d01-48e6-99dc-755b05f2f4e2",
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
              "id": "989b35c7-b628-4b41-8028-ad4482cf17e4"
            }
          ]
        },
        {
          "id": "30f59e0f-e2a1-4143-a503-180695a89a90",
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
              "id": "17b3c5b9-e749-48fc-a454-4d708c8ffe9b"
            }
          ]
        },
        {
          "id": "76f76df6-2142-49eb-a5b3-d2d8fda32014",
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
              "id": "4a8e4b28-5494-4929-911e-4e482056e787"
            }
          ]
        },
        {
          "id": "56a6a689-4356-40d1-9aa4-2e8904745805",
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
              "id": "305724dd-8386-4d69-b21f-0b0f981e6fa9"
            }
          ]
        },
        {
          "id": "cf46fb42-3e00-4f08-a4e1-645c19136beb",
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
              "id": "0b4830d2-40a5-4862-8405-1d0a42520127"
            }
          ]
        },
        {
          "id": "e81adb3d-3c02-4f06-b29c-bc6e4d5b2b21",
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
              "id": "2a279a34-fab3-4584-ac66-e17e4f0f4e96"
            }
          ]
        },
        {
          "id": "94ec0d35-3467-46c2-9eb1-ae4f0f5da581",
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
              "id": "3f336246-c92b-47c3-a6b0-c95ee22ebd9b"
            }
          ]
        },
        {
          "id": "98f51cfa-91a3-4ba7-8e2b-c72884462903",
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
              "id": "30cdbadd-4a38-4908-a269-c305a895a916"
            }
          ]
        },
        {
          "id": "c3926916-828e-4fac-878f-08c90abbb9c5",
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
              "id": "2d82898c-e0eb-4cb3-9451-97f54a89b5a3"
            }
          ]
        },
        {
          "id": "3ef0b2b3-a702-40cd-b70e-e72d8cc91077",
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
              "id": "b9ad2e12-6427-4472-8164-4cace3be125b"
            }
          ]
        },
        {
          "id": "2e4a4559-f678-4f55-b731-35316fa29c8f",
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
              "id": "a488a57c-0ece-4429-9667-773a5785a40a"
            }
          ]
        },
        {
          "id": "2df84ce8-8cd3-4cd7-bba9-c7b67c9e8277",
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
              "id": "21da7005-8125-46fb-bbfc-1e69b3a750cb"
            }
          ]
        },
        {
          "id": "c84b142e-9f47-48d0-b9a9-e633db0e5702",
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
              "id": "64a837b6-db79-444d-a7fe-42b19035a6f8"
            }
          ]
        },
        {
          "id": "c01e9ff6-e2b1-44ee-86c6-89d47b4f7912",
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
              "id": "e1e0edd4-4443-487e-affc-45aaf43a82a3"
            }
          ]
        },
        {
          "id": "e188237a-9d05-4f00-ada4-eb3a541de587",
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
              "id": "980ff2fc-f454-44bb-a718-2fccf1ae982c"
            }
          ]
        },
        {
          "id": "10d2b088-5ad7-4fa1-a4ba-3dc8d4692722",
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
              "id": "94388130-00cb-4e51-9c21-a48ff96e3bd8"
            }
          ]
        },
        {
          "id": "addfe8f3-54f0-4cbe-9d65-709f236a22bb",
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
              "id": "2daf3f46-de94-4d18-a6a2-6064610377a2"
            }
          ]
        },
        {
          "id": "7a2a1008-9bfd-424a-853f-8e06ef5f8566",
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
              "id": "b4b0babf-4e8a-42ca-8ab4-5e080604c734"
            }
          ]
        },
        {
          "id": "22f474d1-5745-43b9-864f-c698f3f83220",
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
              "id": "243eb5fc-accf-4f8f-9c48-a41ffad184de"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "47d9c5d6-55b4-4331-ac4d-b7c50f04d211",
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
              "id": "82d81d8e-7ffa-49f7-a8b0-926d26aa1db4"
            }
          ]
        }
      ]
    },
    {
      "name": "Deliveryformat",
      "item": [
        {
          "id": "1ad33528-4135-4fe2-965d-ed8d9eea6b84",
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
              "id": "b09d091d-46cc-45ca-9e98-ef00f2bae107"
            }
          ]
        }
      ]
    },
    {
      "name": "Audience",
      "item": [
        {
          "id": "9a08e1fc-b38a-4cb3-92cb-621c8c33bcd7",
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
              "id": "08c8fb77-0d36-4f0c-b23b-e0969311a0cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Clients",
      "item": [
        {
          "id": "b51d7eae-49b0-42e8-adad-0ba1ae0b3cb5",
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
              "id": "f5431c97-b12b-4663-90c0-0c02d40c2316"
            }
          ]
        }
      ]
    },
    {
      "name": "Feo",
      "item": [
        {
          "id": "56782f50-4de5-45d3-88b0-d2d4fffa4998",
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
              "id": "47deb9e2-52a3-41cf-be43-18339c81be48"
            }
          ]
        }
      ]
    },
    {
      "name": "Imaging",
      "item": [
        {
          "id": "90c9d0f1-184c-4982-9b0b-378259a3d65b",
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
              "id": "d13a3363-6dc5-40b4-a541-fabc930d09c1"
            }
          ]
        },
        {
          "id": "a3d63baf-e4c1-4a3a-9311-6b10b504feb7",
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
              "id": "9da9d57e-9375-41e2-84c7-32246e140878"
            }
          ]
        },
        {
          "id": "75a87aa4-a9a8-4246-96f2-5be9d4a7f6a8",
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
              "id": "ea9db528-5d05-4745-b40c-bafb5b6e796f"
            }
          ]
        },
        {
          "id": "2793224d-ab7e-49d4-8ccf-3f4b333d4e71",
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
              "id": "72fffd26-ef76-44b2-9c91-ee30b006adaa"
            }
          ]
        },
        {
          "id": "c2837fb9-18e0-48f5-8ad9-ae7f36204f7d",
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
              "id": "4044361e-17e6-4307-8da1-7c059fb02182"
            }
          ]
        },
        {
          "id": "3bb32ec6-36bd-4318-ba47-d26541de5e4f",
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
              "id": "bd60420f-53a1-46a7-869d-bf5ab3292485"
            }
          ]
        },
        {
          "id": "087e436d-7c30-4d13-8e4a-f17b661a221c",
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
              "id": "a879da28-8785-4859-91c4-15f8df585346"
            }
          ]
        },
        {
          "id": "ae9fefe5-47a6-47eb-93a4-2461bf4e00e4",
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
              "id": "ad240f35-4063-4589-88d2-c2844762886f"
            }
          ]
        },
        {
          "id": "12143bd4-a1d7-40cf-a8ac-8fbc4d0436dd",
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
              "id": "01b7e721-37ea-4507-bda6-f17df77b7521"
            }
          ]
        },
        {
          "id": "82c0274c-3566-47ad-b139-a516ce87535f",
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
              "id": "488f0bb5-93ea-4b5f-b034-fd8e7cc1b93f"
            }
          ]
        },
        {
          "id": "040f6e11-c163-4d68-8fa0-1f85232e53f9",
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
              "id": "333e04ec-f378-46ac-aa8b-92871b4dd0c0"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "39e37606-d31f-4a42-863f-09d0b69f9ad7",
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
              "id": "809cd47f-994d-4457-8a32-9181669884f1"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "00c6024e-72bc-42e2-a365-a3ed670c9855",
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
              "id": "c3bad5fa-2797-42a4-873e-3d6fd7bf8ccb"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoicing",
      "item": [
        {
          "id": "5bcf5f1c-8e28-48f1-85e7-2ad143ff19a4",
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
              "id": "81276ddc-404d-4ac6-b33c-72bc99673dd6"
            }
          ]
        },
        {
          "id": "8b0efed0-4fc7-4c80-a200-cdee28d961f9",
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
              "id": "7f2f6fb7-d658-418e-852a-0489b4cf24e9"
            }
          ]
        },
        {
          "id": "71c9e057-a3ae-4132-85d8-518670be0eb9",
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
              "id": "b79ce4ee-8b41-4232-b04a-018c2b5cd6d0"
            }
          ]
        },
        {
          "id": "510b73e1-66c1-45a5-b536-39d34c2a1a7b",
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
              "id": "1ad1c970-b62b-4a78-999f-ea7b70ee511c"
            }
          ]
        },
        {
          "id": "b2cf61e1-0a42-427e-9c6b-78d73808d665",
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
              "id": "05d68fea-e651-460f-907c-f33e7c732e5b"
            }
          ]
        },
        {
          "id": "f5aea29a-95fb-4fd2-8603-a0260fc0c10b",
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
              "id": "4aedbf81-7556-40fd-a34a-0695e709c2e5"
            }
          ]
        },
        {
          "id": "3eadce67-18e9-4f91-b47d-3c61484a1cc4",
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
              "id": "e036dca9-68ed-48f1-8165-d734bde7d5cf"
            }
          ]
        },
        {
          "id": "d8bc71f2-e22f-4812-8f8e-e39de7676d47",
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
              "id": "1aafd1c8-a379-417d-9e19-d26f459bce95"
            }
          ]
        },
        {
          "id": "06a439bd-3de9-48a0-ac4b-63591e8ecfcc",
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
              "id": "6b925ed3-2f9b-4354-a75c-e208d98223ad"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "0f15a957-e712-4981-abe1-4bc2e7c18fea",
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
              "id": "3778ddc6-3d0f-495c-932c-14f4133dbe5b"
            }
          ]
        }
      ]
    },
    {
      "name": "Configurations",
      "item": [
        {
          "id": "e4e6b19f-1fcb-4ef9-8533-c9111c7ee29f",
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
              "id": "8beac5f3-40f9-4f3a-8e6e-11d0e3eda63d"
            }
          ]
        }
      ]
    },
    {
      "name": "Service",
      "item": [
        {
          "id": "b5c5dbf3-2e6c-40ce-8314-07652a775070",
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
              "id": "cd5121bc-9fda-4d76-a178-3947ea0287f9"
            }
          ]
        },
        {
          "id": "60fa4434-9f34-43d1-a76f-36f405643c0f",
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
              "id": "97ee2ed6-fa61-4fe5-bea0-e78d669cbffb"
            }
          ]
        },
        {
          "id": "5f7a7bcb-c219-4f86-8816-93e2e1597f71",
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
              "id": "bba74bf8-1ceb-4b97-9b0b-727cc9db17b2"
            }
          ]
        },
        {
          "id": "11e58cf0-bc6c-4d25-b006-54282f3055da",
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
              "id": "8d6d445e-8054-41ed-b451-e878be4a0940"
            }
          ]
        }
      ]
    }
  ]
}