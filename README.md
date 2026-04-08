# ♟ Gomoku Game with AI

An intelligent Gomoku game built using Python and Tkinter, featuring Minimax and Alpha-Beta pruning algorithms with multiple heuristic evaluation strategies.

---

## 🎮 Game Features

- Dynamic board sizes (9x9, 10x10, 15x15)
- Three difficulty levels (Easy, Medium, Hard)
- AI powered by:
  - Minimax Algorithm
  - Alpha-Beta Pruning
  - Custom heuristic evaluation functions
- Interactive Tkinter GUI
- Restart functionality
- Optimized move generation using neighbor filtering

---

## 🧠 AI Implementation

### 1️⃣ Minimax
Classic recursive game tree search with depth control based on difficulty level.

### 2️⃣ Alpha-Beta Pruning
Optimized version of Minimax that reduces unnecessary node exploration, improving performance significantly.

### 3️⃣ Heuristic Evaluation
Two custom heuristic functions evaluate board states based on:
- Consecutive pieces
- Open sequences
- Offensive & defensive scoring

---

## ⚙️ Difficulty Levels

- Easy → Depth 1
- Medium → Depth 2
- Hard → Depth 3

---

## 🛠 Technologies Used

- Python
- Tkinter (GUI)
- Minimax Algorithm
- Alpha-Beta Pruning
- Heuristic Search

---

## 🚀 How to Run

```bash
python "AI project (1).py"
