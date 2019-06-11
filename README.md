# ![LOGO](logo.png) LetMC Api V3, reporting **flow**ground Connector

## Description

A generated **flow**ground connector for the LetMC Api V3, reporting API (version v3-reporting).

Generated from: https://api.apis.guru/v2/specs/letmc.com/reporting/v3-reporting/swagger.json<br/>
Generated at: 2019-06-06T16:12:26+03:00

## API Description



## Authorization

Supported authorization schemes:
- API Key- Basic Authentication

## Actions

### Return a collection of mortgages by created date from a specific date

*Tags:* `ReportingController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `branchID` - _required_ - The unique ID of the Branch
* `startDate` - _required_ - The date to search from.
* `offset` - _required_ - The index of the first item to return
* `count` - _required_ - The maximum number of items to return (up to 1000 per request)

### Return a collection of all mortgages updated from a specific date

*Tags:* `ReportingController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `branchID` - _required_ - The unique ID of the Branch
* `startDate` - _required_ - The date to search from.
* `offset` - _required_ - The index of the first item to return
* `count` - _required_ - The maximum number of items to return (up to 1000 per request)

### Return a collection of repossessions by created date from a specific date

*Tags:* `ReportingController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `branchID` - _required_ - The unique ID of the Branch
* `startDate` - _required_ - The date to search from.
* `offset` - _required_ - The index of the first item to return
* `count` - _required_ - The maximum number of items to return (up to 1000 per request)

### Return a collection of all reposessions updated from a specific date

*Tags:* `ReportingController`

#### Input Parameters
* `shortName` - _required_ - The unique client short-name
* `branchID` - _required_ - The unique ID of the Branch
* `startDate` - _required_ - The date to search from.
* `offset` - _required_ - The index of the first item to return
* `count` - _required_ - The maximum number of items to return (up to 1000 per request)

## License

**flow**ground :- Telekom iPaaS / letmc-com-reporting-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
