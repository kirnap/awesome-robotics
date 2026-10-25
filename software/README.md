# 🧠 Software

> Frameworks, models and middleware that make robots move and learn.

[← Back to Awesome Robotics](../README.md)

## Topics

| File | What you will find |
|---|---|
| [learning-frameworks.md](learning-frameworks.md) | End-to-end pipelines for imitation learning, RL and VLA fine-tuning |
| [policies-and-foundation-models.md](policies-and-foundation-models.md) | Policy architectures, pretrained checkpoints, world models |
| [middleware-and-control.md](middleware-and-control.md) | ROS, kinematics and dynamics, motion planning, hardware SDKs, visualization |
| [perception.md](perception.md) | Pose estimation, grasp detection and other perception models for manipulation |

## The open stack at a glance

```
  Teleop / datasets  ──▶  LeRobot (train)  ──▶  Policy (ACT, Diffusion, SmolVLA, Pi0, GR00T)
                                                        │
          ROS 2 / Pinocchio / SDK  ◀──  Deploy  ◀───────┘
                     │
        SO-101 · XLeRobot · reBot-DevArm · your robot
```

## Contributing

Add one line per resource in the right topic file. See [CONTRIBUTING.md](../CONTRIBUTING.md).
