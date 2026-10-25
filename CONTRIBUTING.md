# Contributing to Awesome Robotics

Thank you for helping map the open source robotics world. This guide takes two minutes to read.

## What belongs here

A resource qualifies if **all** of the following are true:

- **Open source.** Code under an OSI-approved license, hardware under an open hardware license (CERN-OHL, TAPR, CC-BY-SA) or with freely available CAD and BOM. Closed products with an open SDK go in `software/middleware-and-control.md` as an SDK, not in `hardware/`.
- **Alive.** Maintained within the last 12 months, or clearly finished and still working.
- **Useful to strangers.** Someone who is not the author can build, run or learn from it.

We do **not** list: paywalled content, vaporware, hardware without published designs, or individual papers without code.

## Where it goes

Every resource lives in exactly one topic file. If it spans categories (LeRobot is hardware, software and datasets), put it where its primary value is and cross-link from other files with a short note.

| Folder | Topic file | Put here |
|---|---|---|
| `hardware/` | `arms.md` | Fixed-base manipulators, leader/follower arm pairs |
| | `mobile-robots.md` | Wheeled bases, mobile manipulators, rovers |
| | `humanoids-and-hands.md` | Humanoids, legged robots, dexterous hands, grippers |
| | `teleoperation.md` | Leader arms, VR/AR rigs, exoskeletons, data gloves, gamepad bridges |
| | `components.md` | Servos, BLDC actuators, motor drivers, control boards, cameras, tactile and depth sensors |
| `simulation/` | `simulators.md` | Physics engines, rendering platforms |
| | `environments-and-benchmarks.md` | Gym environments, task suites, evaluation benchmarks |
| | `robot-models.md` | URDF / MJCF / USD assets, digital twins |
| `software/` | `learning-frameworks.md` | Training pipelines for imitation learning, RL, VLA fine-tuning |
| | `policies-and-foundation-models.md` | Specific policy architectures, pretrained checkpoints, world models |
| | `middleware-and-control.md` | ROS, kinematics and dynamics, motion planning, hardware SDKs |
| `datasets/` | `README.md` | Robot datasets and data formats |
| `community/` | `README.md` | Courses, tutorials, books, chat servers, events, newsletters |

Need a new topic file? Propose it in an issue first so the taxonomy stays clean.

## Entry format

One line per resource. Copy this exactly:

```markdown
- [Name](https://link) - One sentence, present tense, ends with a period. 🏷️ tags
```

Rules:

- **Name** is the project's own name, not a slogan.
- **Link** points to the canonical source repo or docs. No shortlinks, no affiliate links, no tracking parameters.
- **Description** is one sentence under 160 characters. Say what it is and why someone would want it. No marketing adjectives ("revolutionary", "best-in-class").
- **Tags** are optional and come from the legend below. Order them as shown.
- Keep lists **alphabetical** within a section, unless the section is marked "featured".

### Tag legend

| Tag | Meaning |
|---|---|
| 🧩 | Works with [LeRobot](https://github.com/huggingface/lerobot) out of the box or via an official guide |
| 🖨️ | Primary structure is 3D-printable |
| 💵 | Complete build under $1,000 USD at time of listing |
| 🏠 | Designed for household environments |
| 🏭 | Industrial-grade specs (repeatability, payload, duty cycle) |

## Pull request checklist

- [ ] One resource per line, in the correct topic file
- [ ] Entry follows the format above and ends with a period
- [ ] Link works and points to the canonical source
- [ ] Not already listed (search the repo first)
- [ ] Alphabetical order preserved
- [ ] If adding a new section, it has at least 3 entries
- [ ] PR title: `Add <Name>` or `Update <Name>` or `Remove <Name>`

Small PRs merge fast. Batch at most five additions per PR.

## Removing or flagging

Found a dead link or an abandoned project? Open an issue with the label `stale` or send a PR that removes the line with a one-line reason in the description.

## Code of conduct

Be kind, be specific, assume good faith. Harassment of any kind results in removal from the project.
