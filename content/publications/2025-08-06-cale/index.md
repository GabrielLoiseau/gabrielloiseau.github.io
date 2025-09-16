+++
title = "CALE : Concept-Aligned Embeddings for Both Within-Lemma and Inter-Lemma Sense Differentiation"
description = "Bastien Liétard, Gabriel Loiseau"
[taxonomies]
tags = ["arXivPreprint"]
[extra]
accent_color = "#5c616a"
accent_color_dark = "#a4bac0"
+++

## Abstract

Lexical semantics is concerned with both the multiple senses a word can adopt in different contexts, and the semantic relations that exist between meanings of different words. To investigate them, Contextualized Language Models are a valuable tool that provides context-sensitive representations that can be used to investigate lexical meaning. Recent works like XL-LEXEME have leveraged the task of Word-in-Context to fine-tune them to get more semantically accurate representations, but Word-in-Context only compares occurrences of the same lemma, limiting the range of captured information. In this paper, we propose an extension, Concept Differentiation, to include inter-words scenarios. We provide a dataset for this task, derived from SemCor data. Then we fine-tune several representation models on this dataset. We call these models Concept-Aligned Embeddings (CALE). By challenging our models and other models on various lexical semantic tasks, we demonstrate that the proposed models provide efficient multi-purpose representations of lexical meaning that reach best performances in our experiments. We also show that CALE's fine-tuning brings valuable changes to the spatial organization of embeddings. 


## Cite

```
@misc{liétard2025caleconceptalignedembeddings,
      title={CALE : Concept-Aligned Embeddings for Both Within-Lemma and Inter-Lemma Sense Differentiation}, 
      author={Bastien Liétard and Gabriel Loiseau},
      year={2025},
      eprint={2508.04494},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2508.04494}, 
}
```