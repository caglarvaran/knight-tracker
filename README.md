# Knight Tracker

Knight Tracker v12.0.0 — Visual Dashboard Release is a single-page fitness
tracker for running, strength training, nutrition, body measurements, progress
photos, and weekly reviews.

V12 keeps the V11 data-safe foundation and adds a more visual dashboard:

- Visual KPI cards for running, training, nutrition, body, and 10K readiness
- Recent Activity Feed instead of plain recent-log pills
- Weekly Report tab with rule-based coach comments
- Built-in SVG charts with no external libraries
- Achievement-style milestone badges
- Mobile-friendly visual summaries above data tables
- GitHub Pages compatibility with no build step

## Run locally

Open `index.html` in a browser.

For a local server:

```bash
npx serve .
```

## GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to `Settings` -> `Pages`.
3. Set the source to the `main` branch and the root folder.
4. Open the published GitHub Pages URL.

## Data storage

The app stores data in the browser using `localStorage` under the key
`knightTrackerData`.

V12 preserves the V11 versioned data model and migration framework. Old V10/V10.3
exports remain importable, and V11 data continues to load under the same storage
key. Use the built-in export button before clearing browser data, switching
devices, or updating the live GitHub Pages version.
