# mocap-browser 🐒

Browser body-tracking tool (MonkeMocap-inspired).

## Features
- Full-body MediaPipe Pose tracking
- Live green stick-figure preview
- Record / Stop
- Exports:
  1. **Body JSON** – clean pose landmarks
  2. **Nonames JSON** – includes `cameraPoseList`
  3. **GLTF** with:
     - `torso`
     - `head`
     - **4 arm cubes**:
       - `upper_arm.L`
       - `forearm.L`
       - `upper_arm.R`
       - `forearm.R`

These names match common Gorilla Tag IK rig bones so you can parent them easily later.

## How to use
1. Open the page
2. Allow camera
3. Stand so full body is visible
4. Record → Stop
5. Click **GLTF (arms+body)**

## Live demo
https://guestvrgt.github.io/mocap-browser/

Made with tiny kitty paws by GuestVRGT
