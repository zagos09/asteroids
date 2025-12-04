# 🚀 Asteroids  
### A classic arcade-style shooter built in Python & Pygame

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square)
![Pygame](https://img.shields.io/badge/Pygame-2.5-green?style=flat-square)
![Status](https://img.shields.io/badge/Project-Complete-success?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## ⭐ Features

- Player-controlled spaceship with rotation and movement  
- Shooting mechanic with cooldown system  
- Asteroids that split into smaller, faster pieces  
- Collision detection between player, shots, and asteroids  
- Randomized asteroid field generation  
- Smooth movement using delta time  
- Clean update/draw architecture using `pygame.sprite.Group`

---

## 🎮 Gameplay Controls

| Key | Action |
|-----|--------|
| **W** | Move forward |
| **S** | Move backward |
| **A / D** | Rotate left / right |
| **SPACE** | Shoot |

---

## 🧠 How It Works

The game uses several Python classes:

### `Player`
Handles movement, rotation, shooting, and cooldown logic.

### `Asteroid`
Moves freely in space and splits into smaller asteroids when hit.

### `Shot`
Bullets fired by the player with their own velocity and lifetime.

### `AsteroidField`
Handles the random spawning of asteroids.

### `Logger`
Records game events in `game_events.jsonl`.

All game objects inherit from `CircleShape`, which provides collision detection and positional logic.

---

## 🛠 Tech Stack

- **Python 3**  
- **Pygame**  
- **Boot.dev course structure**  
- `pygame.sprite.Group` architecture for object management  

---

## 🔧 Installation & Running the Game

```bash
git clone https://github.com/zagos09/asteroids
cd asteroids

uv sync    # or pip install -r requirements.txt
uv run main.py


📘 Lessons Learned

While building this project I learned:

How to structure a small game using object-oriented programming

How delta time affects smooth movement in games

How to use sprite groups for clean game loops

Collision detection using simple geometric classes

Managing multiple interacting objects (player, shots, asteroids)

Using Python logging for event tracking

This project significantly improved my understanding of Python and game architecture.

💡 Future Improvements

 Add score system

 Add multiple lives & respawn

 Add screen wrapping

 Add particle explosion effects

 Add power-ups (shield, rapid fire, bombs)

 Add starfield background

 Add game-over screen

 Add sound effects