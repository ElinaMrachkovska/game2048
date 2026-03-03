2048 Game — a lightweight browser-based puzzle designed to practice and improve JavaScript skills. The game implements the classic 2048 mechanics: a 4×4 grid, merging tiles with the same value, keyboard arrow controls, score tracking, and win (2048) / game over states. The interface is minimalist and built with HTML/CSS, while the game logic is separated into a modular ES Module (src/modules/Game.class.js).

Key features

Complete game logic: movement in all directions, tile merging, and prevention of double merges within a single move
New tile generation (2 or 4, with a 10% probability for 4) after each valid move
Score tracking and display (score increases by the sum of merged tiles)
Start, restart, win, and game-over notifications
Simple responsive UI with CSS classes for tile styling (field-cell--%value%)

Tech stack

Vanilla JavaScript (ES Modules) — game logic implemented in a Game class
HTML5 / CSS3 (SCSS-friendly structure) — UI and styling
Simple modular approach for code scalability
NPM scripts for running tests (npm run test, npm run test:only)
Production build optimization when needed

DEMO: