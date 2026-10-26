# Policies and Foundation Models

> Policy architectures, pretrained checkpoints, vision-language-action models and world models.

[← Software](README.md) · [← Awesome Robotics](../README.md)

**Legend:** 🧩 LeRobot-compatible

## Contents

- [Vision-language-action models](#vision-language-action-models)
- [Imitation learning policies](#imitation-learning-policies)
- [Model-based RL](#model-based-rl)
- [World models](#world-models)

## Vision-language-action models

- [Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T) - NVIDIA's foundation model for generalist humanoid skills, integrated into LeRobot as GR00T N1.7; code Apache-2.0, weights under a noncommercial NVIDIA license. 🧩
- [Octo](https://github.com/octo-models/octo) - Berkeley generalist transformer policy pretrained on 800k Open X-Embodiment trajectories; code and checkpoints MIT, released 2024 and no longer updated.
- [openpi (Pi0, Pi0.5)](https://github.com/Physical-Intelligence/openpi) - Open weights and training code for Physical Intelligence's VLA models, integrated into LeRobot (Apache-2.0). 🧩
- [OpenVLA](https://github.com/openvla/openvla) - 7B vision-language-action model trained on Open X-Embodiment with open weights (MIT).
- [OpenVLA-OFT](https://github.com/moojink/openvla-oft) - Optimized fine-tuning recipe for OpenVLA with parallel decoding and action chunking; code and LIBERO checkpoints MIT, last update 2025.
- [RDT-1B](https://github.com/thu-ml/RoboticsDiffusionTransformer) - Tsinghua's 1.2B-parameter diffusion transformer foundation model for bimanual manipulation (MIT).
- [SmolVLA](https://huggingface.co/lerobot/smolvla_base) - Hugging Face's 0.5B-parameter VLA trained on community LeRobot datasets and designed for consumer GPUs (Apache-2.0). 🧩

## Imitation learning policies

- [3D Diffusion Policy](https://github.com/YanjieZe/3D-Diffusion-Policy) - Diffusion policy conditioned on compact 3D point-cloud representations for sample-efficient visuomotor learning (MIT).
- [ACT](https://github.com/tonyzhaozh/act) - Action Chunking with Transformers, the policy behind ALOHA and a common first policy for SO-101 data; integrated into LeRobot (MIT, released 2023). 🧩
- [Diffusion Policy](https://github.com/real-stanford/diffusion_policy) - Visuomotor policy learning via action diffusion from Columbia and TRI; integrated into LeRobot (MIT). 🧩
- [VQ-BeT](https://github.com/jayLEE0301/vq_bet_official) - Behavior transformer with vector-quantized action tokens for multimodal demonstrations; integrated into LeRobot (MIT, released 2024). 🧩

## Model-based RL

- [TD-MPC2](https://github.com/nicklashansen/tdmpc2) - Scalable model-based RL with implicit world models for continuous control; TDMPC is integrated into LeRobot (MIT). 🧩

## World models

- [NVIDIA Cosmos](https://github.com/NVIDIA/cosmos) - World foundation models for physical AI that generate and predict video for synthetic data and policy evaluation (OpenMDW-1.1).

## See also

- [Learning frameworks](learning-frameworks.md) for training and deploying these models.
- [Datasets](../datasets/README.md) for the data they were trained on.

---

*Know an open policy or model that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
