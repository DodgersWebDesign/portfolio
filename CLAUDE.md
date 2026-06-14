# CLAUDE.md

## Project
Dodger Holmstedt portfolio site. Static HTML/CSS/JS, no build tools.

## Files
- index.html — main portfolio page
- 3d.html — 3D design subpage
- contact.html — contact page
- koi_pond_final.mp4 — featured video asset

## Design System
--black: #141414
--olive: #565449
--bone: #D8CFBC
--white: #FFFBF4
Font: Jost (100/200/300 weights + italic)

## Components
- Starfield canvas — animated star/shooting star background, fixed, z-index -1
- Custom cursor — SVG crosshair, mix-blend-mode difference, desktop only
- Loader — dismiss after 1750ms (index only)
- Card stack — 3D perspective stack, drag + arrow nav, 4 cards
- Earth globe — canvas, rotates, pins Gearhart OR (index only)
- Scroll reveals — IntersectionObserver, .reveal → .visible

## Breakpoints
- 860px — tablet
- 480px — mobile

## Rules
- Never touch starfield or cursor JS
- Keep all animations intact
- No frameworks, no build step, edit raw HTML/CSS/JS only

## Status
<!-- Updated each session. Tracks what exists, what's decided, what's next. -->
- index.html — complete
- 3d.html — complete + rotating wireframe icosahedron in "more" section
- web.html — complete + browser chrome wrapper; screenshot (dodgerswebsites-screenshot.png) still needs to be copied into project folder
- posters.html — complete; 10 posters wired up (posters/ subfolder); Messi featured hero
- contact.html — complete; node network ambient background; business email + LinkedIn + web studio
- byhand.html — DOES NOT EXIST YET (waiting on photos from phone)

## Session Log
<!-- One-line entries, newest first. Format: YYYY-MM-DD — what changed -->
- 2026-06-13 — Built web.html, posters.html, contact.html; added wireframe/chrome/reg marks/node network; wired 10 posters
- 2026-06-13 — Project started with Claude. Memory system initialized.

## Instructions
After every session, tell me if anything changed that requires updating this file.
At the END of every session, update the Status and Session Log sections above.