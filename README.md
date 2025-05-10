# RL_tictactoe
# Tic-Tac-Toe RL Agent 🤖🎮

A Reinforcement Learning agent that learns to play Tic-Tac-Toe, implemented in a Jupyter Notebook with an interactive GUI for playing against the trained agent.

<img width="372" alt="image" src="https://github.com/user-attachments/assets/33bf1c15-3e4b-42df-a4b3-c1666d58b1f2" />

## Features

*   **Q-Learning Agent:** Learns Tic-Tac-Toe strategy from scratch.
*   **Interactive Play:** Challenge your trained agent via a clickable GUI in Jupyter.
*   **Agent Training:** Train against a random player or another RL agent (self-play).
*   **Performance Metrics:** Evaluate agent skill through direct play and agent vs. agent matchups.
*   **Save/Load Progress:** Persist and reuse trained Q-tables.

## Tech Stack

*   **Python 3**
*   **Jupyter Notebook/Lab**
*   **NumPy:** Board representation.
*   **Matplotlib:** Board visualization.
*   **ipywidgets:** Interactive GUI elements.
*   **Pickle:** Saving/loading Q-tables.
*   **asyncio:** UI responsiveness.

## 🧠 How It Works

*   **`TicTacToe` class:** Manages game logic, state, and rewards.
*   **`RLAgent` class:** Implements Q-learning for decision-making and learning.
*   **`TicTacToeGUI` class:** Provides the interactive game interface.
*   The agent learns by updating its **Q-table** based on rewards received during numerous game episodes, balancing exploration and exploitation.

