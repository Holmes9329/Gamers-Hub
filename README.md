# Gamers Hub

Seven tiny black-and-white browser games, each fully self-contained (one `index.html` per folder — no build step, no server, no dependencies). Open any game's `index.html` directly, or open `arcade-hub/index.html` for a landing page that links to all six.

## Games

- **[arcade-hub](arcade-hub/)** — the landing page linking out to the six games below.
- **[rocket-dodge](rocket-dodge/)** — steer a rocket left/right, dodge or shoot falling aliens, chase powerups.
- **[blocks-and-bounce](blocks-and-bounce/)** — brick breaker with a paddle, 6 layouts (including indestructible blocks), and powerups.
- **[beacon-run](beacon-run/)** — a small original 3-level platformer with a story.
- **[sky-dodge](sky-dodge/)** — one-button flap-and-dodge through scrolling pipe gaps.
- **[connect-four](connect-four/)** — classic 4-in-a-row against a lookahead AI opponent.
- **[memory-match](memory-match/)** — card-flip memory game across 3 rounds of growing grids.

Each game's own README has full controls, scoring, and details.

## Running locally

```bash
git clone https://github.com/Holmes9329/Gamers-Hub.git
cd Gamers-Hub
open arcade-hub/index.html   # or any game's index.html directly
```

No install step — these are plain HTML/CSS/JS files that run straight from disk in any modern browser.
