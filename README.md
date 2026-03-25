# 🌌 3D Galaxy Visualization

An interactive 3D galaxy renderer built with Three.js — explore spiral, elliptical, and irregular galaxies rendered with 50,000+ particles and real-time bloom effects, all in a single HTML file.

---

## ✨ Features

- **Three Galaxy Types** — Spiral (logarithmic arm formula), Elliptical, and Irregular
- **50,000+ Particles** — Rendered via `THREE.Points` for high-performance GPU-accelerated rendering
- **Bloom / Glow Effect** — Post-processing via `UnrealBloomPass` for a cinematic nebula feel
- **Realistic Color Gradient** — White/yellow dense core fading to blue outer arms
- **Subtle Galaxy Rotation** — Continuous ambient rotation animation
- **OrbitControls** — Full mouse-driven camera: rotate, zoom, and pan
- **Zero Dependencies** — Single `index.html` file, no build step, no npm

---

## 🔴 Live Demo

**[Live Demo](https://absurdfounder.github.io/galaxy-3d)**

---

## 🚀 Quick Start

No installation required. Just open the file in any modern browser:

```bash
# Clone the repo
git clone https://github.com/absurdfounder/galaxy-3d.git
cd galaxy-3d

# Open directly in browser
open index.html
```

> **Or** simply download `index.html` and double-click it. That's it.

---

## 🎮 Controls

| Input | Action |
|---|---|
| `Left-click + drag` | Rotate / orbit the galaxy |
| `Scroll wheel` | Zoom in / out |
| `Right-click + drag` | Pan the camera |
| `Spiral` button | Switch to spiral galaxy |
| `Elliptical` button | Switch to elliptical galaxy |
| `Irregular` button | Switch to irregular galaxy |

---

## 🛠 Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| [Three.js](https://threejs.org) | r165 | 3D rendering engine |
| WebGL | — | GPU-accelerated graphics |
| UnrealBloomPass | r165 | Bloom / glow post-processing |
| OrbitControls | r165 | Mouse camera controls |
| Import Maps | — | CDN module resolution, no bundler |

---

## 📁 Project Structure

```
galaxy-3d/
└── index.html    # Everything — geometry, shaders, controls, UI
```

---

## 📄 License

MIT — free to use, modify, and distribute.
