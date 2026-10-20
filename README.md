# mocap-browser 🐒

Nyaaa~!! A silly browser-based motion capture playground inspired by Gorilla Tag / MonkeMocap vibes!

This is **not** a real in-game Gorilla Tag mod (that needs VR + the actual MonkeMocap by NachoEngine).
This is a pure browser toy that uses your **webcam** + MediaPipe to track your body and let you record pose data as JSON.

## Features
- Full-body pose tracking with MediaPipe Pose (33 landmarks)
- Live 3D stick-figure / simple monke visualization
- **Record** button → captures frames while you move
- **Stop** + **Download JSON** → saves the recorded landmark data
- Works entirely in the browser (no install, no server)
- Original silly monke aesthetic

## How to use
1. Open the live page or just open `index.html` (best with a local server or GitHub Pages)
2. Allow camera access
3. Stand so your whole body is visible
4. Click **Record**, move around like a monke, then **Stop**
5. Click **Download JSON** to get the mocap data file

The JSON contains an array of frames with timestamp + 33 pose landmarks (x, y, z, visibility). You can later write a small Blender script to map these onto the NachoEngine Gorilla IK Rig if you want!

## Live demo
Enable GitHub Pages (Settings → Pages → Deploy from main branch) then visit:
https://guestvrgt.github.io/mocap-browser/

## Notes
- Best results with good lighting and your full body in frame
- This is a fun prototype / learning tool, not production mocap quality
- All processing stays on your device (privacy friendly)

Made with ❤️ and tiny kitty paws by GuestVRGT
