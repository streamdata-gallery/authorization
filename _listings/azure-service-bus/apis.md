---
name: Azure Service Bus
description: Depend on Azure Service Bus when you need highly-reliable cloud messaging
  service between applications and services, even when one or more is offline. Available
  in every Azure region, this fully-managed service eliminates the burdens of server
  management and licensing. Asynchronous operations give you flexible, brokered messaging
  between client and server, along with structured first-in, first-out (FIFO) messaging,
  and publish/subscribe capabilitiesmdash;excellent for tasks like order processing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
x-kinRank: "10"
x-alexaRank: ""
tags:
- Stack Network
- Microsoft
- Messaging
created: "2018-03-27"
modified: "2018-03-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/authorization/master/_listings/azure-service-bus/apis.yaml
specificationVersion: "0.14"
apis:
- name: Azure Service Bus API
  description: Depend on Azure Service Bus when you need highly-reliable cloud messaging
    service between applications and services, even when one or more is offline
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: ""
  baseURL: ://management.azure.com//
  tags: Authorization
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/authorization/master/_listings/azure-service-bus/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-servicebus-namespaces-namespacename-topics-topicname-authorizationrules-authorizationrulename-delete.md
- name: Azure Service Bus API Topics Delete Authorization Rule
  description: Deletes a topic authorization rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-service-bus-anything.png
  humanURL: https://azure.microsoft.com/en-us/services/service-bus/
  baseURL: http:://management.azure.com//
  tags: Authorization
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/authorization/master/_listings/azure-service-bus/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-servicebus-namespaces-namespacename-topics-topicname-authorizationrules-authorizationrulename-delete.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/authorization/master/_listings/azure-service-bus/subscriptions-subscriptionid-resourcegroups-resourcegroupname-providers-microsoft-servicebus-namespaces-namespacename-topics-topicname-authorizationrules-authorizationrulename-delete-postman.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-bus/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/service-bus/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/service-bus/
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/service-bus/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-bus/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/service-bus/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/service-bus/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---