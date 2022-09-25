# Deep-Reinforcement-Learning
This is a deep reinforcement learning model over OPENAI gym (cartpole) game using keras-rl2.
First we make an environment (cartpole-v1). We get all the values related to the environment, such as states and all possible actions.
We then go to make a deep learning neural network which has inputs equal to the number of states and output corresponding to the actions.
Then we build an agent using keras-rl2 which takes in the deep neural network model and possible actions and according to the reward policy reinforces the agent to take certin actions under given circumstances to maximize the reward. 
