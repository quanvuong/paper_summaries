[Unsupervised_Learning_of_Object_Landmarks_through_Conditional_Image_Generation](Unsupervised_Learning_of_Object_Landmarks_through_Conditional_Image_Generation.pdf)

- Learns to extract landmarks from pictures of objects in an unsupervised manner.

- The network that extracts the landmarks is trained to output Gaussian heatmap
of a target image, which
is used to reconstruct the target image given a relevant source image.

- The Gaussian heatmap can be thought of as a bottleneck which forces the network
to distills the geometry of the object.