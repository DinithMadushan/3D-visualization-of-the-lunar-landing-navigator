# LUNA SOUTH — Polar Operations Planner

A static browser-based concept demonstrator for exploring lunar south-pole landing sites and visualizing simplified mission-environment trade-offs.

## Run locally

Serve the repository directory with a static web server and open it in a modern WebGL-capable browser:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`. Three.js and OrbitControls are imported from jsDelivr, so an internet connection is required.

## Included

- Interactive Three.js local terrain viewer with selectable mesh resolution, crater bowls, raised rims, ejecta, seeded multiscale relief, rocks, lander, and rover.
- Reference locations for Shackleton Rim, Malapert Massif, and De Gerlache Rim, plus editable custom coordinates.
- A 2D polar surface-map canvas with elevation/shaded relief, slope-risk, solar-illumination, and corridor overlays.
- Date/time and synodic phase controls, animation, and a lunar-month illumination profile.
- A simplified analytical Sun–Moon direction model and approximate Earth libration/visibility model driving the 3D scene and dashboard.
- Configurable approach bearing and corridor length, terrain slope sampling, route visualization, and screening flags for steep segments.
- Operations dashboard with solar elevation, normalized direct-power index, Earth line-of-sight estimate, and route slope assessment.

## Data and safety limitations

This is a conceptual simulation, not a mission-planning or navigation system. The terrain is deterministic procedural relief, not a measured LOLA/SLDEM digital elevation model. The site coordinates are illustrative reference points. Sun/Moon geometry and Earth libration are simplified analytical approximations rather than a validated high-precision ephemeris. The map, slope calculations, power index, communication visibility, and corridor checks are illustrative and omit many operational constraints. They are not certified, must not be used for flight design, landing decisions, or safety-critical work, and should be replaced with validated datasets and models before any engineering use.
