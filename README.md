# 🐍 Snake Game

A classic Snake game built using Python's `turtle` module.  
Guide the snake to eat food that appears at random positions. Each time the snake eats, it grows longer. Avoid running into the walls or yourself—otherwise it's Game Over.

---

##  Project Structure

- **`main.py`** – Launches the game, initializes all components, and starts the game loop.
- **`snake.py`** – Defines the `Snake` class:
  - Builds the snake with a list of segments.
  - Handles movement and the growing mechanism.
  - Detects collisions with walls or tail.
- **`food.py`** – Defines the `Food` class to:
  - Create food at random screen locations.
  - Reposition it when consumed.
- **`scoreboard.py`** – Defines the `Scoreboard` class to:
  - Keep track of the current score and high score.
  - Display results and show "Game Over" when the game ends.
- **`data.txt`** – Stores the high score persistently across game sessions.

---

##  How to Run

```bash
git clone https://github.com/IvanShepeta/snake_game.git
cd snake_game
python main.py
