# Reef Tracker

A personal, offline-first web app for tracking reef-tank water chemistry — weekly test logging,
quarterly Triton ICP import with best-practice re-interpretation (no false trace-element red flags),
target ranges by tank type, and trend charts.

Single self-contained file (`index.html`), no build step, no dependencies, all data stored locally
on the device.

## Use on a phone
Open the hosted page in Chrome → **⋮ menu → Install app / Add to Home screen**. It then runs
full-screen and offline. Data lives only on that device — use **Settings → Export backup** periodically.

## Hosting
Served via GitHub Pages from the `main` branch, root folder. Because everything is inline (no absolute
paths), it works at any URL/base path.
