# SkySprint 3D

A lightweight 3D browser obstacle-racing game built with Three.js.

## Build 2
The game now has a full tournament flow:

- Main menu
- 4-round tournament
- Sky Dash
- Bounce Bridge
- Spinner Summit
- Crown Climb FINAL
- Qualification screens between rounds
- Time-limit elimination
- Checkpoints and respawning
- Moving platforms and rotating knockback hazards
- Keyboard and mobile controls
- Champion screen after winning the final

## Controls
- WASD / Arrow keys: move
- Space: jump
- Q / E or drag: rotate camera
- R: respawn at latest checkpoint
- Mobile: on-screen movement buttons + jump; drag the game view to rotate the camera

## Deploy on Vercel
This project is static. Import the GitHub repository in Vercel and deploy with no build command. The included `vercel.json` routes requests to `index.html`.

If the repo is already connected to Vercel, pushes to `main` should trigger a new deployment automatically.

## Next milestones
- AI opponents for solo tournaments
- Player names and cosmetics
- Private multiplayer rooms
- More maps and finals
