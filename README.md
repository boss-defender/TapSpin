# 🪐 Tiny Planet Runner — Deluxe Edition

A vibrant, fast-paced, and responsive 2D arcade side-scroller built purely with semantic HTML5, CSS custom variables, and vanilla JavaScript using the native Web Canvas API. Run, leap, and maintain your orbit across a rotating mini-world while dodging spike beds, space boulders, and radioactive hazards[cite: 2]!


<img width="1920" height="1036" alt="image" src="https://github.com/user-attachments/assets/061a1b88-8340-46e2-bc05-26cabaf5cf0a" />

---

## 🕹️ Live Demo


---

## 🚀 Key Features

*   **Zero Dependencies:** Engineered from scratch with pure, vanilla HTML5, CSS3, and modern JavaScript[cite: 2]. No heavy frameworks, bundlers, or packages needed.
*   **Dynamic Step Speed Scaling:** The game features an algorithmic milestone framework[cite: 2]. Once you break past **400 points**, the entire game world scales its velocity multiplier dynamically every 200 points to continually challenge your reflexes[cite: 2].
*   **Web Audio Synth engine:** Employs a native browser `AudioContext` wrapper kit to synthesize crisp retro chiptune sound waves dynamically on-the-fly (Triangle, Sine, and Sawtooth oscillators) without loading external audio assets[cite: 2].
*   **Juiced Visuals & Parallax Physics:** Packed with smooth rendering states including dynamic atmosphere lighting, custom dust engine particle bursts, running sparks, organic squash/stretch animations, and scrolling stardust trails[cite: 2].
*   **Adaptive Cross-Platform Scaling:** Responsively custom-built with automatic multi-touch pointer listeners and calculated layout boundaries[cite: 2]. Features an expanded high-DPI retina rendering mode optimized for mobile, tablet, and desktop viewports[cite: 2].

---

## 🎮 How To Play

Keep the runner safely pinned to the surface crust while leaping across widening structural gaps or colliding with deep obstacles[cite: 2]. If you travel too deep below the terrain line, you risk losing your gravity vector[cite: 2]!

### ⌨️ Desktop Controls
*   <kbd>Spacebar</kbd> / <kbd>W</kbd> / <kbd>Arrow Up</kbd> — Start Run / Hop or Jump[cite: 2]
*   <kbd>Escape</kbd> / <kbd>P</kbd> — Hold Orbit / Pause Game[cite: 2]
*   <kbd>Enter</kbd> — Quick start from menu screen overlays[cite: 2]

### 📱 Touch Controls
*   **Tap Anywhere On Canvas** — Start Run / Jump[cite: 2]
*   **HUD Actions** — Toggle persistent audio mute flags or handle pause menus manually[cite: 2].

---

## 🛠️ Architecture & Core Mechanics

The underlying code (`TinyPlanetRunner.html`) showcases efficient browser development conventions[cite: 2]:
*   **Deterministic Loop Architecture:** Driven by a frame-rate independent time-delta matrix (`dt`) linked to `requestAnimationFrame` to ensure consistent execution speeds across diverse 60Hz, 120Hz, or mobile displays[cite: 2].
*   **Mathematical Level Spawning:** Difficulty maps are dynamically built out using custom weighted probability distributions and strict proximity barrier checks to prevent impossible obstacle overlaps[cite: 2].
*   **Lightweight Vector Tracking:** Rotations are computed around a dynamic point center using basic trigonometric bounding boxes[cite: 2], enabling smooth 360-degree environmental planetary rotations.
*   **Local Storage Memory:** Leverages browser data configurations (`localStorage`) to persistently cache your individual highest benchmark distance and audio configurations across sessions[cite: 2].

---

## 📦 Quick Local Setup

Since this game is built entirely in a self-contained document file, just download the file and double click it to play . 
