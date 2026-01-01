# Asteroid Slayer 🚀

A modern implementation of the classic Asteroids arcade game, built with Python (3.12+) and Pygame.

---

## Features

- **Physics-Based Movement**: Inertia-based thrust and rotation.
- **Combat**: Rapid-fire shooting with cooldowns.
- **Dynamic Asteroids**: Asteroids split into smaller chunks when destroyed.
- **Event Logging**: Records game state and events to `.jsonl` files for analysis.

## Installation

### Prerequisites

- Python >= 3.12
- `uv` (Recommended) or standard `pip`

### Quick Start (using `uv`)

```bash
git clone https://github.com/saadiee/asteroid-slayer.git
cd asteroid-slayer
uv run main.py
```

### Standard Setup

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

## Controls

| Key       | Action              |
| :-------- | :------------------ |
| **W**     | Thrust Forward      |
| **S**     | Reverse Thrust      |
| **A / D** | Rotate Left / Right |
| **SPACE** | Shoot               |
| **ESC**   | Quit                |

## Project Structure

- `main.py`: Game loop and entry point.
- `player.py`: Ship logic and movement.
- `asteroid.py`: Asteroid behavior and splitting.
- `shot.py`: Bullet physics.
- `logger.py`: Simulation data logger.
- `constants.py`: Game configuration.
