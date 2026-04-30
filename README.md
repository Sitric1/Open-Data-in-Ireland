# Ireland Data Catalogue

A curated, all-island index of high-value Ireland-related data sources, spanning open data, public datasets, APIs, realtime feeds, geospatial resources, and 3D capture materials.

## Scope

- **Geographic:** Republic of Ireland, Northern Ireland, and all-island topics.
- **Audience:** developers, researchers, mappers, OSINT analysts, heritage-tech practitioners, and civic data users.
- **Inclusion criteria:** discoverable, Ireland-relevant, and metadata-documented sources with clear access paths.

## Not in Scope

- Hosting raw datasets or mirrors.
- Scraping protected or authentication-gated sources.
- Generic global resources that lack meaningful Ireland relevance.

## Quick Navigation

| Category | Description |
|----------|-------------|
| [National Portals](catalog/national-portals.md) | State-scale discovery platforms |
| [Government & Public Bodies](catalog/government-and-public-bodies.md) | Official publishers with direct datasets/APIs |
| [Geospatial & Mapping](catalog/geospatial-and-mapping.md) | Basemaps, boundaries, map services |
| [Transport & Mobility](catalog/transport-and-mobility.md) | GTFS, realtime transit, traffic feeds |
| [Environment & Climate](catalog/environment-and-climate.md) | Weather, hydrology, air quality, marine |
| [Cities & Regions](catalog/cities-and-regions.md) | Local authority and city-level data hubs |
| [Heritage & Culture](catalog/heritage-and-culture.md) | Digital heritage, monuments, cultural archives |
| [Research & Academic](catalog/research-and-academic.md) | University datasets, institutional repositories |
| [3D, LiDAR & Photogrammetry](catalog/three-d-and-photogrammetry.md) | Point clouds, meshes, Gaussian splats, LiDAR |
| [Realtime Feeds & Operational](catalog/realtime-feeds-and-operational.md) | Live sensor networks, telemetry, streaming data |
| [Commercial & Restricted](catalog/commercial-and-restricted.md) | Useful but paid or licence-restricted sources |
| [Watchlist](catalog/watchlist.md) | Unvalidated, intermittent, or unclear-licence items |

## Status Labels

Each entry carries one of the following status tokens:

| Label | Meaning |
|-------|---------|
| `active` | Link works, data updated or operational, licence discoverable |
| `legacy` | Reachable but stale, partially broken, or superseded |
| `archived` | Intentionally frozen or offline; kept for reference |
| `unclear-licence` | Viewable but reuse terms not clearly stated |
| `commercial/non-open` | Paid, proprietary, or restricted access |
| `watchlist` | Not yet validated; pending review |

Full definitions: [docs/status-labels.md](docs/status-labels.md)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to add sources, report broken links, and maintain entries.

Use the [submission checklist](docs/submission-checklist.md) before opening a PR.

## Sourcing Standards

Entries must meet minimum criteria:

1. Clear Ireland relevance (ROI, NI, or all-island).
2. Licence stated or determinable.
3. Machine-readable access path (download, API, or service endpoint).
4. Not duplicating an entry already listed elsewhere in the catalogue.

## Attribution

This project originated as a fork of [`virtualarchitectures/Open-Data-in-Ireland`](https://github.com/virtualarchitectures/Open-Data-in-Ireland). It has since been reorganized with expanded scope, a new taxonomy, standardized entry metadata, and distinct editorial standards.

## Roadmap

- **Phase 1** — Restructure and scaffold (current).
- **Phase 2** — Normalize all existing entries with metadata blocks.
- **Phase 3** — Expand 3D/photogrammetry, heritage, and research categories.
- **Phase 4** — Licence audit and dead-link review.
- **Phase 5** — Ongoing maintenance cadence and community contributions.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for structural changes and major updates.
