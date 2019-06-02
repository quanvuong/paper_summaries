[Efficient_Off_Policy_Meta_Reinforcement_Learning_via_Probabilistic_Context_Variables](Efficient_Off_Policy_Meta_Reinforcement_Learning_via_Probabilistic_Context_Variables.pdf)

- Uses a latent variable to summarize the data collected so far into sufficient statistics about the current task.

- The distribution over the latent variable conditioned on collected data is stochastic to encourage temporally correlated exploration.

- The architecture for the distribution is permutation-invariant wrt its input. (VERY NEAT!)

- Demonstrates that, compared to alternatives, it is better to train the latent variable distribution using recently collected data and train the actor-critic with data uniformly sampled form the experience buffer.

[Meta_Gradient_Reinforcement_Learning](Meta_Gradient_Reinforcement_Learning.pdf)

- Proposes to learn the value of the hyper-parameters lambda and gamma, which parameterize the return function. These are now referred to as meta-parameters.

- Online cross-validation is used to ensure that no extra data is needed to train the meta-parameters.

- The meta-parameters are trained using gradient, with can be obtained in closed form with approximations.

[Exploiting_Hierarchy_for_Learning_and_Transfer_in_KL-regularized_RL](Exploiting_hierarchy_for_learning_and_transfer_in_KL_regularized_RL.pdf)

- The policy has a hierarchical structure, comprising of a high-level policy, which is agnostic to low-level control
and provides instruction to a low-level policy through a latent variable.

- The objective function includes a KL regularization term to ensure the agent's policy does not stray too far
from a default policy, which can be fixed or learnt.

- Restricting information to either the high-level policy or the low-level policy leads to more robust behavior
in the transfer setting.

