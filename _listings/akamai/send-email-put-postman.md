{
  "info": {
    "name": "Akamai API Reset a User&#8217;s Password",
    "_postman_id": "1bbbdae2-7fb3-4531-bc5b-27f092e73842",
    "description": "Reset a User&#8217;s Password",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Galaxy",
      "item": [
        {
          "id": "ead98ef5-9be0-4487-a56a-9318d74f2835",
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
              "id": "367f2293-8a47-4e48-b0bc-acc23492e043"
            }
          ]
        },
        {
          "id": "77d20712-967a-4c07-aa30-e8ea1e27cf5e",
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
              "id": "af1f8508-2c15-4d3a-83f0-8a6b07ccd196"
            }
          ]
        },
        {
          "id": "90f38d24-53e8-481f-9ad1-100953b4552d",
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
              "id": "dea7d468-5403-4024-ad7d-1227455773b6"
            }
          ]
        },
        {
          "id": "162a058a-5790-49d6-af00-fa95ae93f7a3",
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
              "id": "9e9c8917-1e76-44ec-9104-0bca9e7de7ff"
            }
          ]
        },
        {
          "id": "47570c9a-b4c0-4905-8ac5-f5365f424447",
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
              "id": "846a1afa-7461-401c-9985-e344e473e649"
            }
          ]
        },
        {
          "id": "e511fd3b-b498-42a4-b909-cd734a2c500c",
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
              "id": "441d7930-2021-4ee3-ad83-1a1c543ce6f4"
            }
          ]
        },
        {
          "id": "7481be04-22e4-4c2d-b24c-157dabd81960",
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
              "id": "efd14a49-6e2e-49d5-92b1-9ffdfd27d243"
            }
          ]
        },
        {
          "id": "19e5a243-0c2e-485e-8350-8173d0b1a97f",
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
              "id": "e5a3cdbc-268c-4a6b-ade1-d37f5372f3b1"
            }
          ]
        },
        {
          "id": "f0459da8-7bac-4f75-b2b1-b2c0694ca283",
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
              "id": "a3ea0261-1929-41e1-9376-0c98d5c1697f"
            }
          ]
        },
        {
          "id": "7cf5687a-1db7-4183-8d57-7a855366ea87",
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
              "id": "45224269-9159-4cb5-90e8-a9c6badd2d8b"
            }
          ]
        },
        {
          "id": "ac8ea942-9605-46c1-9f8c-2f88e4c64c8c",
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
              "id": "8014ee0d-0cff-4e50-a57b-c1482cf568be"
            }
          ]
        },
        {
          "id": "f4c7bf33-5842-421b-ba22-5f1b69477c98",
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
              "id": "622d222f-db24-4589-a300-235baa8735f1"
            }
          ]
        },
        {
          "id": "d99ec1d8-1bda-4d11-a84a-e93e372f87a5",
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
              "id": "8d09d733-b42a-4709-a6d6-ad272281eb40"
            }
          ]
        },
        {
          "id": "c26aa571-a059-47e9-ba0d-236ed45c6eb7",
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
              "id": "2ee09f73-3b39-4267-81e7-e7294dff878a"
            }
          ]
        },
        {
          "id": "48ab2cbe-3f90-4617-9d04-047a479459fe",
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
              "id": "e59040a5-c783-4fa6-a358-84c442164a82"
            }
          ]
        },
        {
          "id": "41ac6690-224a-498c-8492-f53cc1f59f27",
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
              "id": "fc1b8551-d54b-432d-a19c-bf335ed7d4e1"
            }
          ]
        },
        {
          "id": "ba6fe06d-a1d2-416d-9537-8dd633b2af04",
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
              "id": "c245aa94-7c1c-4780-94f4-37bc5b1196ec"
            }
          ]
        },
        {
          "id": "ee461c34-a40d-4e00-9e59-e77455c4a7c3",
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
              "id": "0b7042c6-7c57-431a-9d3c-8173afbf5683"
            }
          ]
        },
        {
          "id": "bc64e0a9-0525-4c7b-a217-16026e67ca42",
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
              "id": "cf4ef7ad-d112-4ea9-b203-61e1c7a3f05c"
            }
          ]
        },
        {
          "id": "00ecbf17-03ac-4e9d-84ed-e2286fd417b3",
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
              "id": "1d7c4de0-151d-48d8-a2ba-b7d355e12bd4"
            }
          ]
        },
        {
          "id": "494f76bc-3883-4431-9f8f-5ab3b42cea9f",
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
              "id": "1b5fa7a4-4bee-48b7-8ef8-762c7536e952"
            }
          ]
        }
      ]
    },
    {
      "name": "Billing",
      "item": [
        {
          "id": "2f6f5ca4-3267-445b-b1ad-066284e54d5d",
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
              "id": "0ea88ec5-996d-43b6-a14f-d45cbb75db13"
            }
          ]
        },
        {
          "id": "9c7ea636-7eaa-47fc-ac67-56a063ad6b8d",
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
              "id": "03fc5c22-b1ab-46b2-a2c8-fb58918bac36"
            }
          ]
        },
        {
          "id": "a460428d-f376-4ef5-830d-093b11800e74",
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
              "id": "52148d77-7e0b-43b5-acfd-05ad198a99b8"
            }
          ]
        },
        {
          "id": "6317d357-d217-4209-9e85-5b283296494b",
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
              "id": "4ad0d14d-9f6f-4385-9f34-a280e4d019ae"
            }
          ]
        }
      ]
    },
    {
      "name": "Cases",
      "item": [
        {
          "id": "6b852878-7e90-492b-b674-c8dff4f9cbcc",
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
              "id": "bb908666-b5d8-4459-a85b-24bd0978bf55"
            }
          ]
        },
        {
          "id": "a24aee48-764c-4518-bd43-8a7826bb50f0",
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
              "id": "a595d9b0-fd47-4863-a335-3df85ba9b912"
            }
          ]
        },
        {
          "id": "9e19af60-52d2-4a30-82f1-7f9b11f0ae84",
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
              "id": "cd0d2d4e-9be6-4b1a-9125-27beba678dd5"
            }
          ]
        },
        {
          "id": "c59d04ba-d153-412c-be2a-eda3fa39fe8a",
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
              "id": "3fc51281-0ee9-4088-9b3e-df4a1adff7f9"
            }
          ]
        },
        {
          "id": "d317e424-3c20-463c-8449-da47aea28531",
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
              "id": "501adaa8-1c09-43fc-bae9-c43183806755"
            }
          ]
        },
        {
          "id": "22a6631f-4932-423b-8a29-371274426935",
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
              "id": "e7a4b919-e5c8-4a2b-8610-3bbf335b53dd"
            }
          ]
        },
        {
          "id": "41a57007-3de7-4436-99ed-76823f2d64d8",
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
              "id": "d2b05f6c-01ec-4b9f-9fd4-fb8b8426a683"
            }
          ]
        },
        {
          "id": "bd75b856-f193-4315-ad95-1753938e0522",
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
              "id": "67f0e2be-518a-4996-935e-c6818cbb57d5"
            }
          ]
        },
        {
          "id": "a01514af-2a6b-4b42-ab1b-018bfb653d5c",
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
              "id": "b4605999-41f8-4c80-94c6-9702492a1b44"
            }
          ]
        }
      ]
    },
    {
      "name": "Ccu",
      "item": [
        {
          "id": "c3507516-e585-42e1-9033-4ee419cdbbea",
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
              "id": "f0d7ae9a-1562-4731-a3b9-00bd17209f3d"
            }
          ]
        },
        {
          "id": "541bb4c3-3af3-49a0-8553-658649c811f6",
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
              "id": "9f710a25-9998-4db7-982e-5f11e3dec4e6"
            }
          ]
        },
        {
          "id": "9f4226a1-5f14-47ed-9a10-f83cc328ed7e",
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
              "id": "efacfa90-1351-4251-8902-af5f612f524c"
            }
          ]
        },
        {
          "id": "f176c97e-9dca-4695-ade5-a8c41758c479",
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
              "id": "c9921199-4a96-43f3-8417-825c5ece9508"
            }
          ]
        },
        {
          "id": "ead3c0b3-963d-4d79-8350-ae5cc7bccb61",
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
              "id": "bbfc8418-1bb1-4dbc-996a-77e275656819"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlet",
      "item": [
        {
          "id": "e701198e-463e-4073-88ef-bb8dbbec770b",
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
              "id": "a6c9b50b-b5ba-4738-a8e5-e14fa179382b"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudlets",
      "item": [
        {
          "id": "0b766e1c-0d8c-48cc-9333-8bdb9f44377f",
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
              "id": "cc9e9988-3b38-422d-a53d-f167add0fe00"
            }
          ]
        },
        {
          "id": "781f4da3-aa65-447b-b34f-36c064837039",
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
              "id": "7af5ef68-8ae1-4809-b558-76f978c01e06"
            }
          ]
        },
        {
          "id": "ffc20921-4700-492b-969e-5ffa8deb3360",
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
              "id": "5493a812-d29a-44e0-a541-b0432fdcd473"
            }
          ]
        },
        {
          "id": "26c52f9b-ec4f-4273-b18f-7df960b33511",
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
              "id": "a3b4f840-21a8-48c4-89ec-7057c78029b5"
            }
          ]
        },
        {
          "id": "9b4aebb6-718a-42a9-8ada-a458465ee220",
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
              "id": "9b1b365b-527a-42fb-ab04-db1604bbeacd"
            }
          ]
        },
        {
          "id": "110f30a8-99bd-4b09-bb69-e5a7fe117a09",
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
              "id": "473ce0c4-fbce-4982-852d-a1b883457905"
            }
          ]
        },
        {
          "id": "fa02cfc1-afa3-46cf-a983-774080a58e5c",
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
              "id": "de9ad601-9d23-4e8d-9f1e-e533b0239270"
            }
          ]
        },
        {
          "id": "9d4edab0-912e-4bbd-b779-8c61553665bc",
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
              "id": "6bad6865-afa5-45e2-8d1b-6647c50d43da"
            }
          ]
        },
        {
          "id": "2dfbef4f-cbe1-4166-8cce-518817678f8e",
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
              "id": "fc56c8a3-7959-42bb-bce7-e16be317db54"
            }
          ]
        },
        {
          "id": "e3caa63b-8875-4b3e-893f-965b374e15ec",
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
              "id": "7f0dc252-633d-4c5d-9121-7e1d20c284ea"
            }
          ]
        },
        {
          "id": "43132d73-a735-49ab-8850-93ae8a611c14",
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
              "id": "95b24b80-d37a-4348-9304-db6e633117d0"
            }
          ]
        },
        {
          "id": "caf32c67-7a69-406d-bd69-c0b76e798f33",
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
              "id": "7126fda6-4ad5-44a2-a5b2-1b49f263d44e"
            }
          ]
        },
        {
          "id": "59a848c6-25b6-4330-9722-0c266cf15386",
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
              "id": "756af761-8024-4fea-ad4c-3a855cdc0f7f"
            }
          ]
        },
        {
          "id": "ebd4d787-d763-4ef3-95f7-76ed409c822c",
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
              "id": "2ceb19de-c140-42ac-9a17-70884c7e4e87"
            }
          ]
        },
        {
          "id": "3f93d6d4-3ca6-4e78-b12b-8fcb25f23d1d",
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
              "id": "96a50e54-567f-4291-b87a-76f0c71cc0fe"
            }
          ]
        },
        {
          "id": "7d52c691-049d-41df-b560-20b2769014a5",
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
              "id": "dc7f7ae9-7c14-42a7-9cea-f0b8068473a4"
            }
          ]
        },
        {
          "id": "45eb03fb-39fd-4f34-8a54-a112d8125aa2",
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
              "id": "f700bdf4-e683-45e4-a04f-8ff71d6e4e41"
            }
          ]
        },
        {
          "id": "476ed9af-f331-4f39-8dab-cc13e8c62d43",
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
              "id": "39003f2e-9508-48a2-89f3-0e1488ae1c08"
            }
          ]
        },
        {
          "id": "964ee3a9-3540-47bb-ab7f-cae9ce2e74c0",
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
              "id": "d40cda0c-6871-4449-b7a1-b52fbe2aee02"
            }
          ]
        },
        {
          "id": "101c8811-e48c-4e35-8e88-ab2da9f0cccb",
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
              "id": "522cfd54-f064-40bd-898e-068704bfca92"
            }
          ]
        },
        {
          "id": "00d4a850-799b-47c2-b47b-67b5f0fc8e3c",
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
              "id": "8e7b1699-f70d-4de7-9e8f-2d15d9506d4f"
            }
          ]
        },
        {
          "id": "b1ff50be-7c77-4e85-9e28-be0f3adc8a0f",
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
              "id": "91d7c10f-8aee-40a6-9eb4-aa980c61727a"
            }
          ]
        },
        {
          "id": "9bac61ad-961e-490b-973a-a75ad8479d59",
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
              "id": "2dab30e9-7ebb-47f0-bab8-056d39ca95e1"
            }
          ]
        },
        {
          "id": "d001f2cf-c4fc-46bc-8cb2-58bc7ff9a046",
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
              "id": "5af71a8d-a5ed-4c7d-b7e4-7a48eab56170"
            }
          ]
        },
        {
          "id": "c1fea444-2626-44eb-8fa9-1365a91c6731",
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
              "id": "17335f6e-abd9-416a-bc96-e4edb5f13aa9"
            }
          ]
        },
        {
          "id": "493df829-0b17-481f-a953-a1bd38f0000e",
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
              "id": "dd787540-33c3-4805-bb89-4508c3d789e6"
            }
          ]
        },
        {
          "id": "ad8eecf7-ba62-4d99-80e3-aec65a696238",
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
              "id": "d9062ae1-a812-4549-aa45-c2fcb7495b1a"
            }
          ]
        },
        {
          "id": "e1f12c89-1516-4715-a16d-18876b95c8a8",
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
              "id": "8344d9be-b49e-43a5-812c-15383f4b5187"
            }
          ]
        },
        {
          "id": "e0422e32-1da5-4764-a709-03098d132714",
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
              "id": "6082fc29-a6ca-4272-ae1d-6acd1743b70a"
            }
          ]
        },
        {
          "id": "0f3bed07-33bc-42e0-88af-62947bb78b6d",
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
              "id": "d9ca3f81-606e-40b9-a1bd-c78957fdda00"
            }
          ]
        }
      ]
    },
    {
      "name": "Cloudletcode",
      "item": [
        {
          "id": "f751107c-cc2f-4181-8b75-007950439666",
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
              "id": "96fef89e-4117-4f74-9493-8dfba0a020af"
            }
          ]
        }
      ]
    },
    {
      "name": "Cps",
      "item": [
        {
          "id": "eb0ca1c5-df81-4dcf-aa7e-35d000acfd49",
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
              "id": "44cead62-90f4-4b75-98ee-f5e785743f5b"
            }
          ]
        },
        {
          "id": "48c8afff-830e-4561-9ed3-74d1ebb62386",
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
              "id": "1ffc5d85-ace5-4824-86b7-f4ea0dae1b27"
            }
          ]
        },
        {
          "id": "101d4633-f25b-4b5f-a952-d8305c44e76b",
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
              "id": "640a48a5-8c47-4d08-bba3-aec12f8bcaca"
            }
          ]
        },
        {
          "id": "b101cfd8-8d24-4c0f-bf01-b263640ccf52",
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
              "id": "bab8ac94-7728-4c7d-9097-00df4d60b821"
            }
          ]
        },
        {
          "id": "6c0fa10c-aa4e-4856-9ce5-8930e64d0ff6",
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
              "id": "14d56ede-9cba-427d-b794-7a6101cbf586"
            }
          ]
        },
        {
          "id": "7a741f6f-370b-4ec4-86da-a0f1212a377d",
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
              "id": "dea32bbd-fe24-4598-a301-ef76a8287088"
            }
          ]
        },
        {
          "id": "1b3e357a-5f5d-40e7-afe3-2295aead8407",
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
              "id": "6d614d87-28e0-4f97-b00f-49e18b9cf02c"
            }
          ]
        },
        {
          "id": "7dd86893-8b0b-4846-8791-c90f20dabdc3",
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
              "id": "0c3e35d1-84c9-43c0-be57-a216f86a9cd8"
            }
          ]
        }
      ]
    },
    {
      "name": "Information",
      "item": [
        {
          "id": "7d9ce883-1c7f-4b02-bf05-b24248531cd2",
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
              "id": "4dfbcb36-12d7-4cfc-8552-6292e09874b8"
            }
          ]
        }
      ]
    },
    {
      "name": "Update",
      "item": [
        {
          "id": "9df11891-8ba7-4860-80e2-c357b7144235",
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
              "id": "a1d7022d-0c1f-43d5-b2c0-8f5b13977a30"
            }
          ]
        }
      ]
    },
    {
      "name": "Samples",
      "item": [
        {
          "id": "40efb41f-a9ee-47ff-961e-f7ae275789b9",
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
              "id": "43d54910-cee5-455b-88a1-0a79d4dae7e8"
            }
          ]
        },
        {
          "id": "8fd0d7c8-5fa9-4f1a-a7bb-1cfd11d3ad44",
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
              "id": "3d9bc5f3-22ea-4818-b631-667e1c7da379"
            }
          ]
        }
      ]
    },
    {
      "name": "Diagnostic",
      "item": [
        {
          "id": "17dacd95-26a3-4c71-8634-441e861d4bbb",
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
              "id": "cc7980e5-fd68-4871-ae5b-5b5139047add"
            }
          ]
        },
        {
          "id": "d7092df6-78fa-4eb4-bec8-b1ff925333eb",
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
              "id": "a5ebfe71-ab56-46dd-a326-e3ffeab7317f"
            }
          ]
        },
        {
          "id": "07f6b902-efd4-4ca3-a5f7-39bc2557b08f",
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
              "id": "c737075d-8fe1-420a-b2f5-5ab8a6e1313e"
            }
          ]
        },
        {
          "id": "6e25740e-114a-490b-9d60-9dbe8654f381",
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
              "id": "9f46d6da-4f55-4c44-9a1a-66f1837f7f34"
            }
          ]
        },
        {
          "id": "8044af3a-a18c-4d29-bdd3-db8177cd602e",
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
              "id": "ba4d89f3-276d-4602-bed2-16492f893e3d"
            }
          ]
        },
        {
          "id": "3864c25c-fb22-406c-9751-dd430d2c6f5e",
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
              "id": "39ddc88c-b18b-4454-a5cf-6b72d4a364b4"
            }
          ]
        },
        {
          "id": "35febcd1-34cd-459a-872a-22dcc899fd1f",
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
              "id": "8761628b-53ca-4dbd-ac2e-53e3016646b2"
            }
          ]
        }
      ]
    },
    {
      "name": "Token",
      "item": [
        {
          "id": "4664ff20-4c54-4818-b347-15c2eb58bb11",
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
              "id": "4cbf7115-e674-4f1b-afe6-74a6f3a1a93c"
            }
          ]
        },
        {
          "id": "50c5d169-9e4f-4fb1-93be-d3662c4126cd",
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
              "id": "c54c7574-3edf-4c17-bf09-c47263f05433"
            }
          ]
        }
      ]
    },
    {
      "name": "Data",
      "item": [
        {
          "id": "f3b81bbc-1323-4e91-8ca3-2af3319956d0",
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
              "id": "1bae5465-3186-454c-b110-f803af25455d"
            }
          ]
        },
        {
          "id": "4b21fc1c-b0d9-487e-a989-3dded1307dc3",
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
              "id": "9dfce10c-3b0e-4216-b286-dcb551f9711b"
            }
          ]
        }
      ]
    },
    {
      "name": "Etp",
      "item": [
        {
          "id": "859d05e7-630a-42a1-94f6-4a9b8e9f8a37",
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
              "id": "56a6a343-9f2a-4e5f-80d8-0e1e9f74a615"
            }
          ]
        },
        {
          "id": "1100e4d1-7f07-4bd0-874a-e0d3934f0910",
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
              "id": "973d5da0-11b6-4248-aca4-5e56169606e0"
            }
          ]
        },
        {
          "id": "769ee8c6-f10e-40c7-b084-7c7b4a8334ab",
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
              "id": "becd1595-da73-410f-802f-a8c327654aee"
            }
          ]
        },
        {
          "id": "65f0ebb1-7fff-47cf-88fb-9af3d0eb487f",
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
              "id": "a0afd1f7-b37f-45e9-a6d1-b4ff4b651844"
            }
          ]
        },
        {
          "id": "c69ee43a-bd73-45d5-b357-7081d296359d",
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
              "id": "03969a3b-a1dd-4222-bfc9-734f8ae7b8aa"
            }
          ]
        },
        {
          "id": "ba348641-fdfb-424c-885d-c0de1b330186",
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
              "id": "c7357399-5cba-4a1d-a27a-b0f579263bd0"
            }
          ]
        },
        {
          "id": "780a193f-3c6f-4dff-9fce-c252751d9c2c",
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
              "id": "d9783590-b1a2-4a5f-8578-1ba5c96cf084"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "903f2a94-4afc-4af8-85e5-13038be1719a",
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
              "id": "de8f3da3-06e8-416b-a857-4c536a52ae47"
            }
          ]
        },
        {
          "id": "e705ca7c-8eb6-4f56-81aa-2aeeb2f0bcd3",
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
              "id": "755eb33d-456a-43ef-b4f6-0738880cd71c"
            }
          ]
        },
        {
          "id": "0860e630-1839-4d1e-945b-65c82ef249b7",
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
              "id": "891084a1-3d57-40bf-a8de-68fd000e61dd"
            }
          ]
        },
        {
          "id": "f76458af-1019-45c3-93e3-438b92eec24e",
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
              "id": "34f07607-d500-4192-8aca-407b147449d5"
            }
          ]
        },
        {
          "id": "5e1ed96e-1cd8-4b2e-8297-dd37c878687e",
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
              "id": "69c31582-ac47-4bc8-aabc-fd6ac6c6f20e"
            }
          ]
        },
        {
          "id": "27d4b2f2-0a7e-497d-a608-4be96304e87c",
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
              "id": "ee9f4306-1192-47fc-8b0a-53d388a07a7c"
            }
          ]
        },
        {
          "id": "e09865fa-f1d5-408c-b20d-05dc03afe393",
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
              "id": "136ba62d-bf8f-4e30-8c9f-ebed08b0eee8"
            }
          ]
        },
        {
          "id": "b9f5bfdb-1ca1-4ee2-bdda-75d7ceb80253",
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
              "id": "dfbf4aeb-3107-4fed-8cc8-b7fbc0086fbb"
            }
          ]
        },
        {
          "id": "bf84ce9d-61cd-4127-b727-5f6ce898b541",
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
              "id": "3bd00250-ee20-4b7b-b7f6-82515e1792f4"
            }
          ]
        },
        {
          "id": "7ef9a17d-1607-4d67-98fc-4bbc2667bddc",
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
              "id": "c702795f-8454-4c15-907d-ea1dd72f2e20"
            }
          ]
        },
        {
          "id": "c1fd1255-7452-49a4-814a-51ca38bc1b37",
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
              "id": "22622ad7-d91b-4578-9e90-013ed2ab68d1"
            }
          ]
        },
        {
          "id": "03b348bb-4b14-4431-8815-af003e04c954",
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
              "id": "ede5c3f2-1515-4b68-94fb-ef05692b94ef"
            }
          ]
        },
        {
          "id": "e829aaaf-160e-4c5b-978e-a946f768b783",
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
              "id": "bdb63958-20f3-43b6-bcb2-ecd5d0fad5a5"
            }
          ]
        },
        {
          "id": "f775f6ed-338f-4e7f-90d1-8e9bc57d20b4",
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
              "id": "991c6daf-da09-4ae2-a6dd-4d36890c1875"
            }
          ]
        },
        {
          "id": "97e3627e-f263-4625-8e07-b8eed543f846",
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
              "id": "fe08d91c-4a6e-415c-befe-2d499d87531c"
            }
          ]
        },
        {
          "id": "cc0a4b6a-91a7-41cd-8f95-cdf132dba815",
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
              "id": "2d61d5b6-2fab-401f-806c-69391051e306"
            }
          ]
        },
        {
          "id": "91f4d422-03a7-47e4-99e1-40e0d30ce167",
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
              "id": "5f1c7586-822f-4a34-a194-ca96cbd136b4"
            }
          ]
        },
        {
          "id": "a12133ea-6de0-496d-a39a-dd12e599b5fb",
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
              "id": "8851de3d-80de-4572-8e67-7315d61f8481"
            }
          ]
        },
        {
          "id": "3cd3293e-189f-44e3-ab16-1c08ef5993ba",
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
              "id": "b223e25d-32b8-4291-a3a1-01593f389a33"
            }
          ]
        },
        {
          "id": "01d5a6fd-08d2-42e4-a134-7022d460ef9b",
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
              "id": "38a6e672-e0e9-4088-a6b2-3d8626078723"
            }
          ]
        },
        {
          "id": "42a0ee02-c797-44ca-9a3f-9363125aaf91",
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
              "id": "e3a4668f-f191-41ff-a697-d95f8cfa8cb4"
            }
          ]
        },
        {
          "id": "b741d66f-53ca-4694-8bd1-58677436d85e",
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
              "id": "7898569e-65c1-493c-acac-841080ed7ca3"
            }
          ]
        },
        {
          "id": "1d692dd8-e90e-4299-8518-1b8b30343008",
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
              "id": "d0c1bf46-c3ae-4bd7-93e0-9a65d43c940d"
            }
          ]
        },
        {
          "id": "51161c6f-bf75-4c2e-9986-6d0281065bfa",
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
              "id": "e8dd058f-ba32-4adb-bd53-67cd7e7b8477"
            }
          ]
        },
        {
          "id": "7f919b2d-dbad-44d2-b377-6529b3f974ba",
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
              "id": "a868ad86-e039-43a0-92ee-9f9c3e5257b8"
            }
          ]
        },
        {
          "id": "5ce5b8b9-c95f-420c-8ac0-7792ac1710a1",
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
              "id": "5007618c-677d-42eb-a6b7-f99009cf3a7e"
            }
          ]
        },
        {
          "id": "b655e0a3-090b-4031-ac60-8c450c421dca",
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
              "id": "39b60da6-282e-4f72-bdf8-4febd9439f80"
            }
          ]
        },
        {
          "id": "eab1fb1a-0b69-4453-947a-8b8d9713d5bc",
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
              "id": "c72f8b85-bddb-445d-b051-3651710f9725"
            }
          ]
        },
        {
          "id": "e04729a2-4f11-49ff-8d29-6b11296cc8b9",
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
              "id": "654e4529-643e-4fc1-8842-854ea21152f7"
            }
          ]
        },
        {
          "id": "55a9a66f-3cd5-48b6-a90a-86d58ed3196a",
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
              "id": "08e6a46b-0747-4118-a6b9-0689e40a3e70"
            }
          ]
        },
        {
          "id": "33e49776-bd7f-4474-85c7-f2998721cb6b",
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
              "id": "de323c4c-540f-491a-89f7-9f6dda6b4d54"
            }
          ]
        },
        {
          "id": "f00f35a3-6ebc-4ec1-acbc-0f768a9544f4",
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
              "id": "ddb59244-7cc2-49ad-a595-67f85f254239"
            }
          ]
        },
        {
          "id": "3f264ec6-06cb-44b9-9e30-753f9b038b7d",
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
              "id": "c7a68f93-d815-44aa-ba3a-a58587e7b917"
            }
          ]
        },
        {
          "id": "900aa4e0-4085-4b1e-be42-9a2e8b299c7c",
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
              "id": "83f57bc6-c524-4430-bcd1-436c979b7fed"
            }
          ]
        },
        {
          "id": "d705f41c-8333-4eed-a329-e2a3a471eac6",
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
              "id": "676c99c8-fdc3-4fcb-8f53-c3d1b741f6c8"
            }
          ]
        },
        {
          "id": "fdbdcbc6-cb1c-43f5-8f53-b50bbe6db064",
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
              "id": "c16e2095-5382-43f6-b69c-63264594b68d"
            }
          ]
        },
        {
          "id": "cf33a41c-8c68-4e9f-8c3c-c3589ba6599e",
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
              "id": "30e9751e-6e0a-4557-b19a-8b8caa536b9c"
            }
          ]
        },
        {
          "id": "94be70a6-780a-446c-9a2f-86daf62c6aa5",
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
              "id": "b44efa95-0dde-457f-af89-f2ee1ab4c4af"
            }
          ]
        },
        {
          "id": "1817bdba-4179-4096-a375-edab793772c4",
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
              "id": "6f1b7a8c-b7c2-4eff-92aa-6b282b90152b"
            }
          ]
        },
        {
          "id": "fd6cf204-3464-484e-b34a-7055b7c0ef16",
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
              "id": "834de0ce-6f69-4375-9cec-557a71a95beb"
            }
          ]
        },
        {
          "id": "ed1f6650-ac08-4805-bcb3-e1097449fb2b",
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
              "id": "922c70cf-af71-4517-84ef-27f3ee07e7af"
            }
          ]
        },
        {
          "id": "0f59be3e-6c4c-4e15-8c1f-3a011f499858",
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
              "id": "ab3f629e-481f-4328-bac2-c92501de2d6a"
            }
          ]
        },
        {
          "id": "eb43f9f9-7188-43d8-b431-2b113d2dce2f",
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
              "id": "f62c3471-c531-40da-a768-c444c4e1c8b3"
            }
          ]
        },
        {
          "id": "2e2c23d6-f266-4121-8ee7-3594e7a54969",
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
              "id": "a501c25d-f463-43c9-a6e4-ddb2891a1b9c"
            }
          ]
        },
        {
          "id": "68cc73d1-4072-464a-8bde-96ea0d0c17ff",
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
              "id": "167c0d9d-03ce-403c-854e-34889b242874"
            }
          ]
        },
        {
          "id": "08be7139-5e85-4dea-9217-2b80bb99d4e6",
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
              "id": "2acffb13-8e8d-4d1f-8aac-4621d5eb31f6"
            }
          ]
        },
        {
          "id": "e4eb960a-284e-4bba-bc90-ad9a843db5dc",
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
              "id": "f03afa62-b60f-42c8-8605-677e41d20681"
            }
          ]
        },
        {
          "id": "2fbb48e7-c7b6-4d8c-99f8-3e54e0e251fe",
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
              "id": "f9695f1d-7eaa-4ab7-b48f-c9d52d76dc08"
            }
          ]
        },
        {
          "id": "f85270f5-663b-459c-99e4-429b79752b3c",
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
              "id": "74bbb2fe-4bc6-4a8f-b211-3fd050d1ca7e"
            }
          ]
        },
        {
          "id": "bc5aa29e-230c-45ae-a451-c0c2ccb0b0b2",
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
              "id": "e63f99d9-e4d5-4cce-bf3b-d6fe55428562"
            }
          ]
        },
        {
          "id": "589d00c4-00f7-488e-9ab0-f5f4d34de358",
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
              "id": "2a0fe789-d6f4-46f7-8be4-3b269e31d94f"
            }
          ]
        },
        {
          "id": "da7f5ce9-55ee-4499-b4e5-ed5c38736e44",
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
              "id": "6a814274-7bc9-4a3d-a133-d40b5d54b61d"
            }
          ]
        },
        {
          "id": "93cf8a31-1b47-4631-95db-84cf6ca6b96c",
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
              "id": "7f670186-bcae-4845-9d80-391ca1dfcb96"
            }
          ]
        },
        {
          "id": "1f301e34-7de9-4902-8efe-95c4d165e0be",
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
              "id": "f5d62734-e004-48b6-a231-561bb2dc8c64"
            }
          ]
        },
        {
          "id": "64d67d5f-34d7-4c5f-8373-588dacc171e2",
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
              "id": "21b4151e-1b43-487e-94a3-cb0cd5c97593"
            }
          ]
        },
        {
          "id": "608a0795-fa71-46d6-9a38-5960b28e84ba",
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
              "id": "3265d32d-de69-4aba-973b-66f1eb70d46f"
            }
          ]
        },
        {
          "id": "ba516fc7-d4f7-4fdb-9414-d82660e66f3b",
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
              "id": "d5b2052c-335c-469c-a7af-fce85e3c43cf"
            }
          ]
        }
      ]
    },
    {
      "name": "Stream",
      "item": [
        {
          "id": "8795b854-08c4-4576-bdf9-81e40d75c231",
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
              "id": "0969d9d4-1aca-4aa4-8234-895244b6f3e8"
            }
          ]
        }
      ]
    },
    {
      "name": "Deliveryformat",
      "item": [
        {
          "id": "220773ed-9e25-4044-ae13-188bb4e93e9c",
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
              "id": "52837694-e48b-4f8b-84bd-a7227418386e"
            }
          ]
        }
      ]
    },
    {
      "name": "Audience",
      "item": [
        {
          "id": "be7cd9bc-5c27-4b17-b4eb-3f1300c1a446",
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
              "id": "e225ee4c-5b4e-4694-a983-2ed2f5017642"
            }
          ]
        }
      ]
    },
    {
      "name": "Clients",
      "item": [
        {
          "id": "fa0b584b-fdab-4343-b099-f647c11b3c62",
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
              "id": "2a07e520-7163-424a-b2c3-7331db7efd8a"
            }
          ]
        }
      ]
    },
    {
      "name": "Feo",
      "item": [
        {
          "id": "95a759a3-4498-4c71-8438-f837261a9e8c",
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
              "id": "44557211-836a-4802-86bf-0657adaaee91"
            }
          ]
        }
      ]
    },
    {
      "name": "Imaging",
      "item": [
        {
          "id": "ffb5d3c7-f964-4108-8973-54a8cabb3420",
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
              "id": "102afd80-3ef0-467e-a7f9-6b61b505d39a"
            }
          ]
        },
        {
          "id": "663d0da7-6adc-4b38-abaf-59be1b019a41",
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
              "id": "81f1c925-314a-4e7c-8831-97d3d643afd4"
            }
          ]
        },
        {
          "id": "6f908b8d-5b36-4e6f-91bd-a70984d88c50",
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
              "id": "8d853f33-d361-46d5-9847-07a0f666c8d8"
            }
          ]
        },
        {
          "id": "7403541d-cf1d-49a5-a865-e0b509a13cfc",
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
              "id": "4993315e-79c4-4384-914a-e5fe4b41b76d"
            }
          ]
        },
        {
          "id": "b4f89aee-c325-472a-9691-5c339707abfc",
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
              "id": "4859983e-c372-40af-a009-b12221f9f969"
            }
          ]
        },
        {
          "id": "cb00c023-eec6-49f7-aba9-4759b01c14bd",
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
              "id": "68addfa2-f788-41cc-b45e-18e056204081"
            }
          ]
        },
        {
          "id": "481036b1-af53-433d-814b-655c181bc351",
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
              "id": "86aadc9f-733c-430b-b8b7-06eb6ac52f70"
            }
          ]
        },
        {
          "id": "05ca66a3-a5a0-4e5b-8d76-053304a57dfa",
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
              "id": "6020398a-1eb6-4206-b4b1-4ca5b33f754c"
            }
          ]
        },
        {
          "id": "8cda5492-8cc7-4247-b4cd-40ac0ed4bb07",
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
              "id": "6762a0d9-b9b3-4896-9e6b-db999e15e113"
            }
          ]
        },
        {
          "id": "97b0e63f-c2c2-4a73-b9c0-091f63d9bbe2",
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
              "id": "4e531cef-52bc-424d-a1f9-3da6ee787922"
            }
          ]
        },
        {
          "id": "691c1e7e-90fe-4ce8-b436-99910a3b7802",
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
              "id": "f067ab54-5aec-4cbd-bb5e-70cf1f85bc37"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "2423d99d-b759-4fb7-ae7e-762a67d80020",
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
              "id": "11ec7a3a-9fb4-4be8-a53f-e01e88e352dc"
            }
          ]
        }
      ]
    },
    {
      "name": "Images",
      "item": [
        {
          "id": "601b094b-df5f-4578-ab36-367343c4202c",
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
              "id": "4a239c94-f7cb-4601-8e0a-4778b7fe91f1"
            }
          ]
        }
      ]
    },
    {
      "name": "Invoicing",
      "item": [
        {
          "id": "2fd25578-57c7-44e0-9fcc-1140d85d7501",
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
              "id": "7edf680b-2048-43b5-8ce3-643fba368e75"
            }
          ]
        },
        {
          "id": "a0262158-8642-4e25-a88c-ac811856a00f",
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
              "id": "15acc821-a2ea-4e8b-a5aa-5510054e70c5"
            }
          ]
        },
        {
          "id": "9248bb0c-89d6-4c8a-82ea-847039484582",
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
              "id": "bb0f7157-832b-462f-a4bf-811acb21fe53"
            }
          ]
        },
        {
          "id": "27e1fc58-83de-417b-8e85-41462ac8d293",
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
              "id": "8bcde0d1-88bf-4715-8bf3-645bd67e45d3"
            }
          ]
        },
        {
          "id": "8d0e5853-deb8-4c22-ab7d-d67dc71bcb46",
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
              "id": "83da2072-4470-428c-9f73-15037c4f3ae2"
            }
          ]
        },
        {
          "id": "56aaa9be-6852-44e5-986b-317f36c66137",
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
              "id": "69eda808-c518-41f4-9577-0d65ae7ec193"
            }
          ]
        },
        {
          "id": "829e30fb-a5f5-4657-86a0-e3c84bb39315",
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
              "id": "3c6b9124-61ec-406a-aceb-9681ed808ce2"
            }
          ]
        },
        {
          "id": "25e6ed1f-6539-43bf-a278-60497c6f5c97",
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
              "id": "e6043dcc-5594-4691-8626-9683482b2f0e"
            }
          ]
        },
        {
          "id": "490eeafd-f42a-45b6-9083-71cc70fcb9be",
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
              "id": "b3ec81e0-08b5-445d-b349-0d083907ab27"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "7279ac17-f19f-45e1-95e3-2d7f4c4ea41a",
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
              "id": "aa58e6cf-4c1d-4764-9e53-94acaf1ba9bb"
            }
          ]
        }
      ]
    },
    {
      "name": "Configurations",
      "item": [
        {
          "id": "400c1d86-8569-44ae-be9b-4460dd107978",
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
              "id": "99d5709c-e5fb-40e5-b2f9-0e8697e983dc"
            }
          ]
        },
        {
          "id": "ce494971-edf2-4053-858b-61c83e9c3018",
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
              "id": "b433a2ab-55dd-4d29-a4bc-81a29d0daa3b"
            }
          ]
        },
        {
          "id": "84913b16-d90e-4f1f-91a0-3a0d1cd768f0",
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
              "id": "06df3d44-ec0c-4a15-b3fa-356ad65e98c0"
            }
          ]
        },
        {
          "id": "f253591e-f8fc-4119-b562-af90311d2eee",
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
              "id": "1d8ab1fe-1431-4295-947e-266a1b1858f8"
            }
          ]
        },
        {
          "id": "5c2061f4-d4da-43b3-b95b-6ab217dffd79",
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
              "id": "d51bab17-f363-4abb-bddf-968b8d7ca90a"
            }
          ]
        },
        {
          "id": "acf7ae44-fa15-423c-8a52-84e5d8cccca2",
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
              "id": "ca4a5c50-6a37-49ac-b054-85988da523ed"
            }
          ]
        },
        {
          "id": "8456dfa7-6ec5-40fd-bf17-42b7bd4444d7",
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
              "id": "ff758fb8-7eb9-4263-aab0-ca0881b6f8e6"
            }
          ]
        },
        {
          "id": "9d1160ae-4458-4813-b9da-62d9351586cd",
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
              "id": "6e763e76-c29b-465a-b153-0a919d6419d7"
            }
          ]
        },
        {
          "id": "8f615bbc-202c-4375-91fc-e4e4caef0517",
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
              "id": "f323cf74-b683-47c8-9f24-d795dacf5765"
            }
          ]
        },
        {
          "id": "aec3f1af-1778-4bd9-8ebe-34b454b37bc0",
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
              "id": "743ee86e-fefe-4076-b199-64ba5d6531be"
            }
          ]
        },
        {
          "id": "477f0b87-8972-483d-94cb-282c030802c7",
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
              "id": "fc6fd380-cf12-4ed4-8431-7732cd78f165"
            }
          ]
        },
        {
          "id": "6cb5d80c-c008-44f7-925a-8d1414db8dff",
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
              "id": "b27e4dc8-057c-458d-9c9b-686e10098efa"
            }
          ]
        },
        {
          "id": "ff636585-3237-455b-8a8b-880eb2d036ba",
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
              "id": "0b691888-a8c3-44a7-8e1d-3cdd5b349e2a"
            }
          ]
        },
        {
          "id": "cd725471-9966-46b2-90e4-22be8180a8c7",
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
              "id": "988438a7-8cbe-4063-8f12-52d087232443"
            }
          ]
        },
        {
          "id": "b85869c5-70e9-49c0-b65e-80ccff92a980",
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
              "id": "b2cbab75-1636-40ec-ad48-d7e07d68aa1c"
            }
          ]
        },
        {
          "id": "b422f7fe-7551-4b89-b05c-b6314aea0774",
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
              "id": "764c220c-8905-404c-b644-d55ee110aa0c"
            }
          ]
        },
        {
          "id": "f5f990e2-b312-42fa-93a1-5d956b5dadf3",
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
              "id": "f35b775d-27ac-46b4-bf73-288df4f1b349"
            }
          ]
        },
        {
          "id": "6773fadd-e589-46aa-baab-e7a7be5d1e49",
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
              "id": "20a762a8-359d-4df0-be49-3b2aece20f6f"
            }
          ]
        },
        {
          "id": "8a505427-3dbc-4b0e-91e0-95a7fe1f8248",
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
              "id": "6f5cb5f0-e92d-4e07-baec-b448ec755521"
            }
          ]
        },
        {
          "id": "1008c397-8d4c-45b7-bba0-c552152b4d45",
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
              "id": "2545713d-6b3b-4d48-9606-8daf87f975d3"
            }
          ]
        },
        {
          "id": "f33cbc24-9dc1-4ee5-b3bb-8f7026f9dc01",
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
              "id": "99f65dbc-0a62-42f4-9d11-8683e2392036"
            }
          ]
        },
        {
          "id": "890ee1db-7abc-45a1-9610-dd530eccc386",
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
              "id": "6291c256-5fd1-443c-901b-30688d3d1956"
            }
          ]
        },
        {
          "id": "70e52484-661f-4415-b6d0-b6671beb4525",
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
              "id": "dcaf56d9-b2ad-4dda-bea5-45075ea84001"
            }
          ]
        },
        {
          "id": "24322172-9e8a-46ea-8372-699c882a1215",
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
              "id": "7368dd3e-175f-4f98-887e-aef0260d5e94"
            }
          ]
        },
        {
          "id": "fc85b0be-dffb-4d12-8786-1882e4b7e413",
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
              "id": "66939dfc-35de-4fde-8947-1653f68798f3"
            }
          ]
        },
        {
          "id": "d296f6d8-bc0e-4308-91dd-e481dd2cae28",
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
              "id": "ece9c3f2-8844-4e11-868f-61e67198ad85"
            }
          ]
        },
        {
          "id": "e2a24f70-263e-4e04-ad90-be01a054eeac",
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
              "id": "f4fafb5c-5691-4b64-8808-efbca2f89324"
            }
          ]
        },
        {
          "id": "c5571884-c404-4653-92db-1292f4486b79",
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
              "id": "25ef79d9-d7ae-4126-be3d-6eb76f35b14f"
            }
          ]
        },
        {
          "id": "8ca57b4c-ae6f-4ffa-9577-121bc286a567",
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
              "id": "e03dac04-774f-4867-af24-57a25522cfdf"
            }
          ]
        },
        {
          "id": "2d22ed04-7daa-4c01-9b5b-a38ce8ac67c9",
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
              "id": "ce6ad0cc-814f-4625-b281-e7325203e2f4"
            }
          ]
        },
        {
          "id": "fb6ad25c-d73e-4580-a57c-b2bd85ec16b4",
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
              "id": "5783f4f3-6175-4529-87df-c19d23aab3dd"
            }
          ]
        },
        {
          "id": "521f784f-e2b9-46e8-91f8-d0da7f2a5334",
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
              "id": "82d59ad1-1fe0-49bf-b9e5-dcab241a8479"
            }
          ]
        },
        {
          "id": "18508bac-59ff-4b64-86c4-6464e73d7ad4",
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
              "id": "adbbde90-e950-4271-a418-9f985bf79222"
            }
          ]
        },
        {
          "id": "91e0e341-f21a-4e8f-ad20-47619fd1c0b2",
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
              "id": "4213860b-9ca7-41b5-b8f2-c459031c3f82"
            }
          ]
        },
        {
          "id": "5946bf04-5134-4f10-acb7-5b8e3f91d437",
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
              "id": "2475ebc9-564e-49cf-b232-066e178be0d0"
            }
          ]
        },
        {
          "id": "f3ade440-49f5-4f08-98f2-f67b559fd61a",
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
              "id": "98f150b3-0513-4395-8213-fce75a679002"
            }
          ]
        },
        {
          "id": "8204579f-5528-43df-8873-96ad08cdec0e",
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
              "id": "e2397b8e-e22f-4c6e-89ee-30bc2669cb31"
            }
          ]
        },
        {
          "id": "c3733517-dde2-435f-9479-99eb5f3385bb",
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
              "id": "b1fc9fb0-a9e9-494e-b707-96379bb75e38"
            }
          ]
        },
        {
          "id": "093fe966-f1f3-42ce-b086-da3955656f73",
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
              "id": "bfccc1f8-373a-47f9-9d05-4aa8967e5f60"
            }
          ]
        },
        {
          "id": "0b0e4873-86c8-47f6-953a-f6ff361683be",
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
              "id": "19f27255-6839-49b7-b874-6439012a3cac"
            }
          ]
        },
        {
          "id": "939d039a-305f-4f12-9dcc-45459f5f7afb",
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
              "id": "7c53bb19-1938-4f28-b5f3-d11317f66bed"
            }
          ]
        },
        {
          "id": "7d8fbb65-ce73-4f82-9fc3-7f583bc9b0eb",
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
              "id": "e618c6b6-69f0-4803-8f75-e4365262f577"
            }
          ]
        },
        {
          "id": "5129163c-09d4-407f-b15a-c20d6c9d7988",
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
              "id": "1d3c63f4-869b-49be-937a-f420a8983c46"
            }
          ]
        },
        {
          "id": "f16b970e-7051-43dd-8f0c-eda1076e293e",
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
              "id": "82e5bd62-b445-41fb-a9d4-61968d345c42"
            }
          ]
        },
        {
          "id": "90bbb54e-e12f-42e6-89a2-a97ed3fa64a5",
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
              "id": "1ab7a173-59e4-4a7b-ac75-0888b7533f6f"
            }
          ]
        },
        {
          "id": "eacb5462-9501-429e-87e9-e7071ea12a6b",
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
              "id": "4675e07f-791d-4139-92ea-3ba8d28da823"
            }
          ]
        },
        {
          "id": "ed3ffca4-7398-4a75-9ee1-543c27c58bc0",
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
              "id": "b852c2ed-8fcb-44c1-914a-3f6c0bdd6d27"
            }
          ]
        },
        {
          "id": "ae9b17c4-8907-464e-84ec-e77291885113",
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
              "id": "7638c393-70af-4afe-b459-8097c51e8fe6"
            }
          ]
        },
        {
          "id": "02026586-7816-41d5-983f-9c0a2813c048",
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
              "id": "f88ebc44-0cc6-4124-8638-5f771d441b71"
            }
          ]
        },
        {
          "id": "9f7c641a-7047-4304-8e31-f337217ed04d",
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
              "id": "0ec09d09-51bc-4bed-9b3c-9d3479a2d4f7"
            }
          ]
        },
        {
          "id": "a1b44126-6353-4c9d-9316-8bf552413560",
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
              "id": "299ac35c-a4f6-43db-bfae-a334a0ea5ff2"
            }
          ]
        },
        {
          "id": "96b756f8-3076-4e4b-9949-41fb0d51619a",
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
              "id": "4ae28cb4-aacb-448b-a3e3-ddff0b77cae3"
            }
          ]
        },
        {
          "id": "006b011e-50fd-4512-a043-397e8dc88c63",
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
              "id": "1e7c891d-b093-4be5-beb5-cf4a526650e1"
            }
          ]
        },
        {
          "id": "eee151ec-dda9-4efd-9ba1-cfe5f01f2a3b",
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
              "id": "03d10e86-f593-47e3-bce4-455c660490b8"
            }
          ]
        },
        {
          "id": "f79752b9-c297-42a6-a9bb-5113a2c665eb",
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
              "id": "d68bc721-2a98-48dc-8fcf-701bd89dc4dd"
            }
          ]
        },
        {
          "id": "774fda6f-9748-4161-b7cd-24d843c4e814",
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
              "id": "7246af50-8366-4135-b646-19c46543af4d"
            }
          ]
        },
        {
          "id": "66544fe9-1215-4290-bd4d-155c4d59effd",
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
              "id": "c7cfe279-13dd-416a-9e7f-a1490a1f3561"
            }
          ]
        },
        {
          "id": "97cb85fa-7f12-4b2c-ad49-292ae13e2579",
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
              "id": "7d671566-fdcd-489b-8cfa-c6bd15c473d7"
            }
          ]
        },
        {
          "id": "daf83ce2-c83f-44c5-9c64-6b5489774bbc",
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
              "id": "72202551-59ff-4b87-92b3-77c186024bb8"
            }
          ]
        },
        {
          "id": "e3aeba8d-863e-4bb6-bb27-003017d998e2",
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
              "id": "8133d36f-6ca2-4a46-98bf-d7a2815874f6"
            }
          ]
        },
        {
          "id": "159e2757-7b75-4869-a07a-3816dbbec234",
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
              "id": "8d8867be-1587-4148-b3b2-904ef3692d24"
            }
          ]
        },
        {
          "id": "ca3fea05-c1ad-449c-aa48-2bf356c39878",
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
              "id": "2f5d4c0e-760e-45bd-a0a4-1f1e4a7fd1eb"
            }
          ]
        },
        {
          "id": "d06eae6d-bd29-4073-bf61-34129a964033",
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
              "id": "d4b690ea-2192-4868-b194-1bb2644568cb"
            }
          ]
        },
        {
          "id": "afbb768b-7f82-49e9-bafa-89542d097c50",
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
              "id": "4698ce7e-fe7a-42d9-8177-976f7a496a39"
            }
          ]
        },
        {
          "id": "5a00c5eb-7ba5-456d-8ad8-d3cadf44912c",
          "name": "configgtmv1domains",
          "request": {
            "url": "http://developer.akamai.com/config-gtm/v1/domains/",
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
              "id": "3283755c-972a-459b-8174-c6c9f061f561"
            }
          ]
        },
        {
          "id": "c1cc835e-d0ed-43b0-8083-dfbee4b56426",
          "name": "configgtmv1domainsdomain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain"
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
              "id": "911981b2-dcb6-42dc-ab51-c6b56396524d"
            }
          ]
        },
        {
          "id": "c4e3ae42-8d0d-4633-8663-a2fdcf28f53c",
          "name": "configgtmv1domainsdomain",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain"
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
            "description": "Create or Update a Domain"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "be92dcbc-4a0e-44a2-8d53-1b4e068ad089"
            }
          ]
        },
        {
          "id": "8d3ae769-6761-41d2-bbaa-4c2e96bc3dde",
          "name": "configgtmv1domainsdomaindatacenters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/datacenters"
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
            "description": "List Data Centers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24e6eea2-582e-495a-b26e-3c67d65fa25e"
            }
          ]
        },
        {
          "id": "3f628b67-649f-4a27-a039-ad096102a120",
          "name": "configgtmv1domainsdomaindatacenters",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/datacenters"
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
            "description": "Create a Data Center"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "79e5663a-47ba-4417-8dae-3d79e47a6757"
            }
          ]
        },
        {
          "id": "d583b630-e4be-48ab-9d7e-14669c7c1046",
          "name": "configgtmv1domainsdomaindatacentersdatacenterid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/datacenters/:datacenterId"
              ],
              "variable": [
                {
                  "id": "datacenterId",
                  "value": "datacenterId",
                  "type": "string"
                },
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
            "description": "Get a Data Center"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8d23b30-18cf-4129-afbb-5dd759c146c2"
            }
          ]
        },
        {
          "id": "92e74a52-8747-464a-a3ab-dadb21c2be78",
          "name": "configgtmv1domainsdomaindatacentersdatacenterid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/datacenters/:datacenterId"
              ],
              "variable": [
                {
                  "id": "datacenterId",
                  "value": "datacenterId",
                  "type": "string"
                },
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
            "description": "Update a Data Center"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0caa91b1-1f0d-4ee2-9f83-8ad3a8db56bb"
            }
          ]
        },
        {
          "id": "c82a414c-09d9-4689-b5cf-8982efd0ce4b",
          "name": "configgtmv1domainsdomaindatacentersdatacenterid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/datacenters/:datacenterId"
              ],
              "variable": [
                {
                  "id": "datacenterId",
                  "value": "datacenterId",
                  "type": "string"
                },
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
            "description": "Remove a Data Center"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "85245994-21a5-4a76-888c-b8fe5e8db25f"
            }
          ]
        },
        {
          "id": "a686c834-71f2-4925-8539-206f2dbce698",
          "name": "configgtmv1domainsdomainproperties",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/properties"
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
            "description": "List Properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3058fea3-1e21-4dde-a684-6ba642aa2f36"
            }
          ]
        },
        {
          "id": "465ee6f8-f2cc-4225-a07a-2babacf56c88",
          "name": "configgtmv1domainsdomainpropertiespropertyname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/properties/:propertyName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "propertyName",
                  "value": "propertyName",
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
              "id": "9db04697-364a-4a1b-b03c-38c4fb4ea506"
            }
          ]
        },
        {
          "id": "8204d940-575d-489e-9950-dd414450ea0b",
          "name": "configgtmv1domainsdomainpropertiespropertyname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/properties/:propertyName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "propertyName",
                  "value": "propertyName",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Create or Update a Property"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "964f2efc-fddd-44e2-93c1-0cf763c4531a"
            }
          ]
        },
        {
          "id": "692c9b7c-1e82-45d6-b31b-e8d433ef9482",
          "name": "configgtmv1domainsdomainpropertiespropertyname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/properties/:propertyName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "propertyName",
                  "value": "propertyName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Property"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69c95133-f3bc-44b8-b16e-74bf002fc07f"
            }
          ]
        },
        {
          "id": "309e8257-f340-416e-815d-1b301f9c2bd8",
          "name": "configgtmv1domainsdomainresources",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/resources"
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
            "description": "List Resources"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "586db51a-e740-49a1-a078-a46662ded686"
            }
          ]
        },
        {
          "id": "92f65598-06f2-4135-a2f4-cf2aba4ba5a1",
          "name": "configgtmv1domainsdomainresourcesresourcename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/resources/:resourceName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "resourceName",
                  "value": "resourceName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "97ec2556-1a50-455b-adf8-eef34890290b"
            }
          ]
        },
        {
          "id": "c695b5fa-f40a-49ef-ad57-4f821e8e6b08",
          "name": "configgtmv1domainsdomainresourcesresourcename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/resources/:resourceName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "resourceName",
                  "value": "resourceName",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Create or Update a Resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b73a6e87-5e0b-4ba0-9680-98a16e25402b"
            }
          ]
        },
        {
          "id": "3cd5b74d-0a0a-464f-87b6-2133d56c77fd",
          "name": "configgtmv1domainsdomainresourcesresourcename",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/resources/:resourceName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "resourceName",
                  "value": "resourceName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Resource"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "48dc9494-f6c3-494f-8c20-14d0ecf0f45f"
            }
          ]
        },
        {
          "id": "24bf3938-4835-443e-aba8-c2312cdbd1ba",
          "name": "configgtmv1domainsdomaingeographicmaps",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/geographic-maps"
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
            "description": "List Geographic Maps"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7b391590-3e31-4393-bf6b-7885123a3e85"
            }
          ]
        },
        {
          "id": "31b90e50-18a3-44c3-8afb-707a7ffa2a76",
          "name": "configgtmv1domainsdomaingeographicmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/geographic-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Geographic Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c51df872-e7af-4d25-88c7-2c1a9ab6bdce"
            }
          ]
        },
        {
          "id": "e03075b5-0e78-44e0-a30d-40545ed9691d",
          "name": "configgtmv1domainsdomaingeographicmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/geographic-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Create or Update a Geographic Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e11c5326-c06a-410e-adac-f3771b91749b"
            }
          ]
        },
        {
          "id": "48d2f1da-a959-4632-8f64-9cace979cac2",
          "name": "configgtmv1domainsdomaingeographicmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/geographic-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Geographic Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3db25519-98ae-45f4-8c19-4d7b7247e948"
            }
          ]
        },
        {
          "id": "d630ca79-be1a-4440-9bdc-fd504f8eec88",
          "name": "configgtmv1domainsdomaincidrmaps",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/cidr-maps"
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
            "description": "List CIDR Maps"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "71021d95-bb0a-42b9-80e8-1106a1425732"
            }
          ]
        },
        {
          "id": "2535757c-dc1c-4b23-96e8-b4eaf455eae4",
          "name": "configgtmv1domainsdomaincidrmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/cidr-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a CIDR Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd3bbf0e-2721-49f7-b465-1dbe18c60d84"
            }
          ]
        },
        {
          "id": "98702fe1-3bf0-4c98-9466-02ab6ad0ce56",
          "name": "configgtmv1domainsdomaincidrmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/cidr-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Create or Update a CIDR Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d394622d-3b8c-470a-9cad-6a74354ef447"
            }
          ]
        },
        {
          "id": "5bd6cbd7-338a-4fcc-93ca-b4739ca6b74d",
          "name": "configgtmv1domainsdomaincidrmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/cidr-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a CIDR Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "435dfd9d-925c-44a3-87ba-61f5bd332f9b"
            }
          ]
        },
        {
          "id": "27fe4e3e-332d-4729-80db-a8a8f771759b",
          "name": "configgtmv1domainsdomainasmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/as-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an AS Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59874e93-d8eb-4cb7-8702-accf2abf0999"
            }
          ]
        },
        {
          "id": "f959ac43-85f7-4bf2-a539-18a773ba0079",
          "name": "configgtmv1domainsdomainasmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/as-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Create or Update an AS Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8e299d97-e859-4245-9c4f-1a6872586bb0"
            }
          ]
        },
        {
          "id": "65cfe7f5-606a-4a9f-98a7-6521c3c439a1",
          "name": "configgtmv1domainsdomainasmapsmapname",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/as-maps/:mapName"
              ],
              "variable": [
                {
                  "id": "domain",
                  "value": "domain",
                  "type": "string"
                },
                {
                  "id": "mapName",
                  "value": "mapName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove an AS Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bab73621-660e-4e9e-969b-95ca84a58eb8"
            }
          ]
        },
        {
          "id": "de4776fe-f1f6-4a2b-b102-c81b6f75131f",
          "name": "configgtmv1domainsdomainstatuscurrent",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "config-gtm/v1/domains/:domain/status/current"
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
            "description": "Get Current Status"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "311d8ff1-746e-4691-b552-6a09588e3aa8"
            }
          ]
        }
      ]
    },
    {
      "name": "Service",
      "item": [
        {
          "id": "037be960-6a97-4a64-8100-4b2d6f9ea197",
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
              "id": "dd6a06eb-ef77-4089-bc34-91ae3708da3d"
            }
          ]
        },
        {
          "id": "9f994df8-1313-4248-9ae4-fe069e885e01",
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
              "id": "2f7962c7-0b85-4e2f-90e1-c39c192da3b7"
            }
          ]
        },
        {
          "id": "0bb5cb0d-f665-4be1-ab59-1d7ab4969eb9",
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
              "id": "ab496f14-3171-4349-a225-8cb2cebb3323"
            }
          ]
        },
        {
          "id": "e1e6e9d7-d0fe-45d3-90e8-4ae8996ce3b7",
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
              "id": "c4bd7f61-fb24-4302-b60f-fbfdbf5dfe87"
            }
          ]
        }
      ]
    },
    {
      "name": "Services",
      "item": [
        {
          "id": "78ac2372-c4d9-45eb-8909-2f51478fd937",
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
              "id": "25c3fbab-b35f-4844-bd30-e0a24d4dfc09"
            }
          ]
        }
      ]
    },
    {
      "name": "Lds",
      "item": [
        {
          "id": "1a7f1ec2-5312-462c-b91a-9732821ebf4d",
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
              "id": "2ff50144-1429-4ab7-8914-a882d1fb7236"
            }
          ]
        },
        {
          "id": "c4f5b8aa-f946-493e-9700-46815fa1a401",
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
              "id": "4e1d616e-eccf-404a-8229-c7748a8e7e4a"
            }
          ]
        },
        {
          "id": "0ef81baf-3243-4fde-832a-96edd7f03d3a",
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
              "id": "07a44e3f-f7d6-4a35-9bac-3e3313f321a5"
            }
          ]
        },
        {
          "id": "fd83e82f-adf1-47ec-98ef-64a6ff1e1264",
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
              "id": "2d232286-f234-4857-9376-2b1744d87cd2"
            }
          ]
        }
      ]
    },
    {
      "name": "Redelivery",
      "item": [
        {
          "id": "a575a591-3f64-4f6a-8faf-611b266dedee",
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
              "id": "f9ca8a34-56ac-4b65-a5ed-342199d295aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Key",
      "item": [
        {
          "id": "6bf92b32-6d99-4f6b-9e67-047313e519c2",
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
              "id": "12c93e4b-e6cc-493d-b692-84a34d2bad02"
            }
          ]
        }
      ]
    },
    {
      "name": "Media",
      "item": [
        {
          "id": "7cebdbb2-0b3b-4dec-82ef-8fa621e494d0",
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
              "id": "2d9b0cad-ed20-4562-84ae-37152920ff21"
            }
          ]
        },
        {
          "id": "5c8d408b-03ff-43f9-8429-bc1f3af1175a",
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
              "id": "da2d7a39-a260-4ad6-bdb3-6e641f5699f4"
            }
          ]
        },
        {
          "id": "258d3d60-2e36-4bca-ac49-64aa8deef8d2",
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
              "id": "43d8869e-c0a7-499b-8d19-e9239b9a82ee"
            }
          ]
        },
        {
          "id": "797258e3-f488-4054-be52-1042f8624322",
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
              "id": "c27257e7-f6ba-4eca-8c8a-7410949680a3"
            }
          ]
        },
        {
          "id": "88ae5f35-372f-468b-859c-97e7392ecad4",
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
              "id": "26d5f690-a8bc-4822-a354-a283360f83de"
            }
          ]
        },
        {
          "id": "d1fffe68-1a53-4502-b694-70d7988f3303",
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
              "id": "103733be-d646-4557-b04e-04d6a77940ee"
            }
          ]
        },
        {
          "id": "0f993d29-7637-4a80-ab1b-385ca94f2374",
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
              "id": "63da0fb8-3c92-460d-8666-eb603c57d52d"
            }
          ]
        },
        {
          "id": "8844e688-c7a2-469d-8624-3f45afb93155",
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
              "id": "f0b7aa62-53de-4638-bce6-1882c4fbade5"
            }
          ]
        },
        {
          "id": "6721ebfd-084a-4aa8-a4e3-4fab16292a68",
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
              "id": "82f8ca9b-2891-4c82-9332-62041a9a1b30"
            }
          ]
        }
      ]
    },
    {
      "name": "Filterparams",
      "item": [
        {
          "id": "10e62ad5-fedf-40ba-b8cc-8226735a9bc1",
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
              "id": "fe96cc9b-401b-4655-91f3-1f8b6ee67ae9"
            }
          ]
        }
      ]
    },
    {
      "name": "Network",
      "item": [
        {
          "id": "11fb7f79-33ff-43d1-88ce-1514715dc58c",
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
              "id": "8c4d34e3-0434-48a9-a570-f72b2f6cbd81"
            }
          ]
        },
        {
          "id": "f97cbe4d-04fe-43b4-b94c-d5959cb62147",
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
              "id": "e1176961-9284-499f-9b62-6bf3b539ba4e"
            }
          ]
        },
        {
          "id": "4bdc2a14-ee16-41e8-81bb-8ffc97188738",
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
              "id": "adf56481-6a39-49fc-8971-f6fa1129a096"
            }
          ]
        },
        {
          "id": "71a18b63-5fac-4885-87f3-0ec61b828da9",
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
              "id": "ee184f5f-9e2c-4c0d-a878-d484a4e67413"
            }
          ]
        },
        {
          "id": "2017f896-ca17-45de-bc06-3d1e32736c89",
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
              "id": "9e587a2c-46e2-484a-a505-544267b17338"
            }
          ]
        },
        {
          "id": "1c1d00ad-a0a2-42a1-84c7-908e1b7fedf5",
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
              "id": "cfc2acb6-29d2-479f-b7cd-4476f62ab247"
            }
          ]
        },
        {
          "id": "b254d491-ba46-48b0-9b2a-8cd83501b09f",
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
              "id": "4c9fcc25-25b4-4424-8857-0e9b9a5f6b14"
            }
          ]
        },
        {
          "id": "63dd7d0e-dc9e-4596-9706-d155ee6ad342",
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
              "id": "fcd1ec99-1935-41a1-879b-7d37c147d360"
            }
          ]
        },
        {
          "id": "18da528b-ce97-493d-8b15-dd814874acdc",
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
              "id": "99220e0d-0ceb-494d-9bce-99664943b875"
            }
          ]
        },
        {
          "id": "7f90cdb5-1096-4a7c-84f9-3d1483c29a1c",
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
              "id": "eb09c450-31e3-4f4e-8547-d0b9197bbc67"
            }
          ]
        },
        {
          "id": "c8456976-5001-4ad2-8122-7c2d149f91f8",
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
              "id": "bc0dca7d-c2f1-4a8d-ba5a-b96c9adcc5af"
            }
          ]
        },
        {
          "id": "def5bd5d-def0-43b9-8804-ffa74f84c121",
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
              "id": "d3db2552-f452-4fa9-a8f8-bcdc72cac9b9"
            }
          ]
        }
      ]
    },
    {
      "name": "All",
      "item": [
        {
          "id": "8af90448-43cf-4ee8-bb12-2dd11cca8ebf",
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
              "id": "edea49b6-e565-4b92-b7f9-e6288da4325a"
            }
          ]
        }
      ]
    },
    {
      "name": "Prolexic",
      "item": [
        {
          "id": "97a2181b-b9a9-4c3b-9abc-5d5c6d9f1168",
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
              "id": "29eb9af5-12ea-410d-9877-ecff056755c1"
            }
          ]
        },
        {
          "id": "10a545d7-c0ad-4ee7-9756-765b770ce333",
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
              "id": "e54b23d5-2305-48dd-8a05-05638c199204"
            }
          ]
        },
        {
          "id": "33063cba-552b-41a4-82a5-d6ab9b0949ad",
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
              "id": "d4e9dffc-535c-40f2-87a0-a982dea6ac76"
            }
          ]
        },
        {
          "id": "a5b3d628-dba8-4f14-ba61-a3c47e777211",
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
              "id": "87f89a11-0457-41f2-aab4-c57597d48436"
            }
          ]
        },
        {
          "id": "8cd614ee-74d7-4f63-9aea-2b2430cd8a01",
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
              "id": "c82dbe10-7906-439e-8a7f-2384e598b771"
            }
          ]
        }
      ]
    },
    {
      "name": "Type",
      "item": [
        {
          "id": "068246e9-3732-46c9-aefd-77d833a26d8c",
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
              "id": "1a49a436-a3fa-42ec-a94d-a38fbe3fd5ce"
            }
          ]
        }
      ]
    },
    {
      "name": "Papi",
      "item": [
        {
          "id": "2b1bdc73-a4f9-402a-86ca-d763cc571439",
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
              "id": "0347fb75-f21a-468b-80a3-f042c70078a1"
            }
          ]
        },
        {
          "id": "82053472-8369-419f-b1b8-1e88370fce67",
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
              "id": "8bbea032-55b7-48b2-b77f-75626e27a9a9"
            }
          ]
        },
        {
          "id": "4ee585d6-51f4-4f21-b064-18fc0a1bd858",
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
              "id": "b20f40e8-097e-416a-b857-549058e41dd6"
            }
          ]
        },
        {
          "id": "81370012-3909-41a3-a6c6-10c40139c63d",
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
              "id": "a8740a76-1d5a-49b8-8770-c766e39e78f1"
            }
          ]
        },
        {
          "id": "d28e8448-8e2d-4165-8d9d-39a93e3279ed",
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
              "id": "2849d6fa-e963-4797-a452-c045e4e84fac"
            }
          ]
        },
        {
          "id": "51cd9301-fc15-4b28-9c54-af75488f2ccf",
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
              "id": "6c102451-681b-440c-b3c7-a39ce62afb14"
            }
          ]
        },
        {
          "id": "ab7dc256-27fb-4832-9943-28928c14edc6",
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
              "id": "6ef7dc40-255b-41bb-99fb-75f2baf51a1e"
            }
          ]
        },
        {
          "id": "8dc90c83-640e-4b33-bb89-694a29e7bdea",
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
              "id": "15fb5c71-31ae-4316-a691-04555e9facf3"
            }
          ]
        },
        {
          "id": "429d11e0-9a10-4e54-a9ee-3f2c65883cdf",
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
              "id": "ab07daa0-f034-41f9-9fbf-22ce195eeb23"
            }
          ]
        },
        {
          "id": "a3787070-5847-4e49-8438-0f499c62df4a",
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
              "id": "1cae3f3e-9eaf-40c4-ba46-1306a7639a39"
            }
          ]
        },
        {
          "id": "ab04f4a4-00c0-4aab-b078-1a0f9c681cfb",
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
              "id": "58b7f2fc-86e2-4348-82b6-9bc8497b0785"
            }
          ]
        },
        {
          "id": "31beb1f8-7654-4c03-939d-e1adbd48cf8e",
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
              "id": "54476032-210f-4a59-a832-59985b06c5e4"
            }
          ]
        },
        {
          "id": "d2c83e75-56af-45d2-99ef-57300b5a57ee",
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
              "id": "c061e60d-94e6-4b4a-be44-726c0396d4bc"
            }
          ]
        },
        {
          "id": "18747630-3720-4898-8140-d7ff547ba79e",
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
              "id": "8f27c9da-1aac-4259-9d54-f2725091abbc"
            }
          ]
        },
        {
          "id": "5d0fd75c-0107-4044-b7d2-1175ded7e692",
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
              "id": "865f045e-d909-4b80-b650-e662be6eb01d"
            }
          ]
        },
        {
          "id": "bd6f4ec8-7c6a-4827-82a6-9131b65a7124",
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
              "id": "bb5c2f50-f9f1-4015-95b4-373adff70e05"
            }
          ]
        },
        {
          "id": "ebe2e704-b65c-4b30-8d9c-e4a6fc9a68dc",
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
              "id": "ed21e567-b4fe-463d-a645-e020a756833d"
            }
          ]
        },
        {
          "id": "1701a857-7f92-4771-b989-e35109ceb4bb",
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
              "id": "aec55510-3c6b-43d8-9e4f-0f2ef849d439"
            }
          ]
        },
        {
          "id": "d3667138-f4ba-4597-a02c-7d82001e5214",
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
              "id": "fcc42ac9-9dc4-4e74-a17c-9585f4e1d148"
            }
          ]
        },
        {
          "id": "7f2373f2-6b15-443f-9648-e0bf987f1a45",
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
              "id": "0b8c9aa6-f899-4e8d-8d9d-e883400c6c0e"
            }
          ]
        },
        {
          "id": "0c215b23-a692-4b10-bd41-69f1cdbfe4ba",
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
              "id": "a197e916-7eb5-4232-8463-9dca3d264596"
            }
          ]
        },
        {
          "id": "e29d260f-7286-4328-959a-197d866ba7f8",
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
              "id": "34a2d4ac-0360-4b61-acc8-3fba59b11004"
            }
          ]
        },
        {
          "id": "3ebe6742-587a-40c2-a1fd-33a3fd8ec927",
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
              "id": "5be1d9a9-0413-4576-ab54-236eb0717ab3"
            }
          ]
        },
        {
          "id": "3c4e999b-e9b1-4888-9e91-a33bd48d34bf",
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
              "id": "8ae8ea8f-c117-43ab-8372-3460d50c77e9"
            }
          ]
        },
        {
          "id": "4fa807d8-382f-4cfa-995f-ef228adce834",
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
              "id": "9bb00fa6-c6a2-4021-ad73-760faefde9b1"
            }
          ]
        }
      ]
    },
    {
      "name": "Versions",
      "item": [
        {
          "id": "d32e1503-844f-4b5d-9b0b-3c3d44245005",
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
              "id": "e4dd0e52-b868-46e5-b808-99373f120f73"
            }
          ]
        }
      ]
    },
    {
      "name": "Accept",
      "item": [
        {
          "id": "88a7c061-bea5-488f-8f50-3898f87bfb73",
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
              "id": "3a18839c-1c35-4954-8d08-af79c5cd64b6"
            }
          ]
        }
      ]
    },
    {
      "name": "CName",
      "item": [
        {
          "id": "d0e0448e-6819-4fb9-8896-27ff424031db",
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
              "id": "ccb91b75-fda0-4a04-b4d4-7f3803ced469"
            }
          ]
        }
      ]
    },
    {
      "name": "Activations",
      "item": [
        {
          "id": "cf79d500-63c6-47d3-b2cf-7426b0b28773",
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
              "id": "e9160bf0-a244-40d3-8e73-ee3a5ba237e1"
            }
          ]
        }
      ]
    },
    {
      "name": "Retry",
      "item": [
        {
          "id": "9776bf4a-21a0-4dd1-ae19-3cac5ee1bf6f",
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
              "id": "94ce730b-670c-46bc-a5f6-a3043b1e1b7b"
            }
          ]
        }
      ]
    },
    {
      "name": "Status",
      "item": [
        {
          "id": "6a06635b-5ab9-4eeb-b437-aba8ee4f899d",
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
              "id": "4a944903-6436-4305-b3ca-dbacc1901eaf"
            }
          ]
        }
      ]
    },
    {
      "name": "Subscription",
      "item": [
        {
          "id": "2cc6eec7-1bb0-45ed-8bc3-4ab531566e15",
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
              "id": "ad1c39e3-10a1-4555-b438-8df7b69b8dfb"
            }
          ]
        }
      ]
    },
    {
      "name": "Name",
      "item": [
        {
          "id": "083c42de-27ee-4f67-b7a5-b4bad52d9b32",
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
              "id": "ff899b4b-7b1b-4f6f-8b87-80f76d5f2904"
            }
          ]
        }
      ]
    },
    {
      "name": "Security",
      "item": [
        {
          "id": "499d0d60-c81b-4f8b-ba4c-6979633b05d5",
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
              "id": "a5e31911-cd6b-40d2-a422-d3d9062b1edb"
            }
          ]
        },
        {
          "id": "f7bbcccb-f50b-4464-8c7c-d882fded8f4d",
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
              "id": "5d4100c4-2e69-4f75-a77b-161af020ddac"
            }
          ]
        },
        {
          "id": "d75657ae-54fc-4d33-8e36-e59469075e2b",
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
              "id": "c1585395-a373-4268-8779-ca2e9841783e"
            }
          ]
        },
        {
          "id": "027a155c-e52f-441d-b5a8-de1944f39030",
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
              "id": "3ef9192c-3dbf-4476-81e3-7c050888c7e6"
            }
          ]
        }
      ]
    },
    {
      "name": "Sla",
      "item": [
        {
          "id": "eddabcc7-c201-4dd8-bfd3-22186e5b790a",
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
              "id": "e15a6815-4716-4e69-a211-aa6d1272293c"
            }
          ]
        },
        {
          "id": "3b6bf584-8c78-430e-9f67-baf48b55f142",
          "name": "slaapiv1testsslatestids",
          "request": {
            "url": "http://developer.akamai.com/sla-api/v1/tests?slaTestIds=slaTestIds",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Test Configurations"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38652111-1405-4d7f-af40-380103cd8a0a"
            }
          ]
        },
        {
          "id": "a198089c-5c9d-4065-9f62-c1ba1eb71c1f",
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
              "id": "7c2cca48-51f3-4cad-b932-c5a660677492"
            }
          ]
        },
        {
          "id": "62ca8ed2-723e-43e4-9aba-d5b8417fa920",
          "name": "slaapiv1testsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "sla-api/v1/tests/:id"
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
            "description": "Get a Test Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac5ed953-2849-41a4-9e9a-d8bb4d9f7e31"
            }
          ]
        },
        {
          "id": "90945436-b4b1-45fb-a6b2-784bc1141143",
          "name": "slaapiv1testsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "sla-api/v1/tests/:id"
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
            "description": "Update a Test Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f20a265a-c4d5-4674-8037-9c029e8bf912"
            }
          ]
        },
        {
          "id": "333514d3-0497-4e7a-a897-21885ceda03d",
          "name": "slaapiv1testsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "sla-api/v1/tests/:id"
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
            "description": "Delete a Test Configuration"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8b0c075d-de75-4146-8fcf-a048db2ccc34"
            }
          ]
        },
        {
          "id": "b40a2bb1-1f57-49f3-a5bb-c8231b9d434b",
          "name": "slaapiv1agentgroups",
          "request": {
            "url": "http://developer.akamai.com/sla-api/v1/agent-groups",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Agent Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ad0550a-5354-40ea-ba97-53142cceb276"
            }
          ]
        },
        {
          "id": "b7073b35-60d8-4047-9af6-6af82b55864e",
          "name": "slaapiv1testsslatestidreportsperformancestartend",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "sla-api/v1/tests/:slaTestId/reports/performance"
              ],
              "query": [
                {
                  "key": "end",
                  "value": "end",
                  "disabled": false
                },
                {
                  "key": "start",
                  "value": "start",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "slaTestId",
                  "value": "slaTestId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Performance Reports"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c92876c9-abf7-4c25-8246-db4c32786446"
            }
          ]
        },
        {
          "id": "5488dd5d-be50-4407-b0c4-dfdc9598168b",
          "name": "slaapiv1testsslatestidreportsavailabilitystartend",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "sla-api/v1/tests/:slaTestId/reports/availability"
              ],
              "query": [
                {
                  "key": "end",
                  "value": "end",
                  "disabled": false
                },
                {
                  "key": "start",
                  "value": "start",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "slaTestId",
                  "value": "slaTestId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Availability Reports"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd873a4e-dd85-4075-997a-5b8b0e66d337"
            }
          ]
        }
      ]
    },
    {
      "name": "Siteshield",
      "item": [
        {
          "id": "c37710ba-6625-4d8d-976d-75fff7a5eb93",
          "name": "siteshieldv1maps",
          "request": {
            "url": "http://developer.akamai.com/siteshield/v1/maps",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Maps"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8266d38-9921-4372-be9e-318daa51f6e5"
            }
          ]
        },
        {
          "id": "be916391-ad47-4884-875e-12eab18484f9",
          "name": "siteshieldv1mapsid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "siteshield/v1/maps/:id"
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
            "description": "Get a Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eb71d2b5-a518-4bad-acda-2e6cf08f17b7"
            }
          ]
        },
        {
          "id": "3746db93-455c-422f-868f-17fbb62ca005",
          "name": "siteshieldv1mapsidacknowledge",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "siteshield/v1/maps/:id/acknowledge"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Acknowledge a Map"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f17f05b4-dcf9-4968-b4c7-b4c7419c58dc"
            }
          ]
        }
      ]
    },
    {
      "name": "Region",
      "item": [
        {
          "id": "04f06bfe-d0fb-4db3-b565-c79f79786aa1",
          "name": "region",
          "request": {
            "url": "http://developer.akamai.com/region?datacenterId=datacenterId&domain=domain&resource=resource",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Submit Load Data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f31d9be4-e88f-4d1b-9aa1-f0d25a69257e"
            }
          ]
        }
      ]
    },
    {
      "name": "Connections",
      "item": [
        {
          "id": "95ae2387-2a51-4923-adad-4f26ef1901cd",
          "name": "connections",
          "request": {
            "url": "http://developer.akamai.com/connections?datacenterId=datacenterId&domain=domain&resource=resource",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch Load Data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57f5d260-809f-400d-8696-5a2fdd5ea268"
            }
          ]
        }
      ]
    },
    {
      "name": "User",
      "item": [
        {
          "id": "76b31c15-2d16-4cba-b76a-e3c65cee4ab7",
          "name": "useradminv1accountsaccountidgroups",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups"
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
            "description": "List Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a4d81103-ceef-40da-bfa9-82d8327776ba"
            }
          ]
        },
        {
          "id": "8b6ddc47-b893-44b3-80f7-29b2a3fbf200",
          "name": "useradminv1accountsaccountidgroupsgroupidgroups",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId/groups"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
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
            "description": "List Nested Groups"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e164fa90-e248-433e-b950-3c703d90fa59"
            }
          ]
        },
        {
          "id": "91cae222-4d77-4a55-b610-a76f4989fb48",
          "name": "useradminv1accountsaccountidgroupsgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
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
              "id": "99d3b784-4780-4e34-8985-0537da69e88a"
            }
          ]
        },
        {
          "id": "d477bc31-2aae-4bf7-973b-b92e7af50c7f",
          "name": "useradminv1accountsaccountidgroupsgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e82830d5-48a2-4a8c-8aa3-c744241d826f"
            }
          ]
        },
        {
          "id": "16ac4f10-a571-49de-81c8-91d314bf4803",
          "name": "useradminv1accountsaccountidgroupsgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b22d060e-f866-4c72-a257-29444b6425a9"
            }
          ]
        },
        {
          "id": "e1b60ab7-0657-4dda-813f-de47f204cda7",
          "name": "useradminv1accountsaccountidgroupsgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57d8867f-218a-4c25-9ee7-f8a9f7e68571"
            }
          ]
        },
        {
          "id": "26b53855-42d2-4c2d-bf6d-49f7e2603ea3",
          "name": "useradminv1accountsaccountidmovegroupgroupidgroupsdestinationgroupid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/move/group/:groupId/groups/:destinationGroupId/"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "destinationGroupId",
                  "value": "destinationGroupId",
                  "type": "string"
                },
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Move a Group within Another Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d23e0aec-62ab-40e3-8e03-1d60b714d616"
            }
          ]
        },
        {
          "id": "97101069-2db3-40e9-af35-d6684f2319a7",
          "name": "useradminv1accountsaccountidgroupsgroupidproperties",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId/properties"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
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
            "description": "List a Group&#8217;s Properties"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "623a429d-688d-4af6-9f03-f5df0bd371b1"
            }
          ]
        },
        {
          "id": "a3b331eb-622a-4d4d-b6e5-d7ee177b799c",
          "name": "useradminv1accountsaccountidgroupsgroupidpropertiesassetid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId/properties/:assetId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "assetId",
                  "value": "assetId",
                  "type": "string"
                },
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
            "description": "Get a Property"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b75ec34c-fe21-410f-beeb-10e57a6e258f"
            }
          ]
        },
        {
          "id": "e01217c9-5b2c-4af3-8eb3-0ac022957baf",
          "name": "useradminv1accountsaccountidgroupsgroupidpropertiesassetidusers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId/properties/:assetId/users"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "assetId",
                  "value": "assetId",
                  "type": "string"
                },
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
            "description": "List a Property&#8217;s Users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e619128a-43bb-4164-8f6a-63d7569fb71c"
            }
          ]
        },
        {
          "id": "6f94bbb4-5a70-4190-b69c-7274d61b80dc",
          "name": "useradminv1accountsaccountidgroupsgroupiduserscontactidpropertyexceptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId/users/:contactId/propertyExceptions"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "contactId",
                  "value": "contactId",
                  "type": "string"
                },
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
            "description": "List a User&#8217;s Property Exceptions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2785da8-fd80-4327-97e4-f4fd73f4d1d0"
            }
          ]
        },
        {
          "id": "c7fb00d3-57ba-4198-8700-d07952004b35",
          "name": "useradminv1accountsaccountidgroupsgroupiduserscontactidpropertyexceptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId/users/:contactId/propertyExceptions"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "contactId",
                  "value": "contactId",
                  "type": "string"
                },
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a User&#8217;s Set of Property Exceptions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db328fb1-44e5-44f0-a203-547dcb0456ab"
            }
          ]
        },
        {
          "id": "802daeac-b735-4d09-a4e3-3ce9070db830",
          "name": "useradminv1accountsaccountidgroupsgroupiduserscontactidpropertyexceptionspropertyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/groups/:groupId/users/:contactId/propertyExceptions/:propertyId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "contactId",
                  "value": "contactId",
                  "type": "string"
                },
                {
                  "id": "groupId",
                  "value": "groupId",
                  "type": "string"
                },
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a Property Exception"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59a25d4d-36ff-438b-be24-f4664d5c8a1c"
            }
          ]
        },
        {
          "id": "6964edb2-5723-4ded-a92b-8843a0f702b1",
          "name": "useradminv1accountsaccountidpropertiespropertyid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/properties/:propertyId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "propertyId",
                  "value": "propertyId",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Move a Property to Another Group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3bb321e-9390-4dfe-8681-7485d6dd660f"
            }
          ]
        },
        {
          "id": "9db92502-1caa-4cb5-ac1c-23d2786235aa",
          "name": "useradminv1accountsaccountidroles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/roles"
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
            "description": "List Roles"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a59629a7-667e-42e7-9129-f96d7c69cbfd"
            }
          ]
        },
        {
          "id": "ee198c93-5667-4d25-8fe9-64dd1ccba293",
          "name": "useradminv1accountsaccountidroles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/roles"
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
            "description": "Modify a Role"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "88b1032f-edbd-4f02-adfd-bb8f3319bdf4"
            }
          ]
        },
        {
          "id": "fd6a6e2c-6eb8-442a-90c3-882403f8e8c9",
          "name": "useradminv1accountsaccountidroles",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/roles"
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
            "description": "Create a New Role"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e3e81f8-fb6b-403d-9fb8-9b80f7b25b60"
            }
          ]
        },
        {
          "id": "2d9ea923-938b-4556-a127-69094e856dda",
          "name": "useradminv1accountsaccountidrolesroleid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/roles/:roleId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "roleId",
                  "value": "roleId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a Role"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6b06711-1c2c-4456-8fec-b3a044d4539d"
            }
          ]
        },
        {
          "id": "ef6fd9c9-bec8-4d71-b545-dcf53917fb4d",
          "name": "useradminv1accountsaccountidrolesroleid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/roles/:roleId"
              ],
              "variable": [
                {
                  "id": "accountId",
                  "value": "accountId",
                  "type": "string"
                },
                {
                  "id": "roleId",
                  "value": "roleId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a Role"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40f55c67-45c1-4d2d-a33f-46cfb4e8d575"
            }
          ]
        },
        {
          "id": "8543644d-5a2f-4357-8c01-588e7fb5f3bb",
          "name": "useradminv1accountsaccountidrolesgrantable",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/roles/grantable"
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
            "description": "List Grantable Roles"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "716a12a0-b52c-462c-ad49-08ff673206f2"
            }
          ]
        },
        {
          "id": "abf3d35b-c7dc-4152-83f5-f0f37bda9389",
          "name": "useradminv1usersgroupidactions",
          "request": {
            "url": "http://developer.akamai.com/user-admin/v1/users?actions=actions&groupId=groupId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List a Group&#8217;s Users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9aacb7cf-59ee-427c-a93e-2105546839a3"
            }
          ]
        },
        {
          "id": "1efb5a7c-3b84-40b6-9633-ea11c3dc266d",
          "name": "useradminv1users",
          "request": {
            "url": "http://developer.akamai.com/user-admin/v1/users",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create a New User"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69f28297-cac3-4692-9934-65e6d381e2ee"
            }
          ]
        },
        {
          "id": "873143a4-e1e1-4c54-95bc-21a897c7768a",
          "name": "useradminv1accountsaccountidusers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/accounts/:accountId/users"
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
            "description": "List Users"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e146b48b-5835-4ba5-824d-6fde3c98cc44"
            }
          ]
        },
        {
          "id": "f44e1749-0b4f-46b6-a7af-f142bc88bca8",
          "name": "useradminv1userscontactid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/users/:contactId"
              ],
              "variable": [
                {
                  "id": "contactId",
                  "value": "contactId",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Modify a User"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2ad9e26-3393-4b3c-81d2-339124bc752d"
            }
          ]
        },
        {
          "id": "52053037-b262-4f04-8c03-b0a1b8ccb798",
          "name": "useradminv1userscontactid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "developer.akamai.com",
              "path": [
                "user-admin/v1/users/:contactId"
              ],
              "variable": [
                {
                  "id": "contactId",
                  "value": "contactId",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Remove a User"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce86bcfd-597f-4f46-a125-77340e5cee2c"
            }
          ]
        }
      ]
    },
    {
      "name": "Send",
      "item": [
        {
          "id": "b276d1ec-b90d-479e-9404-48f39853fc7b",
          "name": "send-email",
          "request": {
            "url": "http://developer.akamai.com/send_email?contactId=contactId",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Reset a User&#8217;s Password"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dd58da30-904e-4d1d-bc87-a3c92cfb49b8"
            }
          ]
        }
      ]
    }
  ]
}