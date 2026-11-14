# Arcade

A tiny local hub page linking to the 3 black-and-white browser games in
this folder's sibling directories. No build step, no server, no
dependencies — just open `index.html`.

## How to use

Open `arcade-hub/index.html` directly in a browser (double-click, or
Cmd+O). It's one static page with a card for each game:

- **Rocket // Dodge** — steer a rocket left/right, dodge or shoot falling
  aliens, chase powerups.
- **Blocks // Bounce** — brick breaker with a paddle, 3 layouts, and
  powerups.
- **Beacon Run** — a small original 3-level platformer with a story.

Click any card to jump straight into that game (opens
`../<game>/index.html`). Each game is fully self-contained and also works
fine opened on its own.

## Files

```
arcade-hub/
└── index.html   the hub page -- links out to the sibling game folders
```

This hub is local-only (not deployed anywhere) — it's just a convenient
front door to the 3 games sitting alongside it in
`Personal - Engineering/`.
