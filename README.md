# SkySprint 3D

A lightweight 3D browser obstacle-racing prototype built with Three.js.

## Play locally
Open `index.html` from a static web server. The game imports Three.js from jsDelivr, so internet access is required.

## Controls
- WASD / Arrow keys: move
- Space: jump
- Q / E or drag: rotate camera
- R: respawn at latest checkpoint
- Mobile: on-screen movement buttons + jump; drag the game view to rotate the camera

## Deploy on Vercel
This project is static. Import the GitHub repository in Vercel and deploy with no build command. The included `vercel.json` routes requests to `index.html`.

## Current prototype
- Third-person 3D movement and camera
- Jumping and gravity
- Checkpoints and respawning
- Rotating hazards with knockback
- Moving platforms
- Timer, countdown and finish state
- Touch controls for phones/tablets

## Next milestone
Add private multiplayer rooms with an authoritative shared race state, player presence, synchronized transforms, lobby/ready flow, results and rematches.
