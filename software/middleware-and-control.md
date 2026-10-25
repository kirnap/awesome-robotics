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

- [dora](https://github.com/dora-rs/dora) - Low-latency dataflow middleware in Rust with Python nodes, used by OpenArm for teleoperation and data collection (Apache-2.0).
- [ROS 2](https://github.com/ros2/ros2) - The Robot Operating System: message passing, tooling and a vast driver ecosystem, supported by most hardware in this list. [Docs](https://docs.ros.org).
- [Zenoh](https://github.com/eclipse-zenoh/zenoh) - Eclipse pub/sub and query protocol from microcontrollers to cloud, available as a ROS 2 middleware option (Apache-2.0 or EPL-2.0).

## Kinematics and dynamics

- [Crocoddyl](https://github.com/loco-3d/crocoddyl) - Optimal control library for multi-contact robot dynamics built on Pinocchio (BSD-3-Clause).
- [Drake](https://github.com/RobotLocomotion/drake) - Model-based design, simulation and verification toolbox from MIT and Toyota Research Institute (BSD-3-Clause).
- [mink](https://github.com/kevinzakka/mink) - Differential inverse kinematics in Python on MuJoCo with task priorities and limits (Apache-2.0).
- [Pinocchio](https://github.com/stack-of-tasks/pinocchio) - Fast rigid-body dynamics and kinematics with analytical derivatives, used by reBot-DevArm (BSD-2-Clause).

## Motion planning and navigation

- [cuRobo](https://github.com/NVlabs/curobo) - NVIDIA's CUDA-accelerated motion generation library for collision-free arm trajectories in milliseconds (Apache-2.0).
- [MoveIt 2](https://github.com/moveit/moveit2) - The standard ROS 2 motion planning framework for manipulators, used by OpenArm and reBot-DevArm (BSD-3-Clause).
- [Nav2](https://github.com/ros-navigation/navigation2) - The ROS 2 navigation stack for mobile robots, from mapping to behavior trees (Apache-2.0, BSD-3-Clause and LGPL-2.1 by package).
- [OMPL](https://github.com/ompl/ompl) - The Open Motion Planning Library of sampling-based planners that powers MoveIt (BSD-3-Clause).

## Hardware SDKs

- [Reachy Mini SDK](https://github.com/pollen-robotics/reachy_mini) - Python and TypeScript SDK and simulation for Pollen Robotics' desktop robot; hardware files are CC BY-NC-SA, so it is not listed as open hardware (Apache-2.0).
- [unitree_sdk2](https://github.com/unitreerobotics/unitree_sdk2) - Official C++ and Python SDK for Unitree Go2, B2, H1 and G1; the G1 is supported by LeRobot (BSD-3-Clause).

The reBot-DevArm Python SDK ships with the arm; see [arms.md](../hardware/arms.md).

## Visualization

- [Rerun](https://github.com/rerun-io/rerun) - Multimodal data visualization SDK and viewer for time series, images, point clouds and transforms; LeRobot uses it for dataset playback (Apache-2.0).
- [Viser](https://github.com/viser-project/viser) - Web-based 3D visualization and GUI library for Python, handy for URDF viewers and teleop dashboards (Apache-2.0).

---

*Know open middleware or control software that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
