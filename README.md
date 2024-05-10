# Exploring Safe and Effective Reward Patterns in Reinforcement Learning


This repository contains the code for a project on analysing reward systems in reinforcement learning, specifically focusing on the Frozen Lake Problem and the Taxi Problem using Gymnasium (or Gym) Library.

## Folder Structure

- **Frozen_lake_Problem**: Contains Python code for applying Q-learning on the Frozen Lake environment and comparing action penalty and goal-based reward systems using reward wrappers in Gymnasium.
  - `Frozen_lake_steps.py`: Python code for applying Q-learning on Frozen Lake and plotting steps count of reward systems against episodes.
  - `Frozen_lake_success.py`: Python code for applying Q-learning on Frozen Lake and plotting Cumulative success of reward systems against episodes.

- **Taxi_Problem**: Contains Python code for analyzing safe reward systems for environments containing illegal moves in the Taxi Problem environment.
  - `taxi_penalty_count.py`: Python code for applying Q-learning on Taxi problem and plotting number of Illegal actions against episodes.

## Results

- **Frozen Lake Problem**: The analysis shows that the penalized reward system performs better than the goal-based reward system in the Frozen Lake environment.

- **Taxi Problem**: The analysis indicates that a penalty for illegal moves must be higher than the on-route reward for safe and efficient learning in environments with illegal moves.

## Usage

To run the code, make sure you have Python and Gymnasium installed. Simply run the Python scripts in each folder to see the results.
