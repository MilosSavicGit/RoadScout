# cultural-map
Find cultural attractions along your driving route

A trip-planning web app that scans your driving route for cultural attractions worth stopping for — historic sites, museums, viewpoints, monuments, and more — listed in the order you'll reach them along the way.

## What it does

- Enter a start and destination, and see the available driving routes.
- Pick a route, and the app scans a corridor along it for nearby points of interest.
- Each attraction shows a description and photo (pulled from Wikipedia, in the local language where available) plus how far it is into the trip and off the route.
- Rate places you've visited: Worth it / Meh / Skip it.

## How it works

Built as a single self-contained HTML file using free, open mapping services:
- **OSRM** for routing
- **OpenStreetMap (Overpass API)** for points of interest
- **Wikipedia / Wikidata** for descriptions and images
- **MapLibre GL** for the map display

## Status

Early prototype — works on short-to-medium routes across most of the world. A work in progress.
