[Unsupervised_Learning_of_Object_Landmarks_through_Conditional_Image_Generation](Unsupervised_Learning_of_Object_Landmarks_through_Conditional_Image_Generation.pdf)

- Learns to extract landmarks from pictures of objects in an unsupervised manner.

- The network that extracts the landmarks is trained to output Gaussian heatmap
of a target image, which
is used to reconstruct the target image given a relevant source image.

- The Gaussian heatmap can be thought of as a bottleneck which forces the network
to distills the geometry of the object.

[Unsupervised_Learning_of_Object_Keypoints_for_Perception_and_Control.pdf](Unsupervised_Learning_of_Object_Keypoints_for_Perception_and_Control.pdf)

- Use unsupervised learning to detect keypoints, which are interpreted as concise object representations.

- This is done by enforcing a keypoint bottleneck when learnt image features are transported from a source to a target frames

- Benefit: the discovered keypoints track objects more consistently across long-time horizons.

- Benefit wrt RL: using the keypoints and corresponding image features enable more sample efficient RL.

- Benefit wrt RL: exploration by controlling keypoints locations enables deeper exploration, reaching states not reached by random exploration.
