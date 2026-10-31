# Eidolon: Quantum Containment Protocol

A 3D top-down shooter that runs in the browser, built with [Three.js](https://threejs.org/). Hostile entities called Eidolons are pouring through portals in Sector 7. Collect quantum energy orbs to stabilize the breach, shoot down Eidolons, destroy the portals, and survive all 5 levels before time runs out.

## How to play

| Control | Action |
| --- | --- |
| W A S D | Move |
| Mouse | Aim (and turn the camera) |
| Right-click | Shoot |
| Esc | Pause |
| R | Reset |
| 🌓 button | Light / dark theme |

- **Yellow orbs (⚡):** collect them to finish the level. Each level needs more.
- **Green orbs:** restore 25 health and give a short speed boost.
- **Portals:** shoot them to stop new Eidolons and earn bonus points.
- Every level adds 30 seconds and 20 health. Each level makes the Eidolons faster and makes the portals spawn more of them.

## Running it

It's a single `index.html` with no build step. Open it in a browser, or serve the folder with any static server:

```bash
npx serve .
```

Three.js is loaded from the unpkg CDN.

**Play online:** https://eidolon-iota.vercel.app
