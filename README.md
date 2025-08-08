# 🐢 Turtle Crossing Game

A fun arcade-style game built in Python using the `turtle` graphics library.  
Guide your turtle across a busy road, avoid speeding cars, and level up as the traffic gets faster.  

> Created as part of the **100 Days of Python Bootcamp** by Angela Yu.

---

## 🎮 How to Play
- Use the **Arrow Keys** or **WASD** to move your turtle:
  - Up → ⬆ or `W`
  - Down → ⬇ or `S`
  - Left → ⬅ or `A`
  - Right → ➡ or `D`
- Avoid the moving cars.
- Reach the top to level up — cars will move faster each level.
- Colliding with a car ends the game.

---

## 🛠 Tech Stack
- **Language:** Python
- **Graphics:** turtle
- **Modules:** `turtle`, `time`, `random`

---

## 📂 Project Structure
```
├── main.py         # Game loop & event handling
├── chicken.py      # Player logic
├── car_manager.py  # Car creation & movement
├── scoreboard.py   # Scoreboard & Game Over
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/turtle-crossing-game.git
   cd turtle-crossing-game
   ```
2. Run the game:
   ```bash
   python main.py
   ```

---

## 🙏 Credits
- **Angela Yu** — 100 Days of Python Bootcamp
- Inspired by the classic *Frogger* arcade game
