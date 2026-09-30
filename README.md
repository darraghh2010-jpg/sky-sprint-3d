# SkySprint 3D

A lightweight 3D browser obstacle-racing game built with Three.js.

## Build 5.2

Character update:
- 8 original character skins
- Player skin selector on the main menu
- Random AI skins
- Better bean-style bodies with face plates, eyes, arms and feet
- Accessories including crowns, horns, ears and antennas
- Simple running animation

Major tournament update:
- 20-map pool
- 16 regular maps (race + survival/knockout)
- 4 finals
- Random 4-round tournaments
- 12 → 8 → 6 → 4 participant curve
- Physics-based race bots that steer, jump, fall and respawn
- Survival bots that try to stay away from arena edges and hazards
- Patterned carnival-style platform materials instead of flat solid-color floors
- Knockout rounds with shrinking survivor counts
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
- Solid side and underside collision on platforms/rails
- Moving platforms carry the player while standing on them
- Grounded checkpoint pads so checkpoints are never floating over gaps
- Dive move: Shift/F on keyboard or DIVE on mobile
- 11 AI racers in solo mode
- Different bot speeds, hesitations, and spinner mistakes
- Live position counter
- Position-based qualification: top 8, top 6, top 4, then win the final

## Controls
- WASD / Arrow keys: move
- Space: jump
- Shift or F: dive
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
