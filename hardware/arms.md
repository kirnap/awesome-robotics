# Robotic Arms

> Fixed-base manipulators and leader/follower pairs with published design files.

[← Hardware](README.md) · [← Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible · 🖨️ 3D-printable · 💵 Under $1,000 · 🏠 Household · 🏭 Industrial-grade

## Contents

- [Low-cost and 3D-printed](#low-cost-and-3d-printed)
- [Bimanual research rigs](#bimanual-research-rigs)
- [Higher-payload arms](#higher-payload-arms)

## Low-cost and 3D-printed

- [Koch v1.1](https://github.com/jess-moss/koch-v1-1) - 3D-printed Dynamixel leader/follower arm pair, one of the original LeRobot reference designs (Apache-2.0, design complete since 2024). 🧩 🖨️ 💵
- [Low-Cost Robot Arm](https://github.com/AlexanderKoch-Koch/low_cost_robot) - The original 3D-printed Dynamixel arm with BOM that Koch v1.1 descends from (MIT, design complete since 2024). 🖨️ 💵
- [OpenMANIPULATOR-X](https://github.com/ROBOTIS-GIT/open_manipulator) - ROBOTIS open-hardware 4-DOF Dynamixel arm with ROS 2 packages, supported by LeRobot as OMX (Apache-2.0). 🧩
- [SO-ARM100 / SO-101](https://github.com/TheRobotStudio/SO-ARM100) - Standard low-cost leader/follower arm pair of the LeRobot ecosystem, with STEP files, priced BOM and assembly guides (Apache-2.0). 🧩 🖨️ 💵
- [Thor](https://github.com/AngelLM/Thor) - 6-DOF stepper-driven 3D-printed arm with FreeCAD sources, STEP files, BOM and build guides (CC-BY-SA-4.0, design complete, last update 2025). 🖨️ 💵

## Bimanual research rigs

- [ALOHA](https://github.com/tonyzhaozh/aloha) - Stanford's bimanual teleoperation and imitation learning rig built from ViperX arms, the setup behind ACT (MIT, released 2023, no longer updated).
- [Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha) - ALOHA on a wheeled base for whole-body mobile manipulation from demonstrations (MIT, released 2024, no longer updated).

## Higher-payload arms

- [OpenArm](https://github.com/enactic/openarm) - 7-DOF backdrivable humanoid arm for contact-rich research with ROS 2, MuJoCo and LeRobot support (hardware CERN-OHL-S-2.0, software Apache-2.0). [Docs](https://docs.openarm.dev). 🧩
- [reBot-DevArm](https://github.com/Seeed-Projects/reBot-DevArm) - Seeed Studio 6-DOF + gripper arm (B601-DM, B601-RS) with ROS 1/2, LeRobot, Pinocchio and Isaac Sim support (hardware CERN-OHL-W-2.0, software Apache-2.0). [Docs](https://wiki.seeedstudio.com/robotics_page/). 🧩 🏭

## See also

- [Mobile robots](mobile-robots.md) for arms mounted on wheeled bases such as XLeRobot and LeKiwi.
- [Teleoperation](teleoperation.md) for GELLO and other demonstration-collection rigs.
- [Robot models](../simulation/robot-models.md) for URDF / MJCF / USD sources for the arms above.

---

*Know an open arm that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
