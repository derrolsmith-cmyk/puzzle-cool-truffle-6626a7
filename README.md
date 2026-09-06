# Puzzlé 2.0 Preview

Puzzlé is a mobile-first daily brain-games platform. Version 2.0 expands the original crossword prototype into a seven-game daily slate.

## Games in this preview

- **Mini** — compact crossword with variable grid sizing and black-square layouts
- **Groups** — find four hidden groups of four
- **Five** — five-letter word guessing
- **Crown** — row/column placement logic
- **Trail** — numbered path puzzle
- **Digits** — compact 6×6 Sudoku-style puzzle
- **Shift** — one-letter word ladder

## Shared 2.0 platform behavior

- Today dashboard with all seven games
- Per-game completion state
- Daily completion progress
- Shared daily points total
- Daily streak when all seven are completed
- Shareable result text
- Local-device persistence with `localStorage`
- Mobile-first responsive UI

## Branding

Use **Puzzlé** in title case. The name remains a working brand.

## Architecture status

2.0 is intentionally client-only so it can be tested quickly in Netlify Deploy Previews. A backend is not yet connected. The next platform layer should add accounts, daily puzzle data, friend/family groups, cloud leaderboards, and an admin/editor workflow for puzzle publishing.

## Netlify

The repository root remains directly deployable. `index.html` is the application and the existing `netlify.toml` provides the deploy configuration.
