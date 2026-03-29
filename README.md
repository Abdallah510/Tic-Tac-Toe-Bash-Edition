# Tic-Tac-Toe — Bash Edition

A two-player Tic-Tac-Toe game that runs in the terminal, written entirely in Bash. It goes beyond the classic game by adding a scoring system and a set of strategic moves that let players manipulate the board each turn.

## How It Was Made

Built using pure Bash scripting with no external dependencies. It uses associative arrays to represent the grid, recursive functions for input validation, and file I/O for saving and loading game states.

## Features

- Supports 3×3, 4×4, and 5×5 grid sizes
- Two-player turn-based gameplay (X vs O)
- Five move types per turn: place a mark, remove a mark, swap two rows, swap two columns, or swap two cells
- Scoring system that rewards board alignment and penalizes the opponent's alignments
- Save and load game state from a file
- Input validation on all moves and coordinates
