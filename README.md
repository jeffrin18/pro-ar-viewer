# React + Vite
# 🚀 Pro AR Viewer

A professional, app-less Web AR and 3D model viewer.

This project, built with React (Vite) and React Three Fiber, allows users to view, inspect, and interact with a high-fidelity 3D model in the browser. It features realistic environment-based reflections, dynamic shadows, and a "View in AR" mode to place the object in the real world using WebXR.

---

## ✨ Key Features

* **App-less AR:** Uses WebXR to place the 3D model in the real world directly from a mobile browser (no app download required).
* **Realistic Rendering:** Uses an HDRI environment (`moon_lab_1k.hdr`) for lifelike lighting and reflections on the model's surface.
* **Dynamic Shadows:** The model casts realistic shadows on an invisible ground plane for a grounded, realistic look.
* **Interactive Controls:** Smooth `OrbitControls` (click-and-drag, zoom) for desktop inspection, including auto-rotation.
* **Progressive Loading:** A custom React loading bar shows the *actual* download progress of the 3D model assets.
* **Optimized Build:** Built with **Vite** for a lightning-fast development experience and an optimized production build.

---

## 🛠️ Tech Stack

* **React** (with **Vite**): Frontend Library & Build Tool
* **React Three Fiber**: React renderer for `three.js`
* **@react-three/drei**: Helpers for R3F (Controls, Loader, Environment)
* **@react-three/xr**: WebXR (Augmented Reality)
* **three.js**: The core 3D engine

---

🚀 Getting Started
To run this project on your local machine, follow these steps.

1. Clone the Repository
Bash

git clone https://github.com/YOUR_USERNAME/pro-ar-viewer.git
(Replace YOUR_USERNAME with your actual GitHub username.)

2. Navigate to the Project
Bash

cd pro-ar-viewer
3. Install Dependencies
This project uses npm for package management. This will install all packages and apply the overrides fix for zustand.

Bash

npm install
4. Run the Development Server
Bash

npm run dev
The app will be available at http://localhost:5173/.

📱 Testing AR (on a Mobile Device)
To test the WebXR (AR) feature, you must run the server on your local network.

Run the server with the --host flag:

Bash

npm run dev -- --host
The terminal will output a "Network" URL (e.g., http://192.168.1.5:5173/).

Make sure your phone is on the same Wi-Fi network as your computer.

Open the Network URL in your phone's browser (e.g., Chrome on Android or Safari on iOS).

If your device is supported, the "ENTER AR" button will appear.evice is supported, the "ENTER AR" button will appear.
