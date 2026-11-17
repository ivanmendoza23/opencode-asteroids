# Repository guidance

- This is a dependency-free static browser game. `index.html` defines the 800×600 canvas and loads the game logic from `game.js`; there is no build step or package manifest.
- Run it by opening `index.html`, or serve the repo with `npx serve .` and visit `http://localhost:3000`.
- Canvas size is duplicated as `W`/`H` in `game.js`; keep those values in sync with the canvas attributes in `index.html` when resizing.
- There are no configured test, lint, or typecheck commands. Verify gameplay changes in a browser.
- The README is in Spanish and mentions power-ups and a special asteroid, but these are not implemented in the current `game.js`; treat the source as authoritative.
