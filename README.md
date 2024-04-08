# Tic Tac Toe Game

A new Flutter project.

The Tic-Tac-Toe game developed in Flutter is a classic two-player game where players take turns marking spaces in a 3x3 grid with their respective symbols, usually "X" and "O," aiming to achieve a line of three symbols horizontally, vertically, or diagonally. The game is built using Dart programming language and Flutter framework, providing a visually appealing and interactive user experience.

Logic of the code:

Grid Setup: The game initializes a 3x3 grid where players can make their moves.
Turn-Based Play: The game alternates between the two players, allowing them to select an empty cell to place their symbol.
Winning Condition Check: After each move, the game checks if either player has achieved a winning combination (three symbols in a row, column, or diagonal). If a player wins, the game announces the winner and ends.
Draw Check: If all cells are filled and no player has won, the game declares a draw.
Reset Option: Players have the option to reset the game board to start a new round.
The logic in the code involves managing the state of the game board, handling user inputs (taps on the grid cells), checking for winning conditions after each move, updating the UI accordingly, and providing options for game reset. Flutter's widget-based architecture allows for easy implementation of the game's visuals and interactive elements, making it an ideal platform for creating engaging gaming experiences like Tic-Tac-Toe.
