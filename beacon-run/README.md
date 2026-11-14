# Beacon Run

A tiny black-and-white platformer with an original story -- no build
step, open `index.html` in a browser.

## Story

The Grid's three Beacons have gone dark after a Glitch swept through.
BIT -- a small spark-robot -- has to cross three Sectors and relight
each Beacon before the Grid goes out for good. Fully original setting
and character, not modeled on any existing game's IP.

## How to play

- **Run** with Arrow keys or A/D.
- **Jump** with Up arrow, Space, or W. Jumps are full-height every time
  (no short-hop-on-quick-tap) -- what you see is what you get, so the
  levels are tuned around one predictable arc.
- **Stomp** glitches by landing on top of them; touching one from the
  side costs a life. Falling into a gap costs a life too.
- Collect energy shards for points, and relight the Beacon at the end
  of each Sector to advance.
- 3 lives, shared across the whole run (not per level). Losing all 3
  is game over; reaching the last Beacon wins.
- High score is saved locally in the browser and persists between
  sessions.

## Scoring

- Shard: +10
- Stomping a glitch: +25
- Clearing a Sector: +100

## Levels

Three Sectors, each longer and denser than the last: Outskirts, Static
Fields, and The Core.

## Files

```
beacon-run/
└── index.html   everything -- markup, styling, and game logic in one file
```

Built and playtested with a scripted browser bot before shipping --
all three Sectors were confirmed clearable end-to-end without relying
on luck.

Part of the same arcade detour as Rocket // Dodge and Blocks // Bounce.
