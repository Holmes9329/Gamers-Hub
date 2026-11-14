# Rocket // Dodge

A tiny black-and-white 2D browser game. No build step, no dependencies —
just open `index.html` in a browser.

## How to play

- **Steer** with Arrow keys or A/D. That's the only input — the rocket
  fires straight up automatically.
- Aliens fall from the top. Line up under one to shoot it, or steer clear
  to dodge it — both are valid: dodging costs nothing, but only kills
  score points.
- Occasional powerups fall too (circle icons with a letter):
  - **R** — Rapid fire (faster auto-fire), 8s
  - **M** — Multi-shot (3-bullet spread), 8s
  - **S** — Shield (absorbs the next alien hit entirely), up to 10s
- You have 3 lives (top-left triangles). A life is lost only on an actual
  collision with an alien — letting one pass by uncaught is a successful
  dodge, not a penalty.
- Game over when lives hit 0. Press any key or click to restart.

## Scoring

- Killing an alien: +10 (+15 if killed in the top half of the screen —
  rewards shooting early rather than waiting).
- Collecting a powerup: +5, plus its effect.
- High score is saved locally in the browser (`localStorage`) and
  persists between sessions on the same machine/browser.

## Files

```
rocket-dodge/
└── index.html   everything -- markup, styling, and game logic in one file
```

Built as a detour from the nids-project work, purely for fun.
