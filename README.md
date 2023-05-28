#### Video Demo:  <https://youtu.be/s8ZqqDeh2J4>

# Tic-Tac-Toe Game

This is a command-line implementation of the Tic-Tac-Toe game in Python. It allows two players to take turns entering their moves until there is a winner or no more moves are available.

## How to Play

1. Run the Python script `tictactoe.py`.
2. The game board will be displayed, showing a 3x3 grid with empty cells represented by underscores (`_`).
3. Players will take turns entering their moves by specifying the row and column numbers of their desired cell.
4. Row and column numbers start from 1, indicating the top-left cell. For example, the middle cell is represented by row 2, column 2.
5. The game will validate if the chosen cell is empty. If not, the player will be prompted to choose again.
6. The game board will be updated with the players' moves after each turn.
7. The game continues until there is a winner (a player has three of their symbols in a row, column, or diagonal) or no more moves are available (a tie).
8. The winner will be displayed as "Player X wins!" or "Player O wins!", or "Tie" in case of a tie game.
9. The program will exit after displaying the winner or tie result.

## Code Structure

The code consists of the following main components:

- `draw_line`: A helper function to draw a line with a specified width, edge character, and filling character.
- `display_winner`: A function to display the winner of the game based on the player number.
- `check_row_winner`: A function to check if a specific row has a winner and return the player number. Returns 0 if there is no winner.
- `get_col`: A function to retrieve the values of a specific column from the game grid.
- `get_row`: A function to retrieve the values of a specific row from the game grid.
- `check_winner`: A function to check if there is a winner in the game by examining rows, columns, and diagonals.
- `start_game`: A function to initialize the game grid with empty cells.
- `display_game`: A function to display the current state of the game grid.
- `add_piece`: A function to add a player's move to the game grid.
- `check_space_empty`: A function to check if a specific cell in the game grid is empty.
- `convert_input_to_coordinate`: A function to convert user input (1-indexed) to the corresponding 0-indexed coordinate.
- `switch_player`: A function to switch the current player between Player 1 (X) and Player 2 (O).
- `moves_exist`: A function to check if there are any empty cells remaining in the game grid.
- `main`: The main function that orchestrates the game flow.

## Running the Code

To run the Tic-Tac-Toe game, follow these steps:

1. Make sure you have Python installed on your machine.
2. Download the `tictactoe.py` script from this repository.
3. Open a terminal or command prompt and navigate to the directory containing the script.
4. Run the command `python tictactoe.py` to start the game.
5. Follow the on-screen prompts to enter your moves and play the game.

Enjoy playing Tic-Tac-Toe!

