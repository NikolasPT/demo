PR: Add Tic Tac Toe single-file app (tic-tac-toe.html)

Closes #1

This PR adds a single-file Tic Tac Toe web application (tic-tac-toe.html).

Features:
- Fully client-side single HTML file with embedded CSS and JavaScript
- Two-player local play (players alternate X and O)
- Win and draw detection; winning cells highlighted
- Restart / New Game button
- Toggle starting player (X or O)
- Keyboard support: arrow keys to move focus, Enter/Space to place mark
- Accessible status updates (aria-live) and aria labels for cells
- Scoreboard persisted in localStorage (X, O, Draws)

Notes for reviewer:
- Open tic-tac-toe.html in a browser to play
- This addresses issue #1 by providing the playable game
