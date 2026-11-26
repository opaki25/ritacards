# Rita & Shepherd Invitation Studio

A mobile-friendly personalizer for the approved introduction invitation. Enter a guest name, preview it, and download a PNG. Includes adjustable name typography, automatic fitting for long names, a guest-list navigator, and native sharing on supported devices. Guest names are processed only in the browser.

## Run locally

Serve `dist` with any static server, for example `python -m http.server 5173 --directory dist`, then visit http://localhost:5173.

## Deploy on Vercel

Import this repository. The included `vercel.json` selects the `dist` output folder; no framework, dependencies, or build step are needed.

## Files

- `dist/index.html`: page and editor controls
- `dist/style.css`: responsive styles
- `dist/app.js`: canvas preview, name fitting, downloads, sharing, guest navigation
- `dist/card.png`: approved card, including the surface

Validation: JavaScript syntax check, browser name entry and live update, PNG download with visual inspection, and guest-list navigation.
