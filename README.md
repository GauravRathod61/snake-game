# Snake Game

## Introduction
This is a simple console-based Snake Game implemented in C++ using the `<bits/stdc++.h>` and `<conio.h>` libraries. The game allows the player to control a snake that moves within a grid, consuming food to grow in size while avoiding collisions with the walls and itself.

## Features
- **Dynamic Grid Size:** The user can choose from small, medium, or large grid sizes.
- **Different Difficulty Levels:** Easy, Medium, and Hard modes are available.
- **Snake Movement:** The player can control the snake using 'W', 'A', 'S', 'D' or the arrow keys.
- **Food System:** Two types of food appear randomly:
  - `$` (normal food, increases score by 1)
  - `%` (special food, increases score by 5)
- **Score Tracking:** The game keeps track of the highest score achieved.
- **Restart Option:** After the game ends, the player can choose to play again or exit.

## Game Rules
1. The snake moves within a grid and grows when it eats food.
2. The game ends if the snake collides with a wall or itself.
3. The player can control the snake using either:
   - 'W' (up), 'A' (left), 'S' (down), 'D' (right)
   - Arrow keys
4. Different food types give different score increments.
5. The player can choose to restart or exit after the game ends.

## Code Structure
### Classes & Variables
- **SnakeGame Class:**
  - `initialize()`: Initializes the snake, grid, and food.
  - `draw()`: Displays the grid and game elements.
  - `input()`: Takes user input for snake movement.
  - `update()`: Updates the snake's position and handles game logic.
  - `foodPlace()`: Randomly places food on the grid.
  - `run()`: Main game loop.
- **Global Variables:**
  - `playerName`: Stores the player's name.
  - `se`, `sss`: Grid size dimensions.
  - `highscore`: Stores the highest score achieved.

## Compilation & Execution
### Compilation (Windows - MinGW Compiler):
```sh
 g++ snake_game.cpp -o snake_game.exe
```
### Running the Game:
```sh
 snake_game.exe
```

## Future Improvements
- Adding a graphical interface using SFML or SDL.
- Implementing a leaderboard system.
- Introducing obstacles for increased difficulty.
- Multiplayer mode.

## Author
Developed by [Your Name]

## License
This project is open-source and available under the MIT License.
