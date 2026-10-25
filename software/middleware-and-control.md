# Middleware and Control

> ROS, kinematics and dynamics libraries, motion planning, hardware SDKs and visualization.

[← Software](README.md) · [← Awesome Robotics](../README.md)

## Contents

- [Middleware](#middleware)
- [Kinematics and dynamics](#kinematics-and-dynamics)
- [Motion planning and navigation](#motion-planning-and-navigation)
- [Hardware SDKs](#hardware-sdks)
- [Visualization](#visualization)

## Middleware

- [dora-rs](https://github.com/dora-rs/dora) - Low-latency dataflow middleware in Rust with Python nodes, used by OpenArm and other LeRobot-adjacent projects for teleop and data collection.
- [ROS 2](https://github.com/ros2/ros2) - The Robot Operating System: message passing, tooling and a vast driver ecosystem. Supported by reBot-DevArm and most hardware in this list. [Docs](https://docs.ros.org).
- [Zenoh](https://github.com/eclipse-zenoh/zenoh) - Eclipse pub/sub and query protocol that scales from microcontrollers to cloud and ships as a ROS 2 middleware option.

## Kinematics and dynamics

- [Crocoddyl](https://github.com/loco-3d/crocoddyl) - Optimal control library for multi-contact robot dynamics built on Pinocchio.
- [Drake](https://github.com/RobotLocomotion/drake) - Model-based design, simulation and verification toolbox for robotics from MIT and Toyota Research Institute.
- [mink](https://github.com/kevinzakka/mink) - Differential inverse kinematics in Python on MuJoCo with task priorities and limits.
- [Pinocchio](https://github.com/stack-of-tasks/pinocchio) - Fast rigid-body dynamics and kinematics with analytical derivatives. Used by reBot-DevArm.

## Motion planning and navigation

- [cuRobo](https://github.com/NVlabs/curobo) - NVIDIA's CUDA-accelerated motion generation library for collision-free arm trajectories in milliseconds.
- [MoveIt 2](https://github.com/moveit/moveit2) - The standard ROS 2 motion planning framework for manipulators, used by OpenArm and reBot-DevArm.
- [Nav2](https://github.com/ros-navigation/navigation2) - The ROS 2 navigation stack for mobile robots, from mapping to behavior trees.
- [OMPL](https://github.com/ompl/ompl) - The Open Motion Planning Library of sampling-based planners that powers MoveIt.

## Hardware SDKs

- [reBot-DevArm Python SDK](https://github.com/Seeed-Projects/reBot-DevArm) - Python SDK for the B601-DM and B601-RS arms alongside ROS 1/2 packages and LeRobot integration guides.
- [unitree_sdk2](https://github.com/unitreerobotics/unitree_sdk2) - Official C++ and Python SDK for Unitree Go2, B2, H1 and G1 robots. The G1 is supported by LeRobot.

## Visualization

- [Rerun](https://github.com/rerun-io/rerun) - Multimodal data visualization SDK and viewer for time series, images, point clouds and transforms. LeRobot uses it for dataset playback.
- [Viser](https://github.com/nerfstudio-project/viser) - Web-based 3D visualization and GUI library for Python, handy for URDF viewers and teleop dashboards.

---

*Know open middleware or control software that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
