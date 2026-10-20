# mocap-browser 🐒

Browser body-tracking toy inspired by MonkeMocap vibes.

## Features
- Full-body MediaPipe Pose tracking
- Live green stick-figure preview
- **Record / Stop**
- Three export options:
  1. **Body JSON** – clean pose landmarks (for later Blender use)
  2. **Nonames JSON** – includes `cameraPoseList` so the Nonames converter accepts it
  3. **GLTF (4 cubes)** – animated GLTF containing exactly 4 cubes:
     - Torso
     - Head
     - LeftArm
     - RightArm

The 4 cubes are driven by your recorded body movement (shoulders, wrists, nose).

## How to use
1. Open the page / GitHub Pages
2. Allow camera
3. Stand so your whole body is visible
4. Hit **Record**, move around, hit **Stop**
5. Click **GLTF (4 cubes)** to download the animated file

## Live demo
https://guestvrgt.github.io/mocap-browser/

Made with tiny kitty paws by GuestVRGT
