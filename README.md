# Awesome-General-Purpose-Robotics-Software-Layers

## Top General-Purpose Robotics Software Layers Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Robot Orchestration, Fleet Management & Hardware-Agnostic Control*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **General-Purpose Robotics Software Layers**. These tools provide hardware-agnostic operating systems, fleet orchestration, and skill abstraction—giving robots the ability to be assigned variable tasks without rewriting control code for each hardware platform.



**Examples** include InOrbit, Formant, Freedom Robotics, Foxglove, MOV.AI, SVT Robotics, Cogniteam Nimbus, Rocos, Apex.AI, and Polymath Robotics (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, ROS-native orchestration, and open fleet infrastructure—ideal for robotics engineers, integrators, and developers seeking transparent, vendor-independent robot software layers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[InOrbit](https://www.inorbit.ai/)**

  Cloud-based robot operations (RobOps) platform for managing heterogeneous robot fleets. Features real-time observability, mission control, incident response, and cross-vendor orchestration. **The leading vendor-neutral robot fleet management platform.**



- **[Formant](https://formant.io/)**

  Robotics data platform for fleet observability and operations. Features telemetry ingestion, incident detection, remote intervention, and data pipelines for autonomous systems.



- **[Freedom Robotics](https://www.freedomrobotics.com/)**

  Fleet management and remote operations platform for robots. Features real-time monitoring, teleoperation, data collection, and OTA updates across heterogeneous fleets.



- **[Foxglove](https://foxglove.dev/)**

  Robotics observability platform for visualizing and debugging ROS and non-ROS data. Features multi-modal data visualization, team collaboration, and cloud-based data management. **The standard debugging interface for ROS developers.**



- **[MOV.AI](https://mov.ai/)**

  Robotics engine platform providing a unified software stack for AMR development. Features visual programming, fleet management, and integration with existing automation infrastructure.



- **[SVT Robotics](https://svtrobotics.com/)**

  SOFTBOT Platform enabling rapid integration of heterogeneous robots and automation. Features no-code integration, pre-built connectors, and fleet orchestration across vendors.



- **[Cogniteam Nimbus](https://www.cogniteam.com/)**

  Cloud-based operating system for robot fleets. Features autonomous task planning, remote operations, and multi-robot coordination.



- **[Rocos](https://www.rocos.io/)**

  Cloud platform for robot fleet management and remote operations. Acquired by Rockwell Automation to expand robotics capabilities.



- **[Apex.AI](https://www.apex.ai/)**

  Production-grade autonomous mobility software. Features Apex.Grace (ROS 2-based) with automotive-grade safety certification, and Apex.Ida for autonomous driving. **The leading safety-certified ROS-based platform.**



- **[Polymath Robotics](https://polymathrobotics.com/)**

  Hardware-agnostic autonomy platform for industrial vehicles. Features terrain-aware navigation and safety systems deployable across vehicle types.



## Open-Source GitHub Projects



- **[ROS 2 (Robot Operating System 2)](https://github.com/ros2/ros2)**

  **The foundational open-source robotics middleware** (Apache-2.0). Provides hardware abstraction, message passing (DDS), lifecycle management, and a massive ecosystem of packages for navigation, perception, manipulation, and control. **The de facto standard for robotics software development** — most commercial robotics platforms build on or integrate with ROS 2.



- **[Foxglove Studio](https://github.com/foxglove/studio)**

  Open-source robotics visualization and debugging tool (MPL-2.0). **The most widely used open-source ROS data visualization platform.** Features multi-modal panels for 3D, image, plot, log, and raw message viewing. Supports ROS 1, ROS 2, and non-ROS data sources. Desktop app and web version available. **The open-source core of the Foxglove commercial platform.**



- **[Navigation2 (Nav2)](https://github.com/ros-navigation/navigation2)**

  Open-source navigation stack for ROS 2 (Apache-2.0). Features path planning, behavior trees, recovery behaviors, and multi-robot support. **The standard navigation framework for mobile robots** — used in most AMR deployments worldwide.



- **[MoveIt](https://github.com/ros-planning/moveit)**

  Open-source motion planning and manipulation framework (BSD-3-Clause). Features kinematic solvers, collision checking, trajectory optimization, and grasp planning. **The standard manipulation framework for ROS** — used across industrial, research, and service robots.



- **[Open-RMF (Robotics Middleware Framework)](https://github.com/open-rmf)**

  Open-source fleet management and interoperability framework (Apache-2.0) from Open Robotics (now Intrinsic). **The most comprehensive open-source fleet orchestration platform.** Enables heterogeneous robot fleets to share space and coordinate tasks. Features traffic management, task allocation, and building infrastructure integration. **Deployed in hospitals, airports, and logistics facilities worldwide.**



- **[OpenRMF / RMF Demos](https://github.com/open-rmf/rmf_demos)**

  Demonstration packages and reference implementations for Open-RMF. Includes hotel and airport scenarios with multiple robot types. **The best starting point for fleet orchestration projects.**



- **[Micro-ROS](https://github.com/micro-ROS/micro_ros_setup)**

  ROS 2 for microcontrollers (Apache-2.0). Brings ROS 2 to MCUs like ESP32, STM32, and Raspberry Pi Pico. **The most accessible entry point for hardware-level robot control.**



- **[Autoware](https://github.com/autowarefoundation/autoware)**

  Open-source autonomous driving stack built on ROS 2 (Apache-2.0). **The most comprehensive open-source autonomous vehicle software.** Features perception, localization, planning, and control for self-driving applications.



- **[Pixi / Colcon](https://github.com/prefix-dev/pixi)** and **[colcon](https://github.com/colcon/colcon-core)** — Package and build tools for ROS 2 development workflows.



- **[Gazebo / Ignition](https://github.com/gazebosim/gz-sim)**

  Open-source robotics simulator (Apache-2.0). **The most widely used open-source robot simulation platform.** Features physics simulation, sensor models, and ROS 2 integration.



### Additional Strong Open-Source Options



- **[Open-RMF Server](https://github.com/open-rmf/rmf_ros2)** — Core RMF server implementation for fleet coordination.

- **[TurtleBot4](https://github.com/turtlebot/turtlebot4)** — Open-source reference robot platform for ROS 2 development .

- **[MoveIt 2](https://github.com/ros-planning/moveit2)** — MoveIt for ROS 2 with improved architecture.

- **[Rviz2](https://github.com/ros2/rviz)** — 3D visualization tool for ROS 2 (BSD-3-Clause) .

- **[RQt](https://github.com/ros-visualization/rqt)** — Qt-based GUI framework for ROS 2 .

- **[PlotJuggler](https://github.com/facontidavide/PlotJuggler)** — Open-source time series visualization for robotics (MPL-2.0) .

- **[Fuse](https://github.com/locusrobotics/fuse)** — Sensor fusion framework for robot state estimation (BSD-3-Clause) .

- Community **n8n** workflows for robot fleet alert routing and mission orchestration automation.



**Frameworks for building custom systems**: Combine **ROS 2** for robotics middleware with **Nav2** for navigation, **MoveIt** for manipulation, **Open-RMF** for fleet orchestration, **Foxglove Studio** for debugging, and **Gazebo** for simulation—creating a fully self-hosted, enterprise-grade robotics software layer.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Robotics software layers controlling physical robots must comply with safety regulations (ISO 10218, ISO/TS 15066 for collaborative robots, ANSI/RIA R15.06) and implement rigorous safety validation before deployment.

- **Open-source robotics software is mature and production-grade.** ROS 2, Nav2, MoveIt, and Open-RMF are used in commercial deployments worldwide . **These are genuine alternatives to commercial robotics platforms.**

- **Open-RMF is the open-source fleet orchestration leader.** Enables heterogeneous robot fleets to share space and coordinate tasks—deployed in hospitals, airports, and logistics facilities worldwide . **This is the most comprehensive open-source alternative to InOrbit or Formant.**

- **Safety certification requires commercial support.** Apex.AI's Apex.Grace provides automotive-grade safety certification on ROS 2 . **Open-source ROS 2 alone is not safety-certified**—production deployments in safety-critical contexts require certified distributions and validation.

- Self-hosted open-source solutions require proper security hardening, DDS configuration, and ongoing maintenance. Robot fleets are physical systems—cybersecurity incidents can cause physical harm.



---



**Made for robotics engineers, integrators, and developers building transparent robot software layers.**

Let's make General-Purpose Robotics Software Layers more open, data-driven, and hardware-agnostic.
