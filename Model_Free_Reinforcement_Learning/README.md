[Proximal Policy Optimization](PPO_implementation_details.pdf)

- The pdf is not a summary, but a detailed description of the implementation details of PPO.

[Deep Reinforcement Learning with Double Q Learning](Deep_Reinforcement_Learning_with_Double_Q_Learning.pdf)

- In DQN, to construct target for the Q-function, the same Q-function is used for action selection and evaluation.

- This leads to action value over-estimation.

- They show that decoupling action selection and evaluation reduces the degree of over-estimation and increases performance.

[Prioritized_Experience_Replay](Prioritized_Experience_Replay.pdf)

[Off_Policy_Deep_Reinforcement_Learning_without_Exploration](Off_Policy_Deep_Reinforcement_Learning_without_Exploration.pdf)

- Studies the setting where only a replay buffer is available and the agent is not allowed to interact with the environment.

- Proposes that the learnt agent should generate a state-action visitation frequency that is similar to the replay buffer.

[Diagnosing_Bottlenecks_in_Deep_Q_learning_Algorithms](Diagnosing_Bottlenecks_in_Deep_Q_learning_Algorithms.pdf)

- Identifies that the choice of the sampling distribution and architecture choice might play large roles in performance.

- Identifies that convergence might not be an issue in deep Q-learning.