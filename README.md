# Project ReCharge — Multi-page Documentation Website

Static GitHub Pages website with six separate HTML pages.

## Pages
- `index.html` — Overview
- `research.html` — Research & Impact
- `product.html` — Phoenix Pack
- `automation.html` — Automation
- `business.html` — Business & Partners
- `management.html` — Project Management

The shared design is in `styles.css`, functionality and cross-page search in `script.js`, and searchable documentation data in `content.json`. To edit published text, update the relevant HTML page **and** the corresponding entry in `content.json` for search consistency.

## Publish
Upload all files in this folder to the repository root. In GitHub repository Settings → Pages, choose Deploy from a branch → main → /(root). No build step required.

Run a local preview with `python -m http.server 8000` and open `http://localhost:8000`.
