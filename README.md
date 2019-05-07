# ![LOGO](logo.png) ART19 Content MSP Connector

## Description

A generated MSP connector for the ART19 Content API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/art19.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T11:17:14+03:00

## API Description

The ART19 Content API conforms to the JSON-API specification. Details and examples can be found at http://jsonapi.org. <br/><br/>API requests <b>MUST</b> use the HTTP Accept header:<br/><code>Accept: application/vnd.api+json</code><br/><br/>API requests <b>MUST</b> be authenticated using the HTTP Authorization header: <br/><code>Authorization: Token token="your-token", credential="your-credential"</code>

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Fetch resource collection

*Tags:* `ClassificationInclusion`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at

### Fetch resource

*Tags:* `ClassificationInclusion`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `Classification`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `type` - _optional_ - Filter by type
* `q` - _optional_ - Filter by value
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at, value, updated_at

### Fetch resource

*Tags:* `Classification`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `Credit`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `creditable_id` - _optional_ - Filter by creditable_id
* `creditable_type` - _optional_ - Filter by creditable_type
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at, position, updated_at

### Fetch resource

*Tags:* `Credit`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `Episode`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `series_id` - _optional_ - Filter by Series
* `season_id` - _optional_ - Filter by Season
* `q` - _optional_ - Filter by title
* `year` - _optional_ - Filter by released_at year
* `month` - _optional_ - Filter by released_at month
* `rss` - _optional_ - Filter by RSS episodes only
* `sort` - _optional_ - Sort by created_at, released_at, released_or_created_at, sort_title, title, updated_at

### Fetch resource

*Tags:* `Episode`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch next resource

*Tags:* `Episode`

#### Input Parameters
* `id` - _required_ - UUID
* `rss` - _optional_ - Filter by RSS episodes only

### Fetch previous resource

*Tags:* `Episode`

#### Input Parameters
* `id` - _required_ - UUID
* `rss` - _optional_ - Filter by RSS episodes only

### Fetch resource collection

*Tags:* `Image`

#### Input Parameters
* `ids[]` - _required_ - Filter by ID's
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at

### Fetch resource

*Tags:* `Image`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `MediaAsset`

#### Input Parameters
* `ids[]` - _required_ - Filter by ID's
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at

### Fetch resource

*Tags:* `MediaAsset`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `Network`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `q` - _optional_ - Filter by name
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at, name, updated_at

### Fetch resource

*Tags:* `Network`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `Person`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `q` - _optional_ - Filter by first_name and last_name
* `page[number]` - _optional_ - Filter by page number
* `exclude_ids[]` - _optional_ - Filter by excluding ids
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at, first_name, last_name, updated_at

### Fetch resource

*Tags:* `Person`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `Season`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `series_id` - _optional_ - Filter by Series
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `sort` - _optional_ - Sort by created_at, sort_title, title, updated_at

### Fetch resource

*Tags:* `Season`

#### Input Parameters
* `id` - _required_ - UUID

### Fetch resource collection

*Tags:* `Series`

#### Input Parameters
* `ids[]` - _optional_ - Filter by ID's
* `network_id` - _optional_ - Filter by Network
* `page[number]` - _optional_ - Filter by page number
* `page[size]` - _optional_ - Change page size
* `q` - _optional_ - Filter by title
* `sort` - _optional_ - Sort by created_at, episode_released_at, sort_title, title, updated_at

### Fetch resource

*Tags:* `Series`

#### Input Parameters
* `id` - _required_ - UUID

## License

flowground :- Telekom iPaaS / art-19-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
