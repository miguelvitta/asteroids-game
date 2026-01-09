# Asteroids Game

A simple **Python implementation of the classic Asteroids arcade game**.  
Control a spaceship, destroy asteroids, and avoid collisions as they float through space.

This project is written in Python and uses basic game loop logic and object interactions to recreate the traditional Asteroids experience.

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

*(Optional: If you add libraries like `pygame`, list them here with installation instructions.)*

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/miguelvitta/asteroids-game.git
cd asteroids-game
````

Install dependencies if needed:

```bash
# Example if using a virtual environment
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows

pip install -r requirements.txt
```

*(If no requirements file exists, remove or update this step.)*

---

## ▶️ Running the Game

To start the game, run:

```bash
python main.py
```

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

## 🧪 Testing

*(Add instructions here if you include test scripts.)*

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

*(Add your license info here, e.g., MIT License)*

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
