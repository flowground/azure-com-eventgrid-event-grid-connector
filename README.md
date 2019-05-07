# ![LOGO](logo.png) EventGridManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the EventGridManagementClient API (version 2019-01-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/eventgrid-EventGrid/2019-01-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:08+03:00

## API Description

Azure EventGrid Management Client

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List available operations

> List the available operations supported by the Microsoft.EventGrid resource provider

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### List topic types

> List all registered topic types

*Tags:* `TopicTypes`

#### Input Parameters
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get a topic type

> Get information about a topic type

*Tags:* `TopicTypes`

#### Input Parameters
* `topicTypeName` - _required_ - Name of the topic type
* `api-version` - _required_ - Version of the API to be used with the client request.

### List event types

> List event types for a topic type

*Tags:* `TopicTypes`

#### Input Parameters
* `topicTypeName` - _required_ - Name of the topic type
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get an aggregated list of all global event subscriptions under an Azure subscription

> List all aggregated global event subscriptions under a specific Azure subscription

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all regional event subscriptions under an Azure subscription

> List all event subscriptions from the given location under a specific Azure subscription

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Name of the location
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all regional event subscriptions under an Azure subscription for a topic type

> List all event subscriptions from the given location under a specific Azure subscription and topic type.

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - Name of the location
* `topicTypeName` - _required_ - Name of the topic type
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all global event subscriptions for a topic type

> List all global event subscriptions under an Azure subscription for a topic type.

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `topicTypeName` - _required_ - Name of the topic type
* `api-version` - _required_ - Version of the API to be used with the client request.

### List topics under an Azure subscription

> List all the topics under an Azure subscription

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all global event subscriptions under an Azure subscription and resource group

> List all global event subscriptions under a specific Azure subscription and resource group

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all regional event subscriptions under an Azure subscription and resource group

> List all event subscriptions from the given location under a specific Azure subscription and resource group

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `location` - _required_ - Name of the location
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all regional event subscriptions under an Azure subscription and resource group for a topic type

> List all event subscriptions from the given location under a specific Azure subscription and resource group and topic type

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `location` - _required_ - Name of the location
* `topicTypeName` - _required_ - Name of the topic type
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all global event subscriptions under a resource group for a topic type

> List all global event subscriptions under a resource group for a specific topic type.

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `topicTypeName` - _required_ - Name of the topic type
* `api-version` - _required_ - Version of the API to be used with the client request.

### List topics under a resource group

> List all the topics under a resource group

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Delete a topic

> Delete existing topic

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `topicName` - _required_ - Name of the topic
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get a topic

> Get properties of a topic

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `topicName` - _required_ - Name of the topic
* `api-version` - _required_ - Version of the API to be used with the client request.

### Update a topic

> Asynchronously updates a topic with the specified parameters.

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `topicName` - _required_ - Name of the topic
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create a topic

> Asynchronously creates a new topic with the specified parameters.

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `topicName` - _required_ - Name of the topic
* `api-version` - _required_ - Version of the API to be used with the client request.

### List keys for a topic

> List the two keys used to publish to a topic

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `topicName` - _required_ - Name of the topic
* `api-version` - _required_ - Version of the API to be used with the client request.

### Regenerate key for a topic

> Regenerate a shared access key for a topic

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `topicName` - _required_ - Name of the topic
* `api-version` - _required_ - Version of the API to be used with the client request.

### List all event subscriptions for a specific topic

> List all event subscriptions that have been created for a specific topic

*Tags:* `EventSubscriptions`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `providerNamespace` - _required_ - Namespace of the provider of the topic
* `resourceTypeName` - _required_ - Name of the resource type
* `resourceName` - _required_ - Name of the resource
* `api-version` - _required_ - Version of the API to be used with the client request.

### List topic event types

> List event types for a topic

*Tags:* `Topics`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials that uniquely identify a Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription.
* `providerNamespace` - _required_ - Namespace of the provider of the topic
* `resourceTypeName` - _required_ - Name of the topic type
* `resourceName` - _required_ - Name of the topic
* `api-version` - _required_ - Version of the API to be used with the client request.

### Delete an event subscription

> Delete an existing event subscription

*Tags:* `EventSubscriptions`

#### Input Parameters
* `scope` - _required_ - The scope of the event subscription. The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic. For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.
* `eventSubscriptionName` - _required_ - Name of the event subscription
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get an event subscription

> Get properties of an event subscription

*Tags:* `EventSubscriptions`

#### Input Parameters
* `scope` - _required_ - The scope of the event subscription. The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic. For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.
* `eventSubscriptionName` - _required_ - Name of the event subscription
* `api-version` - _required_ - Version of the API to be used with the client request.

### Update an event subscription

> Asynchronously updates an existing event subscription.

*Tags:* `EventSubscriptions`

#### Input Parameters
* `scope` - _required_ - The scope of existing event subscription. The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic. For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.
* `eventSubscriptionName` - _required_ - Name of the event subscription to be updated
* `api-version` - _required_ - Version of the API to be used with the client request.

### Create or update an event subscription

> Asynchronously creates a new event subscription or updates an existing event subscription based on the specified scope.

*Tags:* `EventSubscriptions`

#### Input Parameters
* `scope` - _required_ - The identifier of the resource to which the event subscription needs to be created or updated. The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic. For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.
* `eventSubscriptionName` - _required_ - Name of the event subscription. Event subscription names must be between 3 and 64 characters in length and should use alphanumeric letters only.
* `api-version` - _required_ - Version of the API to be used with the client request.

### Get full URL of an event subscription

> Get the full endpoint URL for an event subscription

*Tags:* `EventSubscriptions`

#### Input Parameters
* `scope` - _required_ - The scope of the event subscription. The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic. For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.
* `eventSubscriptionName` - _required_ - Name of the event subscription
* `api-version` - _required_ - Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-eventgrid-event-grid-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
