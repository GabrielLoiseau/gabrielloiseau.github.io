+++
title = "TAROT: Task-Oriented Authorship Obfuscation Using Policy Optimization Methods"
description = "Gabriel Loiseau, Damien Sileo, Damien Riquet, Maxime Meyer, Marc Tommasi"
[taxonomies]
tags = ["PrivateNLP2025"]
[extra]
accent_color = "#e14775"
accent_color_dark = "#ff6188"
+++

## Abstract

Authorship obfuscation aims to disguise the identity of an author within a text by altering the writing style, vocabulary, syntax, and other linguistic features associated with the text author. This alteration needs to balance privacy and utility. While strong obfuscation techniques can effectively hide the author’s identity, they often degrade the quality and usefulness of the text for its intended purpose. Conversely, maintaining high utility tends to provide insufficient privacy, making it easier for an adversary to de-anonymize the author. Thus, achieving an optimal trade-off between these two conflicting objectives is crucial. In this paper, we propose **TAROT**: **T**ask-Oriented **A**utho**r**ship **O**bfuscation Using Policy Op**t**imization, a new unsupervised authorship obfuscation method whose goal is to optimize the privacy-utility trade-off by regenerating the entire text considering its downstream utility. Our approach leverages policy optimization as a fine-tuning paradigm over small language models in order to rewrite texts by preserving author identity and downstream task utility. We show that our approach largely reduces the accuracy of attackers while preserving utility. We make our code and models publicly available.


## Cite

```
@inproceedings{loiseau-etal-2025-tarot,
    title = "{TAROT}: Task-Oriented Authorship Obfuscation Using Policy Optimization Methods",
    author = "Loiseau, Gabriel  and
      Sileo, Damien  and
      Riquet, Damien  and
      Meyer, Maxime  and
      Tommasi, Marc",
    editor = "Habernal, Ivan  and
      Ghanavati, Sepideh  and
      Jain, Vijayanta  and
      Igamberdiev, Timour  and
      Wilson, Shomir",
    booktitle = "Proceedings of the Sixth Workshop on Privacy in Natural Language Processing",
    month = apr,
    year = "2025",
    address = "Albuquerque, New Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.privatenlp-main.2/",
    doi = "10.18653/v1/2025.privatenlp-main.2",
    pages = "14--31",
    ISBN = "979-8-89176-246-6"
}
```