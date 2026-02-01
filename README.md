### WIDS: RL in Trading Assignments
Hello, I am Mohit Agrawal and this repository reflects the work done in my WIDS asssignments.

## Week 1
In week 1, we learnt the basics of:
- Python: data types, data structures, loops, functions, file operations
- NumPy: arrays, operations on arrays, random
- Matplotlib: graphs, operations in graphs
- Pandas: reading data, cleaning, plotting

Next, we did 3 assignments based on this. 
1. NumPy Assignment: using NumPy functions to perform specific operations on the given data.
2. Matplotlib and Pandas: to practice plotting different types of graphs.

## Week 2

In week 2, we got an introduction to Reinforcement Learning.

Algorithms like greedy, epsilon greedy, optimistic greedy and UCB were introduced.

Assignment was based on the multi bandit problem.

# Multi Bandit Problem

The multi-armed bandit problem is a decision-making problem where we choose between several options, each giving random rewards. The goal is to learn which option is best over time by balancing exploration (trying new options) and exploitation (using the best-known option).

## Week 3

In week 3, we focused on modeling Markov Decision Processes (MDPs) in Python.

We learned to:
- Create MDP models as dictionaries with state spaces, action spaces, and transition probabilities
- Understand the structure of MDPs: (state, action, next_state, reward)
- Work with both deterministic and stochastic environments

Assignments included:
1. **Bandit Walk (BW)**: A deterministic environment with 3 states where the agent learns to navigate from start to goal
2. **Slippery Walk (SW)**: A stochastic environment with 7 states where actions have probabilistic outcomes, simulating real-world uncertainty

These simple environments provided a foundation for understanding RL problem modeling before moving to more complex scenarios.

## Week 4

In week 4, we built a **Reinforcement Learning-based Trading Agent** as the final project.

We implemented:
- **TradingEnv**: A custom environment simulating stock trading where the agent can buy, sell, or hold
- **Market Data Integration**: Downloaded historical stock price data using yfinance
- **Q-Learning Agent**: Trained an agent to make trading decisions using Q-Learning algorithm with parameters:
  - Learning rate (alpha): 0.1
  - Discount factor (gamma): 0.95
  - Exploration rate (epsilon): 0.1

The project demonstrates applying RL algorithms to a real-world financial domain where the agent learns to maximize portfolio value by making optimal buy/sell decisions based on stock prices.


