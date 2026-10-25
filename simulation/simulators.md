# Simulators

> Physics engines and simulation platforms for robotics.

[← Simulation](README.md) · [← Awesome Robotics](../README.md)

## Contents

- [Physics engines](#physics-engines)
- [GPU-parallel and differentiable](#gpu-parallel-and-differentiable)
- [Learning-oriented platforms](#learning-oriented-platforms)
- [ROS-native and general-purpose simulators](#ros-native-and-general-purpose-simulators)
- [Curated lists](#curated-lists)

## Physics engines

- [MuJoCo](https://github.com/google-deepmind/mujoco) - Fast, accurate multi-joint dynamics from Google DeepMind. Compiles to WebAssembly, which is how XLeRobot and reBot-DevArm ship zero-install browser digital twins.
- [Newton](https://github.com/newton-physics/newton) - GPU-accelerated, differentiable physics engine from NVIDIA, Google DeepMind and Disney Research under the Linux Foundation, built on Warp.
- [NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim) - GPU-accelerated, photorealistic simulation on Omniverse with USD scene description. reBot-DevArm ships USD models for it.
- [PyBullet](https://github.com/bulletphysics/bullet3) - The Bullet physics engine with Python bindings, a long-standing default for RL and robotics prototyping.
- [SAPIEN](https://github.com/haosulab/SAPIEN) - Part-level interactive simulator from UC San Diego with articulated objects and ray-traced rendering, the engine behind ManiSkill.

## GPU-parallel and differentiable

- [Brax](https://github.com/google/brax) - Differentiable, massively parallel physics in JAX for fast RL training on TPUs and GPUs.
- [Genesis](https://github.com/Genesis-Embodied-AI/Genesis) - Generative, differentiable physics engine for robotics and embodied AI built for very high simulation throughput.
- [MuJoCo Playground](https://github.com/google-deepmind/mujoco_playground) - GPU-accelerated locomotion and manipulation environments on MuJoCo MJX with sim-to-real recipes.

## Learning-oriented platforms

- [dm_control](https://github.com/google-deepmind/dm_control) - DeepMind's MuJoCo-based control suite and locomotion framework for continuous-control research.
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - Open-source robot learning framework on Isaac Sim for massively parallel RL and imitation learning.

## ROS-native and general-purpose simulators

- [Gazebo](https://github.com/gazebosim/gz-sim) - The long-running open-source robotics simulator with first-class ROS 2 integration.
- [Webots](https://github.com/cyberbotics/webots) - Apache-licensed desktop simulator from Cyberbotics with a large built-in robot library and ROS 2 bridge.

## Curated lists

- [best-of-robot-simulators](https://github.com/knmcguire/best-of-robot-simulators) - Ranked list of 180 robot simulators across 12 domains (generic, aerial, maritime, automotive, space, AI training) scored by GitHub and package metrics. No longer updated but still the broadest index.

## See also

- [Drake](../software/middleware-and-control.md) for model-based simulation and verification.
- [Environments and benchmarks](environments-and-benchmarks.md) for task suites built on these engines.

---

*Know an open simulator that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
