# HRIC-human-arm-model
This reporsitory contains the ROS packages developed for musculoskeletal modelling of the right human arm.
## Overview
human_arm_control - ROS package that contains an implementation of a gravity compensation controller for control of the skeletal human arm model.

human_arm_description - ROS package that contains the skeletal URDF human arm model. The included launch file runs RVIZ with the skeletal human arm model loaded.

markers - ROS package that contains local marker coordinate configuration file. The included luanch file loads the marker coordinates on the parameter server and starts a node that publishes the marker coordinate transforms.

model_fitting - ROS package that contains classes and the algorithm for unconstrained optimisation of constant model parameters. The node run by the launch file creates a demo and logs data in a csv file.

preprocessing - ROS package for extracting and transforming muscle definintions and wrap objects from OSIM files.

right_human_arm - Folder that contains the musculoskeletal model of the human arm. Config files are included to load the model into the hybrid simulator database.

sdfPoseConvert - ROS package to convert poses in a SDF version 1.7 file to poses in a SDF version 1.4 file.
