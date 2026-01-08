#  Snake Water Gun Game (Python)

This is a simple Snake–Water–Gun game implemented in Python, similar to Rock–Paper–Scissors.  
The user plays against the computer, and the winner is decided based on predefined rules.

# Game Rules
Snake (s) drinks Water → Snake wins  
Water (w) douses Gun → Water wins  
Gun (g) kills Snake → Gun wins  
Same choices → Draw

---

# How the Game Works

1. The computer randomly chooses:
   - Snake
   - Water
   - Gun
2. The user inputs their choice:
   - s for Snake  
   - w for Water  
   - g for Gun
3. The program compares both choices and prints:
   - You win
   - You lose
   - It's a draw

##Choice Mapping Used

| Choice | Value |
|------|------|
| Snake | 1 |
| Water | -1 |
| Gun | 0 |

---

# Requirements
- Python 3.x installed
- Run it in VSCode or Terminal
