# Ultimate Bowl

A 3D ten-pin bowling game that runs in the browser — Three.js for rendering, Rapier for physics. Everything lives in a single `index.html`.

## Play

Open `index.html` in a browser, or serve the folder locally (no installs needed on Windows):

```
powershell -ExecutionPolicy Bypass -File serve.ps1
```

Then open http://localhost:8123. The 3D and physics libraries load from a CDN, so an internet connection is required.

## Controls

- **Drag** the ball to position it, then **flick forward and release** to throw. A faster flick throws harder; flick slightly sideways to angle the shot.
- A flick that carries past the foul line releases the ball there as a lofted throw.
- **Spin:** slider, `A` / `D` (or arrow keys), or the mouse wheel. `S` resets it. Curving the swipe adds spin too.

## Features

- 1–4 players, hot-seat, full ten-pin scoring including 10th-frame bonus balls
- Regulation-size lane, pins and ball; oiled front / dry back end so spin hooks late
- Reflective lane, shadows, bloom, synthesised sound
