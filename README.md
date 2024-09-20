# thompson_sampling-reinforcement_learning
## Description
This project implements the Thompson Sampling algorithm to solve the multi-armed bandit problem, particularly for optimizing ad selection. Thompson Sampling balances exploration and exploitation by using a Bayesian approach to estimate the probability of success for each ad and select the one most likely to give the highest reward.

## Dataset
The dataset used is `Ads_CTR_Optimisation.csv`, which contains binary feedback on whether an ad was clicked or not. Each row represents a user interaction, and each column represents a different ad.

## Languages or Tools
- Python
- Jupyter Notebook or any Python IDE

## Libraries
- `pandas`
- `numpy`
- `matplotlib`
- `random`

## Algorithm Overview
Thompson Sampling is a probabilistic algorithm used to solve the multi-armed bandit problem. It uses Beta distributions to model the uncertainty about the reward probabilities of different actions (ads). At each round, the algorithm samples from these distributions and selects the action with the highest sampled value.
