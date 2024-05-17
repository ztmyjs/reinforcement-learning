# Deep Q-Network for the Acrobot Environment

This repository contains a Jupyter notebook that explores the application of a Deep Q-Network (DQN) on the Acrobot environment provided by OpenAI's Gym library.

## Overview

The notebook demonstrates the implementation of a DQN, a type of reinforcement learning algorithm, applied to control the Acrobot—a simple two-link robot in a vertical plane. The goal is to swing the free end of the outer link up to a specified height by applying torque to the joint.

## Environment

The Acrobot environment from Gymnasium consists of two links connected by a joint. The lower link is connected to a fixed base and the upper link can swing freely. The objective is to swing the end of the upper link to reach a target height, simulating a simple robotic control task.

## Features

- Detailed setup and explanation of the Acrobot environment.
- Implementation of Deep Q-Network to learn the optimal actions to achieve the goal.
- Visualization of the learning process and the performance of the trained agent.

## Detail Contexts
- **Point 1.1**: Implement the general recipe for Q Learning algorithm with function approximation.
- **Point 1.2**: Conduct an ablation study to characterize the utility of replay buffers and target networks on the performance of the Q Learning algorithm. Observe the performance of those diagrams.
  - Q learning with neither target networks nor replay buffers
  - Q learning with replay buffers but without target networks
  - Q learning with target networks but without replay buffers
- **Point 1.3**: Select any one hyperparameter of the algorithm and study its effect on the agent’s performance.
- **Point 1.4**: Apply Stable Baselines 3 package and use its implementation of Deep Q Network to learn the optimal policy and observe the performance with comparison.
