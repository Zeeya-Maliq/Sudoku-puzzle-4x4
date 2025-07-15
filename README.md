**4×4 Sudoku Solver**

A Python implementation of a 4×4 Sudoku puzzle generator and solver with interactive gameplay. This project demonstrates backtracking algorithms and puzzle generation techniques in a simplified Sudoku format

**How It Works**
The project consists of three main components:
1. **Puzzle Generation**:
   - Starts by filling diagonal 2×2 boxes with random numbers 1-4
   - Uses backtracking to complete the remaining cells
   - Removes 10 numbers to create the playable puzzle

2. **Game Engine**:
   - Tracks player attempts
   - Validates moves against the solution
   - Provides real-time feedback

3. **Validation System**:
   - Checks rows, columns, and 2×2 boxes for duplicates
   - Ensures all moves follow Sudoku rules
  
**Game Instructions**

> Fill all empty spots (marked as .) with numbers 1-4
> Each number must be unique in its row, column, and 2×2 box
> You get 3 attempts to guess wrong numbers
> The game shows the solution when you run out of attempts

**Why 4×4 Sudoku?**
The 4×4 version provides:

1.A simpler introduction to Sudoku concepts
2.Faster puzzle generation and solving
3.Quick gameplay sessions perfect for beginners
4.The same logical principles as standard 9×9 Sudoku
