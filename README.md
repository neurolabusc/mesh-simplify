# Mesh simplification demo

This repository brings [Tim Knip's](https://github.com/timknip/mesh-decimate/tree/master) classic ThreeJS project to Github pages to provide a live demo web page. The projectt provides both WASM and native JavaScript [quadric mesh simplification](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification).

## Setup
Download [Node.js](https://nodejs.org/en/download/) and run the following commands:

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```

## Links

 - [Tim Knip's original project](https://github.com/timknip/mesh-decimate/tree/master).
 - [Sven Forstmann's quadric mesh simplification](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification).
 - [Jessa Challa's demo for bringing ThreeJS to Github pages](https://github.com/jessachalla/threejs-scroller-gh-pages-demo).
 - [niivue-mesh](https://github.com/niivue/niivue-mesh) demonstrates how marching cubes and mesh simplification can be combined into a [live demo](https://niivue.github.io/niivue-mesh/)