# SlopeGame-76

This repository contains a browser-playable **Slope** game build (HTML + JavaScript + assets). The main entry point is `index.html`. :contentReference[oaicite:0]{index=0}

## Live demo (optional)
If you prefer a hosted version to preview the current build:

https://slopeunblocked76.net

(Linked for convenience; the repository itself is the source of truth.) :contentReference[oaicite:1]{index=1}

---

## What's in this repo
At the root level you’ll find the main page and supporting build/runtime files, including:

- `index.html` (main entry) :contentReference[oaicite:2]{index=2}
- Additional HTML pages: `frame.html`, `ubg235.html`, `games235.html`, `404.html`, `408.html` :contentReference[oaicite:3]{index=3}
- JavaScript/build files: `game-scripts.js`, `loading__.js`, `modules__.js`, `settings__.js`, `start__.js` :contentReference[oaicite:4]{index=4}
- PlayCanvas runtime bundle: `playcanvas-stable.min.js` :contentReference[oaicite:5]{index=5}
- Web app / PWA-related files: `manifest.json`, `appmanifest.json`, `sw.js` :contentReference[oaicite:6]{index=6}
- Asset and data folders: `assets/`, `js/`, `json/`, plus some JSON data files in the root :contentReference[oaicite:7]{index=7}

---

## Run locally

### Option A — open the HTML file
You can try opening `index.html` directly in your browser. :contentReference[oaicite:8]{index=8}

If anything fails to load (some browsers restrict certain features when using `file://`), use Option B.

### Option B — serve as a static site (recommended)
From the project directory:

#### Python
```bash
python -m http.server 8080
