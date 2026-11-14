# Blocks // Bounce

A tiny black-and-white brick breaker. No build step -- open `index.html`
in a browser.

## How to play

- **Move** the paddle with Arrow keys or A/D.
- **Launch** the ball with Space, Up arrow, or a click when it's resting
  on the paddle.
- Break every block to clear the level. There are 3 layouts, each denser
  and faster than the last. Solid white blocks take 2 hits; outlined
  blocks take 1.
- You have 3 lives (top-right dots). A life is lost only when every ball
  on screen falls past the paddle.
- Occasional powerups drop from broken blocks (circle icons):
  - **W** -- Wide paddle, 9s
  - **M** -- Multi-ball (splits into 3 balls)
  - **S** -- Slow ball, 8s
  - **L** -- Extra life
- Clear all 3 layouts to win. High score is saved locally in the browser
  and persists between sessions.

## Scoring

- Breaking a block: 10-40 points depending on row (higher rows score more).
- Collecting a powerup: +5, plus its effect.

## Files

```
blocks-and-bounce/
└── index.html   everything -- markup, styling, and game logic in one file
```

Part of the same detour as Rocket // Dodge -- built for fun between rounds
of the nids-project work.
