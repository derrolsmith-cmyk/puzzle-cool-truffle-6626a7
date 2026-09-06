# PUZZLÉ 1.0

A Netlify-ready, mobile-first daily crossword prototype.

## Deploy
1. Unzip the package.
2. Drag the folder into Netlify Deploys, or connect the folder to a Git repository.
3. Netlify will serve `index.html` automatically.

## Included in 1.0
- Daily 5×5 crossword
- Practice mode
- Touch + physical keyboard support
- Across/Down clue navigation
- Timer
- Check and Reveal
- Completion modal and share text
- Local device stats: plays, solve rate, best time, streak
- Archive/About shells
- Netlify security headers

## Deliberately deferred
- Real accounts/auth
- Shared friend/family groups
- Cloud leaderboard
- Real daily puzzle feed
- Admin/editor for AI-generated puzzles
- Multi-game platform backend
- Push notifications
- Light theme

## Recommended 1.1 architecture
Use Supabase for:
- users
- puzzles
- puzzle_entries
- groups
- group_members
- leaderboard_results

Keep the front-end static on Netlify and add Supabase for auth/data.
