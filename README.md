# Minimax Maze - Cat and Mouse game

A simple game where a cat tries to catch a mouse on a 5x5 grid, using the Minimax algorithm for decision-making. This project was developed as part of my programming studies, and reflects my foundational understanding of algorithmic thinking and strategic problem-solving.

## Problem Description
The game simulates a cat chasing a mouse on a 5x5 grid. The mouse tries to reach an exit point while the cat tries to catch it. The cat's moves are decided using the Minimax algorithm, simulating strategic decision-making.

## Features
- **Decision-Making Algorithm:** Minimax without Alpha-Beta Pruning, optimizing the cat's path based on the minimization of distance.
- **Heuristic Function:** Uses **Manhattan Distance** to estimate the proximity between the cat and the mouse, calculating the sum of the absolute differences in row and column positions.
- **Modular Code Structure:** Organized into functions for better readability and maintenance.
- **Turn-based Simulation:** Handles alternating turns between the cat and mouse.
- **2D Grid Movement Logic:** Includes boundary checking to prevent out-of-bounds errors.

## Technologies Used
- **Python:** Core programming language.
- **Algorithms:** Minimax for decision-making.
- **Game Logic:** Simulation of movement on a 2D grid.

## How to Run
1. Make sure you have Python installed (preferably 3.8+).
2. Clone the repository to your local machine.
3. Run the script using the command:
   ```bash
   python minimax.py

