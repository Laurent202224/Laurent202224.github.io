---
title: "Obstacle Avoidance With Ultrasonic Sensors on Nano Drones"
excerpt: "Bachelor thesis project implementing low-cost, lightweight obstacle avoidance on Crazyflie 2.1 with ToF + ultrasonic sensor fusion."
collection: portfolio
date: 2024-06-01
link: "https://github.com/Laurent202224/Bachelor-Thesis"
video: "https://www.youtube.com/watch?v=Nef4xX0PeBs"
role: "Bachelor thesis"
period: "February 2024 – June 2024"
---

For my bachelor thesis, I developed a lightweight obstacle avoidance algorithm for the Crazyflie 2.1 nano-drone, designed to operate under strict constraints in onboard computation and payload.

The system relies on only two forward-facing sensors: an 8×8 Time-of-Flight (ToF) sensor and an ultrasonic sensor. To ensure robust performance, I implemented a dynamic sensor fusion strategy that continuously adjusts the contribution of each sensor, allowing the drone to adapt to different environmental conditions while maintaining a computationally efficient navigation policy.

The resulting system was able to perform reliable obstacle avoidance in unknown indoor environments, achieving an overall success rate of 80%, including in the presence of transparent and reflective obstacles that are typically challenging for single-sensor approaches. It demonstrated stable performance at speeds of up to 1 m/s and achieved 100% success when navigating through a narrow 75 cm corridor, highlighting the effectiveness of combining complementary sensing modalities on a highly constrained platform.

This work resulted in a peer-reviewed [publication](/publication/2024-10-06-superbat/), which I presented as lead author at the 2024 IEEE International Symposium on Systems Engineering (ISSE) in Perugia, Italy.

[Github Code](https://github.com/Laurent202224/Bachelor-Thesis)

[Video](https://www.youtube.com/watch?v=Nef4xX0PeBs)
