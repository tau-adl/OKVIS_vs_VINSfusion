# OKVIS_vs_VINSfusion
Evaluation of OKVIS SLAM over EuroC including comparison against VINS_fusion
M.Sc Project by Shay Perlmutter

The addition of an inertial sensor to visual SLAM can significantly increase navigation reliability by enabling the rejection of visual outliers,
increasing measurement rate and providing a solution during visual tracking losses.

This project is one of a few projects meant to compose the TAU Drone Lab's infrastructure of visual-Inertial SLAM.

It includes installation and testing of a tightly-coupled open-source visual-inertial algorithm named OKVIS,
and evaluation of it both on an online data set (Euro-C) and a self-created data set from the lab's Realsense 450i camera+imu.
Also, it includes a comparison of OKVIS against another open-souce Visual-Inertial SLAM algorithm, VINS_fusion.

Both evaluations were made based on an open-source tool, rpg_trajectory_evaluation, which was also installed and documented for future use in the lab.
