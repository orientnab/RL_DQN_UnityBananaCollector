# RL_DQN_UnityBananaCollector
Implementation of a Deep Q-Network for solving Unity Banana Collector Environment.

## Introduction
In this project, we train an agent to navigate (and collect bananas!) in a large, square world.

We use a Unity environment and apply Reinforcement Learning techniques to solve the problem, in particular, we'll be using Deep Q-Network.
Information about Unity's ML-Agents can be found in <https://github.com/Unity-Technologies/ml-agents>.

## Trained Agent
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* `0` - move forward.
* `1` - move backward.
* `2` - turn left.
* `3` - turn right.

The environment is considered to be solved when the agent achieves an average score of +13 per episode over 100 consecutive episodes.

## Instructions
Follow the instructions in `myNavigation.ipynb` to get started with training your own agent!

## Dependencies
1. Python3 with matplotlib, jupyter, numpy and torch modules.
2. Unity ML-Agents from <https://github.com/Unity-Technologies/ml-agents>.
