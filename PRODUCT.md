# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
Primary (confirmed): engineers and designers who open CAD/3D files on a phone, away from a laptop (workshop, shop floor, site).
Other audiences (jewelers, 3D-print makers) are hypotheses from the app's features, not confirmed. No audience data on hand.

## Product Purpose
The site is the landing page for RE:solid 3D Viewer, an Android app that views, sections, measures and weighs 3D models offline. It exists to get a visitor to install the app from Google Play.

## Positioning
A "portable engineering desk": STEP assemblies, section analysis, measuring and weight on a phone, fully offline, files never leave the device.

## Capabilities and Constraints
- Formats: STL, OBJ (+MTL), 3MF, STEP, IGES, BREP, PLY, ZIP.
- Freemium: viewing is free forever; a one-time Pro purchase unlocks STEP, sections, measuring and weight; 3 free trial sessions. Never describe the app as plainly "free" (earlier wording was removed as misleading).
- Site is a single `index.html` (+ `assets/`), English by default, Ukrainian via the UK/EN switch; every string lives in the `i18n` dictionary in both languages.
- three.js is pinned to r128. Demo scenes (logo, section, exploded motorcycle, ring) are real app features on real files.

## Evidence on Hand
Real demo models in `assets/` (logo.obj, pulley.bin, moto.bin, ring.bin) and a screen recording of the app. Absent: user counts, reviews, audience research. Do not fabricate testimonials or numbers.

## Product Principles
- Show the real thing, on the page, with real files.
- Honest about Free vs Pro.
- Offline and private is a feature, not a footnote.
- Works on the visitor's phone first (Android, touch, keyboard and screen reader included).

## Accessibility & Inclusion
WCAG 2.2 AA is the working target (contrast, 24px targets, pause controls, keyboard access to 3D).
