# 🐍 Snake & Ladder Game

A terminal-based **Snake and Ladder** game built with Python. Supports multiple players, snakes, and ladders — all played right in your command line!

---

## 🎮 How to Play

1. Run the script
2. Enter the number of players
3. Enter each player's name
4. Players take turns — press **Enter** to roll the dice
5. Land on a 🪜 ladder → move up! Land on a 🐍 snake → slide down!
6. First player to reach **exactly 100** wins 🎉

---

## 🗺 Board Layout

### 🐍 Snakes (head → tail)
| Head | Tail |
|------|------|
| 45   | 7    |
| 51   | 10   |
| 38   | 20   |
| 76   | 54   |
| 91   | 73   |
| 97   | 61   |

### 🪜 Ladders (bottom → top)
| Bottom | Top |
|--------|-----|
| 5      | 58  |
| 14     | 49  |
| 42     | 60  |
| 53     | 72  |
| 64     | 83  |
| 75     | 94  |

---

## ⚙️ Setup & Run

### Requirements
- Python 3.x (no external libraries needed)

### Run the game

```bash
python SnakeLadder.py
```

---

## 📁 Project Structure

```
My-First-Project/
└── SnakeLadder.py   
```

---

## 🚀 What's Next (Ideas to Improve)

- [ ] Add a visual board display in the terminal
- [ ] Track and show all player positions after each turn
- [ ] Add a score/turn counter
- [ ] Save high scores to a file
- [ ] Add color output using the `colorama` library

---
