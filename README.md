# IcoSphere Sweeper

A spherical Minesweeper game using Goldberg Tiling (geodesic sphere) built with Three.js.

## Play Online

- **🌐 Live Game (GitHub Pages)**: https://ozlphrt.github.io/IcoSphere-Sweeper/
- **Main Repository**: https://github.com/ozlphrt/IcoSphere-Sweeper
- **Latest Version (Raw HTML)**: https://raw.githubusercontent.com/ozlphrt/IcoSphere-Sweeper/0d47db7/index.html
- **Master Branch (Raw HTML)**: https://raw.githubusercontent.com/ozlphrt/IcoSphere-Sweeper/master/index.html
- **Latest Commit Tree**: https://github.com/ozlphrt/IcoSphere-Sweeper/tree/0d47db7

### How to Run Locally

1. Download the `index.html` file
2. Open it in a modern web browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   # Then open http://localhost:8000/index.html
   ```

## Features

- **3D Spherical Grid**: Goldberg Tiling creates a geodesic sphere for gameplay
- **Empty Tiles**: Transparent tiles that allow seeing through the sphere
- **Initial Reveal**: Automatically reveals 10% of safe tiles at game start
- **20 Color Presets**: Choose from various color schemes including Blue, Lava, Jungle, Mars, Neon, Mint, Purple, Gold, Shadow, Crimson, Aurora, and more
- **Debug Panel**: Press `CTRL+Shift+Alt+D` to access:
  - Color customization
  - Tile density and mine ratio
  - Camera controls (FOV, position, near/far)
  - Lighting controls (key, rim, ambient)
  - Fog controls
  - Sound settings
- **Rotatable Sphere**: Smooth mouse-driven rotation and panning
- **Scoreboard**: Track mines flagged and tiles explored

## Controls

- **Left Click**: Reveal tile
- **Right Click**: Flag/Unflag tile
- **Right Click + Drag**: Pan sphere
- **Mouse Wheel**: Adjust FOV
- **CTRL+Shift+Alt+D**: Toggle debug panel

## Technical Details

- **Three.js**: 3D graphics and rendering
- **Goldberg Tiling**: Dual polygon method for geodesic sphere
- **Web Audio API**: Synthesized sound effects
- **Canvas 2D API**: Number labels with glow effect
- **Post-processing**: Depth of Field (Bokeh) support

## License

MIT License
