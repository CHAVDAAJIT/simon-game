# simon-game

A simple browser-based Simon game. The game shows an increasing sequence of colored buttons; the player must repeat the sequence by clicking the buttons.

## How to play
- Open [index.html](index.html) in your browser.
- Press any key to start.
- A color will flash — click the buttons in the same order.
- Each successful round increases the level and adds a new color to the sequence.
- The game ends when you make a mistake; press any key to restart.

## Controls
- Start: press any key
- Input: click the colored buttons

## Files
- [index.html](index.html) — game page and UI
- [style.css](style.css) — styles for the buttons and flashes
- [app.js](app.js) — game logic
- [README.md](README.md) — this file

## Key code references
- Game flow: [`levelUp`](app.js)
- User input handler: [`btnPress`](app.js)
- Answer validation: [`checkAns`](app.js)
- Reset state: [`reset`](app.js)
- Game state variables: [`gameSeq`](app.js), [`userSeq`](app.js)

## Development
- Open [index.html](index.html) locally (no build step required).
- Modify styles in [style.css](style.css) or logic in [app.js](app.js) to extend features (e.g., sounds,