# TICTAC-LAB04
This C# program implements a simple command-line Tic Tac Toe game that allows two players to play against each other. Here's what the program does for the user:

Upon running the program, it greets the user with the message "Hi. Let's play TicTacToe!!"

It prompts the user to enter the name of Player 1 and Player 2, respectively.

It creates two Player objects, one for each player, assigning the names provided by the users and assigning "X" marker to Player 1 and "O" marker to Player 2.

It displays the names of the players with a game banner in the format "====== {Player 1 Name} vs {Player 2 Name} =====".

It initializes the Tic Tac Toe board as a 3x3 grid with numbers from 1 to 9 as the initial slots for each cell.

It displays the initial state of the Tic Tac Toe board, showing the players the positions where they can make their moves. The board is displayed in the console.

It starts a loop where the game is played until there is a winner or the game ends in a draw.

Inside the loop, it takes turns for each player. The current player's name is displayed, and they are prompted to choose a slot to place their marker.

After each player makes a move, the updated Tic Tac Toe board is displayed with the current state of the game.

Before updating the board, it checks whether the selected slot is valid or not (i.e., if it's already occupied). If the slot is invalid, the player is prompted to choose again.

If a player manages to get three of their markers in a row (horizontally, vertically, or diagonally), the game detects a winner.

If a winner is found, the program displays a congratulatory message indicating which player won and exits the loop, ending the game.

If no winner is found and the board is filled completely, the game ends in a draw.

If the game ends in a draw (no winner found and all slots are filled), the loop exits, and the program terminates.

Overall, this program allows users to play a simple game of Tic Tac Toe against each other on the console. It handles player turns, input validation, and determines the winner or draw based on the board's state after each move.
