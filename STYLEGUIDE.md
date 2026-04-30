# Style Guide

Editorial standards for maintainers and contributors.

## Tone
- Neutral, factual, concise.
- No marketing language, superlatives, or promotional phrasing.
- Write for a technically literate audience that values precision.

## Entry length
- **Description:** 1 sentence (2 max in exceptional cases).
- **Access notes:** 1 short line.

## Naming conventions
- **Category files:** lowercase kebab-case (e.g. `transport-and-mobility.md`).
- **Entry headings:** use the official source name as-is.
- **Status values:** fixed lowercase tokens from the defined set.

## Markdown formatting
- Category-level headings: `#` (one per file, the file title).
- Entry headings: `###`.
- Metadata fields: bulleted list with bold field names, in fixed order.
- One blank line between entries.
- No trailing whitespace.
- Use fenced code blocks only for literal technical values (endpoint URLs, format examples).

## Field order for entries
1. URL
2. Coverage
3. Type
4. Theme
5. Licence
6. Format
7. Access notes
8. Status
9. Description

## Link checking
- Validate all links before submitting.
- Re-check existing links during quarterly maintenance.

## Dead links
- If a replacement URL exists, update the entry and note the change in commit message.
- If no replacement is found, change status to `legacy` or move to `watchlist.md`.
- Never silently delete entries; leave a paper trail.

## Uncertainty
- Never guess licence terms. Mark as `Unclear` and add: "Licence terms not clearly stated at source."
- If data availability is intermittent, note it in Access notes.

## Avoiding drift
- Reject entries without clear Ireland relevance.
- Reject entries missing required metadata fields.
- Prefer fewer high-quality entries over bulk additions.
- When in doubt, add to `watchlist.md` first.
