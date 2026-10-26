# Environments and Benchmarks

> Gym environments, task suites and evaluation benchmarks for robot learning.

[← Simulation](README.md) · [← Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible

## Contents

- [Manipulation benchmarks](#manipulation-benchmarks)
- [Locomotion and multi-domain suites](#locomotion-and-multi-domain-suites)
- [Household and embodied AI](#household-and-embodied-ai)
- [Real-to-sim evaluation](#real-to-sim-evaluation)
- [LeRobot Gymnasium environments](#lerobot-gymnasium-environments)

## Manipulation benchmarks

- [CALVIN](https://github.com/mees/calvin) - Benchmark for long-horizon, language-conditioned manipulation with a 7-DOF arm in PyBullet (MIT).
- [LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO) - Lifelong robot learning benchmark with procedurally generated manipulation tasks, supported by LeRobot's evaluation pipeline (MIT). 🧩
- [ManiSkill](https://github.com/mani-skill/ManiSkill) - GPU-parallelized manipulation benchmark on SAPIEN with large demonstration sets; code Apache-2.0, bundled assets CC BY-NC 4.0.
- [MetaWorld](https://github.com/Farama-Foundation/Metaworld) - 50 simulated manipulation tasks for multi-task and meta RL, supported by LeRobot's evaluation pipeline (MIT). 🧩
- [RLBench](https://github.com/stepjam/RLBench) - 100 manipulation tasks with demonstrations on CoppeliaSim; Imperial College licence permits noncommercial and academic use only.
- [robosuite](https://github.com/ARISE-Initiative/robosuite) - Modular MuJoCo manipulation framework from Stanford and UT Austin, the base for robomimic and RoboCasa (MIT).

## Locomotion and multi-domain suites

- [Gymnasium-Robotics](https://github.com/Farama-Foundation/Gymnasium-Robotics) - Farama's maintained Fetch, Shadow Hand, maze and ant environments on MuJoCo (MIT).
- [MuJoCo Playground](https://github.com/google-deepmind/mujoco_playground) - GPU-accelerated locomotion and manipulation environments on MuJoCo MJX with sim-to-real recipes (Apache-2.0).

## Household and embodied AI

- [BEHAVIOR-1K](https://github.com/StanfordVL/BEHAVIOR-1K) - 1,000 everyday household activities simulated in OmniGibson on Isaac Sim with fluids, deformables and thermal states (MIT).
- [Habitat](https://github.com/facebookresearch/habitat-sim) - Meta's high-performance simulator for embodied navigation and rearrangement in photorealistic indoor scenes (MIT).
- [RoboCasa](https://github.com/robocasa/robocasa) - Kitchen simulation framework whose RoboCasa365 release spans 365 tasks and 2,500+ scenes; code MIT, assets and datasets CC BY 4.0.

## Real-to-sim evaluation

- [SimplerEnv](https://github.com/simpler-env/SimplerEnv) - Simulated replicas of real evaluation setups for scoring OpenVLA, Octo and RT-X style policies without a robot (MIT).

## LeRobot Gymnasium environments

- [gym-aloha](https://github.com/huggingface/gym-aloha) - Bimanual ALOHA manipulation tasks in MuJoCo as Gymnasium environments (Apache-2.0). 🧩
- [gym-hil](https://github.com/huggingface/gym-hil) - Human-in-the-loop environments for training HIL-SERL policies with gamepad or keyboard intervention (Apache-2.0). 🧩
- [gym-pusht](https://github.com/huggingface/gym-pusht) - The PushT 2D manipulation task from Diffusion Policy as a Gymnasium environment (Apache-2.0). 🧩

## See also

- [XLeRobot](../hardware/mobile-robots.md) ships its own RL environment for the dual-arm mobile robot.

---

*Know an open benchmark that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
