# 🌌 EchoVerse

**EchoVerse** is a premium, high-performance 3D audio visualization platform built with Three.js. It transforms audio signals into immersive, reactive environments using advanced spectral analysis and professional-grade rendering techniques.

---

## ✨ Key Features

### 🎙️ Advanced Audio Analysis
*   **Multi-Band Processing**: Real-time extraction of Sub-Bass, Bass, Low-Mid, Mid, High-Mid, High, and Brilliance.
*   **Transient Detection**: High-precision onset tracking for kicks, snares, and hi-hats.
*   **Harmonic Intelligence**: Real-time Chroma (musical note) analysis and stable BPM estimation.
*   **Stereo Analysis**: Correlation and stereo width monitoring for immersive spatial visuals.

### 🎨 3D Rendering & Geometry
*   **Parametric Math Forms**: Real-time generation of complex geometries including Gyroids, Clifford Tori, Hopf Fibrations, and Möbius Strips.
*   **GPU Particle System**: Millions of particles managed on the GPU with audio-driven attractors, fluid dynamics, and physics-based stretching.
*   **Dynamic Environments**: Procedural background patterns, aurora effects, and volumetric light rays.

### 🎥 Cinema-Grade Camera System
*   **Intelligent Modes**: Orbit, Cinematic, Reactive, Spiral, Vortex, and Pendulum modes.
*   **Visual Fidelity**: Real-time Depth of Field (DoF), Bokeh effects, and lens distortion.
*   **Path Recording**: Record and play back smooth camera movements for professional content creation.

### 🎭 Visual Effects & Post-Processing
*   **Advanced Bloom**: Multi-stage Unreal Bloom for high-quality glow.
*   **Color Grading Pipeline**: Professional Filmic Tone Mapping, Vibrance, and procedural color curves.
*   **Motion Effects**: Custom Afterimage (motion blur), chromatic aberration, and digital glitching.

### 🎵 Streaming & Media Integration
*   **Audius Integration**: Search and stream millions of tracks directly from the Audius decentralized network.
*   **Smart Queue**: Manage your playlist with repeat, crossfade, and automated transitions.
*   **Webcam Fusion**: Integrate your webcam feed into the 3D scene with real-time Chroma Key (green screen) subtraction.

### 🛠️ Professional Tools
*   **Preset Management**: Save complex configurations as local presets or export them to share.
*   **High-Res Capture**: Export snapshots up to 4x native resolution.
*   **Media Recording**: In-browser video recording for capturing performances and visualizers.

---

## 🚀 Getting Started

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/your-repo/EchoVerse.git
    ```
2.  **Serve Locally**:
    Since the project uses ES Modules and textures, it must be run via a web server.
    ```bash
    # If you have Python installed:
    python -m http.server 8000
    ```
3.  **Open in Browser**:
    Navigate to `http://localhost:8000`.

---

## ⌨️ Controls & Shortcuts

| Key | Action |
| :--- | :--- |
| **Space** | Play / Pause Audio |
| **U** | Toggle User Interface Visibility |
| **R** | Randomize Visual Configuration |
| **F** | Toggle Fullscreen |
| **P** | Open Preset Manager |
| **1 - 8** | Switch Settings Tabs |
| **H** | Hide/Show Performance Stats |

---

## 🛠️ Technology Stack

*   **Engine**: [Three.js](https://threejs.org/) (WebGL2)
*   **UI Logic**: Vanilla JavaScript with Declarative Data Binding
*   **Styling**: Modern CSS3 with Glassmorphism and CSS Grid
*   **API**: [Audius API](https://audius.org/) for decentralized music streaming
*   **Analysis**: Web Audio API with custom DSP modules

---

## 📜 License & Usage

© 2026 EchoVerse. All rights reserved.

**Strictly Proprietary**: This software and its source code are the exclusive property of the author. **No part of this project may be used, copied, modified, or distributed without explicit written permission.**
