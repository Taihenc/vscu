# 3D Model Viewer

A simple, lightweight 3D model viewer built with Three.js that can pan, zoom, rotate, and orbit around GLB/GLTF models. Perfect for hosting on GitHub Pages.

## Features

- 🖱️ **Interactive Controls**: Left click to rotate, right click to pan, scroll to zoom
- 📱 **Touch Support**: Pinch to zoom, drag to rotate on mobile devices
- 🎨 **Beautiful UI**: Modern gradient background with control hints
- ⚡ **Fast Loading**: Uses CDN resources for quick loading
- 📱 **Responsive**: Works on desktop, tablet, and mobile
- 🌐 **GitHub Pages Ready**: No build process required

## Controls

- **Rotate**: Left mouse button + drag (or single finger drag on mobile)
- **Pan**: Right mouse button + drag (or two finger drag on mobile)
- **Zoom**: Mouse wheel (or pinch gesture on mobile)

## Usage

1. Place your GLB/GLTF model file in the same directory as `index.html`
2. Update the model path in the JavaScript if needed
3. Open `index.html` in a web browser or host on GitHub Pages

## GitHub Pages Deployment

1. Fork or clone this repository
2. Add your 3D model file to the root directory
3. Go to Settings → Pages in your GitHub repository
4. Select "Deploy from branch" and choose `main` branch
5. Your site will be available at `https://yourusername.github.io/yourrepository`

## Supported Formats

- GLB (binary glTF)
- GLTF (JSON glTF with separate files)

## Browser Compatibility

Works on all modern browsers that support WebGL:

- Chrome 56+
- Firefox 51+
- Safari 12+
- Edge 79+

## Credits

Built with [Three.js](https://threejs.org/) - A lightweight 3D library with a default WebGL renderer.
