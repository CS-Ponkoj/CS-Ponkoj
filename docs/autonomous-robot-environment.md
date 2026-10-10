# Autonomous Robot Environment

[Back to Projects](../projects.md) · [Back to README](../README.md)

A simulation-first MuJoCo environment for a differential-drive robot in a furnished office.

## What I Built

- Robot model with lidar, camera observations, and wheel encoders
- Office scenes with furniture, doorways, and dynamic cat obstacles
- Manual control, baseline navigation, and a Gymnasium interface
- Command-boundary safety intervention and navigation telemetry

## Status and Evaluation

The project supports local navigation experiments and controller development. A safety layer is an implemented mechanism, not a guarantee of collision-free operation. Simulation results do not establish physical-robot performance or observation-only autonomous navigation.

## Technology

Python, MuJoCo, Gymnasium, NumPy, Numba, Pygame, pytest.

## Evidence

- [Source repository](https://github.com/CS-Ponkoj/Autonomous-Robot-Environment)
- [Portfolio case study](https://ponkoj.com/case-studies/autonomous-robot-environment)
