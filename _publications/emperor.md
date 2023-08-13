---
title: "AI/ML and Network Security: The Emperor has no Clothes"
date: 2022-11-07
authors: 'A. S. Jacobs, R. Beltiukov, W. Willinger, R. A. Ferreira, A. Gupta, L. Z. Granville'
venue: "CCS '22: Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security"
paperurl: 'https://dl.acm.org/doi/10.1145/3548606.3560609'
collection: publications
permalink: /publications/emperor
excerpt: 'We show that many published ML models in networking are prone to spurious correlations problems and how to fix it.'
---
In this paper, we focus on synthesizing high-fidelity and low-complexity decision trees to help network operators determine if their ML models suffer from the problem of underspecification. To this end, we present TRUSTEE, a framework that takes an existing ML model and training dataset as input and generates a high-fidelity, easy-to-interpret decision tree and associated trust report as output. Using published ML models that are fully reproducible, we
show how practitioners can use TRUSTEE to identify three common instances of model underspecification; i.e., evidence of shortcut learning, presence of spurious correlations, and vulnerability to out-of-distribution samples.

[Download paper here](https://github.com/TrusteeML/emperor/blob/main/docs/tech-report.pdf)

## Citing

```bibtex
@inproceedings{Jacobs2022,
  title        = {AI/ML and Network Security: The Emperor has no Clothes},
  author       = {A. S. Jacobs and R. Beltiukov and W. Willinger and R. A. Ferreira and A. Gupta and L. Z. Granville},
  year         = 2022,
  booktitle    = {Proceedings of the 2022 ACM SIGSAC Conference on Computer and Communications Security},
  location     = {Los Angeles, CA, USA},
  publisher    = {Association for Computing Machinery},
  address      = {New York, NY, USA},
  series       = {CCS '22}
}
```
