# Contributing

Thank you for helping improve the Ireland Data Catalogue. This guide explains how to add sources, report issues, and maintain entries.

## Adding a new source

1. **Check it does not already exist.** Search the `catalog/` files and `watchlist.md`.
2. **Choose the correct category file** using the [taxonomy](docs/taxonomy.md).
3. **Use the standard entry format** (below).
4. **Complete the [submission checklist](docs/submission-checklist.md).**
5. **Open a pull request** with a clear title (e.g. "Add: Marine Institute wave buoy data").

## Entry template

```md
### Source Name
- **URL:** https://example.org
- **Coverage:** ROI | NI | All-island | Local (name)
- **Type:** Portal | API | Dataset | Map service | Viewer | Archive | Project
- **Theme:** Transport | Environment | Geospatial | Heritage | 3D | ...
- **Licence:** e.g. CC BY 4.0 / OGL / Custom / Unclear
- **Format:** CSV, JSON, GeoJSON, WMS, GTFS, LAS/LAZ, 3D Tiles, etc.
- **Access notes:** API key required / bulk download / rate limits / account needed
- **Status:** active | legacy | archived | unclear-licence | commercial/non-open | watchlist
- **Description:** One concise sentence about what is accessible and why it is useful.
```

## Reporting a broken link

Use the [broken link issue template](.github/ISSUE_TEMPLATE/report-broken-link.yml) or open a PR that:
- Changes the entry status to `legacy` or moves it to `watchlist.md`.
- Notes the date and error observed.

## Updating an existing entry

- Fix URLs, licence info, or status labels via PR.
- Include a brief explanation in the PR description.

## Style rules

- Follow the [Style Guide](STYLEGUIDE.md).
- Keep descriptions to 1-2 factual sentences.
- Never guess licence terms — use `Unclear` if in doubt.
- Place uncertain entries in `watchlist.md` rather than a main category.

## What does NOT belong

- Sources without meaningful Ireland relevance.
- Entries missing required metadata fields.
- Duplicate entries (link to existing instead).
- Marketing pages or data vendors without accessible data.

## Maintenance rhythm

- **Monthly:** quick triage of reported broken links.
- **Quarterly:** full link check and status review across all category files.
- **As needed:** promote or remove watchlist items (90-day target).
