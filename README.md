# Knight Tracker

Knight Tracker v11.0.0 — Foundation Release is a single-page fitness tracker
for running, strength training, nutrition, body measurements, progress photos,
and weekly reviews.

V11 focuses on data safety and maintainability:

- Versioned data model
- Migration framework for V10/V10.3 data
- Data Safety panel
- Improved backup, import, and export behavior
- Standardized edit/delete behavior
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

V11 keeps old V10/V10.3 exports importable and migrates older fields into the
new versioned structure. Use the built-in export button before clearing browser
data, switching devices, or updating the live GitHub Pages version.
