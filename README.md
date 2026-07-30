# Factorio 3D Sprite Baker

A web-based, client-side utility designed to assist modders in rendering 3D models (.gltf, .glb, .obj) into 2D sprite sheets optimized for the game *Factorio*.

## Features
- **Orthographic Factorio Camera:** Locks to the standard 45-degree orthographic projection.
- **Dynamic Bounding-Box Auto-Fit:** Automatically scales the scene, camera zoom, and shadow camera frustum to match the dimensions of any loaded model.
- **Three Render Passes:**
  - **Base Pass:** Standard color and texture render.
  - **Shadow Pass:** Isolates transparent multiplicative shadows on a transparent background.
  - **Normal Map Pass:** Renders screen-space normal map vectors for dynamic lighting support.
- **Factorio Spatial Guide:** Displays a ground grid representing 1x1 Factorio map tiles (1 unit = 1 tile).
- **Animation Selector:** Selects and previews individual skeletal animations from loaded files.
- **Lua Code Generator:** Generates a copy-pasteable layered sprite/animation prototype definition.

## Usage
Simply open `index.html` in any web browser. Load your 3D files (select both the model and texture files together if using separate assets), adjust your parameters, and click **Bake Spritesheet**.

## License & Credits

- **Copyright:** Copyright (c) 2026 Suki Sunako. Licensed under the MIT License.
- **Inspiration:** Highly inspired by the game *Factorio* by Wube Software.
- **Disclaimer:** This tool is an unofficial fan-made project. All rights to *Factorio*, including trademarks, original graphics, and design concepts, belong entirely to Wube Software.
