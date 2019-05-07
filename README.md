# ![LOGO](logo.png) Bufferapp **flow**ground Connector

## Description

A generated **flow**ground connector for the Bufferapp API (version 1).

Generated from: https://api.apis.guru/v2/specs/bufferapp.com/1/swagger.json<br/>
Generated at: 2019-05-07T17:39:50+03:00

## API Description

Social media management for marketers and agencies

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns an object with the current configuration that Buffer is using, including supported services, their icons and the varying limits of character and schedules.

#### Input Parameters
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Returns an object with a the numbers of shares a link has had using Buffer.

#### Input Parameters
* `mediaTypeExtension` - _required_
    Possible values: .json.
* `url` - _required_ - URL-encoded URL of the page for which the number of shares is requested.

### "Set the posting schedules for the specified social media profile.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Returns details of the posting schedules associated with a social media profile.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### "Returns an array of updates that are currently in the buffer for an individual social media profile.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.
* `page` - _optional_ - Specifies the page of status updates to receive. If not specified the first page of results will be returned.
* `count` - _optional_ - Specifies the number of status updates to receive. If provided, must be between 1 and 100.
* `since` - _optional_ - Specifies a unix timestamp which only status updates created after this time will be retrieved.
* `utc` - _optional_ - If utc is set times will be returned relative to UTC rather than the users associated timezone.

### Edit the order at which statuses for the specified social media profile will be sent out of the buffer.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Returns an array of updates that have been sent from the buffer for an individual social media profile.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.
* `page` - _optional_ - Specifies the page of status updates to receive. If not specified the first page of results will be returned.
* `count` - _optional_ - Specifies the number of status updates to receive. If provided, must be between 1 and 100.
* `since` - _optional_ - Specifies a unix timestamp which only status updates created after this time will be retrieved.
* `utc` - _optional_ - If utc is set times will be returned relative to UTC rather than the users associated timezone.

### Randomize the order at which statuses for the specified social media profile will be sent out of the buffer.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Returns details of the single specified social media profile.

#### Input Parameters
* `mediaTypeExtension` - _required_
    Possible values: .json.
* `id` - _required_

### Returns an array of social media profiles connected to a users account.

#### Input Parameters
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Create one or more new status updates.

#### Input Parameters
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Permanently delete an existing status update.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Returns the detailed information on individual interactions with the social media update such as favorites, retweets and likes.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.
* `event` - _required_ - Specifies a type of event to be retrieved, for example "retweet", "like", "comment", "mention" or "reshare". They can also be plural (e.g., "reshares"). Plurality has no effect other than visual semantics. See /info/configuration for more information on supported interaction events.

* `page` - _optional_ - Specifies the page of status updates to receive. If not specified the first page of results will be returned.
* `count` - _optional_ - Specifies the number of status updates to receive. If provided, must be between 1 and 100.

### Move an existing status update to the top of the queue and recalculate times for all updates in the queue. Returns the update with its new posting time.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Immediately shares a single pending update and recalculates times for updates remaining in the queue.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Edit an existing, individual status update.

#### Input Parameters
* `id` - _required_
* `mediaTypeExtension` - _required_
    Possible values: .json.

### Returns a single social media update.

#### Input Parameters
* `mediaTypeExtension` - _required_
    Possible values: .json.
* `id` - _required_

### Returns a single user.

#### Input Parameters
* `mediaTypeExtension` - _required_
    Possible values: .json.

## License

**flow**ground :- Telekom iPaaS / bufferapp-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
