
#  Tic-Tac-Toe Game

A simple implementation of the classic Tic-Tac-Toe (X's and O's) game for two players.

## Features

* Two-player mode (Player X and Player O)
* Simple and intuitive UI (console or graphical, depending on version)
* Detects win, draw, and invalid moves
* Play again option after each round

##  Getting Started

### Prerequisites

Depending on the version, you may need:

* Python 3.x (for Python version)
* A web browser (for web version)
* Node.js (for JavaScript/React version)

### Installation

#### For Python (CLI)

```bash
git clone https://github.com/your-username/tic-tac-toe.git
cd tic-tac-toe
python tic_tac_toe.py
```

#### For Web

```bash
git clone https://github.com/your-username/tic-tac-toe.git
cd tic-tac-toe
open index.html  # or run with live-server
```

##  How to Play

1. The game board is a 3x3 grid.
2. Player X starts first.
3. Players take turns placing their symbol in an empty cell.
4. The first to align 3 of their symbols horizontally, vertically, or diagonally wins.
5. If all 9 cells are filled with no winner, the game ends in a draw.

##  Example

```
 X | O | X
---+---+---
 O | X |  
---+---+---
   | O | X
```

Player X wins diagonally!

##  File Structure

```
tic-tac-toe/
├── tic_tac_toe.py        # Main game script (Python version)
├── index.html            # Web version HTML
├── style.css             # Web version styling
├── script.js             # Web version logic
└── README.md             # Project documentation
```

##  Future Improvements

* Add AI opponent (minimax algorithm)
* Save game history
* Multiplayer over network
* Responsive UI for mobile (web version)

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
