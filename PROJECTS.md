# Project directory

[← Profile](README.md) · [Website & full publication list](https://yanjieze.com)

A curated map of the tools I build, research I coauthor, and contributions I make upstream. Research authorship and repository ownership are different: the links below point to the public project repositories, including those hosted by collaborators and organizations.

## Tools

| Project | Use it for | Availability |
| --- | --- | --- |
| [NodePeek](https://github.com/YanjieZe/NodePeek) | Monitor multiple Linux machines from a Mac: CPU, RAM, per-GPU metrics and connection diagnostics. | MIT; Apple Silicon macOS app. [Install with a coding agent](https://github.com/YanjieZe/NodePeek/blob/main/docs/AGENT_INSTALL.md). |
| [URDF Viewer](https://urdf-viewer.yanjieze.com) | Open, inspect and store robot models in a browser. | Web app listed on my [website](https://yanjieze.com/#tools). |
| [SR Papers](https://sr.yanjieze.com) | Explore *Science Robotics* robot learning papers by task, method and year. | Web index and [public source/data](https://github.com/YanjieZe/SR-Paper-List). |
| [GPU-Watcher](https://github.com/YanjieZe/GPU-Watcher) | Run `gpuwatch` for one or more remote SSH aliases. | Python terminal tool; repository labels it a development version. |

## Research

The projects below have public code repositories and list me as a first or equal-contribution author in their paper or project materials. This describes my research role, not sole ownership of every implementation. Full author lists, citations, installation requirements and release status live in the linked projects.

### Humanoids, motion and teleoperation

| Project | What is available | Research role |
| --- | --- | --- |
| [TWIST2](https://github.com/amazon-far/TWIST2) | Humanoid motion tracking, teleoperation and data collection. [Project](https://yanjieze.com/TWIST2). | First author; ICRA 2026 Oral. |
| [GMR](https://github.com/YanjieZe/GMR) | Human motion retargeting across multiple humanoid robots and motion sources. | Equal-contribution author; ICRA 2026. |
| [TWIST](https://github.com/YanjieZe/TWIST) | Motion data, teacher/student training, checkpoints and simulation/real-robot deployment. | Equal-contribution author; CoRL 2025. |
| [VisualMimic](https://github.com/visualmimic/VisualMimic) | Released simulation pipeline and checkpoints; see the repository's release checklist for remaining components. | Equal-contribution author; arXiv 2025. |
| [iDP3](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy) | Training and deployment for humanoid manipulation with 3D diffusion policies. | First author; IROS 2025 Oral. |
| [Humanoid Teleoperation](https://github.com/YanjieZe/Humanoid-Teleoperation) | Apple Vision Pro teleoperation and data collection, paired with iDP3. | Companion implementation to the same iDP3 research project. |

### Robot learning and representations

| Project | Focus | Research role |
| --- | --- | --- |
| [DP3](https://github.com/YanjieZe/3D-Diffusion-Policy) | 3D visual representations for diffusion-based imitation learning. | Equal-contribution author; RSS 2024 Oral. |
| [GNFactor](https://github.com/YanjieZe/GNFactor) | Generalizable neural feature fields for multi-task robot learning. | Equal-contribution author; CoRL 2023 Oral. |
| [H-InDex](https://github.com/YanjieZe/H-InDex) | Hand-informed representations for visual dexterous manipulation. | First author; NeurIPS 2023. |
| [RL3D](https://github.com/YanjieZe/rl3d) | Self-supervised 3D representations and view synthesis for visual RL. | Equal-contribution author; RA-L / IROS 2023. |
| [MoVie](https://github.com/yangsizhe/MoVie) | Visual model-based policy adaptation for view generalization. | Equal-contribution author; NeurIPS 2023. |
| [Learning from Scratch](https://github.com/gemcollector/learning-from-scratch) | Re-examining pre-training for visuomotor control. | Equal-contribution author; ICML 2023. |
| [SAM-G](https://github.com/wadiuvatzy/SAM-G) | Segment Anything for generalization in visual reinforcement learning. | Equal-contribution author; arXiv 2023. |
| [DPMAC](https://github.com/CANVOLCANO/DPMAC) | Differentially private communication for cooperative multi-agent RL. | Equal-contribution author; IJCAI 2023. |

For other coauthored work, including BEHAVIOR Robot Suite, EgoNav, ResMimic and X-Capture, see my [publication list](https://yanjieze.com/#publications).

## Reading & resources

- [Awesome Humanoid Robot Learning](https://github.com/YanjieZe/awesome-humanoid-robot-learning): humanoid learning papers and resources.
- [Paper List](https://github.com/YanjieZe/Paper-List): research reading lists organized by topic and conference.
- [SR-Paper-List](https://github.com/YanjieZe/SR-Paper-List): searchable literature index, structured data and verification notes.
- [SJTU Course Notes](https://github.com/YanjieZe/SJTU_Course_Notes): earlier computer science course notes.

## Playground

Public-facing experiments linked from my [personal website](https://yanjieze.com/#tools). A web demo is not a claim that its source code is open-source or that a simulation has been deployed on a physical robot.

| Demo | What to explore |
| --- | --- |
| [Robot Picasso](https://robot-picasso.yanjieze.com) | A robot hand drawing in physics simulation. |
| [Robot Cook](https://robot-cook.yanjieze.com) | Bimanual cooking simulation and free-view 3D replay. |
| [Dex Rubik’s Cube](https://dex-rubik-cube.yanjieze.com) | Contact-driven cube manipulation in MuJoCo, with replay controls. |
| [Diorama](https://diorama.yanjieze.com) | Code-generated 3D scenes with a humanoid. |

## Upstream contributions

Specific merged contributions, linked to the upstream projects:

| Project | Contribution | Evidence |
| --- | --- | --- |
| XRoboToolkit PC Service Python bindings | Expose whole-body motion capture through the Python binding. | [PR #2](https://github.com/XR-Robotics/XRoboToolkit-PC-Service-Pybind/pull/2) |
| XRoboToolkit PC Service Python bindings | Expose hand tracking activity state. | [PR #3](https://github.com/XR-Robotics/XRoboToolkit-PC-Service-Pybind/pull/3) |
| XRoboToolkit Orin Video Sender | Add ZMQ + TCP video streaming. | [PR #2](https://github.com/XR-Robotics/XRoboToolkit-Orin-Video-Sender/pull/2) |

## Keeping this directory useful

- Put a new public tool in **Tools**, with one sentence describing its purpose and a working installation or demo link.
- Keep **Selected research** in the profile short; add further projects to this directory.
- Attribute collaborative research and upstream patches explicitly. A fork alone is not evidence of authorship or contribution.
- Link web demos without exposing nonpublic source repositories or internal project details.
- Use each project's README for current requirements and release status; avoid hard-coded star counts here.
