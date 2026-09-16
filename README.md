# ✦ AURELION — Rose Sovereign (v2.0) ✦
### 3D Rose Gold Watch Exploded-View Explorer & Interactive Showcase

[![License: MIT](https://img.shields.io/badge/License-MIT-rose.svg)](LICENSE)
[![Format: WebP](https://img.shields.io/badge/Assets-WebP%20Optimized-00d26a.svg)](#)
[![Stack: Vanilla%20JS%20%2B%20TailwindCSS](https://img.shields.io/badge/Stack-HTML5%20%2F%20CSS3%20%2F%20JS-blue.svg)](#)
[![Edition: Limited%20300](https://img.shields.io/badge/Edition-300%20Pieces-E0A96D.svg)](#)

> *"Rose gold craftsmanship meets skeletal mastery. Every second is a promise."*  
> **AURELION — Rose Sovereign** is an exclusive horology interactive showcase featuring a cinematic, scroll-driven exploded-view sequence of an 18K rose gold skeleton mechanical watch movement.

---

## 🌐 Live Demo

**[View the live website](https://saba1207b.github.io/ad_watch_explorer_v2.0/)**

---

## ✨ Features

- **High-Fidelity 120fps Scroll Animation**: 300 ultra-high-definition frames rendered via HTML5 Canvas with sub-pixel interpolation, frame blending, and DPR capping.
- **Rose Gold Mechanical Exploration**:
  1. *Skeleton Architecture* (312 hand-finished rose gold components)
  2. *Golden Gear Train* (18K rose-gold wheel transmission)
  3. *Full Exploded Assembly* (Complete 3D dispersion of movement)
  4. *Precision Reassembly* (Seamless re-locking into beating rhythm)
- **WebP Asset Optimization**: All 300 frames are converted into modern `.webp` format for rapid preloading, smooth rendering, and lightweight repository size (~21 MB).
- **Luxury Aesthetic**: Rose-gold tones, deep obsidian backdrop, Cormorant Garamond typography, and subtle glassmorphic elements.
- **Interactive Capabilities**:
  - Live technical specifications & jewel bearing metrics
  - Interactive reservation modal with case material selection
  - Compatible with standard web browsers and borderless desktop application runtimes (Electron)

---

## 🚀 Quick Start

### 1. View in Any Browser
No build step is needed!

#### Option A: Windows Shortcut
Double-click `Open in Browser.bat` to launch the local preview server.

#### Option B: Simple Local Server
Using Node.js:
```bash
npx serve . -p 3000
```
Or using Python:
```bash
python -m http.server 3000
```
Then open `http://localhost:3000` in your browser.

---

### 2. Run as a Desktop App (Electron)

```bash
# Install dependencies
npm install

# Start the Electron application
npm start
```

---

## 📁 Project Structure

```text
watch-explorer2/
├── images/                  # 300 WebP animation frames (ezgif-frame-001.webp - 300.webp)
├── index.html               # Main application markup & sections
├── sequence.js              # 120fps canvas rendering engine & scroll scrub logic
├── styles.css               # Production styling & luxury theme tokens
├── main.js                  # Electron desktop application main process
├── package.json             # Project dependencies & npm scripts
├── Open in Browser.bat      # Quick launcher script for local testing
└── .gitignore               # Ignores node_modules and OS metadata
```

---

## 🛠 Tech Stack

- **Frontend**: Vanilla JavaScript (ES6+), HTML5 Canvas 2D Context
- **Styling**: TailwindCSS & Custom Glassmorphism
- **Typography**: Cormorant Garamond & Inter (Google Fonts)
- **Assets**: 300 WebP frames with delta-time lerp smoothing
- **Runtime**: Browser / Electron 33+

---

## 📜 License

Distributed under the MIT License.
