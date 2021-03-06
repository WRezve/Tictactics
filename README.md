# Tictactics
**Team Name:** MWL

**Group Members:** Dylan McLaughlin, Rezve Wohab, Vy Le

**Objective**

This project is contributed to EECS1012. It is a computer program about Tic Tac Toe game developed with 3 members McLaughin, Wohab, and Le.

**Overview**

Our project is to create a game of Tic-Tac-Toe. Players will select places on the board to put their X and try to get three in a row, while the program they play against will place O’s at random in free spaces on the board. If the program places three O’s in a row, the player loses. The program will use arrays and check if any lines on the board are completely filled with the same symbol, then check which symbol it is to see who has won. If the player wins, a point is added to their score. If there is a tie at the end of the game, it is repeated until there is a winner. The match will be a best of three, and the first to two points wins the game.


Functional Requirements:
- User will press a button that displays the message, "START GAME".
- Rules on how to play TicTacToe will be displayed, user will press a button that displays "PLAY" to begin.
- User will place one of nine spaces on checkerboard with their symbol (which is X).
- Turn ends with placing a symbol on the checkerboard.
- Program will pick the next space to place it's symbol (which is O).
- Each player's goal is to place three of their symbols in a row.
- Each player will try to prevent the other from winning by blocking two symbols of their opponents with their own.
- If all the symbols have been placed and there is no winner, another game starts with an empty board.
- Winner will get to place their symbol first on the board.
- Whoever gets to place their symbol first on the board will be chosen at random if the previous game ended with a tie.
- Game repeats with the player and the program taking turns placing their symbols on the board.
- Process is repeated until either the player or the program accumulates two wins.
- After there is a winner, a scoreboard will appear on the side of the screen showing each player's points.
- If the player wins, a message appears saying "You Win!" with confetti and fireworks animations along with a victory song.
- If the player loses, a message appears saying "You Lose!" with an animation of a clown laughing and a sad trombone song.
- Final screen says "GAME OVER" and has a button displaying "PLAY AGAIN", if user wishes to play again.
