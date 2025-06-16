markdown
# MapTiles MCP Server

Welcome to the MapTiles MCP server, your reliable source for high-quality map tiles based on OpenStreetMap data. This server provides map tiles with labels in multiple languages, including English, French, and Spanish, allowing for versatile use in various applications and platforms.

## Overview

MapTiles is designed to offer seamless integration of multilingual map tiles for your web, mobile, or desktop applications. With coverage spanning the entire planet and 20 zoom levels (z0 - z19), MapTiles ensures detailed and accurate mapping for all your needs.

### Key Features

- **Multilingual Support:** Access map tiles with labels in English, French, or Spanish. This feature enhances accessibility and usability for diverse audiences.
- **High Performance:** Enjoy fast delivery and low latency with our edge servers distributed across continents.
- **Versatile Integration:** Use MapTiles with popular map frameworks and software like Leaflet, OpenLayers, QGIS, and more.
- **Customizability:** Choose standard tiles with local language labels for localized mapping needs.

### TileLayer URLs

MapTiles provides specific endpoints for different language labels, allowing you to select the best option for your audience:

- English Labels: `/en/map/v1/{z}/{x}/{y}.png`
- Spanish Labels: `/es/map/v1/{z}/{x}/{y}.png`
- French Labels: `/fr/map/v1/{z}/{x}/{y}.png`
- Local Language Labels: `/local/osm/v1/{z}/{x}/{y}.png`

### Tool Functions

The MapTiles server offers several functions to retrieve map tiles with desired language labels:

1. **get_map_tilewith_spanish_labels:**
   - Provides raster map tiles with Spanish labels.
   - Parameters: `z` (zoom level), `x`, `y` (tile coordinates).

2. **get_map_tilewith_english_labels:**
   - Provides raster map tiles with English labels.
   - Parameters: `z` (zoom level), `x`, `y` (tile coordinates).

3. **get_map_tilewith_french_labels:**
   - Provides raster map tiles with French labels.
   - Parameters: `z` (zoom level), `x`, `y` (tile coordinates).

4. **get_standard_map_tile:**
   - Provides standard tiles with labels in the local language.
   - Parameters: `z` (zoom level), `x`, `y` (tile coordinates).

### Usage Notes

- **Integration:** Ensure to configure the appropriate TileLayer in your map framework to utilize MapTiles effectively.
- **Attribution:** Proper attribution to OpenStreetMap contributors is required when displaying maps using MapTiles.
- **Customization:** For custom enterprise plans and high-volume requirements, please contact us for tailored solutions.

MapTiles offers a robust and flexible mapping solution with high-quality tiles and multilingual support, making it an ideal choice for developers and businesses seeking reliable map integration.