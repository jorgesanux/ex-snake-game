# EX Snake Game

This project is an implementation of the classic snake game in JavaScript. The snake game is an arcade game where the player controls a snake, which moves around the board. The goal of the game is to eat the food that appears in different places on the board. Each time the snake eats, it grows in length. The game ends when the snake collides with the edges of the board or with its own body.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Code Structure](#code-structure)
5. [Contributing](#contributing)
6. [License](#license)

## Features

- Classic snake gameplay: Control a snake that grows in length as it eats food.
- Collision detection: The game ends when the snake collides with the edges of the board or with its own body.
- Random food placement: Food appears in random locations on the board.
- Score tracking: The game keeps track of the number of food items eaten.

## Installation

To install and run this project, follow these steps:

1. Clone the repository to your local machine using `git clone`.
2. Open the `index.html` file in your browser.

## Usage

To play the game, use the arrow keys to control the direction of the snake. Try to eat as much food as possible without colliding.

## Code Structure

The game code is organized into several classes:

- `Point`: Represents a point in a two-dimensional coordinate system.
- `Food`: Represents a food item in the game.
- `Snake`: Represents the snake in the game.
- `Board`: Represents the game board.
- `GameDrawer`: Responsible for drawing the game on the canvas.
- `SnakeGame`: Represents the game itself, including the game logic and the main game loop.

Each of these classes has its own methods that are used to implement the game logic.

## Contributing

Contributions are welcome. Please open an issue to discuss what you would like to change. Please make sure to update tests as appropriate.

## License

This project is licensed under the GNU General Public License v3.0. See the `LICENSE` file for details.
