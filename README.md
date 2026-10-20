# mocap-browser 🐒

Nyaaa~!! Browser-based body tracking playground (MonkeMocap-inspired).

## Features
- Full-body MediaPipe Pose tracking (33 landmarks)
- Live 3D green stick-figure visualization
- **Record / Stop**
- **Two download buttons:**
  1. **Download Body JSON** → clean pose data for later use in Blender (gorilla IK rig etc.)
  2. **Download for Nonames** → includes a `cameraPoseList` so https://nonamesanimations.onrender.com/ accepts the file without the "No cameraPoseList found" error

> Note: the `cameraPoseList` is a **fake** path derived from your head/nose movement. It is only there so the Nonames converter stops complaining. Real AR camera tracking still requires the original Blendartrack / Retargeter phone app.

## How to use
1. Open the page (or enable GitHub Pages)
2. Allow camera
3. Stand so your whole body is visible
4. Hit **Record**, move around, then **Stop**
5. Download whichever JSON you need

## Live demo
https://guestvrgt.github.io/mocap-browser/

Made with tiny kitty paws by GuestVRGT
