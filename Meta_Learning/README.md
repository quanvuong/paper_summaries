[DiCE_The_Infinitely_Differentiable_Monte_Carlo_Estimator](DiCE_The_Infinitely_Differentiable_Monte_Carlo_Estimator.pdf)

- Proposes an objective that can be differentiated n times to obtain an estimate of the n-th order gradient of the original objective.

- The original objective takes the form of sum of cost nodes in a stochastic computational graph.

[Meta_Learning_with_Memory_Augmented_Neural_Networks](Meta_Learning_with_Memory_Augmented_Neural_Networks.pdf)

- Proposes to learn an architecture with a controller and an external memory.

- The controller learns a representation of an input, binds the representation of this input to a its class label, and put the binding in the external memory.

- During test time, given an input, the controller should retrieve a label from the external memory.

[Meta_Learning_with_Differentiable_Convex_Optimization]

- Proposes to use a SVM as the base learner.

- The SVM formulations allows for obtaining the derivative of the post-update policy loss wrt the meta parameters.

- However, the paper does not explain why the method proposes work better than gradient-based method.

[Learning_to_learn_by_gradient_descent_by_gradient_descent](Learning_to_learn_by_gradient_descent_by_gradient_descent.pdf)