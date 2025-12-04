# 🚀 Asteroids  
### A classic arcade-style shooter built in Python & Pygame

This project is a full implementation of the Asteroids game built step-by-step through the Boot.dev curriculum.  
Shoot asteroids, watch them split into smaller fragments, and survive as long as you can!

---

## ⭐ Features

- Player-controlled spaceship with rotation and movement  
- Shooting mechanic with cooldown system  
- Asteroids that split into smaller, faster pieces  
- Collision detection between player, shots, and asteroids  
- Randomized asteroid field generation  
- Smooth updates using delta time  
- Uses `pygame.sprite.Group` for clean update/draw loops  

---

## 🎮 Gameplay

- **W** → Move forward  
- **S** → Move backward  
- **A/D** → Rotate left & right  
- **SPACE** → Shoot  
- Avoid collisions with asteroids  
- Shoot large asteroids → they split into medium ones  
- Shoot medium asteroids → they split into small ones  
- Shoot small asteroids → they disappear  

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
- `pygame.sprite.Group` architecture for object ma
