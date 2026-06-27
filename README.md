# Travel Tracker

A minimal travel dashboard that lets you track which countries you've visited on an interactive world map.

## Features

- **Interactive world map** powered by Leaflet.js — click any country to mark it visited (blue) or unvisited (gray)
- **Sidebar stats** — live count of visited countries and percentage of the world covered
- **Add by name** — type a country name in the sidebar to add it without clicking the map
- **Remove anytime** — each visited country has a remove button in the sidebar list
- **Persists across sessions** — your selections are saved to `localStorage`
- **Light & dark mode** — follows your system preference via `prefers-color-scheme`

## Usage

Open `index.html` directly in a browser — no server or build step required. The GeoJSON map data is bundled locally so it works offline.

## Files

```
travel-tracker/
├── index.html                        # All HTML, CSS, and JS in one file
├── ne_110m_admin_0_countries.geojson # Natural Earth 110m country boundaries
├── README.md
└── .gitignore
```

## Tech

- Vanilla HTML / CSS / JavaScript — no frameworks, no build tools
- [Leaflet.js](https://leafletjs.com/) (CDN) for the map
- [Natural Earth](https://www.naturalearthdata.com/) 110m country GeoJSON for boundaries
- CartoDB tile layer for the base map
