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

- [Isaac GR00T](https://github.com/NVIDIA/Isaac-GR00T) - NVIDIA's open foundation model for generalist humanoid reasoning and skills. GR00T N1.7 is integrated into LeRobot. 🧩
- [Octo](https://github.com/octo-models/octo) - Berkeley's open generalist transformer policy pretrained on 800k Open X-Embodiment trajectories and designed for fast fine-tuning.
- [openpi (Pi0, Pi0.5)](https://github.com/Physical-Intelligence/openpi) - Open weights and training code for Physical Intelligence's VLA models. Pi0 and Pi0.5 are integrated into LeRobot. 🧩
- [OpenVLA](https://github.com/openvla/openvla) - 7B open-source vision-language-action model trained on Open X-Embodiment.
- [OpenVLA-OFT](https://github.com/moojink/openvla-oft) - Optimized fine-tuning recipe for OpenVLA with parallel decoding and action chunking, giving large gains in speed and success rate.
- [RDT-1B](https://github.com/thu-ml/RoboticsDiffusionTransformer) - Tsinghua's 1.2B-parameter diffusion transformer foundation model for bimanual manipulation.
- [SmolVLA](https://huggingface.co/lerobot/smolvla_base) - Hugging Face's compact VLA trained on community-contributed LeRobot datasets, designed to fine-tune and run on consumer GPUs. 🧩

## Imitation learning policies

- [3D Diffusion Policy](https://github.com/YanjieZe/3D-Diffusion-Policy) - Diffusion policy conditioned on compact 3D point-cloud representations for sample-efficient visuomotor learning.
- [ACT](https://github.com/tonyzhaozh/act) - Action Chunking with Transformers, the policy behind ALOHA and the most common first policy trained on SO-101 data. Integrated into LeRobot. 🧩
- [Diffusion Policy](https://github.com/real-stanford/diffusion_policy) - Visuomotor policy learning via action diffusion from Columbia and TRI. Integrated into LeRobot. 🧩
- [VQ-BeT](https://github.com/jayLEE0301/vq_bet_official) - Behavior transformer with vector-quantized action tokens for multimodal demonstrations. Integrated into LeRobot. 🧩

## Model-based RL

- [TD-MPC2](https://github.com/nicklashansen/tdmpc2) - Scalable model-based RL with implicit world models for continuous control. TDMPC is integrated into LeRobot. 🧩

## World models

- [NVIDIA Cosmos](https://github.com/NVIDIA/Cosmos) - World foundation models for physical AI that generate and predict video for synthetic data and policy evaluation.

## See also

- [Learning frameworks](learning-frameworks.md) for training and deploying these models.
- [Datasets](../datasets/README.md) for the data they were trained on.

---

*Know an open policy or model that belongs here? [Add it](../CONTRIBUTING.md) in one line.*
