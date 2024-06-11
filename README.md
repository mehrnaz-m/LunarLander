# Deep Reinforcement Learning Agent for Lunar Lander Simulation

The aim of this project was to design and implement a deep reinforcement learning (DRL) agent capable of successfully landing a spacecraft in the OpenAI Gym’s Lunar Lander environment. Our team utilized a Deep Q-Network (DQN) to achieve this task.

# Project Overview
## Implementing a DRL Agent

We developed a DRL agent using the DQN architecture to learn optimal actions based on environmental states. The main components of our solution include:

- **Environment Setup:** Utilized OpenAI Gym’s ‘LunarLander-v2’ with a virtual display for rendering. We created a function to visualize the learning agent's performance.
- **DQN Architecture:** Implemented a DQN comprising three fully connected layers with ReLU activation functions, outputting Q-values for each possible action.
- **Hyperparameter Tuning:** Key parameters include batch size, learning rate, discount factor, epsilon values for exploration-exploitation trade-off, and the number of training episodes.
- **Replay Memory:** Used to store transitions and enable experience replay for efficient learning.
- **Training and Evaluation:** The agent was trained over 1000 episodes, with performance improving over time as indicated by increasing total rewards per episode.

# Results
The agent demonstrated significant improvement over time, successfully landing the spacecraft in several episodes. Visualizations and recorded videos showcase the agent's progress and learning.

![image](https://github.com/mehrnaz-m/LunarLander/assets/155564679/a5f00b21-06bb-46ae-9806-ddf7c29affdc)


# Future Work
Potential areas for future improvement include exploring more sophisticated algorithms such as Double DQN or Dueling DQN for enhanced performance and stability.

# Team Members
Chaiyatorn Permpornsakul - pscpermp@liverpool.ac.uk 

Chinwa Chimdi-Ezekwe - sgcchimd@liverpool.ac.uk 

Mehrnaz Miri - sgmmiri@liverpool.ac.uk 

Neda Yavari - sgnyavar@liverpool.ac.uk 

Yukabed Ijadi - f.ijadi@liverpool.ac.uk 

# References
Bellemare, M. G., et al. (2016). Unifying count-based exploration and intrinsic motivation. Advances in Neural Information Processing Systems.

Mnih, V., et al. (2015). Human-level control through deep reinforcement learning. Nature.

Osband, I., et al. (2016). Deep exploration via bootstrapped DQN. Advances in Neural Information Processing Systems.

Schulman, J., et al. (2017). Proximal policy optimization algorithms. arXiv preprint arXiv:1707.06347.

Silver, D., et al. (2016). Mastering the game of Go with deep neural networks and tree search. Nature.

Sutton, R. S., & Barto, A. G. (2018). Reinforcement learning: An introduction. MIT press.
