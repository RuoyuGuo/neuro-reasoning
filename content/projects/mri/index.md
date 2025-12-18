---
title: "Brain MRI analysis"   #Required
weight: 10                         #Ignore this
icon: "topics/mri.png"    # Ignore this
class: mri                        #Required, abbreviation
 

#Optional, list full name please, please only include related paper.           
papers:
  - title: "Hypergraph tversky-aware domain incremental learning for brain tumor segmentation with missing modalities"
    authors: "Junze Wang, Lei Fan, Weipeng Jing, Donglin Di, Yang Song, Sidong Liu, Cong Cong"
    venue: "International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)"
    year: 2025
    url: "https://link.springer.com/chapter/10.1007/978-3-032-05141-7_28"
---

Brain MRI analysis plays a central role in neuro-oncology, providing multi-sequence (e.g., T1, T2, FLAIR, T1ce) information for detecting and segmenting brain tumours and guiding treatment planning. However, real-world clinical workflows often face missing or incrementally acquired modalities, which can degrade segmentation performance and make retraining impractical. In our recent work (MICCAI 2025), we propose a domain-incremental framework that uses a replay buffer, a cross-patient hypergraph segmentation network, and a Tversky-aware contrastive loss to learn from newly available MRI modalities without forgetting previously learned ones and to better handle inter-modality imbalance. 

**Future Direction** Promising directions include extending extending this line of work to richer multimodal settings (e.g., combining MRI with clinical and genomic data, in line with our broader multimodal research) and ultimately developing brain MRI foundation models that can be continually adapted across institutions, protocols, and tasks while remaining robust to missing data and domain shifts.

