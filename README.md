
# Lab 3: Calgary Building Permits Map
- **Name:** Mitchell Aitken
- **Class:** ENGO 551
- **Date:** February 27th, 2024

This is a simple map app I put together for ENGO 551 - Advanced Geospatial Topics. It shows building permits in Calgary on a map.

## What's Inside?
- A map that lets you see building permits in Calgary. You can pick dates to see permits from different times.
- It groups a bunch of permits together if they're super close, so the map isn't a huge mess. This is called "marker clustering".
- If markers are on top of each other, it spreads them out like a spider's legs so you can click on them. This is thanks to the "Overlapping Marker Spiderfier".

## Technical details
- We're using Leaflet.js for the map part – it's a JavaScript library for making interactive maps.
- For the clustering, it uses Leaflet.markercluster.
- For the spider-leg thing, it uses OverlappingMarkerSpiderfier.

## Usage
Just open the `index.html` in your browser, and you should see the map. You can pick start and end dates to filter the permits shown on the map.

