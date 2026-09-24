# WebGL Weekly 4

A static WebGL lighting scene built with plain HTML, GLSL, and JavaScript.

## Scene

The starter scene contains:

- Two colored cubes
- A smaller sphere
- A pyramid
- A ground plane
- Ambient lighting
- Directional lighting
- A fixed elevated camera view

The scene is intentionally static. Objects do not animate and the light direction remains fixed.

## Files

- `weekly4.html` contains the canvas, embedded vertex and fragment shaders, and the JavaScript include.
- `weekly4.js` creates the meshes, camera, lighting, and draw calls.

## Run

Open `weekly4.html` in a browser with WebGL enabled. For a local development server, run:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000/weekly4.html](http://localhost:8000/weekly4.html).

## Requirements

- A modern browser with WebGL support
- Python 3, only if using the local development server