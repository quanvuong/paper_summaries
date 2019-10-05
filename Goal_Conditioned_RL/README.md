[Skew_Fit](Skew_fit_state_covering_self_supervised_RL.pdf)

- A policy should accomplish diverse and unknown user-specified goal at test time.

- If the goal specified at test time is unknown, then the policy needs to perform well on all possible goals.

- Then, the goal proposal distribution, from which we sample goals for the policy to practice, should be the uniform distribution over the set of possible goals.

- However, we do not know this set a prior and can only observe sample from the set.

- State and goal are assumed to be equivalent in this paper.

- At each iteration, we can sample state by performing goal-directed exploration. How do we construct the goal proposal distribution at each iteration such that it converges to the uniform dist. over the set of possible goals over time?

