---
layout: archive
title: "Courses"
permalink: /courses/
author_profile: true
---

## M.Sc. Robotics, Systems and Control, ETH Zurich

### Autumn Semester 2024

### Vision Algorithms for Mobile Robotics

This course provided a comprehensive introduction to computer vision methods for robotics applications, with a strong focus on visual perception and state estimation.

Key topics included:

- Camera models, perspective projection, and image formation
- Camera calibration (PnP)
- Image processing techniques such as filtering and edge detection
- Feature detection and description (Harris, SIFT) and feature matching
- Multiple-view geometry: rectification, epipolar constraints, disparity, triangulation
- Estimation methods: eight-point algorithm, P3P, RANSAC, bundle adjustment
- Optical flow and tracking (KLT tracker)
- Visual-inertial fusion and SLAM
- Event-based vision

The course was complemented by hands-on assignments, where these methods were implemented and applied to real-world robotics scenarios.

### Dynamic Programming and Optimal Control

This course focused on decision-making and control of dynamic systems using optimization-based approaches.

Key topics included:

- Infinite-horizon optimal control problems
- Value and policy iteration
- Deterministic systems and shortest path problems
- Continuous-time optimal control
- Bellman equation and dynamic programming algorithm
- Pontryagin's Minimum Principle

The theoretical concepts were reinforced through practical coding exercises, providing experience in solving optimal control problems computationally.

### Robot Dynamics

This course provided an in-depth understanding of the modeling and control of robotic systems, ranging from manipulators to aerial and legged robots.

The course covered:

- Kinematics and dynamics of rigid-body systems
- Rotations and angular velocity representations
- Transformations and multi-body system modeling
- Jacobians and inverse kinematics (differential and analytical)
- Kinematic and multi-task control methods
- Dynamic model-based control
- Floating-base dynamics and control
- Modeling and control of legged robots
- Modeling and control of rotorcraft (e.g., quadrotors, coaxial systems)
- Modeling and control of fixed-wing aircraft

The course emphasized both theoretical foundations and practical applications, with exercises accompanying each topic to develop hands-on experience in modeling and controlling robotic systems.

### Spring Semester 2025

### Computation Control

This course focused on modern control and decision-making algorithms, with an emphasis on learning-based and data-driven approaches.

Key topics included:

- Dynamic programming and Linear Quadratic Regulation (LQR)
- Model Predictive Control (MPC)
- Economic and robust MPC
- Data-driven predictive control (DeePC)
- Markov Decision Processes (MDPs)
- Monte Carlo methods
- Reinforcement learning (SARSA, Q-Learning)

All topics were accompanied by hands-on coding exercises.

Final project:

- Developed and compared three control strategies for traffic management using the SUMO simulator:
  - Model Predictive Control (MPC)
  - Data-Enabled Predictive Control (DeePC)
  - Temporal Predictive Control (TPC)
- Focus on performance, robustness, and scalability in realistic traffic scenarios.

### Model Predictive Control

This course provided an in-depth treatment of Model Predictive Control as an optimization-based control framework for constrained systems.

Key topics included:

- Foundations of optimal control and numerical optimization
- Receding-horizon control for linear systems
- Constraint handling and stability guarantees in MPC
- Tracking and offset-free control
- Soft constraints and practical implementation aspects
- Robust MPC and constraint satisfaction under uncertainty
- Tube MPC

The course combined theory with implementation exercises.

Final project:

- Designed and implemented an MPC controller for a multi-compartment refrigerated truck.
- Objective: regulate temperature across three compartments with external disturbances (ambient weather).

### Recursive Estimation

This course introduced probabilistic state estimation methods for dynamic systems.

Key topics included:

- Bayesian inference and Bayes’ theorem
- Bayesian filtering and tracking
- State estimation from probability distributions
- Kalman filter and its interpretation as a state observer
- Extended Kalman Filter (EKF)
- Particle filters
- Observer-based control and the separation principle

All concepts were reinforced through practical coding exercises, focusing on real-world estimation problems in robotics.

### Autonomous Mobile Robots

This course covered the fundamental principles required to design and build autonomous mobile robotic systems, with a strong emphasis on perception, localization, and navigation.

Key topics included:

- Robot kinematics and locomotion
- Rigid-body motion and control
- Perception: filtering, edge detection, feature extraction and matching
- Probabilistic state estimation (Kalman filtering)
- Simultaneous Localization and Mapping (SLAM)
- Global and local path planning
- Object detection and tracking

The course combined theoretical foundations with practical exercises on real robotic platforms, enabling hands-on experience in developing autonomous systems.

### Autumn Semester 2025

### Advanced Model Predictive Control

This course provided an in-depth exploration of advanced Model Predictive Control (MPC) techniques for uncertain and stochastic systems, with a strong focus on robustness and learning-based extensions.

Key topics included:

- Review of Bayesian statistics, stochastic systems, and stochastic optimal control
- Nominal MPC for uncertain systems (nominal robustness)
- Robust MPC formulations
- Stochastic MPC
- Set-membership system identification and robust data-driven MPC
- Bayesian regression and stochastic data-driven MPC
- MPC as a safety filter for reinforcement learning

The course combined theoretical foundations with practical coding exercises on each topic.

Final projects:

- Design and implementation of a nominal linear MPC controller
- Development of a robust MPC controller for uncertain systems
- Implementation of a robust learning-based MPC approach
- Design of an MPC-based safety filter

These projects provided hands-on experience in bridging classical control methods with modern data-driven and learning-based approaches.
