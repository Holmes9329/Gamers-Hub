# Memory // Match

A tiny black-and-white card-matching game. No build step -- open
`index.html` in a browser.

## How to play

- **Click two cards** to flip them. Matching symbols stay face up;
  anything else flips back after a moment.
- Clear every pair to finish a round. There are 3 rounds, each with a
  bigger grid than the last (6, 8, then 10 pairs).
- Clear all 3 rounds to win. Click or press Space/Enter to move on
  between rounds, and to play again after the final round.

## Scoring

- +20 for every pair you find.
- Clearing a round with fewer moves than par earns a bonus on top --
  the faster you find every pair, the bigger it is.
- High score is saved locally in the browser (`localStorage`) and
  persists between sessions on the same machine/browser.

## Files

```
memory-match/
└── index.html   everything -- markup, styling, and game logic in one file
```

Part of the same Gamers Hub collection as the other games here -- built
for fun.
