# geog458-labs
Lab exercises for GEOG 458: Digital Geography.
# Lab 3: 
Madhuri Parasa

## Map 1: Puget Sound PM2.5 (madhuri_lab3-1.html)
- **Basemap:** Mapbox Light, with commercial POIs filtered out and freeways darkened.
- **Raster:** IDW of 11 EPA PM2.5 monitors, July 5, 2025 (µg/m³).
- **Points:** Monitoring stations with popups.
- **Source:** U.S. EPA AirData.

## Map 2: LA Basin Ozone, 2019 (madhuri_lab3-2.html)
- **Basemap:** Mapbox Outdoors.
- **Raster:** IDW of 30 EPA ozone monitors, 2019 (ppm). Ozone is highest inland, where mountains trap smog.
- **Points:** Ozone monitors with popups.
- **Source:** U.S. EPA AirData, annual_conc_by_monitor_2019.csv, filtered in QGIS to LA-area ozone monitors.

## Methods
- IDW: P = 2, 250 m pixels, EPSG:32610.
- Tiles: QMetaTiles, zoom 8–12, 256 px PNG, XYZ.
- IDW surfaces are estimates, not measurements. Popups show the measured values.