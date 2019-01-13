# DRL_Project_Navigation
This is a project to demonstrate the application of deep reinforcement learning.
The training was executed in the iPython notebook. The agent is defined in file agent.py and the Q-Network used to make the agent learn is in file model.py

## Project Details
* state space: has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction
* action space: Four discrete actions are available, corresponding to move forward, move backward, turn left, and turn right.
* reward: A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana

The environment is considered to be solved when the average score over 100 consecutive episodes is 13 or more.

## Getting Started
This is repository contains the code and the trained weights.
