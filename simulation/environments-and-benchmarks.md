# Environments and Benchmarks

> Gym environments, task suites and evaluation benchmarks for robot learning.

[← Simulation](README.md) · [← Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible

## Contents

- [Manipulation benchmarks](#manipulation-benchmarks)
- [Household and embodied AI](#household-and-embodied-ai)
- [Real-to-sim evaluation](#real-to-sim-evaluation)
- [LeRobot Gymnasium environments](#lerobot-gymnasium-environments)
- [General Gymnasium suites](#general-gymnasium-suites)

## Manipulation benchmarks

- [CALVIN](https://github.com/mees/calvin) - Benchmark for long-horizon, language-conditioned manipulation with a 7-DOF arm in PyBullet.
- [LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO) - Lifelong robot learning benchmark with procedurally generated manipulation tasks. Supported by LeRobot's evaluation pipeline. 🧩
- [ManiSkill](https://github.com/haosulab/ManiSkill) - GPU-parallelized manipulation benchmark on SAPIEN with thousands of environments per GPU and large demonstration sets.
- [MetaWorld](https://github.com/Farama-Foundation/Metaworld) - 50 simulated manipulation tasks for multi-task and meta reinforcement learning. Supported by LeRobot's evaluation pipeline. 🧩
- [RLBench](https://github.com/stepjam/RLBench) - 100 hand-designed manipulation tasks with demonstrations, a standard for vision-based imitation learning.
- [robosuite](https://github.com/ARISE-Initiative/robosuite) - Modular MuJoCo manipulation framework from Stanford and UT Austin, the base for robomimic and RoboCasa.

## Household and embodied AI

- [Habitat](https://github.com/facebookresearch/habitat-sim) - Meta's high-performance simulator for embodied navigation and rearrangement in photorealistic indoor scenes.
- [OmniGibson / BEHAVIOR-1K](https://github.com/StanfordVL/OmniGibson) - 1,000 everyday household activities simulated on Isaac Sim with fluids, deformables and thermal states.
- [RoboCasa](https://github.com/robocasa/robocasa) - Large-scale generative kitchen environments and tasks for training generalist household robots.

## Real-to-sim evaluation

- [SimplerEnv](https://github.com/simpler-env/SimplerEnv) - Simulated replicas of real evaluation setups for scoring OpenVLA, Octo and RT-X style policies without a robot.

## LeRobot Gymnasium environments

- [gym-aloha](https://github.com/huggingface/gym-aloha) - Bimanual ALOHA manipulation tasks in MuJoCo as Gymnasium environments. 🧩
- [gym-hil](https://github.com/huggingface/gym-hil) - Human-in-the-loop environments for training HIL-SERL policies with gamepad or keyboard intervention. 🧩
- [gym-pusht](https://github.com/huggingface/gym-pusht) - The PushT 2D manipulation task from Diffusion Policy as a Gymnasium environment. 🧩
- [gym-xarm](https://github.com/huggingface/gym-xarm) - xArm manipulation tasks in simulation as Gymnasium environments. 🧩

## General Gymnasium suites

- [Gymnasium-Robotics](https://github.com/Farama-Foundation/Gymnasium-Robotics) - Farama's maintained Fetch, Shadow Hand, maze and ant environments on MuJoCo.

## See also

- [XLeRobot](https://github.com/Vector-Wangel/XLeRobot) ships its own RL environment for the dual-arm mobile robot. See [robot-models.md](robot-models.md).

---

*Know an open benchmark that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
