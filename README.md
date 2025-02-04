# Asteroids Game

This repository contains the **Asteroids Game**, a Python-based implementation of the classic arcade game, developed using Pygame.

## Features
- **Asteroid Generation**: Randomized asteroid movement and spawning.
- **Player Controls**: Use arrow keys for movement and spacebar to shoot.
- **Collision Detection**: Detect collisions between asteroids and shots.
- **Scoring System**: Earn points by destroying asteroids.
- **Modular Codebase**: Easily extendable Python modules.

## Files
- `asteroid.py`: Handles asteroid properties and behavior.
- `asteroidfield.py`: Manages multiple asteroids in the game.
- `circleshape.py`: Defines circular shapes used in the game.
- `constants.py`: Stores game constants like screen size and colors.
- `main.py`: The main entry point for running the game.
- `player.py`: Manages player properties and actions.
- `requirements.txt`: Lists dependencies for the game.
- `shot.py`: Handles the properties and behavior of player shots.

## Prerequisites
- Python 3.8 or higher
- Pygame

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/happelj/asteroids-game.git
   cd asteroids-game
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the game:
   ```bash
   python main.py
   ```

## How to Play
1. **Controls**:
   - Arrow keys to move.
   - Spacebar to shoot.
2. **Objective**:
   - Destroy as many asteroids as possible while avoiding collisions.
3. **Scoring**:
   - Points are awarded for every asteroid destroyed.

## Future Enhancements
- Adding power-ups.
- Implementing a leaderboard.
- Enhancing graphics and sound effects.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
[Your Name] - Developer of the Asteroids Game.
