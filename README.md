# أمير سوفت — Repair Tracker

Offline-first PWA for tracking repair jobs (customer, device, issue, price, status, shelf). Arabic/English, no backend.

- Data lives in the browser's `localStorage` — **per device and per browser**. Use the in-app backup (export/import JSON) regularly.
- Clearing site data deletes everything.

## Deploy (GitHub Pages)
1. Push these files to a repo (e.g. `repair-tracker`).
2. Settings → Pages → Deploy from branch → `main` / root.
3. Open `https://ameeralshara.github.io/repair-tracker/` and use "Add to Home Screen".

## Files
`index.html` app · `manifest.json` PWA manifest · `sw.js` offline cache · `icon-*.png` icons · `.nojekyll`
