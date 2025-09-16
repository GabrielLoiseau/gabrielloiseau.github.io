+++
title = "What Musical Knowledge Does Self-Attention Learn?"
description = "Gabriel Loiseau, Mikaela Keller, Louis Bigo"
[taxonomies]
tags = ["NLP4MusA2021"]
[extra]
accent_color = "#d85a28"
accent_color_dark = "#b66cb9"
+++

## Abstract

Since their conception for NLP tasks in 2017, Transformer neural networks have been increasingly used with compelling results for a
variety of symbolic MIR tasks including music analysis, classification and generation. Although the concept of self-attention between
words in text can intuitively be transposed as a relation between musical objects such as notes or chords in a score, it remains relatively unknown what kind of musical relations precisely tend to be captured by self attention mechanisms when applied to musical data. Moreover, the principle of self-attention
has been elaborated in NLP to help model the “meaning” of a sentence while in the musical domain this concept appears to be more subjective. In this explorative work, we open the music transformer black box looking to identify which aspects of music are actually learnt by the self-attention mechanism. We apply
this approach to two MIR probing tasks : composer classification and cadence identification.


## Cite

```
@inproceedings{loiseau-etal-2021-musical,
    title = "What Musical Knowledge Does Self-Attention Learn ?",
    author = "Loiseau, Gabriel  and
      Keller, Mikaela  and
      Bigo, Louis",
    editor = "Oramas, Sergio  and
      Epure, Elena  and
      Espinosa-Anke, Luis  and
      Jones, Rosie  and
      Quadrana, Massimo  and
      Sordo, Mohamed  and
      Watanabe, Kento",
    booktitle = "Proceedings of the 2nd Workshop on NLP for Music and Spoken Audio (NLP4MusA)",
    month = nov,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.nlp4musa-1.2/",
    pages = "6--10"
}
```