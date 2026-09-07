# 🌐 GeoNexus: Global Intelligence Terminal

**GeoNexus** is a single-file, zero-dependency interactive global intelligence dashboard built to visualize geopolitical networks, bilateral security treaties, and multilateral defense and economic pacts.

Designed with an immersive tactical HUD aesthetic, the terminal projects 196+ sovereign nations onto an interactive vector map, dynamically mapping multilateral alliances (NATO, BRICS+, Quad, AfCFTA, Five Eyes, and more) along with high-trust bilateral defense accords.

---

### ✨ Key Features

- **Interactive Global Topology**: Smooth pan-and-zoom Mercator projection powered by **D3.js** and **TopoJSON**, complete with scanline shaders, tactical grid overlays, and radar lock animations.
- **Collision-Free Node Relaxation**: Solves overlapping microstates and dense nation clusters (e.g., Europe, the Caribbean) using iterative geometric relaxation with elastic geographic anchor springs.
- **Multilateral Bloc & Treaty Engine**: Filter and highlight member networks across military, economic, and political alliances in real time.
- **Tactical Entity Readouts**:
  - Hover HUD showing instant target coordinates, military posture, cyber capability, economic power, and diplomatic reach.
  - Interactive sidebar featuring dynamic 5-axis SVG radar charts and detailed relationship score breakdowns.
- **Lite Performance Mode**: One-click toggle that transitions from animated glowing particle flows to hardware-optimized static vectors for low-power devices.
- **Self-Contained Architecture**: Delivered as a 100% client-side, single-file application requiring no backend, build tools, or bundlers.

---

### 🛠️ Built With

- **React 18** (UMD) & **Babel Standalone**
- **D3.js (v7)** & **TopoJSON** (Map projection & spatial computations)
- **Tailwind CSS** (Cyber/Intel custom design palette)
