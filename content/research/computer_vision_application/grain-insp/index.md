---
title: "Grain Quality Inspection"
weight: 10


subprojects:
- title: "GrainBrain: Multiview Identification and Stratification of Defective Grain Kernels" 
  img: "subtopics/grainbrain.png" 
  url: "https://ieeexplore.ieee.org/document/10858482"
  abstract: "Grain appearance inspection is crucial for evaluating grain quality and determining seed stratification. Typically, trained inspectors manually examine each grain kernel to identify and remove defective ones, which is time-consuming and error-prone. In this article, we present GrainBrain, a robotic vision-based system comprising a hardware prototype (A100) and a deep learning model (GrainAD). A100 is equipped with five cameras to capture high-quality, multiview images of each kernel. The identification of defective kernels is treated as an unsupervised anomaly detection task. GrainAD trains a classifier to distinguish between healthy and pseudoanomaly samples generated at both image and feature levels, and a supervised contrastive learning loss is employed to obtain compact feature representations of healthy kernels. In addition, we release a large-scale dataset containing over 100K annotated images of four types of cereal grains."

- title: "AV4GAInsp: An Efficient Dual-Camera System for Identifying Defective Kernels of Cereal Grains" 
  img: "subtopics/AV4GAInsp.png" 
  url: "https://ieeexplore.ieee.org/document/10336896"
  abstract: "Grain Appearance Inspection (GAI) is a pre-requisite for grain quality determination, providing guidance for grain processing, storage, and trade. GAI is routinely performed by trained inspectors who are required to visually inspect cereal grains for each individual kernel. Since grain kernels (e.g., wheat, rice) are tiny with heterogeneous shapes and appearance, manually performing GAI is time-consuming and error-prone. This letter presents a machine vision-based customization of an automated system for grain appearance inspection, called AV4GAInsp, which consists of a device and an analysis framework. The device is equipped with an elaborate feeding module and a capturing module for automatically pre-processing grain kernels and efficiently acquiring high-quality images for these kernels. The framework employs deep convolutional neural networks to process these captured images to classify the kernels as normal or defective. We also built and released a large-scale dataset, named GrainDet, that includes over 140K images for three types of grains: wheat, sorghum, and rice."
  
---
