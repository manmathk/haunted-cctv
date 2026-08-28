# Haunted CCTV

Procedural, passive-viewing 3D-inspired CCTV horror scene designed for browser playback and 24/7 YouTube Live capture.

## Features

- Six switchable surveillance cameras
- Procedural paranormal events with randomized timing
- CRT scanlines, vignette, noise and signal flashes
- Live clock and surveillance HUD
- Keyboard shortcuts: `1`–`6` cameras, `M` manual motion event
- No external build system or server required
- Static-host friendly for Netlify and GitHub Pages

## Local use

Open `index.html` directly in a browser, or serve the folder with any static web server.

## YouTube Live

Open the deployed site in Chrome/Edge, hide browser UI, use a 16:9 capture region in OBS, and leave the scene running. Camera selection is optional; the procedural event system continues indefinitely.

## Deployment

This project is intentionally static. Netlify can serve the repository root directly with no build command and no publish-directory transformation required.
