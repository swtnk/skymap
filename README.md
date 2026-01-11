# Celestial Sky Map 🌌

An interactive 3D planetarium application that allows you to explore the night sky with accurate astronomical positions of constellations, stars, and planets.

## ✨ Features

- **Interactive 3D Visualization**: Navigate through space with intuitive controls powered by Three.js
- **Accurate Astronomical Data**: View constellations, stars, and planets with real positions
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean interface built with React and custom fonts (Orbitron & Space Mono)
- **Optimized Performance**: Brotli-compressed assets for fast loading

## 🚀 Technologies

- **React**: Modern UI framework for building the interface
- **Three.js**: 3D graphics library for rendering the celestial sphere
- **Leaflet**: Mapping library integration
- **Vite**: Build tool for optimized bundling and compression

## 🌐 Live Demo

Open `index.html` in a modern web browser to explore the sky map.

## 📦 Installation

This is a production build. To run it locally:

1. Clone or download this repository
2. Serve the files using any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

3. Open your browser and navigate to `http://localhost:8000`

## 🗂️ Project Structure

```
skymap/
├── index.html              # Main HTML file
├── README.md              # This file
├── robots.txt             # Search engine directives
└── assets/                # Bundled and compressed assets
    ├── index-*.js         # Main application bundle
    ├── react-vendor-*.js  # React library bundle
    ├── three-vendor-*.js  # Three.js library bundle
    ├── index-*.css        # Stylesheet bundle
    └── *.br               # Brotli-compressed versions
```

## 🎯 Usage

- **Navigate**: Click and drag to rotate the celestial sphere
- **Zoom**: Use mouse wheel or pinch gestures to zoom in/out
- **Explore**: Discover constellations, stars, and planets in their astronomical positions

## 📄 License

**All Rights Reserved** - Proprietary License

Copyright (c) 2026 Celestial Sky Map. All Rights Reserved.

This software is proprietary and confidential. No permission is granted to copy, modify, distribute, or use this software for any commercial or personal purposes. See the [LICENSE](LICENSE) file for full details.

## 🙏 Acknowledgments

- Built with modern web technologies
- Astronomical data and calculations
- Community contributions to open-source libraries

---

*Explore the cosmos from the comfort of your browser* ✨
