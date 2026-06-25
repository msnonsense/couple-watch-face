# STATUS

_Last updated: 2026-06-25._

**Live and deployed.** This repo is the public, app-only deployment of the Couple
Watch Face Generator, served via GitHub Pages at:

**https://msnonsense.github.io/couple-watch-face/**

Verified working end to end: the page serves over HTTPS, the embedded font loads,
the watch face renders, and it installs to the iPhone home screen (Safari ▸ Share
▸ Add to Home Screen) and runs offline.

## What's here

Static app only: `index.html` (self-contained, font embedded),
`manifest.webmanifest`, `sw.js` (offline cache), `icons/`, `fonts/OFL.txt`.
Canonical development and the full project notes live in a separate private repo.

## Updating the live app

1. Replace the app files here (and bump the `CACHE` constant in `sw.js`, e.g.
   `watch-face-v2`, so installed copies pick up the change).
2. Commit and push to `main`; GitHub Pages redeploys automatically.
