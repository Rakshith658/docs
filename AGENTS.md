# Documentation project instructions

## About this project

- This is the [Chat-Accounting](https://chataccounting.ai) documentation site, built on [Mintlify](https://mintlify.com)
- Chat-Accounting is a free and open source desktop accounting app; the source lives at [Rakshith658/chatAccounting](https://github.com/Rakshith658/chatAccounting)
- Pages are MDX files with YAML frontmatter
- Configuration and sidebar navigation live in `docs.json`
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify

## Terminology

- The product is **Chat-Accounting** — always hyphenated, never "Chat Accounting" or "Frappe Books"
- Content is adapted from Frappe Books; mention Frappe only in attribution contexts, never as the product name
- Use "company file" for the local `.db` file that holds a company's data
- Use "entry" for a saved record (Sales Invoice, Journal Entry) and "transaction" for entries that post to the ledger

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Use Mintlify callout components (`<Tip>`, `<Info>`, `<Warning>`, `<Danger>`) — never VitePress `:::` syntax

## Content boundaries

- Preserve the `sourceUrl` and `sourceUpdated` frontmatter fields; they record upstream provenance required for AGPL-3.0 attribution
- Store screenshots under `images/<section>/` and reference them with a root-relative path (`/images/settings/print-templates.png`)
- Every page must be listed in `docs.json` navigation, or Mintlify will treat it as orphaned
- Run `mint broken-links` before committing navigation or link changes
