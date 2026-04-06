+++
title = "Distilling Human-Aligned Privacy Sensitivity Assessment from Large Language Models"
description = "Gabriel Loiseau, Damien Sileo, Damien Riquet, Maxime Meyer, Marc Tommasi"
[taxonomies]
tags = ["CALD-pseudo2026"]
[extra]
accent_color = "#d85a28"
accent_color_dark = "#b66cb9"
+++

## Abstract

Accurate privacy evaluation of textual data remains a critical challenge in privacy-preserving natural language processing. Recent work has shown that large language models (LLMs) can serve as reliable privacy evaluators, achieving strong agreement with human judgments; however, their computational cost and impracticality for processing sensitive data at scale limit real-world deployment. We address this gap by distilling the privacy assessment capabilities of Mistral Large 3 (675B) into lightweight encoder models with as few as 150M parameters. Leveraging a large-scale dataset of privacy-annotated texts spanning 10 diverse domains, we train efficient classifiers that preserve strong agreement with human annotations while dramatically reducing computational requirements. We validate our approach on human-annotated test data and demonstrate its practical utility as an evaluation metric for de-identification systems.


## Cite

```
@misc{loiseau2026distillinghumanalignedprivacysensitivity,
      title={Distilling Human-Aligned Privacy Sensitivity Assessment from Large Language Models}, 
      author={Gabriel Loiseau and Damien Sileo and Damien Riquet and Maxime Meyer and Marc Tommasi},
      year={2026},
      eprint={2603.29497},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2603.29497}, 
}
```
