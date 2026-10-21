# Leaflet Map Tutorial - HCI Milestone 1

## Source
This tutorial exercise is adapted from the official **Leaflet Quick Start Guide**:
https://leafletjs.com/examples/quick-start/

The original tutorial explains how to display a map, add markers/circles, show popups, and respond to map-click events. I used those features and changed the example location to Washington, DC. The map uses Leaflet 1.9.4 (loaded from a CDN) and OpenStreetMap map tiles with attribution.

## How to run
1. Make sure you have an internet connection (the map library and map tiles load online).
2. Double-click **index.html** to open it in Chrome, Edge, or Firefox.
3. The map should show Washington, DC. If the browser blocks local content, open a terminal in this folder, run `python -m http.server 8000`, and visit `http://localhost:8000`.

No accounts, API keys, or package installations are needed.

## What to demonstrate (about one minute)
1. Open index.html and show the map.
2. Zoom in or out and drag the map.
3. Click the marker and the blue circle to show their popups.
4. Click another point on the map to show its coordinates.

## Connection to my HCI project
My proposed project is a **hands-free interactive map**. This tutorial is just the first step toward learning how the map itself works. The voice controls, live location, and real navigation directions **are not implemented** in this tutorial demo.
