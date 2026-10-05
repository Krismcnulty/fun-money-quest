# Fun Money Quest

Do real-life tasks, earn points, redeem them for your fun money.

A single-page installable web app (PWA). Progress is stored on the device; use **Setup → Save backup** to keep a copy.

## Files
- `index.html`: the whole app
- `manifest.webmanifest`: makes it installable (name, icon, colours)
- `sw.js`: offline support
- `icons/`: app icons

## Updating
Change the files, commit and push. To make sure installed copies pick up the change, bump `CACHE` in `sw.js` (e.g. `fmq-v2`).
