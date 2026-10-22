# Matrix Reality

A browser-based, real-time 3D cyberpunk megacity built with Three.js. Explore a procedural skyline, luminous data gate, animated code rain, and a live HUD.

## Run it

Open `index.html` in a modern browser, or serve this folder with any static web server. The Three.js runtime is loaded from jsDelivr, so an internet connection is required.

## Controls

- **W A S D / arrow keys:** move
- **Mouse:** look around (click the scene to capture the pointer)
- **Space:** jump
- **Shift:** sprint
- **R:** reseed the code rain
- **Code / HUD buttons:** toggle visual layers
- **Touch:** left virtual stick to move, drag the right side to look, JUMP button

## Free GitHub Pages deployment

This repository includes a GitHub Actions workflow that publishes the root folder to GitHub Pages on every push to `main`. In repository **Settings → Pages**, set the source to **GitHub Actions** if it is not already selected.

Live site (after the workflow finishes): https://karam-g.github.io/matrix-reality/

## Notes

- The world is procedural and generated in the browser.
- Desktop uses a larger particle field; touch devices use a reduced count for performance.
- This is a visual simulation, not a real operating system or an online multiplayer world.
