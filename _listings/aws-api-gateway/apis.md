---
name: AWS API Gateway
x-slug: aws-api-gateway
description: Amazon API Gateway is a fully managed service that makes it easy for
  developers to create, publish, maintain, monitor, and secure APIs at any scale.
  With a few clicks in the AWS Management Console, you can create an API that acts
  as a front door for applications to access data, business logic, or functionality
  from your back-end services, such as workloads running on Amazon Elastic Compute
  Cloud, code running on AWS Lambda, or any Web application. Amazon API Gateway handles
  all the tasks involved in accepting and processing up to hundreds of thousands of
  concurrent API calls, including traffic management, authorization and access control,
  monitoring, and API version management. Amazon API Gateway has no minimum fees or
  startup costs. You pay only for the API calls you receive and the amount of data
  transferred out.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS API Gateway
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/apis.md
specificationVersion: "0.14"
apis:
- name: AWS API Gateway API Root Service
  x-api-slug: aws-api-gateway-api
  description: Represents the root of the Amazon API Gateway control service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///
  tags: Root, Service
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/get-openapi.md
- name: AWS API Gateway API Get API Keys
  x-api-slug: aws-api-gateway-api
  description: Gets the ApiKeys resource representing the set of ApiKey resources
    to identify clients for all of your APIs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///apikeys
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/apikeys-get-openapi.md
- name: AWS API Gateway API Restapi Create
  x-api-slug: aws-api-gateway-api
  description: Creates a new API represented by a RestApi instance in API Gateway.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis
  tags: 'Restapi, '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapis-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapis-post-openapi.md
- name: AWS API Gateway API Restapi Import
  x-api-slug: aws-api-gateway-api
  description: Creates an API from an external API definition.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis?mode=import&amp;failonwarning=true
  tags: Import
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapismodeimportampfailonwarningtrue-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapismodeimportampfailonwarningtrue-post-openapi.md
- name: AWS API Gateway API Get API Key
  x-api-slug: aws-api-gateway-api
  description: Gets the ApiKey resource with the specified key identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///apikeys/hzYAVO9Sg98nsNh65VfX81M84O2kyXVy6K1xwHD7
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/apikeyshzyavo9sg98nsnh65vfx81m84o2kyxvy6k1xwhd7-get-openapi.md
- name: AWS API Gateway API Create Key
  x-api-slug: aws-api-gateway-api
  description: Creates a new ApiKey resource to represent an API key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///apikeys
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/apikeys-post-openapi.md
- name: AWS API Gateway API Imports One Or More API Keys
  x-api-slug: aws-api-gateway-api
  description: Imports one or more API keys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///apikeys?mode=import&amp;format=csv&amp;failonwarnings=false
  tags: Keys, Imports
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/apikeysmodeimportampformatcsvampfailonwarningsfalse-post-openapi.md
- name: AWS API Gateway API Account Update
  x-api-slug: aws-api-gateway-api
  description: Changes information about the associated Account resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///account
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/account-patch-openapi.md
- name: AWS API Gateway API Deletes An Api Key Resource
  x-api-slug: aws-api-gateway-api
  description: Deletes an ApiKey resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///apikeys/a2TprUZuzf2EKbbmMUotDaHYGg8kgxFypcarGved
  tags: Key, Resource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/apikeysa2tpruzuzf2ekbbmmuotdahygg8kgxfypcargved-delete-openapi.md
- name: AWS API Gateway API Apikey Update
  x-api-slug: aws-api-gateway-api
  description: Changes an API key properties, including the description, enabled,
    and name properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///apikeys/hzYAVO9Sg98nsNh65VfX81M84O2kyXVy6K1xwHD7
  tags: Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/apikeyshzyavo9sg98nsnh65vfx81m84o2kyxvy6k1xwhd7-patch-openapi.md
- name: AWS API Gateway API Authorizer Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes an authorizer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/mxsmn867vb/authorizers/4unj71
  tags: Authorizer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapismxsmn867vbauthorizers4unj71-delete-openapi.md
