# Puzzlé 2.1 Preview

Puzzlé is a mobile-first daily brain-games platform with seven games in the daily slate.

## 2.1 changes

- **Scoring normalized:** every game is worth up to 100 points; daily maximum is 700.
- **Long-total design:** weekly/monthly views will use compact K-format totals where space is tight while retaining exact values in detail views.
- **Trail repaired:** the board is built from a known valid 17-cell solution path. Checkpoints 1, 7, and 17 occur at the correct path positions and the route contains exactly 17 cells.
- **Crown upgraded:** 6×6 deduction board with unavailable cells, one crown per row/column, no touching crowns, and an in-app solver assertion that verifies the published board has exactly one solution.
- **Crown scoring:** repeated checks reduce the score slightly; the puzzle is designed as a more substantial logic challenge than the 2.0 demo.
- **Groups/Five scoring:** mistakes or extra guesses reduce score so speed is not the only performance dimension.
- **Branding:** use **Puzzlé** in title case.

## Daily slate

1. Mini — crossword
2. Groups — category grouping
3. Five — five-letter word guessing
4. Crown — placement logic
5. Trail — numbered path
6. Digits — 6×6 Sudoku-style logic
7. Shift — one-letter word ladder

## Architecture status

2.1 remains client-only for rapid Netlify Deploy Preview testing. Accounts, cloud daily puzzle data, private groups, shared leaderboards, weekly/monthly history, and the puzzle publishing/editor backend are the next platform layer after game mechanics are validated.

## Netlify

The repository root is directly deployable. `index.html` is the application and `netlify.toml` provides the deploy configuration.
