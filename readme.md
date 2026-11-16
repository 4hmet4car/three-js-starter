# Three.js Starter

A modular **Three.js/WebGPU starter template** featuring Three.js Shading Language (TSL), resource management, debugging tools, and a structured application lifecycle.

This project is based on **Lesson 26 of [Bruno Simon's Three.js Journey](https://threejs-journey.com/)**, adapted and extended to support WebGPU, TSL, and modern Three.js features.

## Features

- **Modular architecture** — Organized into reusable classes for the scene, camera, renderer, and world components.
- **WebGPU rendering** — Uses Three.js `WebGPURenderer` with WebGL fallback support.
- **TSL support** — Ready for node-based materials and shaders.
- **Resource management** — Centralized asset loading and resource disposal.
- **Debug tools** — Integrated Three.js Inspector with configurable parameters.
- **Lifecycle management** — Structured initialization, update, resize, and cleanup methods.

## Setup

Install [Node.js](https://nodejs.org/en/download/) if you haven't already.

Clone or download the repository, navigate to the project directory, and run:

```bash
# Install dependencies
npm install

# Start the development server
npm run dev

# Build for production
npm run build
```

## Debug Mode

To enable the Three.js Inspector and debugging controls, append `#debug` to the application URL.

For example:

```text
http://localhost:5173/#debug
```

## Credits

Based on the architecture introduced in [Bruno Simon's Three.js Journey](https://threejs-journey.com/), Lesson 26, with adaptations for WebGPU, TSL, resource management, and debugging.
