# mocap-browser 🐒

Browser body-tracking tool (MonkeMocap-inspired).

## Features
- **Live cube preview** (torso + head + 4 arm cubes) instead of creepy stick figure
- Ground clamp: arms never go below Y=0. If any arm tries to go under, the **whole body lifts**
- Record / Stop
- Exports:
  1. Body JSON
  2. Nonames JSON (with cameraPoseList)
  3. GLTF with the same ground-clamped cubes

## Cube names
- `torso`
- `head`
- `upper_arm.L`
- `forearm.L`
- `upper_arm.R`
- `forearm.R`

## How to use
1. Open the page
2. Allow camera
3. Stand so full body is visible — the cubes appear live
4. Record → Stop → export GLTF

## Live demo
https://guestvrgt.github.io/mocap-browser/

Made with tiny kitty paws by GuestVRGT
