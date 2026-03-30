---
title: "Trajectory Prediction"
weight: 10


subprojects:
- title: "Fully Decoupling Trajectory and Scene Encoding for Lightweight Heatmap-Oriented Trajectory Prediction" 
  img: "subtopics/Fully Decoupling Trajectory and Scene.png" 
  url: "https://ieeexplore.ieee.org/document/10592624"
  abstract: "To align the image and trajectory information in pedestrian trajectory prediction, existing heatmap-oriented methods centre the scene images to agents' last observed locations or convert trajectory sequences into images. Such alignment processes cause repetitive executions of the scene encoder for each pedestrian in an input image, thus leading to significant memory consumption. In this letter, we address this problem by fully decoupling scene and trajectory feature extractions so that the scene information is only encoded once for an input image regardless of the number of pedestrians in the image. To do this, we directly extract temporal information from trajectories in a global pixel coordinate system. Then, we propose a transformer-based heatmap decoder to model the complex interaction between high-level trajectory and image features via trajectory self-attention, trajectory-to-image cross-attention and image-to-trajectory cross-attention layers. We also introduce scene counterfactual learning to alleviate the over-focusing on the trajectory features and knowledge transfer from Segment Anything Model to simplify the training."

- title: "HyperTraj: Towards Simple and Fast Scene-Compliant Endpoint Conditioned Trajectory Prediction" 
  img: "subtopics/HyperTraj.png" 
  url: "https://ieeexplore.ieee.org/document/10341647"
  abstract: "An important task in trajectory prediction is to model the uncertainty of agents' motions, which requires the system to propose multiple plausible future trajectories for agents based on their past movements. Recently, many approaches have been developed following an endpointconditioned deep learning framework by firstly predicting the distribution of endpoints, then sampling endpoints from it and finally completing their waypoints. However, this framework suffers a severe efficiency issue as it needs to repeatedly execute a separate decoder conditioned on multiple sampled endpoints. In this work, we propose a simple and fast endpoint conditioned fully convolutional trajectory prediction framework, called HyperTraj, by using dynamic convolutions to generate multiple trajectories, with the main benefits that (1) our prediction is conditioned on endpoint but takes almost constant time when the number of goals increases and (2) our model benefits from convolutional based predictions, such as the acceptance of various scene sizes and better modeling of agent-scene interactions."
  
---
