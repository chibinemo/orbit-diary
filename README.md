# Orbit Diary

Real-time QZSS (Michibiki) satellite tracker PWA with "oshi" personality system.

## Live Demo

**https://chibinemo.github.io/orbit-diary/realtime.html**

## Features

- Real-time satellite position tracking (1-second updates)
- SGP4 orbital propagation via satellite.js
- TLE data from CelesTrak (with offline fallback)
- Sky plot visualization
- Subsatellite point reverse geocoding (prefecture-level for Japan)
- "Oshi" satellite selection with personality narratives
- PWA: installable, works offline

## Tech Stack

- Vanilla HTML/CSS/JS (no framework)
- [satellite.js](https://github.com/shashwatak/satellite-js) for SGP4 propagation
- CelesTrak NORAD TLE data
- Service Worker for offline caching

## QZSS Constellation

| Satellite | Type | Orbit |
|-----------|------|-------|
| QZS-2 | QZO | Figure-8 (incl. 39.5°) |
| QZS-4 | QZO | Figure-8 (incl. 40.1°) |
| QZS-1R | QZO | Figure-8 (incl. 37.3°) |
| QZS-3 | GEO | Geostationary (incl. 0.06°) |
| QZS-6 | GEO | Geostationary (incl. 0.02°) |

## License

MIT
