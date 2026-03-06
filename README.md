# 🌏 Visa-Free Travel Overlap: HK × Taiwan

Interactive world map showing visa-free, visa-on-arrival, and eVisa destinations for both **HKSAR** and **Taiwan** passport holders.

## Live Demo

👉 **[View the map](https://<your-username>.github.io/hk-tw-travel-destination/)**

## What This Shows

- **143 overlapping destinations** where both passport holders can enter without a traditional paper visa
- **30 HK-only** destinations (visa-free for HKSAR but not Taiwan passports)
- **17 Taiwan-only** destinations (visa-free for Taiwan but not HKSAR passports)

Filter by category, search by country name, and tap any dot on the map to see the country.

## Data Sources

| Source | Updated |
|--------|---------|
| [HK Immigration Department](https://www.immd.gov.hk/eng/service/travel_document/visa_free_access.html) | 2026-02-02 |
| [Taiwan BOCA](https://www.boca.gov.tw/) | 2026-03-04 |

## Tech Stack

Single `index.html` file — no build step, no dependencies to install.

- React 18 (CDN)
- D3.js v7 (CDN) — Natural Earth projection
- [world-atlas](https://github.com/topojson/world-atlas) TopoJSON for country outlines
- Google Fonts (DM Sans, JetBrains Mono)

## Deploy

### GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages → Source** → select `main` branch, `/ (root)`
3. Site goes live at `https://<username>.github.io/hk-tw-travel-destination/`

### Cloudflare Pages

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Create project → **Direct Upload** → drag the `index.html`
3. Site goes live at `https://hk-tw-travel-destination.pages.dev`

## Disclaimer

This map is for reference only. Actual visa requirements, entry conditions, and stay durations vary — always verify with official sources before travel.

## License

MIT
