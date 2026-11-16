# RAVEN · Drone Operator Training Simulator

A browser-based drone operator training simulator, built as a Virtual Reality class final project. It runs on desktop and in VR on Meta Quest headsets.

## Run it

- **Locally:** open `index.html` in Chrome, Edge, Firefox or Safari 17+. It needs an internet connection the first time, because it loads the Three.js library from a CDN.
- **Hosted:** upload this folder to any static web host (Netlify, GitHub Pages, and so on). VR on a Quest needs an `https` address: open that address in the Quest Browser and choose **Enter VR**.

## What is in it

- **Airframes:** a hovering bomber that drops grenades, and a one-way FPV strike drone.
- **Missions:** Target Acquisition, Prioritization, Strike, Scenarios (defend the line, convoy interdiction, EW stations, depots, armour), Skill Drills, Free Flight and a Spectate / photo mode.
- **Flight models:** Assist, Angle and Acro (rate mode), with USB radio transmitter support.
- **Battlefield:** about 4 km across, modelled on steppe farmland with tree lines, trenches, villages and a ruined town. The enemy layout changes every mission; enter a seed on the menu to repeat one.
- **Debrief:** after-action report with a flight-path map, Strike Review replay, damage reports and a service record.

## Controls

Open **Controls** on the mission screen for the full list. The essentials on keyboard: `W A S D` to fly, `Space` / `Shift` to climb and descend, `Q E` to turn, `Enter` to drop or arm, `F` to mark a target, `X` to flag an area of interest, `K` for Strike Review, `Esc` for the menu.

## Notes

- Everything is one file, `index.html`. Terrain, models, textures and sound are generated in code; there are no external 3D assets.
- Speeds, weapon ranges, detection and damage values are approximations chosen for believable training. They are not validated data, and the vehicle damage model uses fictional game-balance values.
- Built with AI assistance (Claude) for implementation.
