# Life Beneath the Surface — Marine Observatory

A responsive single-page marine biodiversity data story built with HTML, CSS, JavaScript and Vega-Lite.

## What's included

- `index.html` — page header, introduction, first chart, and section placeholders
- `styles.css` — responsive ocean-inspired visual design
- `js/observations_over_time.vg.json` — Vega-Lite specification for the first chart
- `data/observations_by_year.csv` — annual record counts derived from the supplied occurrence CSVs

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

## Important interpretation note

The chart counts rows/records by calendar year; it does not estimate animal populations. The three supplied datasets cover different time ranges. A year missing for a dataset means no rows were available for that year in the supplied file, not necessarily zero marine life or zero observations worldwide.

## Before submission

- Replace `[Your name]` and `[Date]` in `index.html`.
- Add original dataset URLs, publishers and licence details to the page and README.
- Verify data provenance and whether each dataset is suitable for the assignment's requirement to use reliable, current data from two sources.
- Acknowledge generative AI use as required by the assignment.
- Continue building the remaining charts and include at least three different map idioms.
