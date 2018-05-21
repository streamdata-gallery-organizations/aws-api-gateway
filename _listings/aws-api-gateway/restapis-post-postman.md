{
  "info": {
    "name": "AWS API Gateway API Restapi Create",
    "_postman_id": "24d7d7f7-dadd-4d6e-a82a-e362ffdd83ae",
    "description": "Creates a new API represented by a RestApi instance in API Gateway.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Root",
      "item": [
        {
          "id": "7f63995c-b301-4587-a0a8-3291f7548123",
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
              "id": "1a4e7d67-5751-44c4-80d7-27c48c3046f6"
            }
          ]
        }
      ]
    },
    {
      "name": "Keys",
      "item": [
        {
          "id": "29e930bf-66e0-4c3a-af5a-b59cfe4466d0",
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
              "id": "cf792502-4f38-4c6d-ae40-0b3df5170c39"
            }
          ]
        }
      ]
    },
    {
      "name": "Restapi",
      "item": [
        {
          "id": "a295a2ec-2a16-4e20-8e7d-ada1151edd19",
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
              "id": "88b0c14f-3be9-4958-9567-00aa01793949"
            }
          ]
        }
      ]
    }
  ]
}