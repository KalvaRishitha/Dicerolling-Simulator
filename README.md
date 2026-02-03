# 🎲 Dice Rolling Simulator (Python)

This is a simple **Dice Rolling Simulator** built using **Python**.  
The program simulates rolling a six-sided dice and displays a random number between **1 and 6**, just like a real dice.

---

## 🚀 Features
- Generates a random dice value (1–6)
- Uses Python's built-in `random` module
- Simple and beginner-friendly
- Console-based interaction

---

## 🛠️ Technologies Used
- Python
- `random` module

---

## ▶️ How It Works
1. The user presses **Enter** to roll the dice.
2. The program generates a random number between 1 and 6.
3. The result is displayed on the screen.

---

## 💻 Code
```python
import random

def roll_dice():
    return random.randint(1, 6)

input("Press Enter to roll the dice...")
print("You rolled:", roll_dice())
