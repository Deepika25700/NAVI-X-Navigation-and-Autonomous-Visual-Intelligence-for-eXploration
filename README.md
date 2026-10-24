# NAVI-X: Navigation and Autonomous Visual Intelligence for eXploration

NAVI-X is a ROS 2–based autonomous UAV navigation project designed for GPS-denied environments. The system focuses on robust localization, path planning, and autonomous exploration using a lightweight and modular software stack. It is intended for drone platforms that need to navigate safely in environments where global positioning is unavailable or unreliable.

This project combines:
- GPS-denied navigation logic
- A* path planning
- ROS 2 integration
- Local autonomy for exploration and obstacle-aware motion
- Testable planner components for simulation and validation

## Overview

The project aims to enable a UAV to navigate and explore unknown or partially known areas without GPS. In such environments, the drone must rely on onboard sensing, motion estimation, and planning algorithms to safely move toward a target while avoiding obstacles and maintaining a valid trajectory.

The repository includes core components for:
- path planning
- mission orchestration
- launch configuration
- package setup for ROS 2
- unit testing for path-planning behavior

## Features

- GPS-denied autonomous navigation workflow
- A* path planning for obstacle-aware route generation
- ROS 2 package structure for deployment and simulation
- Modular design for future sensor fusion and navigation enhancements
- Unit tests for planner correctness and path validation
- Lightweight dependencies suitable for research and educational use

## Repository Structure

```text
.
├── README.md
├── LICENSE
├── __init__.py
├── astar_planner.py
├── gps_denied_navigation/
├── planner.launch.py
├── package.xml
├── requirements-dev.txt
├── setup.cfg
├── setup.py
├── test_astar_planner.py
├── testsuite.h
└── DEVELOPMENT_PLAN.md
