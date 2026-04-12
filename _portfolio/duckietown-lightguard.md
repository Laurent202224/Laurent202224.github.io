---
title: "Duckietown — LightGuard"
excerpt: "Autonomous navigation system for a Duckiebot in a miniature urban environment with traffic lights."
collection: portfolio
date: 2025-01-15
period: "September 2024 – January 2025"
---

In this project, we developed an autonomous navigation system for a Duckiebot operating in a miniature urban environment with traffic lights. The objective was to enable the robot to drive safely and reliably while adhering to common traffic rules.

The system was built using a modular architecture combining perception and decision-making components:

- Lane Following:
  - Implemented a vision-based lane following module to ensure stable navigation within the road boundaries.
- Traffic Light Detection:
  - Developed a traffic light detection system capable of identifying the light color, its spatial region, and its form to avoid false positives from similarly colored objects.
- Stop Line Detection:
  - Designed a stop line detector to detect red stop lines and estimate their distance using computer vision methods, enabling precise stopping behavior at intersections.
- Efficient Perception Strategy:
  - Due to limited onboard computation, we optimized the pipeline by using QR codes placed near street signs. These acted as triggers to activate traffic light and stop line detection only when necessary, significantly reducing computational load.
- Decision-Making (State Machine):
  - Integrated all modules into a central controller implemented as a state machine, ensuring robust and reliable behavior across different traffic scenarios.

The complete system architecture is illustrated in the accompanying figure.

This project was carried out in a team of three. My primary contributions were the development of the stop line detection module and the design and implementation of the main control architecture.

[Project Report]({{ base_path }}/files/Final_Report_Gracefulcookingcoco/)

[Video](https://youtu.be/un-Aq-yJrJQ)
