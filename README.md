# Luna South — Lunar South Pole Navigator

A lightweight, browser-based interactive 3D exploration interface for lunar south-pole landing sites.

## Run locally

Serve the repository directory with any static web server, then open the site in a modern browser with WebGL enabled. For example:

```bash
python -m http.server 8000
```

Open `http://localhost:8000`. Three.js and OrbitControls are loaded from jsDelivr, so an internet connection is required.

## Features

- Interactive 3D terrain with crater relief, surface rocks, a modeled lunar lander, and a small rover.
- Preset Shackleton Rim, Malapert Massif, and De Gerlache Rim sites, plus editable custom coordinates.
- Date/time and lunar-phase controls, with a playback animation.
- Estimated solar elevation, illumination, Earth visibility, sunset timing, and a one-lunar-day chart.
- Optional comparison against a second landing site; orbit, pan, zoom, and top-view controls.

## Important note

This is an illustrative concept and its terrain, lighting, Earth visibility, and environmental metrics are simplified procedural estimates. They are not sourced from mission-grade elevation/ephemeris datasets and must not be used for mission planning or safety-critical decisions. Terrain height is exaggerated for readability.
