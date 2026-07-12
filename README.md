# Graduation Trip 2026 — Rockies to the Pacific

An interactive itinerary website. `index.html` is a sidebar shell that loads each
leg's self-contained itinerary (with its own interactive maps) into a frame.

## Legs
1. Sea to Sky — Jul 21
2. Jasper — Jul 22–23
3. Icefields Parkway — Jul 24
4. Banff & Yoho — Jul 25–27
5. Glacier NP — Jul 28–31
6. Mount Rainier & Seattle — Aug 1–3
7. Olympic NP — Aug 3–5
8. Return to Vancouver — Aug 6

## Run locally
Just open `index.html` in a browser. (Or serve the folder: `python3 -m http.server`.)

## Structure
- `index.html` — sidebar + navigation shell
- `itineraries/` — one HTML file per leg
- `.nojekyll` — tells GitHub Pages to serve files as-is
