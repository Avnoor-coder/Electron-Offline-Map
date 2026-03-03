# 🗺️ Offline India Map – Electron Desktop Application

A fully offline desktop map application built using **Electron**, **Leaflet**, and **TileServer-GL**.
This project allows users to view and interact with map data without requiring an internet connection.

---

## 📌 Project Overview

This application renders offline map tiles using MBTiles data and provides a smooth desktop interface powered by Electron. It is designed for:

* Offline GIS visualization
* Secure network environments
* Surveillance & monitoring systems
* Defense or drone-based mapping projects
* Remote area mapping without internet access

---

## 🚀 Features

* Fully offline map rendering
* Leaflet-based interactive UI
* Zoom and pan functionality
* Local MBTiles support
* Lightweight Electron desktop interface
* Cross-platform compatible (Windows / Linux / macOS)

---

## 🛠️ Tech Stack

* Electron (Desktop Framework)
* Leaflet.js (Map Rendering)
* TileServer-GL (Tile Backend)
* Node.js
* MBTiles (Offline Map Data)

---

## 📂 Project Structure

```
project-root/
│
├── main.js
├── package.json
├── index.html
├── renderer.js
├── README.md
└── mbtiles/ (Download separately)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Install Node.js

Download and install Node.js from:
https://nodejs.org

Verify installation:

```
node -v
npm -v
```

---

### 2️⃣ Clone the Repository

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
```

---

### 3️⃣ Install Dependencies

```
npm install
```

---

### 4️⃣ Download MBTiles File

Download India MBTiles data from a trusted source.

Place the `.mbtiles` file inside your project directory.

Example:

```
india.mbtiles
```

---

### 5️⃣ Start TileServer

Install TileServer globally:

```
npm install -g tileserver-gl
```

Run TileServer:

```
tileserver-gl india.mbtiles
```

By default, it runs at:

```
http://localhost:8080
```

---

### 6️⃣ Run Electron App

Open another terminal in the project directory:

```
npm start
```

The Electron desktop application will launch and load the offline map.

---

## 🏗️ Build Desktop Executable (Optional)

To generate a Windows executable:

```
npm install electron-builder --save-dev
npx electron-builder
```

The installer will be generated inside the `dist/` folder.

---

## 🔒 Use Cases

* Drone surveillance systems
* Military-grade offline mapping
* Disaster management systems
* Industrial monitoring
* Secure air-gapped environments

---

## 📈 Future Improvements

* Auto-start TileServer from Electron
* Map search functionality
* Distance measurement tool
* Polygon drawing tools
* GPS simulation
* Integration with drone telemetry

---

## 👨‍💻 Author

Developed as part of a desktop GIS & offline mapping system project.

---

## 📜 License

This project is for educational and research purposes.
