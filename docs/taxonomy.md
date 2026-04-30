# Taxonomy

This document defines the category structure used in `catalog/`.

## Categories

### 1. National Portals
- **Belongs:** state-scale umbrella catalogues (CKAN instances, ArcGIS hubs, official open-data portals).
- **Does not belong:** individual APIs or one-off datasets from those portals.

### 2. Government & Public Bodies
- **Belongs:** official publishers (agencies, departments, regulators) offering direct datasets or APIs outside major portals.
- **Does not belong:** community mirrors or unofficial scrapes of official data.

### 3. Geospatial & Mapping
- **Belongs:** basemaps, boundary datasets, INSPIRE services, map tile services, geodata hubs.
- **Does not belong:** non-spatial tabular data that happens to include a location column.

### 4. Transport & Mobility
- **Belongs:** GTFS/GTFS-RT feeds, rail and bus APIs, traffic sensor data, cycling infrastructure data.
- **Does not belong:** static transport policy documents without machine-readable data.

### 5. Environment & Climate
- **Belongs:** weather forecasts/observations, hydrology, air/water quality, marine telemetry.
- **Does not belong:** policy reports without downloadable data endpoints.

### 6. Cities & Regions
- **Belongs:** city or county data portals, local authority open-data initiatives.
- **Does not belong:** national datasets duplicated here (cross-reference instead).

### 7. Heritage & Culture
- **Belongs:** monument inventories, digitized collections with structured metadata, cultural archives with data access.
- **Does not belong:** editorial tourism content without reusable data.

### 8. Research & Academic
- **Belongs:** university/research-lab datasets, reproducible data repositories, data papers.
- **Does not belong:** papers behind paywalls with no downloadable dataset.

### 9. 3D, LiDAR & Photogrammetry
- **Belongs:** point clouds, mesh reconstructions, Gaussian splats, LiDAR collections, 3D Tiles, photogrammetry outputs.
- **Does not belong:** 2D-only raster map tiles.

### 10. Realtime Feeds & Operational
- **Belongs:** frequently updated machine-readable feeds (sub-hourly or continuous).
- **Does not belong:** monthly or quarterly batch releases.

### 11. Commercial & Restricted
- **Belongs:** Ireland-relevant data sources that are useful but require payment or carry restrictive licences.
- **Does not belong:** sources that are fully open (place those in their thematic section).

### 12. Watchlist
- **Belongs:** potentially valuable entries not yet validated (broken link, unclear licence, unconfirmed access).
- **Does not belong:** entries confirmed to be permanently dead or irrelevant.

## Cross-listing

An entry appears in exactly one category file. If it spans multiple themes, place it in the most specific category and add a cross-reference note.
