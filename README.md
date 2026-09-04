# Chat-Accounting documentation

The documentation site for [Chat-Accounting](https://chataccounting.ai), built with [Mintlify](https://mintlify.com).

Chat-Accounting is free and open source desktop accounting software for small businesses and freelancers. The app lives at [Rakshith658/chatAccounting](https://github.com/Rakshith658/chatAccounting).

## Local development

Install the Mintlify CLI and run the dev server from this directory:

```bash
npm i -g mint
mint dev
```

The site opens at `http://localhost:3000`.

## Checks

```bash
mint broken-links
```

## Structure

- `docs.json` — site config and sidebar navigation
- `*.mdx` — one file per documentation page
- `images/` — page screenshots, referenced as `/images/<section>/<file>`
- `logo/` — navbar wordmark (`light.svg`, `dark.svg`); `favicon.svg` is the app icon

## Attribution

This documentation is adapted from the [Frappe Books documentation](https://docs.frappe.io/books) and is distributed under **AGPL-3.0**, matching the application license. Every page keeps a `sourceUrl` field in its frontmatter recording the upstream page it came from — please preserve these when editing.
