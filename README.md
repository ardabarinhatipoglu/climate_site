# Regional Warming Outlook

Interactive map of projected regional temperature change (IPCC AR6 reference
regions) under SSP1-2.6 / SSP2-4.5 / SSP5-8.5, for near-term (2021-2040),
mid-term (2041-2060), and long-term (2081-2100) horizons.

## Run locally
    npm install
    npm run dev

## Build for production
    npm run build
This outputs static files to `dist/` — upload that folder to any static host.

## Deploy options
- **Vercel / Netlify**: drag-and-drop the `dist/` folder in their dashboard,
  or connect this repo and set build command `npm run build`, output dir `dist`.
- **GitHub Pages**: push this repo, then run `npm run build`, commit `dist/`
  to a `gh-pages` branch (or use the `gh-pages` npm package), and enable
  Pages in repo settings pointing at that branch.
- **Cloudflare Pages**: connect the repo, build command `npm run build`,
  output directory `dist`.

No backend, no API keys, no environment variables needed — it's a fully
static site.
