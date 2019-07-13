[When_to_Trust_Your_Model_Model_based_policy_optimization](When_to_Trust_Your_Model_Model_based_policy_optimization.pdf)

- Use short rollout from the model to train the policy

- Argue that the short rollout allows us to take more policy gradient step per environment step compared to model-free RL

[Exploring_Model_based_Planning_with_Policy_Networks](Exploring_Model_based_Planning_with_Policy_Networks.pdf)

- Argues that performing CEM in the parameter space of a policy network is easier than in the action space.

- Visualizes the reward function surface and uses this visualization to justify their claims.

- The visualization techniques look interesting and can be re-used in other studies.

[Using_Inaccurate_Models_in_Reinforcement_Learning](Using_Inaccurate_Models_in_Reinforcement_Learning.pdf)

- Differentiate through the learnt model to obtain the policy gradient.

- Evaluate this policy gradient at a true trajectory to remove one source of gradient approximation error.