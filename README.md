# Shakthibala Sivagami Balamurugan

**Perception · State estimation · Robot learning**<br>
M.S. Robotics Engineering, Worcester Polytechnic Institute · Expected May 2027 · Massachusetts, USA

[Portfolio](https://shakthi-bala.github.io/) · [LinkedIn](https://www.linkedin.com/in/shakthi-bala/) · [Email](mailto:shakthibala2004@gmail.com)

I’m a student researcher at PeAR Lab, WPI, building lightweight perception for flapping-wing robots. My projects cover visual-inertial estimation, occupancy forecasting, learned manipulation, and reproducible research software.

## Selected projects

Project names link to code; the write-ups include implementation choices, evaluation conditions, demos, and reproduction instructions.

| Project                                                                                                     | Core tools                              | Result / evidence                                                                                                                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------- | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Stereo VIO](https://github.com/Shakthi-Bala/Classical_vio/tree/cpp)                                        | C++17 · ROS 2 · Eigen · Ceres           | **0.156 m mean ATE** across all 11 EuRoC sequences, with SE3 alignment and loop closure disabled. [Write-up](https://shakthi-bala.github.io/projects/stereo-vio/)                                                                      |
| [4D occupancy world model](https://github.com/Shakthi-Bala/4D_occupancy_world_model_for_autonomous_driving) | PyTorch · Transformers · SE(2) geometry | **41.92 mIoU; 42% fewer obstacle collisions** versus the imitation prior in **open-loop** planning with ground-truth past occupancy. [Write-up](https://shakthi-bala.github.io/projects/occupancy-world-model/)                        |
| [UR5e imitation learning](https://github.com/Shakthi-Bala/imitation_learning_agent)                         | PyTorch · MuJoCo · Flow matching · PPO  | PPO reduced low-coverage failures from **11.4% to 6.4%** on 500 matched simulated starts, with similar observed full-solve rates. [Write-up](https://shakthi-bala.github.io/projects/imitation-learning/)                              |
| [DeepVIO](https://github.com/Shakthi-Bala/Deep_vio)                                                         | PyTorch · ResNet-18 · BiLSTM · FiLM     | Team comparison on synthetic test data: **1.5 m ATE for ResNet-18 vision-only** versus 3.5 m for two-stage FiLM fusion. [Write-up](https://shakthi-bala.github.io/projects/deep-vio/)                                                  |
| [Gap navigation](https://github.com/Shakthi-Bala/Navigating_through_unknown-Vizflyt)                        | Python · RAFT · OpenCV                  | A continuous **34-second rendered navigation sequence** showing RGB views, optical-flow detections, and passage through an irregular opening. [Demo & write-up](https://shakthi-bala.github.io/projects/gap-navigation/#project-demo)  |
| [DevResearchFlow](https://github.com/Shakthi-Bala/DevResearchFlow/tree/dev)                                 | Python · JSON Schema · Git · CI         | A CLI for reviewed protocols and captured experiment evidence. The v0.3.0 validation reports **88 passing tests** and **84% combined statement/branch coverage**. [Write-up](https://shakthi-bala.github.io/projects/devresearchflow/) |

[Browse all projects](https://shakthi-bala.github.io/work/) · [Technical notes](https://shakthi-bala.github.io/writing/)

## Research

**PeAR Lab, WPI — Student Researcher** · Jan 2026–present<br>
Advisor: Prof. Nitin Sanket

- Developing **ThermalUSFusionNet**, a FiLM-conditioned encoder–decoder for metric depth and uncertainty up to 7 m from thermal images and ultrasonic A-scans.
- Built a **24 g sensing package for a 148 g flapping-wing MAV** and deployed the stack on a **Raspberry Pi Zero 2W at 18 Hz**.
- Evaluated across 10+ indoor/outdoor sites, including tests with acrylic, aluminum foil, and matte black surfaces; the work targets navigation in degraded visibility.

**MER Lab, WPI — Student Researcher** · Aug–Dec 2025<br>
Advisor: Prof. Berk Calli

- Benchmarked classical and learned grasping methods across **1,000+ grasp attempts**, using simulation and real-world data.
- Developed ensemble grasp selection and failure-analysis tools to distinguish perception errors from execution failures.

Questions I’m working on:

- How can explicit geometry improve learned world models?
- How should uncertainty influence perception-driven planning?
- What keeps localization working when visual tracking deteriorates?

Previously at DManD Lab, SUTD; our team earned **2nd Runner-Up in ICRA 2025 Simulation Sorting**. [Experience →](https://shakthi-bala.github.io/about/#experience)

Away from robotics: [photography](https://shakthi-bala.github.io/photography/), chess, books, and films with a good plot.
