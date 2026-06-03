# 🪕 Bluegrass Trivia

A clean, modern, mobile-friendly single-file web trivia game about bluegrass music history, legends, songs, and players.

## Features
- 15 questions per game (11 Regular @ 100 pts + 4 Shorts @ 200 pts)
- Max score: 1700 points
- Live questions pulled from the community (with solid fallback)
- Randomized selection + answer order every game
- Instant feedback with correct answer reveal
- Score tracking + progress
- Final score + percentage + performance message
- Submit name to persistent local leaderboard (top scores saved in browser)
- Fully playable with keyboard (1-4 or A-D to answer, N/Enter to advance)
- Beautiful bluegrass-inspired design (forest green, amber gold, warm cream)
- Responsive: great on phones, tablets, and desktop

## How to Play
1. Open `index.html` in any modern browser (double-click works)
2. Click **Start New Game**
3. Answer multiple choice questions (click or press 1-4)
4. See your running score and progress
5. At the end, enter a name and submit to the leaderboard
6. Play Again for a fresh random set of 15 questions

## Questions
Questions are community-sourced and load live at runtime (with an embedded fallback set for offline play). The full question pool is not exposed in the interface.

## Tech
- Single HTML file (no build step)
- Tailwind CSS via CDN
- Vanilla JS
- localStorage for leaderboard
- Works completely offline after first load (uses embedded fallback questions)

## Development Notes
- The question data is fetched at runtime from a community source (the URL is not linked in the UI or docs).
- Leaderboard is per-browser (intentional — no backend)
- Seeded demo scores appear on first run for a lively leaderboard

Enjoy pickin' and grinnin'!
