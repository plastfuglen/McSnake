# McSnake

A Monte Carlo simulation tool for snakes and ladders (stigespill).

**Live app:** https://plastfuglen.github.io/McSnake/

## How to use

1. **Configure the board** — set the number of squares (10–500), dice sides, and number of players (1–4). Click "Tilbakestill til klassisk layout" to load the standard 10×10 setup.
2. **Add snakes and ladders** — use the editor to add connections. Ladders go from a lower square to a higher one; snakes go from higher to lower. Invalid entries (out of range, duplicate starts, wrong direction) are rejected with an error message.
3. **Run the simulation** — choose how many games to simulate (1 000 / 10 000 / 100 000) and click "Kjør simulasjon". A progress bar shows while the simulation runs.
4. **Read the results** — after completion you get:
   - Average, median, minimum and maximum number of turns
   - A histogram showing the turn distribution
   - A slider to read off the cumulative probability of finishing within N turns
   - Per-player averages and win percentages (multi-player mode)

The mini board on the right gives a visual overview of where snakes (red) and ladders (green) are placed.

## Features

- Configurable board size (10–500 squares), dice sides, and number of players (1–4)
- Snakes and ladders editor with add/remove and inline validation
- "Reset to classic" button loads the canonical 10×10 layout
- Run 1 000, 10 000, or 100 000 simulations without freezing the UI
- Results: average, median, min/max turns, histogram, cumulative probability slider
- Multi-player win percentage table
- Mini board visualisation with snake/ladder arrows
- No build step or external dependencies — open `index.html` directly in a browser

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
