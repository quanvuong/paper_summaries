[Dex-Net 1.0: A Cloud-Based Network of 3D Objects for Robust Grasp Planning Using a Multi-Armed Bandit Model with Correlated Rewards](dex_net_1.pdf)

- Given an object, find a grasp that maximizes a binary success metric subjected to uncertainty in object, environment, robot state.

- Leverage a large dataset of obj-grasp-grasp quality to reduce the number of grasp evaluations required to find the optimal grasp.

[Dex-Net 2.0](dex_net_2.pdf)

- Learning to grasp from purely synthetic data.

- They only consider grasping singulated obj in this paper. Unclear how it will work in clutter.

- The main component in the approach is a Grasp Quality CNN (GQ-CNN), which predicts binary success label for depth image - grasp configuration pair.

- To pick grasp, they just use CEM.

[Dex-Net 3.0](dex_net_3.pdf)

- Suction grasp is widely used for pick-and-placed tasks in industry and warehouse order fulfillment. Suction has an advantage over parallel-jaw or multi-finger grasping due to its ability to reach into narrow spaces and pick up objects with a single point of contact.

- Apply the approach taken in dex-net 2.0 to to suction grasp.

- Propose a new model to evaluate grasp robustness of suction-based grasp by analyzing seal formation and wrench resistance.

- Achieves success rate of $98\%$, $82\%$, $58\%$ on basic (prismatic or cylindrical), typical (with more complex geometry), and adversarial (with few available suction-grasp points) respectively.

[Supersizing_Self_supervision_Learning_to_Grasp_from_50K_Tries_and_700_Robot_Hours](Supersizing_Self_supervision_Learning_to_Grasp_from_50K_Tries_and_700_Robot_Hours.pdf)

- Autonomous large-scale dataset collection for robotic grasping through trial and error.

[Learning_Hand_Eye_Coordination_for_Robotic_Grasping_with_Deep_Learning_and_Large_Scale_Data_Collection](Learning_Hand_Eye_Coordination_for_Robotic_Grasping_with_Deep_Learning_and_Large_Scale_Data_Collection.pdf)

- Learning hand-eye coordination for robotic grasping from monocular images from scratch, with minimal prior knowledge and manual engineering.

- End-to-end training directly from pixel input to output task-space gripper motion with minimal human supervision.

- Precise camera calibration is not used.

- The method learns servo the robotic gripper to position where grasps are likely to be successful.

