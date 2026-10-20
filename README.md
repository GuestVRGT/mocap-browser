# mocap-browser 🐒

Browser body-tracking tool (MonkeMocap-inspired).

## Features
- Live cube preview with **hands**
- Better torso placement (sits under the shoulders)
- Ground clamp: nothing goes below Y=0 (whole body lifts if needed)
- Record / Stop
- Exports Body JSON, Nonames JSON, and animated GLTF

## Cube names in the GLTF
- `torso`
- `head`
- `upper_arm.L` / `forearm.L` / `hand.L`
- `upper_arm.R` / `forearm.R` / `hand.R`

## How to use
1. Open the page
2. Allow camera
3. Stand so full body is visible — cubes appear live
4. Record → Stop → export GLTF

## Live demo
https://guestvrgt.github.io/mocap-browser/

Made with tiny kitty paws by GuestVRGT
