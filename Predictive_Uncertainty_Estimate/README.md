[Evaluating Predictive Uncertainty Estimate](Evaluating_Predictive_Uncertainty_Estimate.pdf)

- Examines commonly used loss functions to determine which loss function penalizes over and under-confident prediction and which do not

[Simple and Scalable Predictive Uncertainty Estimation using Deep Ensembles](Simple_and_Scalable_Predictive_Uncertainty_Estimation_using_Deep_Ensembles.pdf)

- Train an ensemble of DNN to estimate predictive uncertainty
- Train each ensemble member with a proper scoring rule as the loss function
- Adversarial training to smooth the predictive distribuion

[Predictive Uncertainty Estimate via Prior Network](Predictive_Uncertainty_Estimate_via_Prior_Network.pdf)

- Model 3 sources of uncertainty separately: model, data, distributional
- Use a DNN to parameterize the distribution over predictive distribution parameters to model distributional uncertainty
- Demonstrate the advantage of the differential entropy as a measure to detect out-of-distribution samples