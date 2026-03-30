---
title: "Rip Current Detection"
weight: 10


subprojects:
- title: "RipGAN: A GAN-Based Rip Current Data Augmentation Method" 
  img: "subtopics/ripgan.png" 
  url: "https://ieeexplore.ieee.org/document/11128547"
  abstract: "While it is intuitive to consider developing an automated rip current detection system to assist lifeguards in protecting beachgoers, rip current detection is in its infancy due to the lack of high-quality large-scale annotated rip current datasets. Also, the collection and annotation of rip current images require expert knowledge, which makes it more difficult to build datasets. So, this paper proposes a GAN-based rip current data augmentation method, RipGAN, to improve the performance of rip current detectors by increasing representative training data. To create new training images, RipGAN, has two branches. One is a texture generator that enriches the pattern and texture details of waves, making the image more realistic. The other is a rip generator based on FFFM-Unet. FFFM (Fast Fourier Fusion Module) uses Fast Fourier convolution to fuse the features from the low and the high layers, so as to further optimise the generated image. Furthermore, we trained Yolov8, YOLOv10, DINO and RT-DETR as rip current detectors to prove the effectiveness of RipGAN."

- title: "AIM 2025 Rip Current Segmentation (RipSeg) Challenge Report" 
  img: "subtopics/AIM 2025 Rip Current Segmentation.png" 
  url: "https://arxiv.org/abs/2508.13401"
  abstract: "This report presents an overview of the AIM 2025 RipSeg Challenge, a competition designed to advance techniques for automatic rip current segmentation in still images. Rip currents are dangerous, fast-moving flows that pose a major risk to beach safety worldwide, making accurate visual detection an important and underexplored research task. The challenge builds on RipVIS, the largest available rip current dataset, and focuses on single-class instance segmentation, where precise delineation is critical to fully capture the extent of rip currents. The dataset spans diverse locations, rip current types, and camera orientations, providing a realistic and challenging benchmark. In total,  75 participants registered for this first edition, resulting in 5 valid test submissions. Teams were evaluated on a composite score combining F1, F2, AP50, and AP[50:95]. This report outlines the dataset details, competition framework, evaluation metrics, and final results, providing insights into the current state of rip current segmentation. We conclude with a discussion of key challenges, lessons learned from the submissions, and future directions for expanding RipSeg."
  
---
