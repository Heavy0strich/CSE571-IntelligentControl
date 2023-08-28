# Low-power Reinforcement learning on Visual Confined-Space Navigation for Insect-scale Robots

In our project, we do corridor following along a non-straight corridor sing pure camera
input.
We add rich textures on the walls such that the robot can perceive information to calculate the optic
flow. Our robot has two cameras, one for each side to mimic the omnidirectional camera. We fix the
altitude and only do navigation on x-y plane because the altitude is controlled by other controller
which is beyond the scope of the project.
In the training process, the robot will be equipped with two cameras, and the sensor to know its
ground truth positions (x, y, φ) to calculate the reward. And for the test process, the robot will
be only equipped with two cameras because the sensor to measure positions is too heavy and too
power-hungry for insect-scale robots
