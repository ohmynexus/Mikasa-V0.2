# MIKASA V0.2 — Premium Offline

Premium offline-first WiFi billing dashboard.

## Source package
Download `MIKASA-Premium-Offline-v0.2.zip` from the ChatGPT conversation and upload it to this repo using **Add file → Upload files**. The connected GitHub tool can commit text, but cannot upload binary ZIP/PNG files or write the full 114 KB HTML in one request.

## Included source files (expected)
- `index.html` — main app
- `manifest.json` — PWA manifest
- `sw.js` — offline service worker
- `icon-192.png`, `icon-512.png` — PWA icons
- `OFFLINE-README.html` — usage notes

## Usage
Serve over HTTPS or localhost for service worker support. Data remains in browser local storage; create periodic backups.