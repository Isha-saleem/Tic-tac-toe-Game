#  Tic-Tac-Toe Game With AI

A classic **Tic-Tac-Toe** game with a twist — play against an **unbeatable AI** opponent powered by the **Minimax algorithm**.  
Built using **Python** and **Pygame**, this project was completed as part of [CS50’s Introduction to Artificial Intelligence with Python](https://cs50.harvard.edu/ai/2020/).


##  How It Works

The AI always plays optimally using the **Minimax algorithm**. It looks ahead to evaluate all possible future moves and selects the one that maximizes its chances of winning — or at least prevents losing.


##  Features

-  Graphical interface using **Pygame**
-  **Player vs AI** gameplay
-  **Minimax algorithm** (no external AI libraries)
-  Choose your side: X or O
-  Cleanly separated logic (`tictactoe.py`) and UI (`runner.py`)
  
## How to Play:

1. Launch the game using Pygame (run the script).
2. Choose to play as X or O.
3. Click on the 3x3 grid to place your move.
4. The AI opponent (Minimax algorithm) will respond.
5. Win by aligning 3 of your symbols in a row — horizontally, vertically, or diagonally.
6. The game announces a winner or a tie, and you can restart to play again.

##  Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/tic-tac-toe-ai.git
   cd tic-tac-toe-ai
      
2. **Install required packages**:

```bash
pip install -r requirements.txt
```
3. **Run the game**:
```bash
python runner.py
```
