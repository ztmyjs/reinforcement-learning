# Reinforcement Learning - MDP 

## Overview
This repository contains implementations for various reinforcement learning algorithms demonstrated through solutions to selected problems. These solutions aim to illustrate concepts such as policy evaluation, value iteration, and temporal difference learning.

## Environment
Frozen Lake environment from Gymnasium (formerly OpenAI Gym).

## Math Fomular
![equation](https://latex.codecogs.com/gif.latex?Q_%5Cpi%28s%2C%20a%29%20%3D%20%5Csum_%7Bs%27%20%5Cin%20S%7D%20T%28s%27%7Cs%2C%20a%29%5C%7BR%28s%2C%20a%2C%20s%27%29%20%2B%20%5Cgamma%20V_%5Cpi%28s%27%29%5C%7D.)


## Contents
- **Point 1**: Implementation of Policy Evaluation for the Frozen Lake environment using given reward functions.
- **Point 2**: Application of the Value Iteration method to determine the optimal policy for the Frozen Lake environment.
- **Point 3**: Policy Iteration algorithm implementation and its efficiency comparison to brute force methods in solving Markov Decision Processes (MDP).

## Detail Contents
- **Point 1.2**: We will implement the policy evaluation algorithm for the Frozen Lake environment from Gymnasium (formerly OpenAI Gym). The reward signal in the Frozen Lake environment is a deterministic function of the (state, action, next state)-tuple.
- **Point 1.3**: Compute the Qπ values of a policy π.
- **Point 2.1**: Compute the optimal policy π∗, V∗, and Q∗.
- **Point 2.2**: For a discount factor of γ = 0.99, generate and report the following two plots
-   • maxs |V (s) − Vprevious_iteration(s)| with respect to iteration number
-   • maxs |V (s) − Vfinal_iteration(s)| with respect to iteration number
- **Point 2.3**: For a discount factor of γ = 0.99, observe the number of iterations after which the algorithm converged.
- **Point 2.4**: Plot the number of iterations after which the algorithm converged with respect to discount factor for γ ∈ {0, 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9, 0.95, 0.99}. 
- **Point 2.5**: Use the educated guess of the optimal policy to warm start the value iteration algorithm. 
- **Point 3.2**: Compute the optimal policy π∗



## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You need Python 3.x and Jupyter Notebook installed on your machine. Additionally, the following Python libraries are required:
- `numpy`
- `matplotlib`
- `gym`

You can install these packages using pip:
```bash
pip install numpy matplotlib gym

