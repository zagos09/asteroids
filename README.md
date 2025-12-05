# 🚀 Asteroids - Python Arcade Game

A classic space shooter game built with **Python** and **Pygame**.
This project was developed as part of the Boot.dev backend engineering curriculum to practice **Object-Oriented Programming (OOP)**, game loop logic, and collision detection.

<img width="682" height="388" alt="asteroid_real" src="https://github.com/user-attachments/assets/ee62b84c-2ec6-46a9-bba2-af66690b2be4" />



## 🎮 Features
* **Player Movement:** Smooth rotation and acceleration mechanics using vector math.
* **Shooting System:** Projectile management with cooldowns and range limits.
* **Asteroid Logic:** Random generation and splitting mechanics (Large -> Medium -> Small).
* **Collision Detection:** Circle-based collision logic for high performance.
* **Game Loop:** Custom-built game loop managing updates and drawing.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Library:** Pygame

## 🚀 How to Run Locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/zagos09/asteroids.git](https://github.com/zagos09/asteroids.git)
    cd asteroids
    ```

2.  **Create a Virtual Environment (Optional but Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install pygame
    ```

4.  **Start the game:**
    ```bash
    python main.py
    ```

## 🕹️ Controls
* **W / Up Arrow:** Accelerate
* **A / Left Arrow:** Rotate Left
* **D / Right Arrow:** Rotate Right
* **Space:** Shoot
