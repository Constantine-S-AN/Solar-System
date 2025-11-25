**Live Demo:** https://constantine-s-an.github.io/Solar-System/

# Solar System

Interactive Three.js solar-system explorer with bilingual labels, orbiting planets, moons, asteroid belt, comet trail, and bloom-lit sun.

## Features
- Planets, moons, asteroid belt, star field, and comet rendered in WebGL with bloom.
- Click labels to focus on a planet; reset with the button or `ESC`.
- Bilingual UI toggle (EN / 中) for labels and instructions.
- Smooth camera orbit/zoom, hold mouse to accelerate time, animated sun shader.
- No build step; everything lives in `index.html`.

## Controls
- `Click` planet label: focus camera on that planet.
- `ESC` or “Return to Panorama” button: reset camera.
- `A / D` (or Arrow Left/Right): rotate camera.
- `W / S` (or Arrow Up/Down): zoom in/out.
- `Hold Mouse`: temporarily accelerate time.

## Quick Start
1) Clone: `git clone https://github.com/Constantine-S-AN/Solar-System.git`
2) Serve locally (recommended):  
   `cd Solar-System && python3 -m http.server 8000`
3) Open `http://localhost:8000` (or open `index.html` directly for a quick preview).

## Notes
- No external assets; textures are procedural.  
- Runs fully client-side—ideal for GitHub Pages.  
- Adjust planet data and visuals in `index.html` to customize the scene.
