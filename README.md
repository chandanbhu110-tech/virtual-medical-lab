# 🏥 Virtual Medical Lab

An **interactive 3D medical learning platform** built with React, Three.js, and Tailwind CSS. Explore anatomical structures, physiological processes, and lab equipment in a stunning clinical UI.

![Virtual Medical Lab](https://img.shields.io/badge/React-19-61DAFB?logo=react) ![Three.js](https://img.shields.io/badge/Three.js-r170-black?logo=threedotjs) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss) ![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite)

## ✨ Features

### 🔬 Interactive 3D Viewport
- **Real GLB Models** — Anatomical heart and compound microscope loaded from Poly Pizza (CC-BY)
- **Procedural DNA Helix** — Beautiful rotating double-strand with color-coded nucleotide bases
- **OrbitControls** — Drag to rotate, scroll to zoom, auto-rotation enabled
- **Animations** — Heartbeat pulsing, gentle rotations, floating particles

### 📑 Three Subject Tabs
| Tab | 3D Model | Info Panel |
|-----|----------|------------|
| 🫀 **Anatomy** | Low-poly anatomical heart (GLB) | Heart structures, chambers, arteries |
| 🧬 **Physiology** | Procedural DNA double helix | Base pairs, nucleotides, backbone |
| 🔬 **Microbiology** | Omax compound microscope (GLB) | Eyepiece, objectives, condenser |

### 🤖 Lab Assistant
- AI-powered chat sidebar with medical knowledge
- Quick question buttons for instant answers
- Typing indicator and markdown formatting

### 🎨 Clinical UI Design
- **Sterile White** theme with glassmorphism effects
- Animated stats bar with counters and progress indicators
- Live clock, status indicators, and responsive layout
- Google Fonts (Inter + JetBrains Mono)

## 🚀 Getting Started

### Prerequisites
- **Node.js** 18+ and **npm**

### Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/virtual-medical-lab.git
cd virtual-medical-lab

# Install dependencies
npm install

# Start the development server
npm run dev
```

Open **http://localhost:5173/** in your browser.

### Build for Production

```bash
npm run build
npm run preview
```

## 🛠️ Tech Stack

- **React 19** — UI framework
- **Vite 7** — Build tool & dev server
- **Three.js** + **@react-three/fiber** + **@react-three/drei** — 3D rendering
- **Tailwind CSS v4** — Utility-first styling
- **Lucide React** — Icon library

## 📁 Project Structure

```
virtual-medical-lab/
├── public/
│   ├── heart.glb          # Anatomical heart 3D model
│   └── microscope.glb     # Compound microscope 3D model
├── src/
│   ├── components/
│   │   ├── Header.jsx     # Top bar with logo, clock, status
│   │   ├── TabBar.jsx     # Subject tabs + toolbar
│   │   ├── Viewport3D.jsx # Three.js 3D canvas
│   │   ├── InfoPanel.jsx  # Subject detail panel
│   │   ├── StatsBar.jsx   # Animated metrics bar
│   │   └── LabAssistant.jsx # AI chat sidebar
│   ├── App.jsx            # Main layout
│   ├── main.jsx           # Entry point
│   └── index.css          # Design system & tokens
├── index.html
├── vite.config.js
└── package.json
```

## 📜 Credits & Licenses

### 3D Models (CC-BY)
- **Heart** by [Poly by Google](https://poly.pizza) via Poly Pizza
- **Omax Compound Microscope** by [3Donimus](https://poly.pizza) via Poly Pizza

### Fonts
- [Inter](https://fonts.google.com/specimen/Inter) — UI text
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) — Monospace / code

## 📄 License

MIT License — feel free to use, modify, and distribute.

---

Built with ❤️ for medical education and interactive learning.
