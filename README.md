# ⭐ 3D Interactive Cube Scene — WebGL / Three.js

This project is a real-time **3D interactive experience** built with **Three.js**, featuring a rotating cube with individually colored faces, dynamic post-processing effects, and an animated gradient environment.

The user can **orbit**, **zoom**, and **toggle rotation**, all while enjoying a modern neon-styled visual aesthetic.

---

## ✨ Features

-  Multi-colored 3D cube with glossy reflective materials  
-  Dynamic lighting and bloom effects for a glowing neon look  
-  Screen-space outline rendering 
-  Animated shader background using a 360° sky-sphere  
-  Interactive mouse camera control (OrbitControls)  
-  Button to **pause/resume cube rotation**  
-  Camera movement limits:
  - Prevents zooming inside the cube  
  - Prevents zooming infinitely outward  
  - Prevents rotating below the floor plane

---

## 🛠️ Technology Stack

| Category | Tool |
|---------|------|
| 3D Rendering | Three.js |
| Post-Processing | UnrealBloomPass, OutlinePass |
| Input Controls | OrbitControls |
| Language | JavaScript (ES Modules) |
| Rendering | WebGL (browser) |

---

## 🎮 Controls

| Action | Input |
|--------|------|
| Orbit camera | Left mouse drag |
| Zoom | Scroll wheel / trackpad |
| Pause / resume cube rotation | Button in top left corner |

---

## 🚀 Getting Started

Download the project and run it locally using a simple web server (required for ES module imports).

