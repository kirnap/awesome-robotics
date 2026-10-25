# Learning Frameworks

> End-to-end pipelines for collecting data, training policies and deploying them to real robots.

[← Software](README.md) · [← Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible

## Contents

- [End-to-end frameworks](#end-to-end-frameworks)
- [Reinforcement learning on real robots](#reinforcement-learning-on-real-robots)

## End-to-end frameworks

- [LeRobot](https://github.com/huggingface/lerobot) - Hugging Face's PyTorch library for real-world robot learning. Record with leader arms or gamepads, store in LeRobotDataset, train imitation learning (ACT, Diffusion, VQ-BeT), RL (HIL-SERL, TDMPC) or VLAs (Pi0, Pi0.5, SmolVLA, GR00T N1.7), evaluate on LIBERO and MetaWorld, deploy to SO-100, LeKiwi, Koch, HopeJR, Reachy2, Unitree G1, OpenARM, reBot B601 and more. Apache-2.0. 🧩

## Reinforcement learning on real robots

- [HIL-SERL](https://github.com/rail-berkeley/hil-serl) - Human-in-the-loop sample-efficient RL that learns real-world manipulation in an hour or two, from UC Berkeley RAIL. Integrated into LeRobot. 🧩
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - Massively parallel RL and imitation learning on GPU simulation, with sim-to-real workflows. See also [simulators.md](../simulation/simulators.md).

## See also

- [Policies and foundation models](policies-and-foundation-models.md) for the individual architectures these frameworks train.
- [Datasets](../datasets/README.md) for the data they consume.

---

*Know an open learning framework that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
