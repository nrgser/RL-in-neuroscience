# Reinforcement Learning in Neuroscience

This project implements the **ε-greedy algorithm** from scratch to solve a grid-based navigation task inspired by neuroscience learning principles. The goal is to find the optimal path in a reward-based environment using reinforcement learning techniques.

##  Project Overview

- The environment is represented as an **N×N grid**, where each cell contains a reward or penalty.
- The agent must learn the best route from the bottom-left corner to the top-right corner by moving only **upward or rightward**.
- Rewards and punishments are predefined in a configuration file (`Grid.xlsx`).
- The project evaluates the performance of the RL algorithm based on:
  - A **heatmap** showing the optimal path.
  - The **cumulative reward trend** across training episodes.

##  Key Features

- Implements **ε-greedy Q-learning** without using external reinforcement learning libraries.
- Visualizes:
  - The learned optimal route on the grid.
  - Cumulative reward across episodes.
- Allows hyperparameter tuning for:
  - Learning rate (α)
  - Discount factor (γ)
  - Exploration rate (ε)
- Evaluates performance over multiple grid sizes (e.g., 6×6, 30×30).

##  Tools & Technologies

- **Python**
- **NumPy**, **Matplotlib**, **Pandas**
- No external RL libraries used – all RL logic implemented from scratch.



