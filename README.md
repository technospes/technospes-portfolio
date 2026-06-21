# Ayush Shukla — 3D Portfolio

A fully interactive 3D portfolio built with Three.js, GSAP, and vanilla JS.  
Live at: **[URL coming soon....]**

## Tech Stack

- **Three.js** — 3D room scene with orthographic camera
- **GSAP** — animation timeline for intro and scroll sequences  
- **Vite** — build tool and dev server
- **Vanilla JS + CSS** — no frameworks

## Features

- Animated 3D isometric room that assembles on scroll
- Dark / light theme toggle
- Fully responsive — desktop and mobile layouts
- Diagonal GitHub project card marquees
- GSAP-powered preloader and intro sequence
- Scroll-triggered room assembly animation

## Project Structure
├── Experience/          # Three.js core

│   ├── Camera.js        # Perspective + orthographic cameras

│   ├── Renderer.js      # WebGL renderer config

│   ├── Preloader.js     # GSAP intro/second intro timelines

│   ├── Theme.js         # Dark/light mode

│   └── World/           # 3D scene objects

├── index.html           # Main HTML + nav + hero markup

├── style.css            # All styles including mobile breakpoints

└── main.js              # Entry point

## Running Locally

```bash
npm install
npm run dev
```

## Deployment

Deployed via GitHub Pages from the `main` branch.

## Contact

- GitHub: [@technospes](https://github.com/technospes)
- Portfolio: [URL coming soon...]
