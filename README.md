# markdown
# Framer - Quantum Neural Network

Interactive 3D visualization of a quantum neural network with real-time effects and glassmorphism UI.

## Features

- **3D Interactive Network**: Click to create energy pulses, drag to orbit around the structure
- **Multiple Themes**: Switch between different color palettes (Purple Nebula, Sunset Fire, Ocean Aurora)
- **Dynamic Morphing**: Change between different network formations (Sphere, Helix, Fractal)
- **Real-time Controls**: 
  - Adjust network density
  - Pause/play animations
  - Reset camera view
- **Responsive Design**: Works on desktop and mobile devices
- **Glassmorphism UI**: Modern frosted glass interface elements

## Technologies

- Three.js for 3D rendering
- GLSL shaders for custom visual effects
- WebGL for hardware-accelerated graphics
- Modern CSS with backdrop-filter for glass effects

## How to Use

1. **Click anywhere** on the canvas to send energy pulses through the network
2. **Drag** to rotate the camera around the structure
3. **Scroll** to zoom in/out
4. Use the control panel to:
   - Change color themes
   - Adjust network density
   - Morph between different formations
   - Freeze/play animations
   - Reset camera view

## Deployment on GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Set source to "Deploy from a branch"
4. Select branch (usually `main` or `master`)
5. Select folder `/ (root)`
6. Click Save

Your site will be live at: `https://[your-username].github.io/framer/`

## Local Development

Simply open `index.html` in a modern browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js with http-server
npx http-server
