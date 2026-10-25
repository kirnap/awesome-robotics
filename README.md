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

Three projects that together form a complete, fully open robotics stack. Pick an arm, put it on wheels, train it with imitation learning. Every link below is open source end to end.

| Project | What it is | Why it matters |
|---|---|---|
| [**LeRobot**](https://github.com/huggingface/lerobot) 🧩 | Hugging Face's PyTorch library for real-world robot learning: policies, datasets, hardware drivers, teleop. | The de facto open standard for training and sharing robot policies. Supports ACT, Diffusion, Pi0, SmolVLA, GR00T and more. |
| [**XLeRobot**](https://github.com/Vector-Wangel/XLeRobot) 🧩 🖨️ 💵 🏠 | Dual-arm mobile household robot built on LeRobot, starting around $660. | The cheapest practical path to a mobile manipulator you can actually run in your home. MuJoCo sim included. |
| [**reBot-DevArm**](https://github.com/Seeed-Projects/reBot-DevArm) 🧩 🏭 | Seeed Studio's 6-DOF + gripper open source arm (B601-DM, B601-RS) with ROS 1/2, LeRobot, Pinocchio and Isaac Sim support. | Industrial-grade repeatability (<0.2 mm) with a fully open hardware and software stack. Hardware under CERN-OHL-W-2.0. |

**Legend:** 🧩 LeRobot-compatible · 🖨️ 3D-printable · 💵 Under $1,000 · 🏠 Household · 🏭 Industrial-grade

---

## 🗺️ Taxonomy

Every resource lives in exactly one folder. Each folder has a `README.md` index plus topic files.

```
awesome-robotics/
├── hardware/                 Things you can build or buy, with open designs
│   ├── arms.md                 Robotic arms and manipulators
│   ├── mobile-robots.md        Wheeled bases and mobile manipulators
│   ├── humanoids-and-hands.md  Humanoids, legged robots, dexterous hands
│   ├── teleoperation.md        Leader arms, VR rigs, exoskeletons, gamepads
│   └── components.md           Actuators, control boards, sensors, cameras
├── simulation/               Where robots are born before they are built
│   ├── simulators.md           Physics engines and sim platforms
│   ├── environments-and-benchmarks.md  Gym envs, task suites, benchmarks
│   └── robot-models.md         URDF / MJCF / USD assets and digital twins
├── software/                 Code that makes robots move and learn
│   ├── learning-frameworks.md  Imitation learning, RL, end-to-end training
│   ├── policies-and-foundation-models.md  VLAs, world models, pretrained checkpoints
│   └── middleware-and-control.md  ROS, kinematics, planning, SDKs
├── datasets/                 Open robot data and formats
└── community/                Courses, tutorials, Discords, events
```

---

## 🦾 Hardware

> Open designs you can print, order, assemble and modify. → [Browse all hardware](hardware/README.md)

### Arms → [hardware/arms.md](hardware/arms.md)

- [reBot-DevArm](https://github.com/Seeed-Projects/reBot-DevArm) - 6-DOF + gripper open source arm from Seeed Studio in two variants (B601-DM: 1.5 kg payload, B601-RS: 2.5 kg). ROS 1/2, LeRobot, Pinocchio, Isaac Sim, Python SDK. 🧩 🏭
- [SO-ARM100 / SO-101](https://github.com/TheRobotStudio/SO-ARM100) - The standard low-cost 3D-printed leader/follower arm pair used across the LeRobot ecosystem. 🧩 🖨️ 💵
- [Koch v1.1](https://github.com/jess-moss/koch-v1-1) - Low-cost 3D-printed arm, one of the original LeRobot reference designs. 🧩 🖨️ 💵
- [OpenArm](https://github.com/enactic/OpenArm) - 7-DOF backdrivable bimanual humanoid arm for contact-rich research, with ROS 2, MuJoCo and LeRobot support. Hardware CERN-OHL-S-2.0. 🧩

### Mobile robots → [hardware/mobile-robots.md](hardware/mobile-robots.md)

- [XLeRobot](https://github.com/Vector-Wangel/XLeRobot) - Dual-arm mobile home robot built on LeRobot, SO-100/101 and LeKiwi, from around $660. 🧩 🖨️ 💵 🏠
- [LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi) - Low-cost omnidirectional mobile base with an SO-100 arm, natively supported by LeRobot. 🧩 🖨️ 💵
- [Bambot](https://github.com/timqian/bambot) - Open-source low-cost bimanual mobile robot built around SO-100 arms. 🧩 🖨️ 💵

### Humanoids and hands → [hardware/humanoids-and-hands.md](hardware/humanoids-and-hands.md)

- [HopeJR](https://github.com/TheRobotStudio/HOPEJr) - Open humanoid arm and dexterous hand from The Robot Studio, supported by LeRobot. 🧩 🖨️

---

## 🌍 Simulation

> Train, test and break your robot before it exists. → [Browse all simulation](simulation/README.md)

### Simulators → [simulation/simulators.md](simulation/simulators.md)

- [MuJoCo](https://github.com/google-deepmind/mujoco) - Fast, accurate physics engine from Google DeepMind. Runs in the browser via WebAssembly, which is how XLeRobot and reBot ship zero-install digital twins.
- [NVIDIA Isaac Sim](https://github.com/isaac-sim/IsaacSim) - GPU-accelerated, photorealistic simulation on Omniverse. reBot-DevArm ships USD models for it.
- [Isaac Lab](https://github.com/isaac-sim/IsaacLab) - Open-source robot learning framework built on Isaac Sim for massively parallel RL and imitation learning.
- [Genesis](https://github.com/Genesis-Embodied-AI/Genesis) - Generative physics engine for robotics and embodied AI, built for speed and differentiability.
- [Gazebo](https://github.com/gazebosim/gz-sim) - The classic open-source robotics simulator, tightly integrated with ROS 2.

### Environments and benchmarks → [simulation/environments-and-benchmarks.md](simulation/environments-and-benchmarks.md)

- [LIBERO](https://github.com/Lifelong-Robot-Learning/LIBERO) - Lifelong robot learning benchmark, supported by LeRobot's evaluation pipeline.
- [MetaWorld](https://github.com/Farama-Foundation/Metaworld) - 50 manipulation tasks for multi-task and meta RL, supported by LeRobot.
- [gym-aloha](https://github.com/huggingface/gym-aloha) - Bimanual ALOHA tasks in MuJoCo, packaged as a Gymnasium environment for LeRobot. 🧩

### Robot models → [simulation/robot-models.md](simulation/robot-models.md)

- [MuJoCo Menagerie](https://github.com/google-deepmind/mujoco_menagerie) - Curated, high-quality MJCF models of popular robots, maintained by DeepMind.
- [XLeRobot Simulation](https://github.com/Vector-Wangel/XLeRobot) - URDFs, keyboard/Xbox/Joy-Con/Quest 3 control scripts, an RL environment and a browser MuJoCo demo. 🧩

---

## 🧠 Software

> Frameworks, models and middleware. → [Browse all software](software/README.md)

### Learning frameworks → [software/learning-frameworks.md](software/learning-frameworks.md)

- [LeRobot](https://github.com/huggingface/lerobot) - End-to-end robot learning in PyTorch: record data, train ACT / Diffusion / VQ-BeT / TDMPC / HIL-SERL / VLAs, deploy to real hardware. 🧩
- [HIL-SERL](https://github.com/rail-berkeley/hil-serl) - Human-in-the-loop sample-efficient RL for real robots, from UC Berkeley. Integrated in LeRobot.

### Policies and foundation models → [software/policies-and-foundation-models.md](software/policies-and-foundation-models.md)

- [SmolVLA](https://huggingface.co/lerobot/smolvla_base) - Hugging Face's compact vision-language-action model, trained on community LeRobot data and runnable on consumer GPUs. 🧩
- [openpi (Pi0 / Pi0.5)](https://github.com/Physical-Intelligence/openpi) - Open weights and code for Physical Intelligence's VLA models.
- [Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T) - NVIDIA's open foundation model for generalist humanoid robot reasoning and skills.
- [OpenVLA](https://github.com/openvla/openvla) - 7B open-source vision-language-action model trained on Open X-Embodiment.
- [ACT](https://github.com/tonyzhaozh/act) - Action Chunking with Transformers, the imitation learning policy behind ALOHA.
- [Diffusion Policy](https://github.com/real-stanford/diffusion_policy) - Visuomotor policy learning via action diffusion.

### Middleware and control → [software/middleware-and-control.md](software/middleware-and-control.md)

- [ROS 2](https://github.com/ros2/ros2) - The Robot Operating System. Supported by reBot-DevArm and most hardware in this list.
- [Pinocchio](https://github.com/stack-of-tasks/pinocchio) - Fast rigid-body dynamics and kinematics library. Used by reBot-DevArm.
- [Drake](https://github.com/RobotLocomotion/drake) - Model-based design and verification toolbox for robotics from MIT and TRI.

---

## 📦 Datasets

> Open robot data and the formats that make it shareable. → [Browse all datasets](datasets/README.md)

- [LeRobotDataset](https://huggingface.co/lerobot) - Hugging Face's dataset format: synchronized MP4 video plus Parquet state/action tables, thousands of community datasets on the Hub. 🧩
- [Open X-Embodiment](https://robotics-transformer-x.github.io/) - Over 1M real robot trajectories across 22 embodiments from 21 institutions.
- [DROID](https://droid-dataset.github.io/) - Large-scale in-the-wild manipulation dataset, 76k demonstrations across 564 scenes.

---

## 🧑‍🤝‍🧑 Community

> Learn, ask, meet. → [Browse community resources](community/README.md)

- [XLeRobot Docs](https://xlerobot.readthedocs.io) - Step-by-step build, assembly, software and simulation guides.
- [Seeed Studio Robotics Wiki](https://wiki.seeedstudio.com/robotics_page/) - Tutorials for reBot-DevArm, LeRobot integration and Isaac Sim.
- [Hugging Face LeRobot Hub](https://huggingface.co/lerobot) - Models, datasets and community spaces.

---

## 🤝 Contributing

Contributions are what make this list awesome. Adding a resource takes under two minutes:

1. Find the right folder and topic file in the [taxonomy](#%EF%B8%8F-taxonomy).
2. Add one line in the format `- [Name](url) - One-sentence description. 🏷️ tags`.
3. Open a pull request. That is it.

Read [CONTRIBUTING.md](CONTRIBUTING.md) for the full guidelines, or [open an issue](../../issues/new/choose) if you would rather we add it for you.

**Rules of the list:** open source only (code, CAD or both), actively maintained, and useful to someone other than its author.

---

## 📜 License

[Apache 2.0](LICENSE). Project names and descriptions belong to their respective authors.

<div align="center">

**If this list helped you, ⭐ star it and share it. Every star brings one more builder.**

</div>
