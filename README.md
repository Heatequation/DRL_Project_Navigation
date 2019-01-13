# DRL_Project_Navigation
This is a project to demonstrate the application of deep reinforcement learning.
It uses an environment built on Unity where an agent can collect yellow and blue bananas in a large square world.

## Project Details
*state space: has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction
*action space: Four discrete actions are available, corresponding to move forward, move backward, turn left, and turn right.
*reward: A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana

The environment is considered to be solved when the average score over 100 consecutive episodes is 13 or more.

## Getting Started
The dependencies for this project include a custom build of a unity environment.
Download the environment here:
Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
Then, place the file in the p1_navigation/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.

Further dependencies are numpy and matplotlib.

## Introduction
Clone this repository. Make sure the dependencies mentioned above are installed. Then run the code in the iPython notebook.
