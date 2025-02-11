Tic-Tac-Toe Game (Tkinter)
A simple Tic-Tac-Toe game implemented using Python's Tkinter library, allowing two players to play against each other on a 3x3 grid in a GUI-based environment.

Features
2-Player Gameplay: Two players alternate turns to play as 'X' and 'O'.
Responsive UI: A user-friendly graphical interface with clickable buttons for each cell of the Tic-Tac-Toe board.
Winner Detection: The game automatically detects when a player wins or when a tie occurs.
Game Reset: After a win or tie, the game board resets for a new match.
Requirements
Python 3.x
Tkinter library (comes pre-installed with Python)
Installation
Clone the Repository:
To get started with the project, clone the repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/your-username/tic-tac-toe.git
Install Python (if not already installed):
Download and install Python from python.org.
Running the Game:
Navigate to the project directory:
bash
Copy code
cd tic-tac-toe
Run the game using Python:
bash
Copy code
python tic_tac_toe_gui.py
Dependencies:
This project uses Tkinter, which is included with Python. No additional libraries need to be installed.

How to Play
The game is played on a 3x3 grid, where players alternate placing their marks ('X' or 'O').
Click on any empty cell to place your mark. The game will automatically switch to the next player after each move.
The game checks for a winner or tie after every move.
Once a player wins or the game ends in a tie, a message box will appear showing the result. You can click "OK" to reset the game.
How the Game Works
Game Board: The board consists of 9 buttons arranged in a 3x3 grid.
Player Turns: Players alternate between 'X' and 'O'. Each player clicks an empty button to place their mark.
Winner Detection: The game checks if any row, column, or diagonal contains three of the same mark to declare a winner.
Tie Detection: If all the cells are filled without a winner, the game declares a tie.
Reset: After the game ends, the board resets automatically for a new game.
Example Screenshots
Initial Board:

Player X Wins:

Tie Game:

Contributing
Fork this repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

