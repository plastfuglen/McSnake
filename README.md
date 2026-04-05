# McSnake

A Monte Carlo simulation tool for snakes and ladders (stigespill).

## Features

- Configurable board size (10–500 squares), dice sides, and number of players (1–4)
- Snakes and ladders editor with add/remove and inline validation
- "Reset to classic" button loads the canonical 10×10 layout
- Run 1 000, 10 000, or 100 000 simulations without freezing the UI
- Results: average, median, min/max turns, histogram, cumulative probability slider
- Multi-player win percentage table
- Mini board visualisation with snake/ladder arrows

## Usage

Open `index.html` directly in a browser — no build step or dependencies required.

## Classic layout (10×10)

| Ladders (bottom → top) | Snakes (top → bottom) |
|---|---|
| 4 → 14 | 17 → 7 |
| 9 → 31 | 54 → 34 |
| 20 → 38 | 62 → 19 |
| 28 → 84 | 64 → 60 |
| 40 → 59 | 87 → 24 |
| 51 → 67 | 93 → 73 |
| 63 → 81 | 95 → 75 |
| 71 → 91 | 99 → 78 |
