# Minesweeper AI

This project is an AI-powered Minesweeper game developed using Python and Pygame. The game features an intelligent AI algorithm that plays automatically.

## Features

- Customizable board dimensions (width and height)
- Adjustable number of mines
- AI-powered automatic gameplay
- Visual interface
- Game status indicator (remaining mines, game state)
- Colored number display

## Requirements

- Python 3.x
- Pygame

## Installation

1. Install Python on your computer
2. Install the Pygame library:
```
pip install pygame
```

## Usage

To start the game:

```python
python minesweep.py
```

Default settings:
- Board size: 32x32
- Number of mines: 200
- AI move delay: 0.1 seconds

## Customization

You can modify the game settings by editing the variables at the end of `minesweep.py`:

```python
BOARD_WIDTH = 32        # Board width
BOARD_HEIGHT = 32       # Board height
NUM_MINES = 200         # Number of mines
MAX_AI_TURNS = BOARD_WIDTH * BOARD_HEIGHT  # Maximum AI turns
AI_MOVE_DELAY = 0.1     # AI move delay (seconds)
```

## How It Works

- The AI selects the safest moves using basic Minesweeper rules and probability calculations
- Probability of each cell containing a mine is calculated
- AI attempts to play by selecting cells with the lowest risk
- Cells that are definitely safe or definitely mines are prioritized

## Controls

The game is played entirely by the AI. You can use the close button (X) to exit the window.
