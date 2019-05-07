# ![LOGO](logo.png) NetworkManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the NetworkManagementClient API (version 2018-12-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/network-ddosProtectionPlan/2018-12-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:31+03:00

## API Description

The Microsoft Azure Network management API provides a RESTful set of web services that interact with Microsoft Azure Networks service to manage your network resources. The API has entities that capture the relationship between an end user and the Microsoft Azure Networks service.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Gets all DDoS protection plans in a subscription.

*Tags:* `DdosProtectionPlans`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets all the DDoS protection plans in a resource group.

*Tags:* `DdosProtectionPlans`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes the specified DDoS protection plan.

*Tags:* `DdosProtectionPlans`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ddosProtectionPlanName` - _required_ - The name of the DDoS protection plan.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Gets information about the specified DDoS protection plan.

*Tags:* `DdosProtectionPlans`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ddosProtectionPlanName` - _required_ - The name of the DDoS protection plan.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a DDoS protection plan.

*Tags:* `DdosProtectionPlans`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `ddosProtectionPlanName` - _required_ - The name of the DDoS protection plan.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - The subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-network-ddos-protection-plan-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
