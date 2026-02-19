# Terrain Map Studio

A single-file interactive terrain map renderer that runs entirely in the browser.

**Live demo:** [submarat.github.io/terrain-map](https://submarat.github.io/terrain-map/)

## Requirements

- **Terrain rendering** — Fetch and render hillshaded elevation data for any location using Terrarium-encoded tiles from AWS
- **Viewport targeting** — Set latitude, longitude, zoom level, and tile grid size to control the rendered area
- **Text annotations** — Click to place text labels on the map with configurable font size, color, and weight
- **Dashed spline creation** — Click to place control points that form a smooth Catmull-Rom spline rendered with a configurable dashed stroke
- **No labels** — Terrain maps are rendered without any built-in labels or place names

## Features

- Entirely self-contained in a single `index.html` — no backend, no build step, no dependencies to install
- Pan and zoom the canvas with mouse drag and scroll wheel
- Select, drag, and delete annotations
- Adjustable spline stroke width, color, and dash pattern
- Export the final map with all annotations baked in as a PNG
- Keyboard shortcuts: **V** (pan), **T** (text), **S** (spline), **A** (select), **Escape** (deselect), **Delete** (remove)

## Hosting

Drop `index.html` on any static file host — GitHub Pages, Netlify, S3, or just open it locally in a browser.
