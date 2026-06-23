# Knight Tracker

Knight Tracker is a single-page fitness tracker for running, strength training,
nutrition, body measurements, progress photos, and weekly reviews.

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
`knightTrackerData`. Use the built-in export button before clearing browser
data or switching devices.

