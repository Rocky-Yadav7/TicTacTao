# Tic Tac Toe Game (Java GUI)

## Description
This is a simple Tic Tac Toe game implemented in Java using the Swing library for the graphical user interface (GUI). The game allows two players to take turns and play Tic Tac Toe. The program checks for a winner after each move and announces the result accordingly. If the board is full without a winner, it declares a draw.

## Features
- Simple and interactive GUI built using Swing.
- Two-player turn-based gameplay.
- Automatic win detection.
- Draw detection when the board is full.
- Option to restart the game after a win or draw.

## How to Run
1. Install [Java](https://www.java.com/en/download/) if not already installed.
2. Clone this repository:
   ```sh
   git clone https://github.com/your-github-username/your-repository-name.git
   ```
3. Navigate to the project directory:
   ```sh
   cd your-repository-name
   ```
4. Compile the Java file:
   ```sh
   javac TicTacToeGUI.java
   ```
5. Run the program:
   ```sh
   java TicTacToeGUI
   ```

## Code Structure
- `TicTacToeGUI` Class:
  - Initializes the JFrame window.
  - Creates a 3x3 grid of buttons for gameplay.
  - Manages player turns (X and O).
  - Checks for winning conditions after each move.
  - Displays a message dialog for the winner or draw.
  - Provides an option to restart or exit after game completion.

## Example Output
```
Player X wins!
Do you want to play again?
[Yes] [No]
```

## Future Improvements
- Add an AI opponent to play against the computer.
- Implement different difficulty levels for AI.
- Enhance the UI with better styling and animations.


