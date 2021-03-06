[Task_Relevant_Adversarial_Imitation_Learning](Task_Relevant_Adversarial_Imitation_Learning.pdf)

- They show that a critical challenge in applying adversarial imitation from high-dimensional sensory data is the tendency of the discriminator network to use task-irrelevant features in the state to discriminate between the expert and imitator trajectories.

- They propose to train the discriminator with a modified obj, such that the discriminator is penalized if it uses task-irrelevant feature to discriminate between states generated by the expert and states generated by the imitator.

[Imitation_Learning_from_Video_by_Leveraging_Proprioception]

- Use a GAN-like approach to derive a reward function from the discriminator.

- Use the proprioceptive state instead of visual observation as input into the imitator.

[One_Shot_Hierarchical_Imitation_Learning_of_Compound_Visuomotor_Tasks](One_Shot_Hierarchical_Imitation_Learning_of_Compound_Visuomotor_Tasks.pdf)

- The goal is to learn multi-state vision-based tasks from a single video of a human performing the task.

- They argue that for task which can be decomposed into primitive skills, it is better to learn the primitive skills and how to compose them than learning how to perform the task directly.

- Given a test-time video of human performing the task with compositional structure, they first segment it into primitive segments where each primitive segment requires the execution of one primitive skill. Each segment is then used to obtain the policy to perform the primitive skill through an adaptation procedures.

[Playing_hard_exploration_games_by_watching_YouTube](Playing_hard_exploration_games_by_watching_YouTube.pdf)

- Imitation learning with access to the expert's actions and rewards is too restrictive.

- They propose a 2-stage method that does away with these 2 assumptions by relying on unaligned footage.

- They first learn to map unaligned videos from multiple sources to a common representation using a self-supervised objective constructed over both time (temporal distance classification) and modality (cross-model temporal classification).

- They then embed a single Youtube video in this representation to construct a reward function that encourages an agent to imitation human gameplay.

[goal_conditioned_imitation_learning](goal_conditioned_imitation_learning.pdf)

- Goal-reaching practice is an effective form of self-supervised learning for robotics.

- But defining a reward fun. in high dimensional space is hard.

- The breath first nature of existing strategy (HER) means that some areas of the state space takes a long time to learn.

- They propose goalGAIL, which can boost goal-conditioned policy learning with only state demonstrations.

[Reinforcement_and_Imitation_Learning_for_Diverse_Visuomotor_Skills](Reinforcement_and_Imitation_Learning_for_Diverse_Visuomotor_Skills.pdf)

- Use demonstration to speed up training of RL policies in simulation.

- Leverage privileged and task-specific information to speed up training in simulation.

- Some success in zero-shot sim2real transfer.
