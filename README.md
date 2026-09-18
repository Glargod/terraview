# Terraview

Map on top. Live elevation mesh underneath. Pan or zoom the map and the mesh follows.

## Use

Open `index.html` (GitHub Pages or any static host).

- Search or tap a preset
- Tilt with **3D**
- Live mesh samples AWS Terrarium DEM for the current viewport
- Uncheck **Follow map** to freeze the mesh
- **Forge 3D model** opens a higher-res studio with OBJ / GLTF export
- **Pin likely beds** is a terrain-only guess (southish mid-slopes)

## Data

- Elevation: AWS Terrain Tiles (Terrarium, no key)
- Basemaps: Esri + OpenTopoMap
- Geocode: Nominatim

No build step. Vanilla HTML / CSS / JS + MapLibre + Three.js.