- name: AWS API Gateway API Authorizer Byid
  x-api-slug: aws-api-gateway-api
  description: Gets the Authorizer resource representing a custom authorizer of a
    specified identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/mxsmn867vb/authorizers/40j2n8
  tags: Authorizer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapismxsmn867vbauthorizers40j2n8-get-openapi.md
- name: AWS API Gateway API Authorizer Create
  x-api-slug: aws-api-gateway-api
  description: Creates an Authorizer resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/mxsmn867vb/authorizers
  tags: Authorizer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapismxsmn867vbauthorizers-post-openapi.md
- name: AWS API Gateway API Clientcertificate Byid
  x-api-slug: aws-api-gateway-api
  description: Gets the ClientCertificate resource with the specified identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///clientcertificates/9ao60f
  tags: Certificates, Byid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/clientcertificates9ao60f-get-openapi.md
- name: AWS API Gateway API Clientcertificate Generate
  x-api-slug: aws-api-gateway-api
  description: Generates a new ClientCertificate resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///clientcertificates
  tags: Certificates, Generate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/clientcertificates-post-openapi.md
- name: AWS API Gateway API Deployment Update
  x-api-slug: aws-api-gateway-api
  description: Changes information about the deployment resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/deployments/dzacq7
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtrideploymentsdzacq7-patch-openapi.md
- name: AWS API Gateway API Deployment Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes the deployment resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/deployments/dzacq7
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtrideploymentsdzacq7-delete-openapi.md
- name: AWS API Gateway API Domainname Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes the domain name resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///domainnames/mon-api.com
  tags: Domainname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/domainnamesmonapi-com-delete-openapi.md
- name: AWS API Gateway API Get Domain Base Path
  x-api-slug: aws-api-gateway-api
  description: Gets the BasePathMappings resource representing the collection of base
    path mappings for the specified custom domain name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///domainnames/a.b.c.com/basepathmappings
  tags: Domain, Base, Path
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/domainnamesa-b-c-combasepathmappings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/domainnamesa-b-c-combasepathmappings-get-openapi.md
- name: AWS API Gateway API Integrationresponse Update
  x-api-slug: aws-api-gateway-api
  description: Changes information about an integration response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/integration/responses/200
  tags: Integrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetintegrationresponses200-patch-openapi.md
- name: AWS API Gateway API Integration Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes an integration response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/integration/responses/200
  tags: Integrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetintegrationresponses200-delete-openapi.md
- name: AWS API Gateway API Integration Update
  x-api-slug: aws-api-gateway-api
  description: Changes information about an integration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/integration
  tags: Integration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetintegration-patch-openapi.md
- name: AWS API Gateway API Integration Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes an integration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/integration
  tags: Integration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetintegration-delete-openapi.md
- name: AWS API Gateway API Integrationresponse Put
  x-api-slug: aws-api-gateway-api
  description: Set up an IntegrationResponse for the integration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/integration/responses/200
  tags: Integrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetintegrationresponses200-put-openapi.md
- name: AWS API Gateway API Integration Responses
  x-api-slug: aws-api-gateway-api
  description: Specifies the integration&#39;s responses.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/integration/responses/200
  tags: Integrations, Responses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetintegrationresponses200-get-openapi.md
- name: AWS API Gateway API Get Response
  x-api-slug: aws-api-gateway-api
  description: Represents a method response of a given HTTP status code returned to
    the client. The method response is passed from the back end through the associated
    integration response that can be transformed using a mapping template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/responses/200
  tags: Response
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetresponses200-get-openapi.md
- name: AWS API Gateway API Methodresponse Update
  x-api-slug: aws-api-gateway-api
  description: Update MethodResponse resource&#39;s properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/resources/0cjtch/methods/GET/responses/200
  tags: Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57resources0cjtchmethodsgetresponses200-patch-openapi.md
- name: AWS API Gateway API Methodresponse Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes method response settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/resources/0cjtch/methods/GET/responses/200
  tags: Method, Responses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57resources0cjtchmethodsgetresponses200-delete-openapi.md
