# Asteroids Game

A **Python recreation of the classic Asteroids arcade game** using Pygame.  
Control a spaceship, destroy asteroids, avoid collisions, and survive as long as possible.  
The game features modular code, asteroid splitting, and simple physics for fun and easy extensibility.

---

## 🚀 Features

- Player‑controlled spaceship with rotation and shooting
- Asteroid objects with basic movement and splitting behavior
- Simple collision detection
- Modular Python code structure

---

## 🧠 How It Works

The core gameplay loops through frame updates, handling:

- Player input for movement and firing
- Physics updates for all game objects
- Rendering objects to the screen
- Collision detection and cleanup

Asteroids split into smaller pieces when shot, and the player must survive as long as possible.

---

## 🛠️ Requirements

This project requires:

- Python (version 3.7+)
- A terminal/command prompt

## 🛠️ Installation

This project uses **uv** for Python environment and dependency management.

1. **Clone the repository**

```bash
git clone https://github.com/miguelvitta/asteroids-game.git
cd asteroids-game
````

1. **Install dependencies**

uv uses the `uv.lock` file to lock dependencies. To install them, run:

```bash
uv install
```

This will:

- Create a virtual environment for the project

- Install **pygame==2.6.1** as specified in `uv.lock` and `pyproject.toml`

1. **Run the game**

```bash
uv run main.py
```

This runs the game using the uv-managed Python environment without requiring manual activation of a virtual environment.

Use the keyboard controls to rotate, thrust, and shoot.

---

## 📁 Project Structure

| File               | Description               |
| ------------------ | ------------------------- |
| `main.py`          | Entry point for the game  |
| `player.py`        | Player ship logic         |
| `asteroid.py`      | Asteroid object behavior  |
| `shot.py`          | Projectile logic          |
| `constants.py`     | Game constants            |
| `circleshape.py`   | Shape utility functions   |
| `asteroidfield.py` | Asteroid field generation |

---

## 🙌 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/foo`)
3. Commit your changes (`git commit -m "Add feature"`)
4. Push to the branch (`git push origin feature/foo`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🚧 TODO / Future Features

These are planned improvements and enhancements for the game:

- **Add a scoring system**
- **Implement multiple lives and respawning**
- **Add an explosion effect for the asteroids**
- **Add acceleration to the player movement**
- **Make the objects wrap around the screen instead of disappearing**
- **Add a background image**
- **Create different weapon types**
- **Make the asteroids lumpy instead of perfectly round**
- **Make the ship have a triangular hit box instead of a circular one**
- **Add a shield power‑up**
- **Add a speed power‑up**
- **Add bombs that can be dropped**

---
