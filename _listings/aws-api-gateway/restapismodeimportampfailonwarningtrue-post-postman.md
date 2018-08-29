{
  "info": {
    "name": "AWS API Gateway API Restapi Import",
    "_postman_id": "87d92dc4-5348-40b5-9eb0-1fd00bb58689",
    "description": "Creates an API from an external API definition.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Root",
      "item": [
        {
          "id": "2f65e0fd-0374-494e-947f-20e5ef4aa2f3",
          "name": "apiGateway",
          "request": {
            "url": "http://example.com/api/?UnauthorizedException=UnauthorizedException",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "",
                "disabled": false
              },
              {
                "key": "Host",
                "value": "Host",
                "description": "",
                "disabled": false
              },
              {
                "key": "X-Amz-Date",
                "value": "X-Amz-Date",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Represents the root of the Amazon API Gateway control service."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69e3899f-a980-4b08-a79e-0827839c0286"
            }
          ]
        }
      ]
    },
    {
      "name": "Keys",
      "item": [
        {
          "id": "d701a742-195e-4bc0-90c2-882b9c1e015e",
          "name": "apigatewayApi-keys",
          "request": {
            "url": "http://example.com/api/apikeys?REST API Reference=REST%20API%20Reference",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "",
                "disabled": false
              },
              {
                "key": "Host",
                "value": "Host",
                "description": "",
                "disabled": false
              },
              {
                "key": "X-Amz-Date",
                "value": "X-Amz-Date",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets the ApiKeys resource representing the set of ApiKey resources to identify clients for all of your APIs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad4472b3-de43-4086-9744-56ec2f2f3a9c"
            }
          ]
        }
      ]
    },
    {
      "name": "Restapi",
      "item": [
        {
          "id": "b665e2a1-af93-4530-8200-dd9ea414e71e",
          "name": "restapiCreate",
          "request": {
            "url": "http://example.com/api/restapis?REST API Reference=REST%20API%20Reference",
            "method": "POST",
            "header": [
              {
                "key": "&quot;description&quot;",
                "value": "&quot;description&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;name&quot;",
                "value": "&quot;name&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "",
                "disabled": false
              },
              {
                "key": "Host",
                "value": "Host",
                "description": "",
                "disabled": false
              },
              {
                "key": "X-Amz-Date",
                "value": "X-Amz-Date",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a new API represented by a RestApi instance in API Gateway."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50ca1152-ef68-4987-a51f-f37b37a06869"
            }
          ]
        }
      ]
    },
    {
      "name": "Import",
      "item": [
        {
          "id": "0af93efe-7a3d-4c17-add0-6d73c93a807a",
          "name": "restapiImport",
          "request": {
            "url": "http://example.com/api/restapis?mode=import&amp;failonwarning=true?REST API Reference=REST%20API%20Reference",
            "method": "POST",
            "header": [
              {
                "key": "&quot;$ref&quot;",
                "value": "&quot;$ref&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;/&quot;",
                "value": "&quot;/&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;200&quot;",
                "value": "&quot;200&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;application/json&quot;",
                "value": "&quot;application/json&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;basePath&quot;",
                "value": "&quot;basePath&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;consumes&quot;",
                "value": "&quot;consumes&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;Content-Type&quot;",
                "value": "&quot;Content-Type&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;default&quot;",
                "value": "&quot;default&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;definitions&quot;",
                "value": "&quot;definitions&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;description&quot;",
                "value": "&quot;description&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;Empty&quot;",
                "value": "&quot;Empty&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;get&quot;",
                "value": "&quot;get&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;headers&quot;",
                "value": "&quot;headers&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;host&quot;",
                "value": "&quot;host&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;httpMethod&quot;",
                "value": "&quot;httpMethod&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;info&quot;",
                "value": "&quot;info&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;integration.request.header.Content-Type&quot;",
                "value": "&quot;integration.request.header.Content-Type&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;method.response.header.Content-Type&quot;",
                "value": "&quot;method.response.header.Content-Type&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;passthroughBehavior&quot;",
                "value": "&quot;passthroughBehavior&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;paths&quot;",
                "value": "&quot;paths&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;produces&quot;",
                "value": "&quot;produces&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;requestParameters&quot;",
                "value": "&quot;requestParameters&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;requestTemplates&quot;",
                "value": "&quot;requestTemplates&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;responseParameters&quot;",
                "value": "&quot;responseParameters&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;responses&quot;",
                "value": "&quot;responses&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;responseTemplates&quot;",
                "value": "&quot;responseTemplates&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;schema&quot;",
                "value": "&quot;schema&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;schemes&quot;",
                "value": "&quot;schemes&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;statusCode&quot;",
                "value": "&quot;statusCode&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;swagger&quot;",
                "value": "&quot;swagger&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;title&quot;",
                "value": "&quot;title&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;type&quot;",
                "value": "&quot;type&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "&quot;x-amazon-apigateway-integration&quot;",
                "value": "&quot;x-amazon-apigateway-integration&quot;",
                "description": "",
                "disabled": false
              },
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "Content-Type",
                "description": "",
                "disabled": false
              },
              {
                "key": "Host",
                "value": "Host",
                "description": "",
                "disabled": false
              },
              {
                "key": "X-Amz-Date",
                "value": "X-Amz-Date",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates an API from an external API definition."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "12e3799e-b048-45d1-a1ad-371bad1e0772"
            }
          ]
        }
      ]
    }
  ]
}