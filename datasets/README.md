# 📦 Datasets

> Open robot data and the formats that make it shareable.

[← Back to Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible

## Contents

- [Formats](#formats)
- [Large-scale datasets](#large-scale-datasets)
- [Community datasets](#community-datasets)

## Formats

- [LeRobotDataset](https://huggingface.co/docs/lerobot/lerobot-dataset-v3) - Hugging Face's format for training data: synchronized MP4 video plus Parquet state and action tables, versioned and hosted on the Hub (Apache-2.0). 🧩
- [MCAP](https://github.com/foxglove/mcap) - Container format and libraries for logging timestamped robot messages, the default rosbag2 storage since ROS 2 Iron; for logs, not training datasets (MIT).

## Large-scale datasets

- [AgiBot World](https://github.com/OpenDriveLab/AgiBot-World) - Manipulation data from 100 AgiBot robots across 100+ scenarios, from 100k trajectories in the Alpha release (data CC BY-NC-SA 4.0, noncommercial).
- [BridgeData V2](https://rail-berkeley.github.io/bridgedata/) - 53k language-annotated trajectories on a WidowX arm across 24 environments, a core pretraining set for Octo and OpenVLA (CC BY 4.0).
- [DROID](https://droid-dataset.github.io/) - 76k in-the-wild manipulation demonstrations across 564 scenes and 86 tasks, distributed via TensorFlow Datasets; no license stated on the project site.
- [Open X-Embodiment](https://robotics-transformer-x.github.io/) - Over one million real robot trajectories spanning 22 embodiments, the training corpus behind RT-X and OpenVLA; licenses vary by contributing dataset.
- [RH20T](https://rh20t.github.io/) - 110k contact-rich manipulation sequences with force-torque and multi-view video; one subset CC BY-SA 4.0, the other noncommercial.
- [RoboMIND](https://x-humanoid-robomind.github.io/) - 107k demonstrations across 479 tasks on Franka, UR5e, AgileX dual-arm and humanoid platforms (Apache-2.0 on Hugging Face).

## Community datasets

- [Hugging Face LeRobot Hub](https://huggingface.co/lerobot) - Thousands of community-recorded SO-100, SO-101, LeKiwi and XLeRobot datasets in LeRobotDataset format, searchable and streamable. 🧩

## See also

- [Learning frameworks](../software/learning-frameworks.md) for training on these datasets.
- [Teleoperation](../hardware/teleoperation.md) for collecting your own.

---

*Know an open dataset that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
