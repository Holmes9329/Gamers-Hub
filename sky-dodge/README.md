# Sky // Dodge

A tiny black-and-white one-button dodge game. No build step -- open
`index.html` in a browser.

## How to play

- **Flap** with Space, Up arrow, W, or a click/tap. That's the only input
  -- gravity pulls you down constantly, flapping gives you a burst upward.
- Fly through the gaps between pipes. Clipping a pipe (or the ground)
  ends the run immediately -- there are no lives, no second chances.
- Hitting the ceiling is harmless; it just stops your climb.
- Gaps get tighter and the pipes scroll faster as your score climbs, up
  to a cap, so the game keeps asking a bit more of you without ever
  becoming unfair.

## Scoring

- +1 for every pipe pair you pass.
- High score is saved locally in the browser (`localStorage`) and
  persists between sessions on the same machine/browser.

## Files

```
sky-dodge/
└── index.html   everything -- markup, styling, and game logic in one file
```

Part of the same Gamers Hub collection as the other games here -- built
for fun.
