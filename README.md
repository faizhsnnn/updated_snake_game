# 🐍 Snake Game (Python – Refactored)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Challenge](https://img.shields.io/badge/Challenge-90DaysOfCode-orange)

---
# 📌 Overview

This is an updated and refactored version of a classic Snake Game built using Python’s turtle module.
The project was revisited during my #90DaysOfCode journey to improve code structure, reset logic, and data persistence, rather than adding visual complexity.

The focus of this version is on:

Clean object-oriented design

Improved game state handling

File-based high-score persistence

Readable and maintainable code

---

# 🚀 Features

🐍 Smooth snake movement with segment-following logic

🎮 Keyboard controls with direction validation

🍎 Random food generation and snake growth

📊 Real-time score and persistent high-score tracking (file-based)

💥 Collision detection (wall & self) with clean reset logic

🧠 Modular OOP structure using multiple classes

⚡ Smooth animation using screen.tracer(0) optimization

---
# 📁 Project Structure
```
python-snake-game/
│
├── main.py        # Main game loop & event handling
├── snake.py       # Snake movement, growth, and reset logic
├── food.py        # Food generation and random positioning
├── scoreboard.py # Score display & file-based high score handling
├── data.txt       # Stores persistent high score
├── README.md      # Project documentation
```
---
# 🛠 Installation & Running the Game

1️⃣ Clone the repository
```
git clone https://github.com/faizhsnnn/python-snake-game.git
cd python-snake-game
```

2️⃣ IMPORTANT: High Score File Location

This project uses file operations to store the high score.


✅ Recommended (Best Practice)

Ensure that data.txt is located in the same directory as scoreboard.py, and update the file path in scoreboard.py to:

with open("data.txt") as data:


⚠️ Alternative

If you keep an absolute path, make sure to update it to match your local system, otherwise the game will raise a FileNotFoundError.


3️⃣ Run the game
```
python main.py
```
 

🖥 A Turtle graphics window will open.

Use the arrow keys to control the snake.
On collision, the game resets while preserving the high score.

---
# 🧠 Concepts Practiced

Python Turtle Graphics

Object-Oriented Programming (OOP)

Class composition and responsibility separation

Event-driven programming (keyboard input)

Game loop and screen refresh handling

Collision detection

File handling (read/write operations)

State management (score & high score persistence)

Code refactoring and cleanup

---
# 🔄 What Was Improved in This Version

Cleaner snake reset logic (no ghost collisions)

Improved scoreboard reset handling

File-based high score persistence

Better separation of concerns across classes

More predictable and stable game flow

---
# 🔮 Possible Future Enhancements

Prevent food from spawning on the snake

Speed scaling based on score

Pause / resume functionality

Sound effects

Pygame-based version

Configurable difficulty levels

---
# 👨‍💻 Author

Faiz Hasan

BCA Final Year, Graphic Era University

🚀 #90DaysOfCode | Python Developer

*“Refactoring your own code is where real learning begins.”*
