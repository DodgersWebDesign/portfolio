# CLAUDE.md

## Project
Dodger Holmstedt portfolio site. Static HTML/CSS/JS, no build tools.

## Files
- index.html — main portfolio page
- 3d.html — 3D design subpage
- web.html — web design subpage
- posters.html — poster work subpage
- byhand.html — illustration & drawing subpage
- contact.html — contact page
- koi_pond_final.mp4 — featured video asset
- favicon.svg — crosshair SVG favicon, used on all pages
- byhand/ — 6 illustration/drawing images (fly_color, frieren, mech_paint, IMG_1089, IMG_4106, IMG_6401)
- posters/ — 10 poster images

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
- Lightbox — fullscreen image viewer on byhand.html + posters.html; swipe on mobile, arrow keys on desktop
- Floating sketch marks — byhand.html only; pencil strokes/dots drifting upward on canvas
- Node network — contact.html ambient background
- Wireframe icosahedron — 3d.html "more" section canvas
- Registration marks — posters.html fixed SVG corner marks

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
- 3d.html — complete; rotating wireframe icosahedron in "more" section
- web.html — complete; browser chrome wrapper; dodgerswebsites-screenshot.png wired up
- posters.html — complete; 10 posters wired up (posters/ subfolder); Messi featured hero; lightbox
- contact.html — complete; node network ambient background; business email + LinkedIn + web studio
- byhand.html — complete; 6 pieces (pencil, ink, digital); floating sketch marks ambient; lightbox; Reach featured hero
- LIVE at dodgerportfolio.com (Cloudflare Pages, GitHub: DodgersWebDesign/portfolio)

## Session Log
<!-- One-line entries, newest first. Format: YYYY-MM-DD — what changed -->
- 2026-06-14 — Built byhand.html; added lightbox to byhand+posters; floating sketch marks ambient; image compression; lazy loading; OG tags; favicon; prefers-reduced-motion on all pages; pushed to GitHub; deployed to dodgerportfolio.com
- 2026-06-13 — Built web.html, posters.html, contact.html; added wireframe/chrome/reg marks/node network; wired 10 posters
- 2026-06-13 — Project started with Claude. Memory system initialized.

## Instructions
After every session, tell me if anything changed that requires updating this file.
At the END of every session, update the Status and Session Log sections above.