# Robotics first project 2022 
Description of the project in the pdf file **Project1** with the related bags in their folder. 
The **documentation** file explains all the files in the repository, the structure of our solution and how to run it.

## Short description of the project

Given 3 ROS bags with recorded data of an omnidirectional robot with four meccanum wheels and some geometric parameters of the robot, the goals to achieve using ROS are:
1. Compute odometry using appropriate kinematics:
    - Compute robot linear and angular velocities v, ⍵ from wheel encoders;
    - Compute odometry using both Euler and Runge-Kutta integration;
    - Calibrate robot parameters to match ground truth;
2. Compute wheel control speeds from v, ⍵;
3. Add a service to reset the odometry to a specified pose (x,y,θ);
4. Use dynamic reconfigure to select between integration methods.
