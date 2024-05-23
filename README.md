## AngryBird Game - README

### Introduction
Welcome to AngryBird, a Python-based game inspired by the popular Angry Birds game. This game involves launching birds to knock down structures and defeat pigs. The codebase includes several modules for handling different aspects of the game, such as the user interface, game objects, maps, and the physics engine.

### Features
- **Physics-based gameplay**: Realistic physics simulations for bird trajectories and object interactions.
- **Multiple levels**: Various maps with different layouts and challenges.
- **Rich graphics**: Custom images and fonts for an engaging visual experience.

### Prerequisites
- Python 3.8 or higher
- Pygame library

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/AngryBird.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd AngryBird
   ```
3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Game
To start the game, run the `index.py` file:
```bash
python index.py
```

### Project Structure
- **index.py**: Main entry point of the game. Initializes the game loop and handles user input.
- **interface.py**: Manages the game's user interface, including menus and HUD elements.
- **maps.py**: Contains definitions for different game levels and their layouts.
- **objects.py**: Defines the game objects such as birds, pigs, and blocks.
- **physics_engine.py**: Implements the physics engine to simulate realistic interactions between game objects.
- **Fonts/**: Contains font files used in the game.
  - `arfmoochikncheez.ttf`
  - `Comic_Kings.ttf`
- **Images/**: Contains image assets for the game.
  - `bird.png`
  - `block_destroyed1.png`
  - `block1.png`
  - `pig_damaged.png`
  - `pig1.png`
  - `pig3.png`
  - `wall_horizontal.png`
  - `wall_vertical.png`
- **.idea/**: Contains IDE-specific configuration files.
- **__pycache__/**: Stores compiled Python bytecode files.

### How to Play
1. Launch the game using the instructions above.
2. Use the mouse to aim and adjust the trajectory of the bird.
3. Release the mouse button to launch the bird.
4. The goal is to knock down structures and defeat all the pigs on the level.

### Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

### License
This project is licensed under the MIT License.

### Acknowledgments
- Pygame: The game library used for development.
- The open-source community for providing resources and inspiration.
