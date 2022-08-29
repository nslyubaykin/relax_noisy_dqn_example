# Example Noisy DQN implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_noisy_dqn_example/blob/master/noisy_dqn_tutorial.ipynb) of noisy deep q-network (Noisy DQN) with ReLAx.

Noisy DQN actor was trained on Boxing-v0 Atari Gym environment for 3m env-steps. 

__!Note:__ For demonstration purposes training was run only for 3m steps. In papers, DQN and its augmentations are trained for 200m steps, which may require several days of learning. That is why performance is lower than reported in papers.

The graph of average return vs environment step is shown below (logs done every 50k steps):

![noisy_dqn_training](https://github.com/nslyubaykin/relax_noisy_dqn_example/blob/master/noisy_dqn_training.png)

The distribution of estimated Q-values vs data Q-values is shown below:

![noisy_dqn_q_func](https://github.com/nslyubaykin/relax_noisy_dqn_example/blob/master/noisy_dqn_q_func.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187172622-66a5b744-f2b4-456b-8113-058bc60e3601.mp4
