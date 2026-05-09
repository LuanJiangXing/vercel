# South Africa RegionGuessing

An interactive map for exploring and guessing South African regions. Built with [Leaflet](https://leafletjs.com/) and OpenStreetMap tiles.

## How it works

- The map displays regions across South Africa, each defined by a GeoJSON polygon.
- Hover over a region to see its name and a short description.
- Click a region to open a detail view with a photo and a Google Maps link.
- Region data is loaded from `data.json`.

## Data

Each region entry in `data.json` includes:

| Field         | Description                                      |
|---------------|--------------------------------------------------|
| `name`        | Region name (underscores are displayed as spaces) |
| `nickname`    | Short label shown on the map                     |
| `geojson`     | Polygon coordinates defining the region boundary |
| `description` | Brief landscape / terrain description            |
| `image`       | Photo filename in the `images/` directory        |
| `link`        | Google Maps link to the location                 |

## Files

```
index.html   — main page with map and modal UI
data.json    — region data (names, polygons, descriptions, images)
images/      — location photos (1.png – 10.png)
README.md    — this file
```

## Future plans

- Add more UI features
- Expand region coverage across South Africa
- Extend to other countries
- Contributions and ideas are welcome
