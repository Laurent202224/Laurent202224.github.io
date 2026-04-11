---
title: "Real-World Robotics: Versatile Visionaires"
excerpt: "Design and integration of a dexterous robotic hand on a Franka Emika arm with teleoperation and imitation learning." 
collection: portfolio
date: 2025-01-20
period: "September 2024 - January 2025"
---

In this project, we designed and built a robotic hand from scratch using Dynamixel motors and a spool-driven actuation system. After assembling the hand, we mounted it on a Franka Emika robotic arm and focused on developing the full software pipeline for dexterous manipulation.

To support development and testing, we used MuJoCo as our simulation environment. For human-to-robot control, we implemented a retargeting system based on motion-capture gloves, which enabled intuitive teleoperation of the robotic hand. On top of this, we built a complete teleoperation pipeline to collect demonstration data for imitation learning.

Using this setup, we recorded datasets containing both joint command trajectories and visual observations from two overhead cameras monitoring the scene. These demonstrations were then used to train an imitation learning policy based on a Transformer encoder.

The goal of the learned policy was to perform a color-based sorting task: cubes of different sizes were placed at varying positions in the workspace, and the robot had to pick them up and place them onto the correct track according to their color.

This project combined mechanical design, robot integration, teleoperation, simulation, dataset collection, and learning-based control into one complete real-world robotics system, and was developed in a team of seven people.

[Project Report]({{ base_path }}/files/Report_RWR/)

[Video](https://youtu.be/xAx0lqlHMjE)
