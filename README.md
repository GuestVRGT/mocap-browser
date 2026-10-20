# mocap-browser 🐒

Browser body-tracking tool (MonkeMocap-inspired).

## Features
- Full-body MediaPipe Pose tracking
- Live green stick-figure preview
- Record / Stop
- Three exports:
  1. **Body JSON** – clean pose landmarks
  2. **Nonames JSON** – includes `cameraPoseList`
  3. **GLTF (4 cubes)** – animated GLTF with cubes named:
     - `torso`
     - `head`
     - `hand.L`
     - `hand.R`

These names match the main parts of common Gorilla Tag IK rigs so you can easily parent or replace them later.

## How to use
1. Open the page
2. Allow camera
3. Stand so full body is visible
4. Record → Stop
5. Click **GLTF (4 cubes)**

## Live demo
https://guestvrgt.github.io/mocap-browser/

Made with tiny kitty paws by GuestVRGT
