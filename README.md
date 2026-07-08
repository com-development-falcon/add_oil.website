# addoil.bagging.app

Data endpoint for the 加油 (Add Oil) iOS app.

- `v1/quotes.json` — the live quote library the app fetches. **Do not move or rename this URL**; shipped apps hardcode `https://addoil.bagging.app/v1/quotes.json`.
- `_redirects` — forwards the old marketing/privacy/terms pages to the Studio site (`studio.bagging.app/add-oil/…`), which is now the source of truth for those.

To update quotes: edit `v1/quotes.json`, commit, and deploy (`wrangler pages deploy . --project-name add-oil-website`).
