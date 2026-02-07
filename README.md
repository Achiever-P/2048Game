# 2048Game

2048Game is a MATLAB-based terminal implementation inspired by the popular puzzle game **2048**.  
The game is built using matrix operations, loops, and user input handling to recreate the core mechanics of 2048 in a command-line environment.

This project was created by **Asdrubal Cheng**, at the request of his brother **Aaron Cheng**, as a learning-focused recreation of the classic game.

---

## 🎮 Game Overview

The game is played on a **4×4 matrix** where numbers combine when moved in the same direction.  
The goal is to merge equal numbers and continue playing until no valid moves remain.

---

## 🕹️ Controls

Use the following keys to play:

- **`w`** → Move tiles up  
- **`a`** → Move tiles left  
- **`s`** → Move tiles down  
- **`d`** → Move tiles right  
- **`e`** → Exit the game  

After each valid move, a new tile (**2 or 4**) is randomly placed on the board.

---

## 📜 Rules

- Tiles with the same value merge when they collide.
- Merged tiles produce a new tile with the summed value.
- A tile can merge only once per move.
- The game ends when:
  - There are no empty cells, and  
  - No adjacent tiles can be merged.

---

## 🚀 How to Run

1. Open **MATLAB**
2. Navigate to the project directory
3. Run the script:
   ```matlab
   Math_Game
