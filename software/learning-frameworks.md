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
- [SERL](https://github.com/rail-berkeley/serl) - Sample-efficient RL software suite for real-world manipulation, the predecessor of HIL-SERL (Apache-2.0).
- [unitree_rl_gym](https://github.com/unitreerobotics/unitree_rl_gym) - Unitree's RL training and sim-to-real pipeline for Go2, H1 and G1 on Isaac Gym and MuJoCo (BSD-3-Clause, last update mid-2025).

## See also

- [Policies and foundation models](policies-and-foundation-models.md) for the individual architectures these frameworks train.
- [Datasets](../datasets/README.md) for the data they consume.

---

*Know an open learning framework that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
