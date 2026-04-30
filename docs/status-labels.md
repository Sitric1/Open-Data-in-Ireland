# Status Labels

Every entry in the catalogue carries exactly one status label.

## Definitions

### `active`
The source is reachable, the data is being maintained or is still operational, and the licence or terms of use are discoverable at the source.

### `legacy`
The source is still reachable but exhibits one or more of: stale data, partially broken endpoints, superseded by a newer resource, or uses deprecated formats.

### `archived`
The source is intentionally frozen, taken offline, or only available via web archives. Kept in the catalogue for historical reference.

### `unclear-licence`
The data can be viewed or accessed but the licence or reuse terms are not clearly stated. Cannot be confidently classified as open data.

### `commercial/non-open`
The source is useful and Ireland-relevant but requires payment, registration with restrictive terms, or operates under a proprietary licence.

### `watchlist`
The entry has not been fully validated. Possible reasons: broken link pending investigation, intermittent availability, unconfirmed licence, or unresolved duplicate.

## Usage Rules

- Every entry must have exactly one status label.
- When status changes, update the entry and note the date in a commit message.
- Items on `watchlist` should be reviewed within 90 days; promote or remove.
