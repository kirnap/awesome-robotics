# Learning Frameworks

> End-to-end pipelines for collecting data, training policies and deploying them to robots.

[← Software](README.md) · [← Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible

## Contents

- [End-to-end frameworks](#end-to-end-frameworks)
- [Imitation learning toolkits](#imitation-learning-toolkits)
- [Reinforcement learning](#reinforcement-learning)

## End-to-end frameworks

- [LeRobot](https://github.com/huggingface/lerobot) - Hugging Face's PyTorch library for real-world robot learning: recording, LeRobotDataset, imitation, RL and VLA training, drivers for many robots (Apache-2.0). 🧩

## Imitation learning toolkits

- [robomimic](https://github.com/ARISE-Initiative/robomimic) - Stanford framework for learning from demonstrations with standardized datasets, offline algorithms and robosuite integration (MIT).

## Reinforcement learning

- [HIL-SERL](https://github.com/rail-berkeley/hil-serl) - Human-in-the-loop sample-efficient RL that learns real-world manipulation in one to two hours, from UC Berkeley RAIL; integrated into LeRobot (Apache-2.0). 🧩
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - NVIDIA's robot learning framework on Isaac Sim for massively parallel RL and imitation learning with sim-to-real workflows (BSD-3-Clause).
- [RSL-RL](https://github.com/leggedrobotics/rsl_rl) - GPU-accelerated, lightweight PPO and student-teacher distillation library from ETH Zurich, used by Isaac Lab and MuJoCo Playground (BSD-3-Clause).
- [SERL](https://github.com/rail-berkeley/serl) - Sample-efficient RL software suite for real-world manipulation, the predecessor of HIL-SERL (Apache-2.0).
- [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3) - Reliable PyTorch implementations of PPO, SAC, TD3 and other RL algorithms that plug into Gymnasium robot environments (MIT).
- [unitree_rl_lab](https://github.com/unitreerobotics/unitree_rl_lab) - Unitree's official Isaac Lab based RL training and sim-to-real pipeline for Go2, G1 and H1, successor to unitree_rl_gym (Apache-2.0).

## See also

- [Policies and foundation models](policies-and-foundation-models.md) for the individual architectures these frameworks train.
- [Datasets](../datasets/README.md) for the data they consume.

---

*Know an open learning framework that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
