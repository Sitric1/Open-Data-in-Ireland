# Migration Notes

This document tracks decisions made during the restructure from the original single-file format.

## Origin

The repository was forked from [`virtualarchitectures/Open-Data-in-Ireland`](https://github.com/virtualarchitectures/Open-Data-in-Ireland), a curated list of Irish open data sources maintained as a single README.

## Structural changes

1. Content split from one README into thematic files under `catalog/`.
2. Entry format standardized with metadata fields (URL, coverage, type, licence, status, etc.).
3. New categories added: Heritage & Culture, Research & Academic, 3D/LiDAR/Photogrammetry, Realtime Feeds, Commercial & Restricted, Watchlist.
4. Inactive links tagged `legacy` or moved to `watchlist` rather than deleted.
5. Governance files added: CONTRIBUTING.md, STYLEGUIDE.md, issue templates.

## Entry mapping from original README

| Original section | New location |
|-----------------|--------------|
| Open Data | `catalog/national-portals.md` |
| Spatial Data | `catalog/geospatial-and-mapping.md` |
| Property Data | `catalog/government-and-public-bodies.md` |
| Energy Data | `catalog/government-and-public-bodies.md` |
| Transport Data | `catalog/transport-and-mobility.md` |
| Tourism Data | `catalog/government-and-public-bodies.md` |
| Environment Data | `catalog/environment-and-climate.md` |
| Health And Wellbeing | `catalog/government-and-public-bodies.md` |
| Business Data | `catalog/government-and-public-bodies.md` |
| Cities > Dublin | `catalog/cities-and-regions.md` |
| Cities > Cork | `catalog/cities-and-regions.md` |
| Other Useful Links | Split across relevant categories |
| Service Providers | `catalog/commercial-and-restricted.md` |
