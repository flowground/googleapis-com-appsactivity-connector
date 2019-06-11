# ![LOGO](logo.png) Drive Activity **flow**ground Connector

## Description

A generated **flow**ground connector for the Drive Activity API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/appsactivity/v1/swagger.json<br/>
Generated at: 2019-06-11T18:14:34+03:00

## API Description

Provides a historical view of activity.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of activities visible to the current logged in user. Visible activities are determined by the visiblity settings of the object that was acted on, e.g. Drive files a user can see. An activity is a record of past events. Multiple events may be merged if they are similar. A request is scoped to activities from a given Google service using the source parameter.

*Tags:* `activities`

#### Input Parameters
* `drive.ancestorId` - _optional_ - Identifies the Drive folder containing the items for which to return activities.
* `drive.fileId` - _optional_ - Identifies the Drive item to return activities for.
* `groupingStrategy` - _optional_ - Indicates the strategy to use when grouping singleEvents items in the associated combinedEvent object.
    Possible values: driveUi, none.
* `pageSize` - _optional_ - The maximum number of events to return on a page. The response includes a continuation token if there are more events.
* `pageToken` - _optional_ - A token to retrieve a specific page of results.
* `source` - _optional_ - The Google service from which to return activities. Possible values of source are: 
- drive.google.com
* `userId` - _optional_ - Indicates the user to return activity for. Use the special value me to indicate the currently authenticated user.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-appsactivity-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
