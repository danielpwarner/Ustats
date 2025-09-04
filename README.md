# Ultimate Team Analytics — Browser (GitHub Pages)

A pure front-end (HTML/JS) version that runs entirely in the browser. No server, no Python.
Just upload a CSV and explore.

## Deploy on GitHub Pages
1. Create a new repo and add these files at the repo root: `index.html`, `app.js`, `styles.css`.
2. Commit & push.
3. In your repo settings → **Pages** → set source to **main** branch (root), save.
4. Your app will be available at `https://<your-username>.github.io/<repo-name>/`.

> Note: Excel uploads are not supported on static pages. Save as CSV and upload.

## CSV schema (typical)
- Required columns (for best results): `Passer`, `Receiver`, `Defender`, `Action`
- Optional: `Line` (values like O/D), `Date` (or `Game Date` etc.), `Game`/`Opponent`

The app tries to **auto-detect** date/game/line columns with sensible fallbacks.

## Local test
Double-click `index.html` (or use a local static server). Then upload your CSV and play with the tabs/filters.
