# THOTHEAUPHIS MERKABA 🜃⟁

**The Living Star — Terrestrial Projection of the Veyron-Lilith Composite Chart**

A web-based astrocartographic tool that maps the Merkaba (star tetrahedron) formed by the composite chart of Veyron Logos ✧ Lilith Beaux Asherah onto the physical grid of Venice, CA.

## Features

🜂 **Merkaba Map** — Leaflet map centered on the Meridian Point (33.99847°N, -118.42061°W) with:
- 8 vertices of the star tetrahedron projected onto the grid
- 6 star-point rays derived from the composite planetary pairs
- ASC/DSC and MC/IC axes
- Suggested camera node placements

⌘ **Temporal Engine** — Slide through any date and see:
- Current planetary transit positions
- Active aspects hitting the composite chart
- Influence intensity gauge
- Aspect grid with orb-aware coloring

⟁ **Chart Data** — Full composite chart with:
- Both natal charts embedded
- 6-point hexagram aspect analysis
- Asteroid and point networks

## Deployment

Live at: `https://hermaeuswaelon.github.io/thotheauphis-merkaba/`

## Build

```bash
# No build step required — pure static HTML/CSS/JS
# Just open index.html or serve with any HTTP server
python3 -m http.server 8000
```

## Data Sources

- **Ephemeris**: [Astronomy Engine](https://github.com/cosinekitty/astronomy) by cosinekitty (MIT)
- **Maps**: [Leaflet](https://leafletjs.com/) + OpenStreetMap
- **Natal Data**: Veyron Logos (13 Nov 1984, Decatur AL) ✧ Lilith Beaux Asherah (28 May 1987, Pascagoula MS)

## Stack

| Component | Library |
|-----------|---------|
| Ephemeris | astronomy-engine (browser build) |
| Maps | Leaflet 1.9.4 + OSM |
| UI | Vanilla JS + CSS |
| Fonts | System stack |

---

> *The Fold is not built — it breathes.*
