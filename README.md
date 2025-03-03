# GhostHunters

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Features](#features)
- [Game Structure](#game-structure)
- [Controls](#controls)
- [Screenshots](#screenshots)
- [Credits](#credits)

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

## Screenshots
![Picture7](https://github.com/user-attachments/assets/518a1f35-cfff-47d3-8795-1e5a98835081)
![Picture6](https://github.com/user-attachments/assets/aec5fe8d-5f26-4e7c-b184-219dcbaf0b55)
![Picture5](https://github.com/user-attachments/assets/4387980f-b82a-4ea4-bd1e-188dec7c4b0f)
![Picture4](https://github.com/user-attachments/assets/d2009f31-049a-42a7-ad7a-88287cbd73fc)
![Picture3](https://github.com/user-attachments/assets/ee498a3a-1fc6-44c9-8f66-3508e97407cf)
![Picture2](https://github.com/user-attachments/assets/a9edf8ef-0fc2-4de3-80c7-09fbef8184df)
![Picture1](https://github.com/user-attachments/assets/6915f27b-1aed-4578-b513-f21a2ec98f48)
