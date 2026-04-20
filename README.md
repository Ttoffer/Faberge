# Images - Faberge

This folder contains a branded `index.html` scene showing a stylized 3D Faberge-style egg on an ornate stand.

## Included behaviour

- The stand and egg rotate slowly for a museum-display effect.
- After 5 seconds, the egg opens gradually.
- The interior reveals a decorative setting with a central diamond ring.
- The ring and gem sparkle with animated lighting.
- A **Reset Animation** button restarts the full sequence.

## Files

- `index.html` - Main 3D page (Three.js via CDN).
- `header-logo.svg` - Standard Hal AI by CJF logo.
- `README.md` - Project notes.

## How to run

Open `index.html` in a modern browser with internet access (needed for the Three.js CDN import).

## Notes

- This is a single-file front-end scene with no build step.
- If you want offline operation, download Three.js locally and replace the CDN import path in `index.html`.
