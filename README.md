# Snake Game - Java GUI Project

This repository contains the **Snake Game**, a Java-based GUI application developed as part of my 2nd-semester project. The game is a modern take on the classic Snake game, implemented using Java's Swing framework.
## Screenshots
![Game Start Screen](https://github.com/zainasif123/Snake--Rewind-Java/blob/main/images/Screenshot%202024-08-11%20004044.png)
![Game Play Screen](https://github.com/zainasif123/Snake--Rewind-Java/blob/main/images/Screenshot%202024-08-11%20004100.png)

## Table of Contents
- [Features](#features)
- [Game Overview](#game-overview)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Code Structure](#code-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Responsive Controls**: Smooth snake movement using keyboard inputs.
- **Dynamic Difficulty**: The game speeds up as the snake grows longer.
- **Colorful Graphics**: Randomized snake body colors for a vibrant gameplay experience.
- **Game Over Screen**: Displays the player's score with a restart option.

## Game Overview
The Snake Game is a simple yet engaging game where the player controls a snake that grows longer as it eats rats. The objective is to eat as many rats as possible without crashing into the walls or the snake's own body. The game ends when the snake crashes, displaying the player's score and a "Game Over" message.

### Classes & Key Components:
- **`Game_Class`**: The main class that initializes the game frame.
- **`Game_Code`**: The core class that handles game mechanics, including snake movement, rat generation, collision detection, and rendering.
  - **Snake Movement**: Controlled using arrow keys (WASD).
  - **Rat Generation**: Randomized placement of the rat within the game window.
  - **Collision Detection**: Ends the game if the snake collides with itself or the game boundaries.
- **`MyKeyAdapter`**: Inner class for handling keyboard events.

## Installation

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- An IDE like IntelliJ IDEA, Eclipse, or NetBeans

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/snake-game.git
   ```
2. Open the project in your preferred Java IDE.
3. Build and run the project using the IDE's build tool.

## How to Play
1. Use the **W** (Up), **A** (Left), **S** (Down), **D** (Right) keys to control the snake's direction.
2. Eat the green rat that appears randomly on the screen to grow the snake and increase your score.
3. Avoid colliding with the walls or the snake's own body.
4. If you crash, the game will display your score and a "Game Over" message.
5. Click the "Restart" button to play again.

## Code Structure
- **`Game_Class`**: The entry point of the application. Initializes the game window.
- **`Game_Code`**: Contains the main game logic, including:
  - **`Play_Game()`**: Initializes game variables and starts the game loop.
  - **`paintComponent()`**: Custom painting method to draw the snake and the rat.
  - **`draw()`**: Handles the rendering of the snake and the rat.
  - **`newRat()`**: Generates a new rat at a random location.
  - **`Snake_Movement()`**: Updates the snake's position based on user input.
  - **`check_Rat()`**: Checks if the snake has eaten the rat and updates the score.
  - **`check_Crash()`**: Checks for collisions and ends the game if necessary.
  - **`gameOver()`**: Displays the final score and a "Game Over" message.
- **`MyKeyAdapter`**: Handles keyboard input for controlling the snake's movement.




## Contributing
Contributions are welcome! If you have any ideas or suggestions, feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

