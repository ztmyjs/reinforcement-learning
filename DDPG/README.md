# Deep Deterministic Policy Gradient (DDPG) for Continuous Control Environments

This repository contains a Jupyter notebook that explores the application of the Deep Deterministic Policy Gradient (DDPG) algorithm on a continuous control environment provided by OpenAI's Gym library.

## Overview

The notebook demonstrates the implementation of DDPG, a type of actor-critic algorithm designed for environments with continuous action spaces. The goal is to train an agent to perform optimally by exploring and exploiting the environment using policy-based and value-based methods.

## Environment

DDPG is demonstrated on a specific Gym environment, which includes continuous state and action spaces. The environment can include robotic arms or any other systems requiring precise control.

## Features

- Detailed setup and explanation of the chosen environment.
- Implementation of DDPG to learn the optimal policy in a continuous action space.
- Visualization of the learning process and evaluation of the agent's performance.

## Detailed Contents

- **Point 1.1**: Implement the general recipe for Deep Deterministic Policy Gradient (DDPG) algorithm with function approximation.
- **Point 1.2**: Report results of five runs of your algorithm and summarize the performance in a single plot.
- **Point 1.3**: Explore the impact of exploration strategies on DDPG's performance.
- **Point 1.4**: Use the Stable Baselines 3 package to compare a standard DDPG implementation with the custom implementation for performance and efficiency.

## Installation

To run this notebook, install the required packages using the following command:

```bash
pip install gym matplotlib numpy tensorflow stable-baselines3
