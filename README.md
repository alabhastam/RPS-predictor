# 🤖 Rock Paper Scissors AI

This is a simple machine learning project where a bot plays the game **Rock, Paper, Scissors** against a human player — and tries to **learn your behavior over time to beat you** using a basic Markov Chain model.

## 🎯 Project Goal

- Build an AI agent that can learn patterns in a human player's moves.
- Predict the next user move based on previous ones.
- Choose a counter-move that can beat the predicted move.

## 🧠 How It Works

1. The user plays the game by entering one of the choices: `rock`, `paper`, or `scissors`.
2. Each round result is saved to a `CSV` file: `game_results.csv`.
3. The AI uses a **first-order Markov model** to analyze the history of your moves.
4. It predicts your next move based on your last one.
5. Then, it selects the best counter-move to try to beat you.


## 📝 Requirements

- Python 3.x
- No external libraries needed (only built-in Python modules)

