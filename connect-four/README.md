# Connect // Four

A tiny black-and-white Connect Four against a real AI opponent. No build
step -- open `index.html` in a browser.

## How to play

- **Click a column** (or use Left/Right + Space/Enter/Down) to drop a
  piece. You play first and you're the solid white disc; the AI plays
  the hatched disc.
- Get 4 in a row -- horizontally, vertically, or diagonally -- before
  the AI does. The board is full and no one connects 4: it's a draw.
- Click, Space, or Enter restarts once a game ends.

## The AI

The opponent isn't random -- it searches several moves ahead (minimax
with alpha-beta pruning) weighing center control and every possible
3-in-a-rows and 2-in-a-rows for both sides, and it always takes an
immediate win or blocks an immediate loss when one exists. It's beatable,
but it won't hand you a win by accident.

## Scoring

- Wins, losses, and draws are tallied and saved locally in the browser
  (`localStorage`), and persist between sessions on the same
  machine/browser.

## Files

```
connect-four/
└── index.html   everything -- markup, styling, and game logic in one file
```

Part of the same Gamers Hub collection as the other games here -- built
for fun.
