# ![LOGO](logo.png) Inventory **flow**ground Connector

## Description

A generated **flow**ground connector for the Inventory API (version 3.0.1).

Generated from: https://api.apis.guru/v2/specs/walmart.com/inventory/3.0.1/swagger.json<br/>
Generated at: 2019-05-07T17:44:47+03:00

## API Description

Please make sure you use the correct version of the APIs for your use case. To find out the appropriate version, go to the API Docs  drop down on the menu.

## Authorization

This API does not require authorization.

## Actions

### Upload an inventory feed

> You can upload an inventory feed. If the feed successfully processed, it returns a feed ID. Use the returned feed ID to retrieve a feed status. You need Your Consumer ID and the private key to upload the feed

*Tags:* `Version 2`

#### Input Parameters
* `feedType` - _required_ - Feed Type
    Possible values: inventory.
* `WM_CONSUMER.CHANNEL.TYPE` - _required_ - Channel Type
    Possible values: SWAGGER_CHANNEL_TYPE.
* `WM_CONSUMER.ID` - _required_ - Your Consumer ID
* `WM_SEC.TIMESTAMP` - _required_ - Epoch timestamp
* `WM_SEC.AUTH_SIGNATURE` - _required_ - Authentication signature
* `WM_SVC.NAME` - _required_ - The Service name
* `WM_QOS.CORRELATION_ID` - _required_ - A Transaction ID

### Get inventory for an item

> This endpoint retrieves inventory for a given item.

*Tags:* `Version 2`

#### Input Parameters
* `sku` - _required_ - The SKU (seller-provided product identifier) of the item whose inventory we are retrieving
* `WM_CONSUMER.CHANNEL.TYPE` - _required_ - Channel Type
    Possible values: SWAGGER_CHANNEL_TYPE.
* `WM_CONSUMER.ID` - _required_ - Your consumer id
* `WM_SEC.TIMESTAMP` - _required_ - Epoch timestamp
* `WM_SEC.AUTH_SIGNATURE` - _required_ - Authentication signature
* `WM_SVC.NAME` - _required_ - Service name
* `WM_QOS.CORRELATION_ID` - _required_ - Correlation id
* `Accept` - _required_ - application/xml

### Upload an inventory feed

> You can upload an inventory feed. If the feed successfully processed, it returns a feed ID. Use the returned feed ID to retrieve a feed status. You need Your Consumer ID and the private key to upload the feed

*Tags:* `Version 3`

#### Input Parameters
* `feedType` - _required_ - Feed Type
    Possible values: inventory.
* `shipNode` - _required_ - Ship Node
* `WM_CONSUMER.CHANNEL.TYPE` - _required_ - Channel Type
    Possible values: SWAGGER_CHANNEL_TYPE.
* `WM_CONSUMER.ID` - _required_ - Your Consumer ID
* `WM_SEC.TIMESTAMP` - _required_ - Epoch timestamp
* `WM_SEC.AUTH_SIGNATURE` - _required_ - Authentication signature
* `WM_SVC.NAME` - _required_ - The Service name
* `WM_QOS.CORRELATION_ID` - _required_ - A Transaction ID

### Get inventory for an item

> This endpoint retrieves inventory for a given item.

*Tags:* `Version 3`

#### Input Parameters
* `sku` - _required_ - The SKU (seller-provided product identifier) of the item whose inventory we are retrieving
* `shipNode` - _required_ - Ship Node
* `WM_CONSUMER.CHANNEL.TYPE` - _required_ - Channel Type
    Possible values: SWAGGER_CHANNEL_TYPE.
* `WM_CONSUMER.ID` - _required_ - Your consumer id
* `WM_SEC.TIMESTAMP` - _required_ - Epoch timestamp
* `WM_SEC.AUTH_SIGNATURE` - _required_ - Authentication signature
* `WM_SVC.NAME` - _required_ - Service name
* `WM_QOS.CORRELATION_ID` - _required_ - Correlation id
* `Accept` - _required_ - application/xml

## License

**flow**ground :- Telekom iPaaS / walmart-com-inventory-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
