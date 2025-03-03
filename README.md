# GhostHunters
![Picture1](https://github.com/user-attachments/assets/1dbfdd5a-4121-4f16-961c-e50e8d1e3422)
![Picture2](https://github.com/user-attachments/assets/07c37784-8a8f-4ef0-a86b-2ccd27dd8d10)
![Picture3](https://github.com/user-attachments/assets/a6dcfb80-bfd4-4839-9c87-f1588fd28269)
![Picture4](https://github.com/user-attachments/assets/437d9dae-e5fc-4012-bd49-dd1d150f9464)
![Picture5](https://github.com/user-attachments/assets/a88eda45-980d-4f3f-a1d7-84fa2645a9e1)
![Picture6](https://github.com/user-attachments/assets/a65cb7f0-57a6-4920-84ca-817e7e011574)
![Picture7](https://github.com/user-attachments/assets/85d3c658-43ea-46de-8aaf-fa5115cbbe9d)

## Introduction
**GhostHunters** is a 2D maze game where players navigate through a maze to collect coins while avoiding ghosts. The game offers multiple difficulty levels, high score tracking, and various scenes, including a start menu, help screen, and score display. The objective is to collect all coins in the maze and avoid the ghosts to win.

## How to Play
- **Start the game** and choose your preferred **difficulty level**: Easy, Medium, or Hard.
- Use the **arrow keys** to navigate your player through the maze.
- Your goal is to **collect all the coins** in the maze.
- **Avoid the ghosts**: Colliding with a ghost will cost you a life.
- Complete the maze before the **timer runs out**.

## Features
- **Multiple Difficulty Levels**: Choose between Easy, Medium, and Hard modes.
- **High Score Tracking**: Your best times for each difficulty are saved and displayed.
- **Dynamic Enemy Movement**: Ghosts patrol the maze with different movement patterns.
- **Time-based Challenges**: Complete the maze within a time limit for each level.
- **Interactive Menus**: Navigate through menus to start the game, view scores, or get help.

## Game Structure
### Core Classes
- **Player**: Manages player movement, collision detection, and rendering.
- **Enemy**: Controls ghost behavior and patrolling logic.
- **Coin**: Represents the collectible items scattered around the maze.
- **CollisionHandler**: Handles collision detection between player, coins, and ghosts.

### Scene Classes
- **StartMenuScene**: The main menu that allows navigation to other parts of the game.
- **GameplayScene**: The main gameplay screen where the maze, player, and enemies are rendered.
- **LevelSelectionScene**: Lets players select the difficulty level before starting a game.
- **ScoresScene**: Displays and manages the high scores for each difficulty level.
- **GameOverScene**: Displays the results after the game ends, with an option to return to the main menu.
- **HelpScene**: Displays the instructions on how to play the game.
- **AboutScene**: Provides information about the game and its creators.

## Controls
- **Arrow Keys**: Move the player character (Up, Down, Left, Right).
- **Enter**: Select menu options (e.g., start the game, select difficulty, etc.).
- **Escape**: Return to the main menu during gameplay.
