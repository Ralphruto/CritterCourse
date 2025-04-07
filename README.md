# Critter Course - Maze Game

A 2D maze game built with Python and Pygame, featuring enemy AI, level progression, and win/lose conditions.

## Overview

Critter Course is an interactive 2D maze game where players navigate through levels, avoid enemies, and collect keys to progress. The game includes custom screens for start, instructions, credits, and game-over states, with a focus on modular design for performance optimization. This project demonstrates skills in game development, including sprite animations, collision detection, and AI implementation.

## Features

- **Gameplay Mechanics**:
  - Navigate a player character through a maze to collect keys and reach the goal.
  - Avoid enemies with basic AI that patrol or chase the player.
  - Win/lose conditions based on player progress and interactions.
- **Level Progression**:
  - Multiple levels with increasing difficulty, loaded from external files.
  - Smooth transitions between levels with win screens.
- **Custom Screens**:
  - Start screen with instructions.
  - Credits screen to acknowledge contributors.
  - Game-over screen with options to restart or exit.
- **Technical Features**:
  - Collision detection for player-enemy and player-wall interactions.
  - Sprite animations for the player and enemies.
  - Modular game structure with separate files for player, enemy, levels, and settings.
- **Performance Optimization**:
  - Efficient rendering using Pygame’s sprite system.
  - Modular code design for maintainability and scalability.

## Project Structure

- `Critter Course.py`: Main game file that initializes and runs the game loop.
- `enemy.py`: Defines enemy behavior and AI logic.
- `game.py`: Manages the game state and core mechanics.
- `level.py`: Handles level loading and progression.
- `player.py`: Defines the player character and controls.
- `settings.py`: Stores game settings and constants.
- `tile.py`: Manages tile-based map rendering.
- `graphics/`: Folder containing sprite images for the player, enemies, and environment.
- `levels/`: Folder with level data files.
- `sounds/`: Folder with sound effects and background music.
- `requirements.txt`: Lists dependencies (Pygame).

## Technologies Used

- **Python**: For game logic and scripting.
- **Pygame**: For rendering graphics, handling input, and managing game mechanics.

## Credits

This project was developed in collaboration with JalenPacker (https://github.com/JalenPacker/Critter-Course-Game). I contributed to features such as enemy AI, collision detection, and level progression mechanics. This repository hosts my version of the project for portfolio purposes.

## Contributing

Feel free to fork this repository and submit pull requests to contribute to the project. For major changes, please open an issue to discuss your ideas.

