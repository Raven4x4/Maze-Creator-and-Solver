# Maze Solver Game

## Overview

This project is a simple maze solver game implemented in Python using the Pygame library. The game generates a maze, and the player can visualize the solution path from the start point to the end point by clicking a "Start" button.

## Features

- Random maze generation using Depth-First Search (DFS) algorithm.
- Maze solving and visualization of the solution path.
- Interactive Pygame window with a start button to initiate the maze-solving process.
- Visual feedback for start and end points in the maze.

## Requirements

- Python 3.x
- Pygame library
- NumPy library

## Installation

1. Ensure you have Python 3 installed on your system.
2. Install the required libraries using pip:
   ```bash
   pip install pygame numpy
   ```

## Usage

1. Clone the repository or download the source code.
2. Navigate to the project directory.
3. Run the game:
   ```bash
   python maze_solver.py
   ```

## Code Structure

- **Button Class**: Handles the creation and interaction of buttons in the game.
- **generate_maze**: Generates a random maze using the DFS algorithm.
- **solve_maze**: Solves the maze using a stack-based DFS approach.
- **draw_maze**: Draws the generated maze on the screen.
- **draw_path**: Visualizes the solution path from start to end.
- **draw_start_end**: Highlights the start and end points in the maze.
- **display_message**: Displays messages on the screen.
- **initialize_game**: Sets up initial game parameters and creates the start button.
- **handle_events**: Manages user input events, including button clicks and quitting the game.
- **main_game_loop**: Contains the main logic for generating the maze, drawing elements, and handling user interactions.
- **prompt_new_maze**: Displays a prompt to start a new maze after solving the current one.

## Controls

- **Start Button**: Click to solve the generated maze.
- **Quit**: Close the window to exit the game.

## How It Works

1. The game initializes with a start and end point, and a "Start" button.
2. The main game loop generates a random maze and displays it.
3. Clicking the "Start" button triggers the maze-solving function, which visualizes the solution path.
4. After solving the maze, the game prompts the user to start a new maze by pressing any key or clicking the mouse.

## Customization

- **Maze Dimensions**: Adjust the `WINDOW_SIZE` and `BLOCK_SIZE` constants to change the size of the maze.
- **Button Appearance**: Modify the `Button` class to change button colors, sizes, and text.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- [Pygame](https://www.pygame.org/) for providing the game development framework.
- [NumPy](https://numpy.org/) for efficient numerical computations.

Enjoy solving mazes!