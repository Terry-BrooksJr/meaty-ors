# Meaty-ors 🚀🪨

A fast-paced **Asteroids-style arcade game** built with **Python and Pygame**, where you pilot a ship through space and destroy incoming asteroids before they destroy you.

## 🎮 Overview

**Meaty-ors** is a classic arcade-inspired game that focuses on:

- Real-time player movement and controls
- Projectile-based combat
- Asteroid spawning and destruction
- Collision detection and game state management

Survive as long as possible while clearing the screen of increasingly chaotic asteroid waves.

---

## 🧱 Tech Stack

- **Python 3.x**
- **Pygame** – Game loop, rendering, input handling

---

## 🚀 Features

- 🕹️ Smooth ship movement (rotation + thrust)
- 🔫 Shooting mechanics with projectile tracking
- 🪨 Dynamic asteroid spawning
- 💥 Collision detection (ship ↔ asteroid, bullet ↔ asteroid)
- 🔁 Continuous game loop with real-time updates
- 🧠 Simple physics-based movement system

---

## 📂 Project Structure
├── main.py            # Entry point and game loop
├── player.py          # Player ship logic
├── asteroid.py        # Asteroid behavior and spawning
├── shot.py          # Projectile logic
├── asteroidfield.py        # Game configuration/constants
├── constants.py            # Constants used throughout the game
├── circleshape.py            # Base class for all game classes
├── logger.py            # All logging functions
├── pyproject.toml            # Build Config
└── README.md

*(Adjust file names if your structure is slightly different — I’m not psychic, just suspiciously accurate.)*

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Terry-BrooksJr/meaty-ors.git
cd meaty-ors
```
### 2. Install dependencies
```bash
uv pip install pygame
```
### Running Game
```bash
uv run main.py
```
### 🎮 Controls

| Key | Action              |
|-----|---------------------|
| W   | Thrust forward      |
| A   | Rotate left         |
| D   | Rotate right        |
| S   | Reverse / Brake     |
| Space | Shoot            |
| Esc | Quit game           |


