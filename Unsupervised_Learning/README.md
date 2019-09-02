[Unsupervised_Learning_of_Object_Landmarks_through_Conditional_Image_Generation](Unsupervised_Learning_of_Object_Landmarks_through_Conditional_Image_Generation.pdf)

- Learns to extract landmarks from pictures of objects in an unsupervised manner.

- The network that extracts the landmarks is trained to output Gaussian heatmap
of a target image, which
is used to reconstruct the target image given a relevant source image.

- The Gaussian heatmap can be thought of as a bottleneck which forces the network
to distills the geometry of the object.

[Unsupervised_Learning_of_Object_Keypoints_for_Perception_and_Control](Unsupervised_Learning_of_Object_Keypoints_for_Perception_and_Control.pdf)

- Use unsupervised learning to detect keypoints, which are interpreted as concise object representations.

- This is done by enforcing a keypoint bottleneck when learnt image features are transported from a source to a target frames

- Benefit: the discovered keypoints track objects more consistently across long-time horizons.

- Benefit wrt RL: using the keypoints and corresponding image features enable more sample efficient RL.

- Benefit wrt RL: exploration by controlling keypoints locations enables deeper exploration, reaching states not reached by random exploration.

[Interpretable_Intuitive_Physics_Model](Interpretable_Intuitive_Physics_Model.pdf)

- An interpretable intuitive physics model where dimensions in the bottleneck layer corresponds to different physical properties.

- Intuitive as in the model is not able to predict the precise value of the physical properties, but still able to predict the approximate change in the world following a change in physical properties.

- The NN architecture seems standard, the key to success is the training procedure and loss fnc.

- Benefit is generalization to unseen conditions and interpretable latent dimensions. For example, the latent dimension can be interpolated, where interpolation in a specific dimension leads to meaningful and accurate change in the final prediction of the properties associated with that dimension.
