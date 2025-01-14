# Bataille Navale

## Description

Bataille Navale is a classic battleship game implemented using Python with a graphical interface built with Tkinter. The project is structured into multiple modules, each handling specific functionalities to ensure clarity and maintainability.

## Project Structure

The codebase is organized into several modules and a main file as follows:

- **`navire.py`**: Contains the `Navire` class, representing a ship in the game.
- **`plateau.py`**: Contains the `Plateau` class, managing the game board.
- **`joueur.py`**: Contains the `Joueur` class, managing players and their actions.
- **`interface.py`**: Contains the `ApplicationBatailleNavale` class, handling the user interface and interactions using Tkinter.
- **`main.py`**: Initializes the application and starts the game.

## Module Details

### navire.py

This module defines the `Navire` class, which represents a ship in the game.

- **Attributes**:
  - `nom`: Name of the ship.
  - `taille`: Size of the ship.
  - `positions`: List of the ship's positions on the board.
  - `positions_touchees`: Set of the ship's positions that have been hit.

### plateau.py

This module defines the `Plateau` class, which manages the game board.

- **Attributes**:
  - `taille`: Size of the board (10x10).
  - `grille`: Representation of the board grid.
  - `navires`: List of ships placed on the board.

### joueur.py

This module defines the `Joueur` class, which represents a player in the game.

- **Attributes**:
  - `nom`: Name of the player.
  - `plateau`: Game board associated with the player.
  - `est_humain`: Boolean indicating whether the player is human.

### interface.py

This module contains the `ApplicationBatailleNavale` class, which is the main class for the game's user interface. It handles grid creation, user interactions, and game flow using Tkinter.

## How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Run `main.py` to start the game.

```bash
python main.py



    
