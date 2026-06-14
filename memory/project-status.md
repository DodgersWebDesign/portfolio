---
name: project-status
description: Current state of Dodger's portfolio — what pages exist, what's complete, deployment details
metadata:
  type: project
---

Portfolio site for Dodger Holmstedt. Static HTML/CSS/JS, no build tools, no frameworks.
Live at **dodgerportfolio.com** — deployed via Cloudflare Pages, GitHub repo at DodgersWebDesign/portfolio.

## Pages — all complete
- index.html — Starfield, cursor, loader, card stack (4 cards), earth globe, about section, footer.
- 3d.html — Koi pond video featured. Rotating wireframe icosahedron in "more" section.
- web.html — Browser chrome wrapper around dodgerswebsites-screenshot.png.
- posters.html — Messi as featured hero. 10 posters in grid from posters/ subfolder. Registration marks. Lightbox.
- byhand.html — Reach (pencil hand+butterfly) as featured hero. 5 grid pieces: 飛べ/Fly, Frieren, Mech, Warrior, Botanical. Floating sketch marks ambient animation. Lightbox.
- contact.html — Node network ambient background. Three contacts: fluidwork@dodgerswebsites.org, dodgerswebsites.org, LinkedIn.

## Unique Page Elements
- index.html — earth globe canvas (about section)
- 3d.html — rotating wireframe icosahedron canvas
- web.html — CSS browser chrome bar above screenshot
- posters.html — SVG printers' registration marks (fixed, 4 corners)
- contact.html — drifting node network with connection lines
- byhand.html — floating pencil sketch marks drifting upward on canvas

## Shared Features
- Lightbox on byhand.html + posters.html — click image to fullscreen, swipe on mobile, arrow keys on desktop
- Favicon — crosshair SVG (favicon.svg) on all pages
- OG/Twitter meta tags on all pages
- prefers-reduced-motion on all pages
- lazy loading on all below-fold images

## Deployment
- GitHub: https://github.com/DodgersWebDesign/portfolio.git (branch: main)
- Cloudflare Pages: auto-deploys on every push to main
- Domain: dodgerportfolio.com (registered through Cloudflare)
- To update: edit files → git add → git commit → git push → auto-deploys in ~1 min

## Key Decisions
- Personal email (dodgerjh@live.com) removed from contact page — business email only
- Messi poster chosen as featured hero on posters page
- Reach (hand+butterfly pencil drawing) chosen as featured hero on byhand page
- No contact form — static site, no backend
- All subpages use ← Portfolio nav link back to index.html
- Images compressed to max 2400px at quality 82 (ATCQ: 40MB→1.8MB, Messi: 13MB→1MB)

**Why:** Tracks session-to-session continuity so we don't lose progress context.
**How to apply:** Read this at the start of each session to orient on where things stand. Update at end of session.
