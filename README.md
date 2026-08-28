# Haunted CCTV — Night Watch

A procedural 3D haunted-surveillance scene designed for passive 24/7 YouTube Live capture.

## Features

- Six distinct surveillance locations
- Real-time Three.js 3D geometry, perspective, lighting and fog
- CRT scanlines, vignette and animated grain
- Randomized paranormal events with rarity tiers
- Rare apparition events and proximity events
- Camera switching with `1`–`6`
- Force a paranormal event with `M`
- Random camera with `Space`
- No backend and no finite end state
- Netlify-ready static deployment

## Deployment

The site is a static `index.html`. `netlify.toml` configures the repository root as the publish directory.

For YouTube Live, capture the deployed page with OBS at 1920×1080 and keep the browser source running continuously.