- name: AWS API Gateway API Method Update
  x-api-slug: aws-api-gateway-api
  description: Update the method settings.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET
  tags: Method
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsget-patch-openapi.md
- name: AWS API Gateway API Method Delete
  x-api-slug: aws-api-gateway-api
  description: Delete the method resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/8ekh4oszgl/resources/4oa3abz7jc/methods/GET
  tags: Method
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapis8ekh4oszglresources4oa3abz7jcmethodsget-delete-openapi.md
- name: AWS API Gateway API Methodresponse Put
  x-api-slug: aws-api-gateway-api
  description: Set up the method response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/responses/200
  tags: Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetresponses200-put-openapi.md
- name: AWS API Gateway API Integration Put
  x-api-slug: aws-api-gateway-api
  description: Set up the method&#39;s integration request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET/integration
  tags: Integration, Put
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsgetintegration-put-openapi.md
- name: AWS API Gateway API Method Responses
  x-api-slug: aws-api-gateway-api
  description: Gets a method response associated with a given HTTP status code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/resources/0cjtch/methods/GET/responses/200
  tags: Method, Responses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57resources0cjtchmethodsgetresponses200-get-openapi.md
- name: AWS API Gateway API Method Integration
  x-api-slug: aws-api-gateway-api
  description: Gets the method&#39;s integration responsible for passing the client-submitted
    request to the back end and performing necessary transformations to make the request
    compliant with the back end.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/resources/0cjtch/methods/GET/integration
  tags: Method, Integration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57resources0cjtchmethodsgetintegration-get-openapi.md
- name: AWS API Gateway API Model Create
  x-api-slug: aws-api-gateway-api
  description: Creates a new Model for this API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57models-post-openapi.md
- name: AWS API Gateway API Model Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models/CalcOutput
  tags: Model
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57modelscalcoutput-delete-openapi.md
- name: AWS API Gateway API Model Generatetemplate
  x-api-slug: aws-api-gateway-api
  description: Generates a sample mapping template that can be used to transform a
    payload into the structure of a model.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models/output/default_template
  tags: Model, Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57modelsoutputdefault-template-get-openapi.md
- name: AWS API Gateway API Model Byname
  x-api-slug: aws-api-gateway-api
  description: Gets information about the Model of a specified name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/models/output
  tags: Model, Byname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57modelsoutput-get-openapi.md
- name: AWS API Gateway API Resource Createchild
  x-api-slug: aws-api-gateway-api
  description: Creates a child API resource of a given API resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/47rxl6
  tags: Resource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources47rxl6-post-openapi.md
- name: AWS API Gateway API Method Byhttpmethod
  x-api-slug: aws-api-gateway-api
  description: Gets the method (as a Method resource) on a specified API resource
    (as Resource resource) of the given HTTP method type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uojnr9hd57/resources/0cjtch/methods/GET
  tags: Method, Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuojnr9hd57resources0cjtchmethodsget-get-openapi.md
- name: AWS API Gateway API Resource Methods
  x-api-slug: aws-api-gateway-api
  description: Gets an API resource&#39;s method of a given HTTP verb.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2/methods/GET
  tags: Resource, Methods
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2methodsget-get-openapi.md
- name: AWS API Gateway API Resource Byid
  x-api-slug: aws-api-gateway-api
  description: Gets an API resource of the Resource type for a given resource identifier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2
  tags: Resource, Byid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2-get-openapi.md
- name: AWS API Gateway API Resource Create
  x-api-slug: aws-api-gateway-api
  description: Creates an API resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources/3kzxbg5sa2
  tags: 'Resource, '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources3kzxbg5sa2-post-openapi.md
- name: AWS API Gateway API Restapi Update
  x-api-slug: aws-api-gateway-api
  description: Changes properties of a RestApi resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/
  tags: Restapi
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtri-patch-openapi.md
- name: AWS API Gateway API Restapi Resources
  x-api-slug: aws-api-gateway-api
  description: Gets an API&#39;s resource collection as represented by a Resources
    instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/resources
  tags: Restapi, Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtriresources-get-openapi.md
- name: AWS API Gateway API Restapi Deployments
  x-api-slug: aws-api-gateway-api
  description: Gets an API&#39;s Deployments resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/deployments?limit=2
  tags: Restapi, Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtrideploymentslimit2-get-openapi.md
