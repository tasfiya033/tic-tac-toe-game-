# tic-tac-toe-game-
Description:
This C++ code implements a console-based Tic-Tac-Toe game for two players, Player A and Player B. The game is played on a 3x3 grid, and players take turns entering their moves. The program checks for a winner or a tie after each move and displays the updated game board. The game allows for multiple rounds, and players can choose to continue playing by entering 'Y' or 'y' when prompted.

Features:
1. *Interactive Gameplay:* Players take turns entering their moves, and the program updates the game board accordingly.

2. *Input Validation:* The code includes switch statements to validate player input (1 to 9) and ensures that players cannot overwrite each other's moves.

3. *Winning Conditions:* After each move, the code checks for winning conditions in rows, columns, and diagonals. If a player meets the winning criteria, a congratulatory message is displayed, and the game exits the current round.

4. *Tie Detection:* If no player wins after a certain number of moves (5 moves in this case), the game is declared a tie.

5. *Console Screen Clearing:* The system("CLS") function is used to clear the console screen, providing a clean interface after each move or round.

6. *Delay Effect:* The Sleep function from the Windows API is employed to introduce delays after displaying certain messages, enhancing the user experience.

7. *Multiple Rounds:* Players have the option to continue playing multiple rounds by entering 'Y' or 'y' when prompted.

Enjoy the game!!
