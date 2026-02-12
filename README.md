# Computer_Vision_Toolkit

This repository now includes a standalone **3D Snake Cube puzzle game** built with Three.js.

## Run locally

Open `index.html` directly in your browser, or serve the folder with a local static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Controls

- **Mouse drag / wheel**: Orbit and zoom camera.
- **Click hinge cube (gold)**: Select hinge and rotate the chain tail +90°.
- **X / Y / Z**: Select active rotation axis.
- **R / F**: Rotate selected hinge +90° / -90°.
- **Q / E**: Select previous/next hinge.
- **U**: Undo previous move.
- **S**: Scramble using legal folds.
- **0**: Reset puzzle.

## Gameplay features

- Smooth animated 90° folding.
- Collision prevention and chain integrity checks.
- Grid-snapped positions for robust logic.
- 3×3×3 solved-state detection.
- Visual status HUD and move history.
