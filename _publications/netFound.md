---
title: "netFound: Foundation Model for Network Security"
collection: publications
permalink: /publications/netfound
authors: 'Satyandra Guthula, Navya Battula, Roman Beltiukov, Wenbo Guo, Arpit Gupta'
excerpt: 'netFound is a foundation model for network traffic analysis'
date: 2023-10-25
venue: 'ArXiv'
paperurl: 'https://arxiv.org/abs/2310.17025'
citation: 'Guthula, S., Battula, N., Beltiukov, R., Guo, W., & Gupta, A. (2023). NetFound: Foundation Model for Network Security. ArXiv. /abs/2310.17025'
selected: false
---
In ML for network security, traditional workflows rely on high-quality labeled data and manual feature engineering, but limited datasets and human expertise hinder feature selection, leading to models struggling to capture crucial relationships and generalize effectively. Inspired by recent advancements in ML application domains like GPT-4 and Vision Transformers, we have developed netFound, a foundational model for network security. This model undergoes pre-training using self-supervised algorithms applied to readily available unlabeled network packet traces. netFound's design incorporates hierarchical and multi-modal attributes of network traffic, effectively capturing hidden networking contexts, including application logic, communication protocols, and network conditions.

With this pre-trained foundation in place, we can fine-tune netFound for a wide array of downstream tasks, even when dealing with low-quality, limited, and noisy labeled data. Our experiments demonstrate netFound's superiority over existing state-of-the-art ML-based solutions across three distinct network downstream tasks: traffic classification, network intrusion detection, and APT detection. Furthermore, we emphasize netFound's robustness against noisy and missing labels, as well as its ability to generalize across temporal variations and diverse network environments. Finally, through a series of ablation studies, we provide comprehensive insights into how our design choices enable netFound to more effectively capture hidden networking contexts, further solidifying its performance and utility in network security applications. 

## Citing

```bibtex
@misc{saty2023netfound,
    title={netFound: Foundation Model for Network Security},
    author={Satyandra Guthula and Navya Battula and Roman Beltiukov and Wenbo Guo and Arpit Gupta},
    year={2023},
    eprint={2310.17025},
    archivePrefix={arXiv},
    primaryClass={cs.NI}
}
```
