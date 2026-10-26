<div align="center">

# Awesome Robotics 🤖

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square)](LICENSE)
[![Open Source Hardware](https://img.shields.io/badge/Open_Source-Hardware-orange.svg?style=flat-square)](hardware/README.md)

**A community-curated map of open source robotics: hardware you can build, simulators you can run, software you can train.**

*Build a robot this weekend. Train it next week. Share it with everyone.*

[Hardware](#-hardware) · [Simulation](#-simulation) · [Software](#-software) · [Datasets](#-datasets) · [Community](#-community) · [Contribute](#-contributing)

</div>

---

## 🚀 Start Here

Three projects that together cover learning software, a mobile household robot and a research-grade arm. Each publishes its hardware designs or code under an open license.

| Project | What it is | Why it matters |
|---|---|---|
| [**LeRobot**](https://github.com/huggingface/lerobot) 🧩 | Hugging Face's PyTorch library for real-world robot learning: policies, datasets, hardware drivers, teleop. | The most widely used open training stack for low-cost robots. Supports ACT, Diffusion, Pi0, SmolVLA, GR00T and more. |
| [**XLeRobot**](https://github.com/Vector-Wangel/XLeRobot) 🧩 🖨️ 💵 🏠 | Dual-arm mobile household robot built on LeRobot, from $660 per the project's BOM. | A documented, low-cost path to a mobile manipulator with simulation and VR teleop included. |
| [**reBot-DevArm**](https://github.com/Seeed-Projects/reBot-DevArm) 🧩 🏭 | Seeed Studio's 6-DOF + gripper arm (B601-DM, B601-RS) with ROS 1/2, LeRobot, Pinocchio and Isaac Sim support. | Sub-0.2 mm repeatability per its spec sheet, hardware under CERN-OHL-W-2.0 and software under Apache-2.0. |

**Legend:** 🧩 LeRobot-compatible · 🖨️ 3D-printable · 💵 Under $1,000 · 🏠 Household · 🏭 Industrial-grade

## 🧭 I want to...

| Goal | Start here |
|---|---|
| Build my first arm | [hardware/arms.md](hardware/arms.md) |
| Collect demonstrations | [hardware/teleoperation.md](hardware/teleoperation.md) |
| Train from demonstrations | [software/learning-frameworks.md](software/learning-frameworks.md) |
| Test a policy in simulation | [simulation/environments-and-benchmarks.md](simulation/environments-and-benchmarks.md) |
| Plan and control motion | [software/middleware-and-control.md](software/middleware-and-control.md) |
| Find robot data | [datasets/README.md](datasets/README.md) |
| Learn the fundamentals | [community/README.md](community/README.md) |

---

## 🗺️ Taxonomy

Every resource has one canonical entry in a topic file. Each folder has a `README.md` index. The sections below are highlights; the topic files are complete.

```
awesome-robotics/
├── hardware/                 Things you can build or buy, with published designs
│   ├── arms.md                 Robotic arms and manipulators
│   ├── mobile-robots.md        Wheeled bases and mobile manipulators
│   ├── humanoids-and-hands.md  Humanoids, legged robots, dexterous hands
│   ├── teleoperation.md        Leader arms, handheld interfaces, exoskeletons, VR
│   └── components.md           Motor controllers, actuators, servo SDKs, sensors
├── simulation/               Where robots are tested before they are built
│   ├── simulators.md           Physics engines and sim platforms
│   ├── environments-and-benchmarks.md  Gym envs, task suites, benchmarks
│   └── robot-models.md         URDF / MJCF / USD collections and loaders
├── software/                 Code that makes robots move and learn
│   ├── learning-frameworks.md  Imitation learning, RL, end-to-end training
│   ├── policies-and-foundation-models.md  VLAs, world models, pretrained checkpoints
│   ├── middleware-and-control.md  ROS, kinematics, planning, SDKs, visualization
│   └── perception.md           Pose estimation, grasp detection
├── datasets/                 Open robot data and formats
└── community/                Courses, textbooks, chat servers, sibling lists, events
```

---

## 🦾 Hardware

> Published designs you can print, order, assemble and modify. → [Browse all hardware](hardware/README.md)

### Arms → [hardware/arms.md](hardware/arms.md)

- [reBot-DevArm](https://github.com/Seeed-Projects/reBot-DevArm) - 6-DOF + gripper arm with ROS 1/2, LeRobot, Pinocchio and Isaac Sim support (hardware CERN-OHL-W-2.0). 🧩 🏭
- [SO-ARM100 / SO-101](https://github.com/TheRobotStudio/SO-ARM100) - Standard low-cost 3D-printed leader/follower arm pair of the LeRobot ecosystem. 🧩 🖨️ 💵
- [OpenArm](https://github.com/enactic/openarm) - 7-DOF backdrivable humanoid arm for contact-rich research (hardware CERN-OHL-S-2.0). 🧩

### Mobile robots → [hardware/mobile-robots.md](hardware/mobile-robots.md)

- [XLeRobot](https://github.com/Vector-Wangel/XLeRobot) - Dual-arm mobile home robot built on LeRobot, SO-101 and LeKiwi. 🧩 🖨️ 💵 🏠
- [LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi) - Low-cost omnidirectional mobile base with an SO-100 arm, natively supported by LeRobot. 🧩 🖨️ 💵

### Humanoids, legged robots and hands → [hardware/humanoids-and-hands.md](hardware/humanoids-and-hands.md)

- [Berkeley Humanoid Lite](https://github.com/HybridRobotics/berkeley-humanoid-lite) - Humanoid with 3D-printed cycloidal gearboxes, Onshape CAD and Isaac Lab training code. 🖨️
- [Open Duck Mini](https://github.com/apirrone/Open_Duck_Mini) - 3D-printed biped inspired by Disney's BDX droids, walking with RL policies trained in MuJoCo. 🖨️ 💵

---

## 🌍 Simulation

> Train, test and break your robot before it exists. → [Browse all simulation](simulation/README.md)

### Simulators → [simulation/simulators.md](simulation/simulators.md)

- [MuJoCo](https://github.com/google-deepmind/mujoco) - Fast, accurate physics engine from Google DeepMind; its browser build powers the XLeRobot and reBot digital twins.
- [NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim) - GPU-accelerated, photorealistic simulation on Omniverse.
- [Newton](https://github.com/newton-physics/newton) - GPU-accelerated, differentiable physics engine from NVIDIA, Google DeepMind and Disney Research.

### Environments and benchmarks → [simulation/environments-and-benchmarks.md](simulation/environments-and-benchmarks.md)

- [LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO) - Lifelong robot learning benchmark, supported by LeRobot's evaluation pipeline. 🧩
- [ManiSkill](https://github.com/mani-skill/ManiSkill) - GPU-parallelized manipulation benchmark on SAPIEN.
- [MuJoCo Playground](https://github.com/google-deepmind/mujoco_playground) - GPU-accelerated locomotion and manipulation environments with sim-to-real recipes.

---

## 🧠 Software

> Frameworks, models and middleware. → [Browse all software](software/README.md)

### Learning frameworks → [software/learning-frameworks.md](software/learning-frameworks.md)

- [LeRobot](https://github.com/huggingface/lerobot) - End-to-end robot learning in PyTorch: record, train ACT / Diffusion / VLAs, deploy to real hardware. 🧩
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - Massively parallel RL and imitation learning on Isaac Sim.

### Policies and foundation models → [software/policies-and-foundation-models.md](software/policies-and-foundation-models.md)

- [SmolVLA](https://huggingface.co/lerobot/smolvla_base) - Hugging Face's 0.5B-parameter VLA, trained on community LeRobot data for consumer GPUs. 🧩
- [openpi (Pi0 / Pi0.5)](https://github.com/Physical-Intelligence/openpi) - Open weights and code for Physical Intelligence's VLA models. 🧩
- [ACT](https://github.com/tonyzhaozh/act) - Action Chunking with Transformers, the imitation learning policy behind ALOHA. 🧩

### Middleware and control → [software/middleware-and-control.md](software/middleware-and-control.md)

- [ROS 2](https://github.com/ros2/ros2) - The Robot Operating System, supported by most hardware in this list.
- [MoveIt 2](https://github.com/moveit/moveit2) - The standard ROS 2 motion planning framework for manipulators.
- [Pinocchio](https://github.com/stack-of-tasks/pinocchio) - Fast rigid-body dynamics and kinematics, used by reBot-DevArm.

### Perception → [software/perception.md](software/perception.md)

- [FoundationPose](https://github.com/NVlabs/FoundationPose) - NVIDIA's unified 6D pose estimation and tracking for novel objects (noncommercial license).

---

## 📦 Datasets

> Open robot data and the formats that make it shareable. → [Browse all datasets](datasets/README.md)

- [LeRobotDataset](https://huggingface.co/lerobot) - Hugging Face's dataset format and Hub, with thousands of community datasets. 🧩
- [Open X-Embodiment](https://robotics-transformer-x.github.io/) - Over one million real robot trajectories across 22 embodiments.
- [BridgeData V2](https://rail-berkeley.github.io/bridgedata/) - 53k language-annotated WidowX trajectories (CC BY 4.0).

---

## 🧑‍🤝‍🧑 Community

> Learn, ask, meet. → [Browse community resources](community/README.md)

- [Hugging Face Robotics Course](https://huggingface.co/learn/robotics-course/en/unit0/1) - Free course connecting robotics foundations with LeRobot workflows.
- [LeRobot Discord](https://discord.gg/q8Dzzpym3f) - The official community server for questions, show-and-tell and hardware help.
- [XLeRobot Docs](https://xlerobot.readthedocs.io) and [Seeed Robotics Wiki](https://wiki.seeedstudio.com/robotics_page/) - Build and integration guides for the featured hardware.

---

## 🤝 Contributing

Contributions are what make this list awesome. Adding a resource takes under two minutes:

1. Find the right folder and topic file in the [taxonomy](#%EF%B8%8F-taxonomy).
2. Add one line in the format `- [Name](url) - One-sentence description. 🏷️ tags`.
3. Open a pull request. That is it.

Read [CONTRIBUTING.md](CONTRIBUTING.md) for the full guidelines, or [open an issue](../../issues/new/choose) if you would rather we add it for you.

**Rules of the list:** open source only (code, CAD or both, with a stated license), maintained within the last year or clearly complete and usable, and useful to someone other than its author.

---

## 📜 License

[Apache 2.0](LICENSE). Project names and descriptions belong to their respective authors.

<div align="center">

**If this list helped you, ⭐ star it and share it. Every star brings one more builder.**

</div>
