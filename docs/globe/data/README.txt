Place data files here to serve without external network:

Required files (exact names):
- countries.geojson  (from datasets/geo-countries/data/countries.geojson)
- countries.json     (from mledoze/countries/countries.json)
Optional for faster, offline coastlines:
- land-50m.json      (from world-atlas@2/land-50m.json)
- land-110m.json     (from world-atlas@2/land-110m.json)
- countries-50m.json (from world-atlas@2/countries-50m.json)
- countries-110m.json(from world-atlas@2/countries-110m.json)

When present, the globe prefers these local files. Otherwise it falls back to CDN.
