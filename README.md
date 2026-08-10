# West Cape May Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the West Cape May municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01411390, Cape May Harbor
- PETSS / NOAA station: 8536110
- NAVD88 thresholds: 3.68 ft minor, 4.68 ft moderate, 5.68 ft major
- MLLW thresholds: 6.7 ft minor, 7.7 ft moderate, 8.7 ft major
- MLLW = NAVD88 + 3.02 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the West Cape May Borough boundary at 5-foot resolution.
