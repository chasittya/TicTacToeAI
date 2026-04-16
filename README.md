# Tic Tac Toe AI

An AI-powered Tic Tac Toe game built in Python with an interactive Pygame interface. The application allows users to play against different AI opponents, including Minimax and Monte Carlo Tree Search algorithms.
The project demonstrates how search algorithms can be applied to deterministic environments to produce optimal and probabilistic decision-making.
---

## Overview

This project implements a classic Tic Tac Toe game enhanced with artificial intelligence. It explores game theory and search algorithms by allowing the user to compete against multiple AI strategies.

---

## Features

* Interactive game interface built with Pygame
* Play against multiple AI opponents:

  * Minimax algorithm
  * Monte Carlo Tree Search (MCTS)
  * Random move selection
* Game state evaluation (win, lose, draw detection)
* Dynamic user vs AI gameplay

---

## Algorithms Implemented

### Minimax

* Recursively evaluates all possible game states
* Chooses the optimal move assuming perfect play
* Guarantees the best possible outcome for the AI

### Monte Carlo Tree Search (MCTS)

* Simulates multiple random game outcomes
* Uses probabilistic decision-making to choose moves
* Balances exploration and exploitation

---

## Tech Stack

* Python
* Pygame

---

## Project Structure

```text
TicTacToeAI/
├── assets/
│   ├── Play Rect.png
│   ├── Options Rect.png
│   └── Quit Rect.png
├── tictactoe.py
├── runner.py
├── button.py
├── requirements.txt
└── README.md
```

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/chasittya/TicTacToeAI.git
cd TicTacToeAI
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the game:

```bash
python runner.py
```

---

## Gameplay

* Choose your player (X or O)
* Select an AI opponent
* Play against the computer in real time
* The game automatically detects wins, losses, and ties

---

## Challenges

* Implementing optimal decision-making using Minimax
* Balancing performance and accuracy in MCTS simulations
* Managing game state transitions efficiently
* Synchronizing UI updates with game logic

---

## Future Improvements

* Add difficulty levels for AI opponents
* Optimize MCTS for faster simulations
* Improve UI/UX design
* Add a web-based version of the game

---

## Author

Chasitty Ayala
