# Tic Tac Toe - Player vs Computer

A simple, interactive **Tic Tac Toe** game developed in Java using **Swing** for the GUI.  
You play as **'X'**, and the computer plays as **'O'** with basic AI logic.

## Features

- Play against a basic computer AI.
- Computer tries to win, blocks the player, or plays strategically.
- Keeps track of scores (number of wins) for both player and computer.
- Polished and colorful user interface with:
  - Game board
  - Scoreboard (Leaderboard)
  - Play Again option after each game (Win / Lose / Draw)

## How the AI Works

- If the computer can win immediately, it does.
- If the player is about to win, the computer blocks the move.
- Otherwise, the computer plays:
  - Center first if available
  - Then a corner
  - Then an edge
