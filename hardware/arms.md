# Robotic Arms

> Fixed-base manipulators and leader/follower pairs with open designs.

[← Hardware](README.md) · [← Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible · 🖨️ 3D-printable · 💵 Under $1,000 · 🏠 Household · 🏭 Industrial-grade

## Contents

- [Low-cost and 3D-printed](#low-cost-and-3d-printed)
- [Bimanual research rigs](#bimanual-research-rigs)
- [Industrial-grade open arms](#industrial-grade-open-arms)
- [Humanoid-style arms](#humanoid-style-arms)

## Low-cost and 3D-printed

- [Dummy-Robot](https://github.com/peng-zhihui/Dummy-Robot) - Wildly popular 3D-printed 6-axis desktop arm with custom-designed servo drives and a full open mechanical and electronics stack. 🖨️ 💵
- [Koch v1.1](https://github.com/jess-moss/koch-v1-1) - Low-cost 3D-printed leader/follower arm, one of the original LeRobot reference designs. 🧩 🖨️ 💵
- [Low-Cost Robot Arm](https://github.com/AlexanderKoch-Koch/low_cost_robot) - The original 3D-printed Dynamixel arm that Koch v1.1 and much of the LeRobot hardware lineage descend from. 🧩 🖨️ 💵
- [OpenMANIPULATOR-X](https://github.com/ROBOTIS-GIT/open_manipulator) - ROBOTIS open-hardware 4-DOF Dynamixel arm with full ROS 2 support, listed as OMX in LeRobot. 🧩
- [SO-ARM100 / SO-101](https://github.com/TheRobotStudio/SO-ARM100) - The standard low-cost arm pair of the LeRobot ecosystem, powered by Feetech STS3215 servos, with full STEP files and assembly guides. 🧩 🖨️ 💵
- [Thor](https://github.com/AngelLM/Thor) - Long-running open 6-DOF 3D-printed arm with stepper motors, a classic of the maker robotics community. 🖨️ 💵

## Bimanual research rigs

- [ALOHA](https://github.com/tonyzhaozh/aloha) - Stanford's low-cost bimanual teleoperation and imitation learning rig with ViperX arms, the setup that popularized ACT.
- [Mobile ALOHA](https://github.com/MarkFzp/mobile-aloha) - ALOHA on a wheeled base for whole-body mobile manipulation from human demonstrations.

## Industrial-grade open arms

- [reBot-DevArm](https://github.com/Seeed-Projects/reBot-DevArm) - Seeed Studio's 100% open 6-DOF + gripper arm in two variants: B601-DM (Damiao motors, 1.5 kg payload, 767 mm reach, 24 V) and B601-RS (Robstride motors, 2.5 kg payload, 754 mm reach, 48 V), both with <0.2 mm repeatability, ROS 1/2, LeRobot, Pinocchio, Isaac Sim and a Python SDK. Hardware CERN-OHL-W-2.0, software Apache-2.0. [Docs](https://wiki.seeedstudio.com/robotics_page/). 🧩 🏭

## Humanoid-style arms

- [HopeJR](https://github.com/TheRobotStudio/HOPEJr) - Open humanoid arm and dexterous hand from The Robot Studio, supported by LeRobot. See also [humanoids-and-hands.md](humanoids-and-hands.md). 🧩 🖨️
- [OpenArm](https://github.com/enactic/OpenArm) - 7-DOF backdrivable humanoid arm from Enactic for contact-rich physical AI research, $6,500 for a full bimanual system. ROS 2 with ros2_control and MoveIt, MuJoCo models, LeRobot support, dora-rs teleop. Hardware CERN-OHL-S-2.0, software Apache-2.0. [Docs](https://docs.openarm.dev). 🧩

## See also

- [Mobile robots](mobile-robots.md) for arms mounted on wheeled bases such as XLeRobot and LeKiwi.
- [Teleoperation](teleoperation.md) for leader arms such as GELLO and other demonstration-collection rigs.
- [Robot models](../simulation/robot-models.md) for URDF / MJCF / USD files of the arms above.

---

*Know an open arm that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
