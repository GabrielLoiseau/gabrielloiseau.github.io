+++
title = "Adaptive Text Anonymization: Learning Privacy-Utility Trade-offs via Prompt Optimization"
description = "Gabriel Loiseau, Damien Sileo, Damien Riquet, Maxime Meyer, Marc Tommasi"
[taxonomies]
tags = ["arXivPreprint"]
[extra]
accent_color = "#557273"
accent_color_dark = "#c0d2a5"
+++

## Abstract

Anonymizing textual documents is a highly context-sensitive problem: the appropriate balance between privacy protection and utility preservation varies with the data domain, privacy objectives, and downstream application. However, existing anonymization methods rely on static, manually designed strategies that lack the flexibility to adjust to diverse requirements and often fail to generalize across domains. We introduce adaptive text anonymization, a new task formulation in which anonymization strategies are automatically adapted to specific privacy-utility requirements. We propose a framework for task-specific prompt optimization that automatically constructs anonymization instructions for language models, enabling adaptation to different privacy goals, domains, and downstream usage patterns. To evaluate our approach, we present a benchmark spanning five datasets with diverse domains, privacy constraints, and utility objectives. Across all evaluated settings, our framework consistently achieves a better privacy-utility trade-off than existing baselines, while remaining computationally efficient and effective on open-source language models, with performance comparable to larger closed-source models. Additionally, we show that our method can discover novel anonymization strategies that explore different points along the privacy-utility trade-off frontier. 


## Cite

```
@misc{loiseau2026adaptivetextanonymizationlearning,
      title={Adaptive Text Anonymization: Learning Privacy-Utility Trade-offs via Prompt Optimization}, 
      author={Gabriel Loiseau and Damien Sileo and Damien Riquet and Maxime Meyer and Marc Tommasi},
      year={2026},
      eprint={2602.20743},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2602.20743}, 
}
```
