📝 Project Report – Tic Tac Toe (Java Console Game)

🔹 Objective

The objective of this project is to implement a Tic Tac Toe game in Java that can be played in the console. The game demonstrates concepts of loops, conditionals, arrays, functions, and AI search methods (Minimax) in Java.


---

🔹 Features

1. Two Player Mode – Player X vs Player O.


2. Player vs AI Mode – Computer uses Minimax algorithm (AI search).


3. Console-based grid display after every move.


4. Input validation – prevents invalid or repeated moves.


5. Win detection – checks rows, columns, and diagonals.


6. Draw detection – declares draw when board is full.


7. Replay Option (optional) – restart game without exiting.


8. Lightweight & portable – runs in any Java-supported environment.




---

🔹 Algorithm (Minimax for AI)

1. Generate all possible moves from the current board.


2. If AI’s turn → choose move with maximum score.


3. If Player’s turn → choose move with minimum score.


4. Assign scores:

+10 → AI wins

-10 → Player wins

0 → Draw



5. Continue recursively until the end of the game tree.


6. Use Alpha-Beta Pruning to skip unnecessary branches.




---

🔹 Sample Console Output

Welcome to Tic Tac Toe (You = X, AI = O)
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
Enter your move (row and col 0-2): 0 0
-------------
| X |   |   | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------
AI is making a move...
-------------
| X |   | O | 
-------------
|   |   |   | 
-------------
|   |   |   | 
-------------


---

🔹 Conclusion

This project demonstrates how Java console applications can implement classic games like Tic Tac Toe. The inclusion of the Minimax AI search method ensures the computer always plays optimally, making it unbeatable.


---

👉 Do you want me to make this into a ready-to-submit PDF/Word report for your project?

