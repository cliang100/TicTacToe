# Tic-Tac-Toe Game

Welcome to the Tic-Tac-Toe game! This simple console-based game allows you to play Tic-Tac-Toe against a computer opponent. 

## Instructions

1. **File Placement:**
   - Ensure that both `game.py` and `player.py` files are in the same folder.

2. **Run the Game:**
   - Open a terminal or command prompt.
   - Navigate to the folder where `game.py` and `player.py` are located.
   - Run the game by executing the command:
     ```
     python game.py
     ```
     If you're using Python 3, use:
     ```
     python3 game.py
     ```

3. **Gameplay:**
   - Follow the on-screen instructions to make your moves in the Tic-Tac-Toe game.
   - When prompted, enter your moves by specifying a number from 0 to 8, representing the position on the board (as shown during the game).

4. **Enjoy the Game!**
   - Play against the computer and try to win the game by forming a horizontal, vertical, or diagonal line with your symbol ('X').

## Files

- **`game.py`**: This file contains the main logic for the Tic-Tac-Toe game, including the game loop, board management, and the `play` function that orchestrates player moves.

- **`player.py`**: This file defines the player classes (`HumanPlayer`, `RandomComputerPlayer`, and `GeniusComputerPlayer`) used in the game. Each player class has a `get_move` method that determines how the player makes their move.

## Notes

- The game board is displayed in the console, and each cell is represented by a number from 0 to 8. When making a move, enter the corresponding number to place your symbol ('X') in that position.

- The computer opponent has varying levels of intelligence. The `RandomComputerPlayer` makes random moves, while the `GeniusComputerPlayer` uses the minimax algorithm to play strategically.

- Have fun playing Tic-Tac-Toe! If you encounter any issues or have suggestions, feel free to reach out.
