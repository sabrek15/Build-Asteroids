# Asteroids Game

## Overview

This is a simple **Asteroids** game built **Python** and **Pygame**. The player controls a spaceship that can rotate, move, and shoot bullets to destory asteroids. The game features collision detection and movement.


## Features

- Player-controlled spaceship
- Shooting mechanism
- Asteroid movement and collision detection
- Basic game physics
- Simple graphics using Pygame


## Installation

### Prerequisties

Ensure you have **Python 3.12**(or later) installed on your system. If you do not have python installed, follow these steps:

#### Installing Python

#### **Windows**:
1. Download Python from the official site(https://www.python.org/downloads/)

2. Run the installer and make sure to check **'Add python to PATH'** before installing
3. verify the installation by  running this command in terminal or command prompt(cmd).
    ```sh
    python --version
    ```

#### **macOS**:
1. Install Homebrew if not installed:
    ```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

2. Install Python using Homebrew:
    ```sh
    brew install python
    ```

3. Verify the installation:
    ```sh
    python3 --version
    ```

#### **Linux**(Debain/Ubuntu-based):

1. Update the package lists and install Python:
    ```sh
    sudo apt update && sudo apt install python3 python3-venv python3-pip
    ```

2. Verify the Installation:
    ```sh
    python3 --version
    ```


### Steps to Install

1. Clone the respository:
    ```sh
    git clone https://github.com/sabrek15/Build-Asteroids.git
    cd Build-Asteroids
    ```

2. Creater a virtual environment(optional but recommended):
    ```sh
    python3 -m venv venv
    source venv/bin/ acitvate   # On Windows use: venv\Scripts\activate
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Run the game:
    ```sh
    python3 main.py
    ```


## **Game Controls**
- **w**  - Move forward
- **s** - Move backward
- **a** - Rotate left
- **d** - Rotate right
- **Spacebar** - shoot bullets

## **File Structure and Breif Description**

```
Build-Asteroids/
|-- .gitignore
|-- constansts.py       # Defines game constants such as speed, size, etc..,
|-- main.py             # Entry point of the game, initializes the game loop
|-- player.py           # Defines Player class, handles movements and shooting
|-- asteroid.py         # Defines the Asteroid class, handles the asteroid creation and updating
|-- shot.py             # Defines the Shot classe, handles bullet creation
|-- circeshape.py       # Defines the CircleShape class for circlular objects, provides common functionality
|-- asteroidfeild.py    # Defines AsteroidField class which manges the movement of asteroids and creation of asteroids
|-- requirements.txt    # This file contains whatever required library files, etc.., to be installed to run the game
```

## **Future Improvements**

- Implementing a scoring system
- Implementing mulitple lives and asteroids
- Adding a background Image
- Implementing the speed power-up


## **Contributions**

Contributions are welcome! If you'd like to improve the game, feel free to submit a pull request or report issues.


<!-- ## **Author** -->
