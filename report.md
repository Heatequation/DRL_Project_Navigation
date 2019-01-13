# Report

### Learning Algorithm
The agent learns by training a Deep-Q-Network with replay buffer and fixed Q-Targets.
The idea behind a Deep-Q-Network like are based on the research paper [Human-level control through deep reinforcement
learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf): 
  
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
  

### Ideas for Improvement
More advanced techniques could be employed. For example:
* Double DQN: Deep-Q-Learning tends to overestimate action values. Using a double DQN instead (as laid out in [this research paper](https://arxiv.org/abs/1509.06461)) can help solve this issue.
* Dueling DQN: the main benefit is that a duelling DQN generalizes learning across actions without imposing any change to the underlying reinforcement learning algorithm. The dueling DQN is described in [this research paper](https://arxiv.org/abs/1511.06581).
* Prioritized Experience Replay: uniform sampling from the experience replay buffer might lead to important observations being neglected. Using prioritized experience replay (as laid out in [this research paper](https://arxiv.org/abs/1511.05952)) can help solve this issue.
