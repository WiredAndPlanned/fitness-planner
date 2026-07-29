# Fitness Planner — WiredAndPlanned

Lightweight build for hosting (GitHub Pages / any static host).

## Files
- index.html  — the app
- support.js  — runtime (must sit beside index.html)
- image-slot.js — photo-slot component

Total ~290 KB. Fonts and icons load from CDN, so this needs an internet
connection. For a fully offline single file use the standalone bundle
("Fitness Planner App (responsive).html", ~7 MB — it has every font embedded).

## GitHub Pages
Push these three files, then enable Pages on the branch. Open the site root.

## Data
Everything is stored per-device in localStorage, namespaced per profile
(wp.fp.<profileId>.*). Each profile keeps its own workouts, meals and
progress; add or switch profiles from the avatar → Profile panel.