- name: AWS API Gateway API Restapi Models
  x-api-slug: aws-api-gateway-api
  description: Gets an API&#39;s model collection represented by a Models instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/l9kujxkzq2/models
  tags: Models
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisl9kujxkzq2models-get-openapi.md
- name: AWS API Gateway API Restapi Authorizers
  x-api-slug: aws-api-gateway-api
  description: Gets an API&#39;s collection of custom authorizers that is represented
    as an Authorizers instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/86l3267lf6/authorizers
  tags: Restapi, Authorizers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapis86l3267lf6authorizers-get-openapi.md
- name: AWS API Gateway API Restapi Put
  x-api-slug: aws-api-gateway-api
  description: Update the definition of a REST API, including the resources, methods,
    templates, and models.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/wn611yeyp3?mode=merge
  tags: Restapi
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapiswn611yeyp3modemerge-put-openapi.md
- name: AWS API Gateway API Stage Update
  x-api-slug: aws-api-gateway-api
  description: Changes information about the stage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/fugvjdxtri/stages/stage1
  tags: Stage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisfugvjdxtristagesstage1-patch-openapi.md
- name: AWS API Gateway API Stage Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes a named stage of a given API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uycll6xg9a/stages/alpha
  tags: Stage
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuycll6xg9astagesalpha-delete-openapi.md
- name: AWS API Gateway API Stage Flush
  x-api-slug: aws-api-gateway-api
  description: Flushes the cached data of a named stage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uycll6xg9a/stages/alpha/cache/data
  tags: Stage, Flush
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuycll6xg9astagesalphacachedata-delete-openapi.md
- name: AWS API Gateway API Stage Flush
  x-api-slug: aws-api-gateway-api
  description: Flushes all cached Authorizer entries on a named stage.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///restapis/uycll6xg9a/stages/alpha/cache/authorizers
  tags: Stage, Flush
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/restapisuycll6xg9astagesalphacacheauthorizers-delete-openapi.md
- name: AWS API Gateway API Clientcertificate Delete
  x-api-slug: aws-api-gateway-api
  description: Deletes the ClientCertificate resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///usageplans/{usageplanId}/keys/{keyId}
  tags: Certifications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/usageplansusageplanidkeyskeyid-delete-openapi.md
- name: AWS API Gateway API Clientcertificate Update
  x-api-slug: aws-api-gateway-api
  description: Changes information about the ClientCertificate resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: ://///clientcertificates/{clientcertificate_id}
  tags: Certificates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/clientcertificatesclientcertificate-id-patch-openapi.md
- name: AWS API Gateway API
  x-api-slug: aws-api-gateway-api
  description: Amazon API Gateway is a fully managed service that makes it easy for
    developers to create, publish, maintain, monitor, and secure APIs at any scale.
    With a few clicks in the AWS Management Console, you can create an API that acts
    as a front door for applications to access data, business logic, or functionality
    from your back-end services, such as workloads running on Amazon Elastic Compute
    Cloud, code running on AWS Lambda, or any Web application. Amazon API Gateway
    handles all the tasks involved in accepting and processing up to hundreds of thousands
    of concurrent API calls, including traffic management, authorization and access
    control, monitoring, and API version management. Amazon API Gateway has no minimum
    fees or startup costs. You pay only for the API calls you receive and the amount
    of data transferred out.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-api-gateway-icon.png
  humanURL: https://aws.amazon.com/api-gateway/
  baseURL: :///
  tags: AWS API Gateway
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-api-gateway/master/_listings/aws-api-gateway/openapi.md
x-common:
- type: x-documentation
  url: https://docs.aws.amazon.com/apigateway/api-reference/
- type: x-faq
  url: https://aws.amazon.com/api-gateway/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/api-gateway/getting-started/
- type: x-partners
  url: https://aws.amazon.com/api-gateway/partners/
- type: x-pricing
  url: https://aws.amazon.com/api-gateway/pricing/
- type: x-website
  url: https://aws.amazon.com/api-gateway/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---