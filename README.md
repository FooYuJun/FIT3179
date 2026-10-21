# Australia Marine Life

A responsive single-page marine biodiversity in Australia.

## What's included

- `index.html` — page header, introduction, first chart, and section placeholders
- `styles.css` — responsive ocean-inspired visual design
- `js/` — Vega-Lite specification for each chart
- `data/` — dataset supplied for this visualisation

## Run locally

Because the chart loads JSON files, serve the folder over HTTP rather than opening `index.html` directly.

Python:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository (for example `marine-observatory`).
2. Upload the contents of this folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for deployment and open the Pages URL shown in Settings → Pages.

## Technologies Used
HTML5 — Page structure and content.
CSS3 — Layout, typography, styling and responsive design.
JavaScript — Interactive webpage functionality.
Vega-Lite — Declarative specifications for data visualisation.
CSV — Storage of processed observation data.
Python HTTP server — Local development and testing.

## Created by
Foo Yu Jun
34074619
Updated on - 21/10/2026
