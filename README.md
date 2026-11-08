# Yellow Static

A liminal Backrooms horror game that runs in the browser (Three.js, single `index.html`).
11 levels, 24 tapes, 3 endings, flashlight, sanity, drawers and items, voice acting, and 2-player co-op.

## Play
Open the GitHub Pages link for this repo (see "Deploy" below). WASD to move, Shift to sprint, F flashlight,
E interact, G flare, T tapes. Co-op: title screen, "Co-op", then swap two codes with your friend.

## Deploy (GitHub Pages)
1. Create a new public repository on github.com.
2. Upload `index.html`, `README.md` and `.nojekyll` (or `git push` them).
3. Settings, Pages, Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`, Save.
4. After a minute the game is live at `https://<your-username>.github.io/<repo-name>/`.

## Credits
- Monster: "Captain Clark Rigged (Fixed)" by sushi4055, licensed CC BY 4.0
  (https://sketchfab.com/3d-models/captain-clark-rigged-fixed-dfe9529c43d8479ea1c0b5adac7d3348). Embedded in `index.html`.
- Human model: "Cesium Man" by Cesium, licensed CC BY 4.0
  (https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/2.0/CesiumMan). Embedded in `index.html`.
- Rendering: three.js r128 (MIT), loaded from cdnjs.
- Voices use your browser's built-in speech synthesis, so they differ per device.
