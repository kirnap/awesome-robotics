# Simulators

> Physics engines and simulation platforms for robotics.

[← Simulation](README.md) · [← Awesome Robotics](../README.md)

## Contents

- [Physics engines](#physics-engines)
- [GPU-parallel and differentiable](#gpu-parallel-and-differentiable)
- [Simulation platforms](#simulation-platforms)

## Physics engines

- [MuJoCo](https://github.com/google-deepmind/mujoco) - Fast, accurate multi-joint dynamics from Google DeepMind; its WebAssembly build powers the browser twins of XLeRobot and reBot-DevArm (Apache-2.0).
- [Newton](https://github.com/newton-physics/newton) - GPU-accelerated, differentiable physics engine from NVIDIA, Google DeepMind and Disney Research under the Linux Foundation, built on Warp (Apache-2.0).
- [NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim) - Photorealistic GPU simulation on Omniverse with USD scenes; core code Apache-2.0, some dependencies under other NVIDIA terms.
- [PyBullet](https://github.com/bulletphysics/bullet3) - The Bullet physics engine with Python bindings, a long-standing default for RL and robotics prototyping (zlib).
- [SAPIEN](https://github.com/haosulab/SAPIEN) - Part-level interactive simulator from UC San Diego with articulated objects and ray-traced rendering, the engine behind ManiSkill (Apache-2.0).

## GPU-parallel and differentiable

- [Brax](https://github.com/google/brax) - Differentiable, massively parallel rigid-body physics in JAX for fast RL training on TPUs and GPUs (Apache-2.0).
- [Genesis](https://github.com/Genesis-Embodied-AI/genesis-world) - Generative, differentiable physics platform for robotics and embodied AI built for very high simulation throughput (Apache-2.0).
- [MuJoCo Warp](https://github.com/google-deepmind/mujoco_warp) - GPU-optimized MuJoCo for NVIDIA hardware developed within the Newton project, with a batch ray-tracing renderer and MJX interoperability (Apache-2.0).

## Simulation platforms

- [dm_control](https://github.com/google-deepmind/dm_control) - Google DeepMind's MuJoCo-based control suite and locomotion framework for continuous-control research (Apache-2.0).
- [Gazebo](https://github.com/gazebosim/gz-sim) - The long-running open-source robotics simulator with first-class ROS 2 integration (Apache-2.0).
- [Webots](https://github.com/cyberbotics/webots) - Desktop simulator from Cyberbotics with a large built-in robot and sensor library and a ROS 2 bridge (Apache-2.0).

## See also

- [Isaac Lab](../software/learning-frameworks.md) for robot learning on Isaac Sim.
- [Environments and benchmarks](environments-and-benchmarks.md) for task suites built on these engines, including MuJoCo Playground.
- [best-of-robot-simulators](../community/README.md#sibling-awesome-lists) for a metrics-ranked index of 180 simulators.

---

*Know an open simulator that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
