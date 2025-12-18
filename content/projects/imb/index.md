---
title: "Class Imbalanced Learning"   #Required
weight: 10                         #Ignore this
icon: "topics/imbalance.png"    # Ignore this
class: imbalance                       #Required, abbreviation
 

#Optional, list full name please, please only include related paper.           
papers:
  - title: "Imbalanced histopathology image classification using deep feature graph attention network"
    authors: "Cong Cong, Yixing Yang, Sidong Liu, Maurice Pagnucco, Yang Song"
    venue: "2022 IEEE 19th International Symposium on Biomedical Imaging (ISBI)"
    year: 2022
    url: "https://ieeexplore.ieee.org/abstract/document/9761619"
    
  - title: "Decoupled Optimisation for Long-Tailed Visual Recognition"
    authors: "Cong Cong, Shiyu Xuan, Sidong Liu, Shiliang Zhang, Maurice Pagnucco, Yang Song"
    venue: "Proceedings of the AAAI conference on artificial intelligence (AAAI)"
    year: 2024
    url: "https://ojs.aaai.org/index.php/AAAI/article/view/27902"

  - title: "Adaptive unified contrastive learning with graph-based feature aggregator for imbalanced medical image classification"
    authors: "Cong Cong, Sidong Liu, Priyanka Rana, Maurice Pagnucco, Antonio Di Ieva, Shlomo Berkovsky, Yang Song"
    venue: "Expert Systems with Applications"
    year: 2024
    url: "https://www.sciencedirect.com/science/article/pii/S0957417424006493"
---

Class-imbalanced and long-tailed learning focus on scenarios where some classes have many samples while others have very few. Standard deep networks tend to overfit majority classes and under-represent rare but clinically important categories, leading to biased decision boundaries and poor minority-class performance. Our contributions span both medical and natural image domains. In medical imaging, we propose imbalance-aware methods such as a deep feature graph attention network for histopathology (ISBI 2022), which models patch–patch relationships to better capture minority patterns, and adaptive unified contrastive learning with graph-based feature aggregation (ESWA), which reweights contrastive objectives to reduce majority-class bias. In the natural image domain, we develop a decoupled optimisation framework (AAAI 2024) for long-tailed recognition that separates and optimises different parameter groups with tailored objectives, significantly improving performance across head, medium, and tail classes.

**Future Direction** Promising directions include extending our imbalance-aware methods to multi-modal and federated settings, integrating them with large-scale vision/foundation models, and developing automatic, data-centric strategies (e.g., adaptive augmentation or reweighting) that can handle long-tailed distributions with minimal manual tuning.


