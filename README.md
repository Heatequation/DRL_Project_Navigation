# DRL_Project_Navigation

### Introduction
For this project, I trained an agent to navigate (and collect bananas!) in a large, square world.  
This is a project to demonstrate the application of deep reinforcement learning.

The training was executed in the iPython notebook. The agent is defined in file agent.py and the Q-Network used to make the agent learn is in file model.py

The environment in which the agent learns can be described in the following way:
* state space: has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction
* action space: Four discrete actions are available, corresponding to move forward, move backward, turn left, and turn right.
* reward: A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana

The environment is considered to be solved when the average score over 100 consecutive episodes is 13 or more.

### Getting Started

1. Download the environment from one of the links below depending on your operating system.
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

2. Place the file in this repository's root folder, and unzip (or decompress) the file. 

### Instructions

To train the agent follow the instructions in `Navigation_Project.ipynb`. 
