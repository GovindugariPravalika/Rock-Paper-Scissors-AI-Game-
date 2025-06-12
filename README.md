# Rock Paper Scissors AI

A simple command-line implementation of the classic **Rock, Paper, Scissors** game, enhanced with basic AI that learns from the player's past choices.

## 💡 Features

- Play against an AI that tries to predict your next move.
- Tracks player move history and adjusts AI choices accordingly.
- Simple, interactive CLI-based gameplay.

## 🧠 How the AI Works

- In the first 3 rounds, the AI chooses moves randomly.
- After that, it analyzes the player's most frequently chosen move and selects the counter-move.

## 🕹️ How to Play

1. Run the script in a Python environment.
2. Type `rock`, `paper`, or `scissors` when prompted.
3. Type `exit` anytime to quit the game.

## 📋 Requirements

- Python 3.x
- No external dependencies

## 🚀 Running the Game

```bash
python rock_paper_scissors.py
```

## 📦 File Structure

```
rock_paper_scissors.py   # Main game file with AI logic
```

## 📜 Example Gameplay

```
Welcome to Rock, Paper, Scissors AI!
Type 'rock', 'paper', or 'scissors'. Type 'exit' to quit.

Your move: rock
AI played: paper
AI wins!

Your move: scissors
AI played: rock
AI wins!
