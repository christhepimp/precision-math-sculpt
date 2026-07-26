# Precision Math Sculptor

**Start with a perfect square clay box. Sculpt it with pure mathematics.**

A real-time 3D sculpting tool that begins with a unit cube ("clay box") and lets you deform it using exact mathematical formulas. No freehand guessing — every change is precise, parametric, and reproducible.

## Live Demo
Open the GitHub Pages site (once enabled):
**https://christhepimp.github.io/precision-math-sculpt/**

Or just open `index.html` locally.

## What you get
- Starts with a clean square clay box (high-resolution cube mesh)
- Apply mathematical deformations in real time:
  - Sine / cosine waves
  - Radial falloffs
  - Polynomial bends
  - Spherical / cylindrical projections
  - Simplex-style noise (math-based)
  - Custom formula input (x, y, z → displacement)
- Orbit, zoom, and inspect the result
- Reset to original clay box anytime
- Export the current mesh as OBJ (basic)

## How to use
1. Open the page
2. Choose a preset deformation or type your own formula
3. Adjust strength / frequency / falloff parameters
4. Watch the clay box reshape with mathematical precision
5. Stack operations or reset and try new equations

## Tech
- Three.js (WebGL)
- Pure client-side — no backend needed
- GitHub Pages ready

## Future ideas you can add
- Boolean math ops (intersection / union via signed distance)
- Subdivision + math smoothing
- Formula history / undo stack
- Export to STL for 3D printing
- GLSL live shader sculpting

Made for people who want **precision** over freehand clay tools.

Clone it, open it, start sculpting.