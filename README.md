# addoil.bagging.app

The 加油 (Add Oil) product site + the app's live data endpoint.

- `index.html` / `privacy.html` / `tos.html` — the Add Oil marketing + legal pages (Add Oil's own dawn theme). The App Store support/marketing/privacy URLs point here.
- `v1/quotes.json` — the live quote library the app fetches. **Never move or rename this URL**; shipped apps hardcode `https://addoil.bagging.app/v1/quotes.json`.

Add Oil is a Bagging Studio product; the studio links here from studio.bagging.app.
Deploy: `wrangler pages deploy . --project-name add-oil-website`.
