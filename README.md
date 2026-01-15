# Asteroids

A classic **Asteroids-style arcade game** built with **Python + Pygame**. Pilot your ship, dodge incoming rocks, and blast them into smaller pieces while trying not to get smashed to space dust.


---

## Features

- Player-controlled ship movement
- Asteroids that drift across the screen
- Shooting (bullets/projectiles)
- Collision detection (ship ↔ asteroids, bullets ↔ asteroids)
- Simple game loop with lose conditions

Optional ideas to extend it:
- Score + high score saving
- Multiple lives + respawn invincibility
- Screen wrapping for ship/asteroids/bullets
- Power-ups (shield, rapid fire, speed boost)
- Better animations, particles, sound effects

---

## Requirements

- **Python 3.10+** (3.11/3.12/3.13 works too)
- **Pygame**

Install Pygame:

```bash
pip install pygame
```

---

## How to Run

From the root of the project:

```bash
python main.py
```

### Using a Virtual Environment (recommended)

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install pygame
python main.py
```

---

## Controls

- **W / A / S / D** or **Arrow Keys** — Move / Rotate
- **Space** — Shoot
- **Esc** — Quit

---

## Project Structure

(Example — update to match your repo)

```text
.
├── main.py
├── player.py
├── asteroid.py
├── bullet.py
├── assets/
│   ├── images/
│   └── sounds/
└── README.md
```

---

## Extending the Game

Some solid next upgrades:
- Add score + on-screen HUD
- Add lives + respawn logic
- Add screen-wrapping
- Add sound effects + particles
- Add menus (start/pause/game over)

---
