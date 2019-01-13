# Report

## Learning Algorithm
 
  The agent learns by training a Deep-Q-Network with replay buffer and fixed Q-Targets.
  The following hyperparameters are used:
    * replay buffer size: BUFFER_SIZE = int(1e5)
    * minibatch size: BATCH_SIZE = 64
    * discount factor: GAMMA = 0.99
    * soft update of target parameters: TAU = 1e-3
    * learning rate: LR = 1e-4
    * how often to update the network: UPDATE_EVERY = 4
  The model architecture is a deep neural network with one hidden layer. Input and hidden layer use ReLu activation.
  The trained aged solved the environment in 462 episodes. The following plot shows the rewards per episode:
  ![reward plot](https://github.com/Heatequation/DRL_Project_Navigation/blob/master/reward_episodes.png)
  

## Ideas for Improvement
  More advanced techniques could be employed. For example a double DQN, a dueling DQN, and/or prioritized experience replay.
