# MediCare — Next-Generation 3D Healthcare Technology Platform

[![React](https://img.shields.io/badge/React-19.0-61dafb.svg?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178c6.svg?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Three.js](https://img.shields.io/badge/Three.js-r182-black.svg?logo=three.js&logoColor=white)](https://threejs.org/)
[![Vite](https://img.shields.io/badge/Vite-8.3-646cff.svg?logo=vite&logoColor=white)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v4.0-38bdf8.svg?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

MediCare is a high-performance healthcare web platform designed with interactive 3D digital-twin simulation, real-time telemetry, and smart medication adherence management.

---

## Key Features

- **Interactive 3D Healthcare Hero**: Built using **React Three Fiber**, **Three.js**, and **Drei**, featuring realistic floating medical capsules, translucent shields, contact shadows, and cursor-reactive camera tracking.
- **Dual Visual Theme System**:
  - **Bright Mode**: Baltic Blue (`#05668d`), Teal (`#028090`), Verdigris (`#00a896`), Mint Leaf (`#02c39a`), and Cream (`#f0f3bd`).
  - **Dark Mode**: Light Cyan (`#e0fbfc`), Light Blue (`#c2dfe3`), Cool Steel (`#9db4c0`), Blue Slate (`#5c6b73`), and Jet Black (`#253237`).
- **Patient Dashboard & Caregiver Telemetry**:
  - One-click dose verification with satisfying micro-interaction checkmarks and streak trackers.
  - Multi-patient switching with emergency contact speed-dial and gentle nudge pings.
  - Adherence analytics with weekly compliance bar charts and 30-day rolling trendlines.
- **AI Prescription Scanner**: Simulated computer-vision OCR scanning for paper prescriptions with automated drug identification and dosage extraction.
- **Technology That Cares**: 3D interactive hardware and AI showcase featuring Chrono-Sync, Guardian Protocol, and Vision Engine.

---

## Tech Stack

| Domain | Libraries & Tools |
| :--- | :--- |
| **Frontend Framework** | React 19, TypeScript, React Router DOM v7 |
| **3D Graphics** | Three.js, `@react-three/fiber`, `@react-three/drei` |
| **Styling & Effects** | Tailwind CSS v4, Glassmorphism, CSS Mesh Gradients |
| **Animations** | Framer Motion, GSAP, Lenis Smooth Scroll |
| **Icons & Charts** | Lucide React, Recharts |
| **Tooling & Bundler** | Vite 8, Oxlint |

---

## Local Development

```bash
# Clone the repository
git clone https://github.com/Muneeb7Siddiqui/medicare.git

# Navigate to project directory
cd medicare

# Install dependencies
npm install

# Start local development server
npm run dev
```

Visit `http://localhost:5173` in your browser.

---

## Deploy to Vercel

The project is pre-configured for zero-configuration deployment on **Vercel**:

1. Push this repository to your GitHub account.
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import the `medicare` repository.
4. Framework preset will automatically detect **Vite**.
5. Click **Deploy**.

---

## License

MIT License. Designed with care for modern healthcare innovation.
