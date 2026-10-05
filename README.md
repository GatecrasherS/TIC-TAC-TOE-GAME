# TIC-TAC-TOE-GAME
A 3x3 Tic-Tac-Toe Game Engine using 2D arrays

## How to Approach Game-Play

1. Run the program execution command.
2. Player 1 selects a preferred marker starting point (`X` or `O`).
3. Players alternate inputs by typing slot IDs mapped between numerical indexes `1` to `9`.
4. The system automatically shifts control vectors and determines victory or draw updates instantly.


## Key Features

* **Dynamic Grid Rendering:** Utilizes a standard 3x3 2D array matrix to track and draw board configurations instantly after every turn.
* **O(1) Win Condition Verification:** Implements optimized algorithmic matrix tracking to evaluate rows, columns, and cross-diagonals for terminal states within constant time execution constraints.
* **Robust Input Sanitization:** Includes penalty-loop validations that intercept out-of-bounds inputs or duplicate move requests without breaking execution loops or causing stack faults.
* **Modular Codebase Architecture:** Follows clean procedural design patterns by separating rendering logic, movement processing tools, and state manipulation loops.

## Core Technical Concepts Explored

* Multi-dimensional array handling (`char board[3][3]`)
* Conditional loop tracking and structural control statements
* Algorithmic coordinate lookup optimization
* Command-line pointer reference formatting

## Compilation & Execution Instructions

To compile and execute the engine locally using any standard GCC compiler, run the following terminal strings inside your system path directory:

```bash
# Compile the C++ source file
g++ -o tictactoe main.cpp

# Run the compiled application executable
./tictactoe
```

