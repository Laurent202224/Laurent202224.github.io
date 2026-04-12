---
title: "Language-Guided Drone Control"
collection: portfolio
period: "February 2025 – June 2025"
---

In this project, I developed a system that enables a quadcopter to autonomously execute tasks specified through natural language commands. The approach is based on imitation learning, where a control policy maps multimodal inputs to continuous flight actions.

The system integrates three key input modalities: natural language instructions, the drone’s current state, and visual observations from an onboard camera. To process these inputs, I used vision-language models such as CLIP and ResNet to encode textual and visual information into a shared embedding space. These embeddings were then fused with the state representation and provided as input to the control policy.

The policy architecture consists of a three-layer multilayer perceptron (MLP) augmented with a transformer encoder to capture temporal dependencies. This combination enables the generation of smooth and consistent control commands, outputting continuous velocity signals for real-time quadcopter control.

The system achieved a success rate of 75% in simulation and 62.22% in real-world experiments, demonstrating robustness and the ability to generalize to previously unseen but semantically similar language inputs.

In addition, I explored the integration of the Language Behavioral Transformer (LangBeT), trained using a MinGPT-based framework with a k-means discretization of the action space.

Overall, this project demonstrates the potential of combining vision-language models with imitation learning to enable intuitive and flexible human-drone interaction.
 
[Project Report]({{ base_path }}/files/Language_Guided_Drone_Control_final_reduce_size/)

[Video](https://youtu.be/eHxgtxZ4PxI)
