# A Surprisingly Simple yet Effective Multi-Query Rewriting Method for Conversational Passage Retrieval

This repository contains the code and data used to generate the results presented within the following the paper:

> I. Kostric and K. Balog. **A Surprisingly Simple yet Effective Multi-Query Rewriting Method for Conversational Passage Retrieval**. In: Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR '24). 2024. [[DOI: 10.1145/3626772.3657933](https://doi.org/10.1145/3626772.3657933)]

## Summary

Conversational passage retrieval is challenging as it often requires the resolution of references to previous utterances and needs to deal with the complexities of natural language, such as coreference and ellipsis.  To address these challenges, pre-trained sequence-to-sequence neural query rewriters are commonly used to generate a single de-contextualized query based on conversation history.

We propose the use of a neural query rewriter to generate multiple queries and show how to integrate those queries in the passage retrieval pipeline efficiently.  The main strength of our approach lies in its simplicity: it leverages how the beam search algorithm works and can produce multiple query rewrites at no additional cost.  We further show how to utilize multi-query rewrites in both sparse and dense first-pass retrieval and demonstrate that applying our approach on top of a standard passage retrieval pipeline delivers state-of-the-art performance without sacrificing efficiency.

## Repository Organization

This repository is structured as follows:

  - `data/`: TBD

## Citation

If you use this code or data, please cite the following paper:

```bibtex
@inproceedings{Kostric:2024:SIGIR,
  author = {Kostric, Ivica and Balog, Krisztian},
  title = {A Surprisingly Simple yet Effective Multi-Query Rewriting Method for Conversational Passage Retrieval},
  year = {2024},
  booktitle = {Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  pages = {2271–2275},
  series = {SIGIR '24}
}
```

## Contact

Should you have any questions, please contact Ivica Kostric at <ivica.kostric@uis.no>.
