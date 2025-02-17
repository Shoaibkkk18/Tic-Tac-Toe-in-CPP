🎮 Tic-Tac-Toe Game in C++
📌 Project Overview
This project is a console-based Tic-Tac-Toe game implemented in C++. It allows two players to take turns marking spaces on a 3×3 grid until a player wins or the game ends in a draw.

🚀 Features
✔️ Two-player mode
✔️ Simple and interactive board UI
✔️ Win detection for rows, columns, and diagonals
✔️ Draw detection when all spaces are filled
✔️ Input validation to prevent overwriting moves

🏗️ How It Works
The game starts with an empty 3×3 board.
Player 1 (X) and Player 2 (O) take turns choosing a position (1-9).
The board updates after each valid move.
The game checks for a win condition (matching row, column, or diagonal).
If all spaces are filled and no one wins, the game ends in a draw.
🖥️ How to Run
Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/tic-tac-toe-cpp.git
cd tic-tac-toe-cpp
Compile the code using g++
bash
Copy
Edit
g++ tic_tac_toe.cpp -o tic_tac_toe
Run the executable
bash
Copy
Edit
./tic_tac_toe
🏆 Winning Conditions
A player wins if their marks (X or O) form a line in any of the following ways:
✅ Horizontal: Three in a row
✅ Vertical: Three in a column
✅ Diagonal: Three in a diagonal

📜 Code Structure
checkwin() – Determines if a player has won or if the game is a draw.
board() – Displays the game board.
main() – Controls the game loop, player turns, and input handling.
🔮 Future Enhancements
🔹 Add a computer AI opponent
🔹 Implement a graphical interface (GUI)
🔹 Improve input handling for better user experience

📜 License
This project is licensed under the MIT License.

Enjoy the game! 🎉

Contact For any questions or suggestions, feel free to reach out:

Shoaib Khan

Email: shoaibk2604@gmail.com

GitHub: your-Shoaibkkk18
