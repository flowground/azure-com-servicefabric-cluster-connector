# ![LOGO](logo.png) ServiceFabricManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ServiceFabricManagementClient API (version 2018-02-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/servicefabric-cluster/2018-02-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:58+03:00

## API Description

Azure Service Fabric Resource Provider API Client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Service Fabric resource provider API operations.

> Get the list of available Service Fabric resource provider API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The version of the Service Fabric resouce provider API

### Gets the list of Service Fabric cluster resources created in the specified subscription.

> Gets all Service Fabric cluster resources created or in the process of being created in the subscription.

*Tags:* `Cluster`

#### Input Parameters
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

### Gets the list of Service Fabric cluster code versions available for the specified location.

> Gets all available code versions for Service Fabric cluster resources by location.

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions. This is different from cluster location.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

### Gets information about a Service Fabric cluster code version available in the specified location.

> Gets information about an available Service Fabric cluster code version.

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions. This is different from cluster location.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.
* `clusterVersion` - _required_ - The cluster code version.

### Gets the list of Service Fabric cluster code versions available for the specified environment.

> Gets all available code versions for Service Fabric cluster resources by environment.

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions. This is different from cluster location.
* `environment` - _required_ - The operating system of the cluster. The default means all.
    Possible values: Windows, Linux.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

### Gets information about a Service Fabric cluster code version available for the specified environment.

> Gets information about an available Service Fabric cluster code version by environment.

*Tags:* `ClusterVersion`

#### Input Parameters
* `location` - _required_ - The location for the cluster code versions. This is different from cluster location.
* `environment` - _required_ - The operating system of the cluster. The default means all.
    Possible values: Windows, Linux.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.
* `clusterVersion` - _required_ - The cluster code version.

### Deletes a Service Fabric cluster resource.

> Delete a Service Fabric cluster resource with the specified name.

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

### Gets a Service Fabric cluster resource.

> Get a Service Fabric cluster resource created or in the process of being created in the specified resource group.

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

### Updates the configuration of a Service Fabric cluster resource.

> Update the configuration of a Service Fabric cluster resource with the specified name.

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

### Creates or updates a Service Fabric cluster resource.

> Create or update a Service Fabric cluster resource with the specified name.

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `clusterName` - _required_ - The name of the cluster resource.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

### Gets the list of Service Fabric cluster resources created in the specified resource group.

> Gets all Service Fabric cluster resources created or in the process of being created in the resource group.

*Tags:* `Cluster`

#### Input Parameters
* `resourceGroupName` - _required_ - The name of the resource group.
* `api-version` - _required_ - The version of the Service Fabric resource provider API. This is a required parameter and it's value must be "2018-02-01" for this specification.
    Possible values: 2018-02-01.
* `subscriptionId` - _required_ - The customer subscription identifier.

## License

**flow**ground :- Telekom iPaaS / azure-com-servicefabric-cluster-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
