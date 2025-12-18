---
title: "Histopathology Stain Normalisation"   #Required
weight: 10                         #Ignore this
icon: "topics/stainnorm.png"    # Ignore this
class: sn                       #Required, abbreviation
 

#Optional, list full name please, please only include related paper.           
papers:
  - title: "Texture Enhanced Generative Adversarial Network For Stain Normalisation In Histopathology Images"
    authors: "Cong Cong, Sidong Liu, Antonio Di Ieva, Maurice Pagnucco, Shlomo Berkovsky, Yang Song"
    venue: "2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI)"
    year: 2021
    url: "https://ieeexplore.ieee.org/abstract/document/9433860"
    
  - title: "Semi-supervised Adversarial Learning for Stain Normalisation in Histopathology Images"
    authors: "Cong Cong, Sidong Liu, Antonio Di Ieva, Maurice Pagnucco, Shlomo Berkovsky, Yang Song"
    venue: "International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)"
    year: 2021
    url: "https://link.springer.com/chapter/10.1007/978-3-030-87237-3_56"

  - title: "Colour adaptive generative networks for stain normalisation of histopathology images"
    authors: "Cong Cong, Sidong Liu, Antonio Di Ieva, Maurice Pagnucco, Shlomo Berkovsky, Yang Song"
    venue: "Medical Image Analysis"
    year: 2022
    url: "https://www.sciencedirect.com/science/article/pii/S1361841522002195"
---

Stain normalization aims to reduce colour and intensity variations in H&E-stained histopathology images that arise from differences in staining protocols, reagents, and scanners. These variations can seriously degrade the robustness and generalisability of downstream algorithms for classification, segmentation, and detection, especially in multi-centre settings. To address this challenge, we have proposed several deep learning–based stain normalization methods. Our earlier work (ISBI 2021) showed that using hematoxylin components as input can effectively enhance texture feature generation, leading to higher-quality stain-normalised outputs. Building on this, we developed a semi-supervised adversarial framework for stain normalization in histopathology images (MICCAI 2021) and later introduced the Colour Adaptive Generative Network (CAGAN) (MedIA 2022).

**Future Direction** Promising directions include extending stain normalization to multi-stain and multiplex settings, integrating normalization modules into large pathology foundation models, and jointly optimising stain-invariant representations with downstream tasks in a fully self-supervised or federated manner.



