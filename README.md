# 🎮 Number Guessing Game (Python)

A simple command-line based Number Guessing Game built using Python.  
The computer randomly selects a number, and the player has to guess it with hints.

---

## 🚀 Features

- 🔢 Random number generation between **-1000 to 1000**
- 🎯 Interactive guessing system with hints:
  - "It's Greater"
  - "It's Smaller"
- 🔁 Replay option
- 📊 Tracks total number of attempts
- 💻 Clean CLI (Command Line Interface)

---

## 🛠️ Technologies Used

- Python 3
- `random` module

---

## 📌 How It Works

1. User chooses whether to play the game
2. Computer generates a random number
3. User keeps guessing:
   - If guess is lower → "It's Greater"
   - If guess is higher → "It's Smaller"
4. Game continues until correct guess
5. Total attempts are displayed
6. User can choose to replay

---

## ▶️ How to Run

1. Make sure Python is installed
2. Save the file as `guessing_game.py`
3. Run the program:

```bash
python guessing_game.py
