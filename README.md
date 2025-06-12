# ❌⭕ Tic Tac Toe Game in Python

A simple command-line Tic Tac Toe game built using Python. It allows two players to play on a 3×3 grid, switching turns until one wins or the game ends in a tie.

---

## 🧠 Features

- Two-player gameplay (Player X and Player O)
- Clean and readable board output
- Input validation with error messages
- Automatic win and tie detection
- Player switching logic after every turn

---

## 📋 How to Play

1. Run the Python script in any terminal or code editor.
2. Players take turns entering a number between 1 and 9.
3. Each number corresponds to a position on the 3×3 board.
4. The game continues until:
   - A player wins by completing a row, column, or diagonal.
   - All cells are filled without a winner, resulting in a tie.

---

## 🧩 Game Flow Description

### 🔢 Board Structure
The board is a list with 9 positions representing a 3×3 grid. Initially, all positions are empty and marked with a dash (`-`).

---

### 📥 Player Input
Each player is asked to enter a number between 1 to 9. The input is checked:
- It must be within range.
- The selected position must not already be taken.
If invalid, the player is asked to try again.

---

### 🏆 Win Checking

#### Horizontal
The game checks if any of the three rows have the same player's mark.

#### Vertical
The game checks each of the three columns for identical marks.

#### Diagonal
Two diagonals are checked to see if they contain the same player symbol.

If any of these checks pass, the current player is declared the winner.

---

### ⚖️ Tie Checking
If all positions are filled and no winner is found, the game ends in a tie.

---

### 🔄 Switching Players
After each valid move, the game automatically switches between Player X and Player O.

---

### 🔁 Game Loop
The main loop runs continuously:
- Displays the board
- Takes input from the current player
- Checks for win or tie
- Switches the player
The loop ends when there's a win or a tie.

---

## 🚀 How to Run

To play the game:
1. Save the file as `tic_tac_toe.py`
2. Open a terminal and run:
   ```bash
   python tic_tac_toe.py
