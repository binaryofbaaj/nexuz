# NEXUS // Spatial Interface

**NEXUS** is a premium, high-tech 3D visualization platform designed for cinematic model exploration and interactive data display. Built with Three.js and modern web technologies, it features a dual-themed "Deep Space" and "Nebula White" interface.

![NEXUS UI](https://raw.githubusercontent.com/mrdoob/three.js/master/files/icon.png) *<!-- Replace with actual screenshot if available -->*

## 🚀 Features

- **Dual-Theme Engine**: Seamlessly switch between a high-contrast "Deep Space" Dark Mode and a clean "Nebula White" Light Mode.
- **Cinematic Visuals**: Advanced post-processing feel with noise textures, vignettes, and dynamic environment reflections.
- **Interactive 3D**: 
  - **Auto-Rotate**: Smooth 360-degree model rotation.
  - **Explode**: Deconstruct model meshes for internal inspection.
  - **Gravity Drop**: Physics-inspired drop and bounce animation.
  - **Hyper Spin**: High-velocity rotational bursts.
  - **Particle Burst**: Sonar-style particle emission.
- **Tactical HUD**: Real-time telemetry including FPS tracking, vertex counts, and spatial coordinates.
- **Customizable Accents**: On-the-fly color palette switching with persistence across sessions.

## 🛠️ Tech Stack

- **Core**: HTML5, Vanilla CSS3, JavaScript (ES6+)
- **3D Engine**: [Three.js](https://threejs.org/)
- **Typography**: Inter (UI), Space Mono (Data)
- **Icons**: Google Material Symbols

## 📖 Usage

Simply open `index.html` in any modern web browser.

### Controls
- **Left Click + Drag**: Rotate Camera
- **Right Click + Drag**: Pan Camera
- **Scroll Wheel**: Zoom In/Out
- **Click Anywhere**: Trigger Sonar Pulse

### Control Panel
- **ROTATE**: Toggle automatic rotation.
- **WIRE**: Toggle mesh wireframe mode.
- **EXPLODE**: Expand/contract the model's component meshes.
- **DROP**: Trigger the gravity physics simulation.
- **BURST**: Emit a burst of particles from the center.
- **SPIN**: Increase rotational velocity to hyper-speeds.
- **SHADOW**: Toggle high-quality soft shadows.

## 🎨 Themes

NEXUS supports two distinct aesthetic profiles:
1. **Deep Space (Dark)**: Neon-cyan accents on a deep-black canvas. Best for low-light environments and "Hacker" aesthetics.
2. **Nebula White (Light)**: Dark emerald and navy accents on a crisp white canvas. Optimized for high-legibility and professional presentations.

## 📂 Project Structure

```text
ui/
├── index.html    # All-in-one application (HTML, CSS, JS)
└── README.md     # Documentation
```

## 📝 License

This project is open-source and free to use.

---
*NEXUS v0.8.0 - Developed for the Future.*
