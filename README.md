# KAIROS • Curated Global Summits & Experiences

An editorial luxury event management & experience showcase website mockup drawing inspiration from Ahmet Loca's signature Framer scrolling component ([CollectUI Inspiration](https://collectui.com/designs/framer-ui-design-inspiration/71b15c89-e651-4715-a3c6-e992ac853dce)), elevated with **Three.js WebGL spatial mechanics**.

Everything is completely self-contained in a single file: `index.html`.

🌐 **Live Demo**: [https://test-framer-cyan.vercel.app](https://test-framer-cyan.vercel.app)

---

## Key Features

### 1. Framer-Inspired Hero Showcase
- **Floating Glassmorphic Control Toolbar (Top-Center)**:
  - **Preset**: Toggle between *Custom* and *Minimal*.
  - **Title Mode**: Switch giant right index between **Words** (`ONE`, `TWO`...), **Roman** (`I`, `II`...), and **Dates** (`OCT 14`...).
  - **Content Alignment**: Move editorial block to *Top-Left*, *Bottom-Left*, or *Center*.
  - **Shader Mode**: Toggle between **Ripple** (liquid displacement) and **Wave** (curtain stretch).
  - **Switches**: Interactive switches for *Zoom* (Ken-Burns), *Dots* (left pagination rail), and *Autoplay*.
- **Giant Typographic Index**:
  - Outline strokes for inactive items (`-webkit-text-stroke: 1.5px rgba(255, 255, 255, 0.35)`).
  - Solid glowing white fill on active selection with spring cubic-bezier transitions.
- **Three.js WebGL Shader Transitions**:
  - Custom GLSL vertex and fragment shaders powering smooth liquid displacement, wave deformation, and chromatic aberration between slides.

### 2. Interactive 3D Spatial Staging & Venue Visualizer (Three.js)
- 3D amphitheater stage model with OrbitControls (rotate, zoom, pan).
- Real-time staging lighting rigs (*Nocturne Atmosphere*, *Golden Hour Amber*, *Pure Architectural Monolith*, *Aurora Borealis Glow*).
- Camera waypoints (*Stage Front*, *Mezzanine*, *Top Ortho*).

### 3. Interactive 3D Holographic Pass & Booking Modal (Three.js)
- Tilt-reactive 3D VIP lanyard pass with dynamic holographic foil sheen, custom attendee details, and QR barcode.
- Multi-tier membership selection (*Day Observer*, *Summit Fellow*, *Patron Circle*).
- Instant credential generation and cryptographic confirmation.

### 4. Curated Summits Roster & Multitrack Matrix
- Filterable summits grid (*Architecture & Space*, *Audiovisual Arts*, *Gastronomy*, *Synthetic Intelligence*).
- Day 01–03 timetable schedule matrix.
- Ambient harmonic soundscape synthesizer built on the Web Audio API.

---

## Getting Started

Simply open `index.html` in any modern web browser:

```bash
# Or run with any local static server:
python3 -m http.server 8080
```

Visit `http://localhost:8080/index.html`.
