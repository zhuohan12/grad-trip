# Graduation Trip 2026 — Rockies to the Pacific

An interactive itinerary website. `index.html` is a sidebar shell that loads each
leg's self-contained itinerary (with its own interactive maps) into a frame.

## Legs
1. Jasper — Jul 22–23
2. Icefields Parkway — Jul 24
3. Banff & Yoho — Jul 25–27
4. Glacier NP — Jul 28–31
5. Mount Rainier — Aug 1
6. Olympic NP — Aug 2–4

## Run locally
Just open `index.html` in a browser. (Or serve the folder: `python3 -m http.server`.)

## Structure
- `index.html` — sidebar + navigation shell
- `itineraries/` — one HTML file per leg
- `.nojekyll` — tells GitHub Pages to serve files as-is
