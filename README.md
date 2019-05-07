# ![LOGO](logo.png) StorageManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StorageManagementClient API (version 2015-12-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-quotas/2015-12-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:33+03:00

## API Description

The Admin Storage Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of storage quotas at the given location.

*Tags:* `StorageQuotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `location` - _required_ - Resource location.
* `api-version` - _required_ - REST Api Version.

### Delete an existing quota

*Tags:* `StorageQuotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `api-version` - _required_ - REST Api Version.
* `location` - _required_ - Resource location.
* `quotaName` - _required_ - The name of the storage quota.

### Returns the specified storage quota.

*Tags:* `StorageQuotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `api-version` - _required_ - REST Api Version.
* `location` - _required_ - Resource location.
* `quotaName` - _required_ - The name of the storage quota.

### Create or update an existing storage quota.

*Tags:* `StorageQuotas`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id.
* `location` - _required_ - Resource location.
* `api-version` - _required_ - REST Api Version.
* `quotaName` - _required_ - The name of the storage quota.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-quotas-2-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
