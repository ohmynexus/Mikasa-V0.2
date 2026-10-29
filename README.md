# MIKASA V0.2 — Premium Offline

MIKASA Wireless Billing & Analytics, premium offline-first UI package.

## Files
- `index.html` — main single-file application
- `manifest.json` — progressive web app manifest
- `sw.js` — offline cache service worker
- `icon-192.png`, `icon-512.png` — application icons
- `OFFLINE-README.html` — Indonesian offline usage notes

## Usage
Serve this folder from HTTPS or localhost. Open `index.html` to use the app. Data is stored in the browser's local storage; back it up before clearing browser data or switching devices.

## Offline
Open the app once online to cache its local shell. Fonts may fall back to system fonts while offline. For spreadsheet imports, use CSV if the XLSX library is not cached.

Note: the GitHub connector in this workspace only writes text files, so binary PNG icons and the ZIP bundle still need upload via GitHub's web UI.