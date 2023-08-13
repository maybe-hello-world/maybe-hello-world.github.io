---
title: "In Search of netUnicorn: A Data-Collection Platform to Develop Generalizable ML Models for Network Security Problems"
collection: publications
permalink: /publications/netunicorn
excerpt: 'netUnicorn is a data-collection platform to develop generalizable ML models for network security problems.'
date: 2023-06-15
venue: 'arXiv preprint arXiv:2306.08853'
paperurl: 'https://arxiv.org/abs/2306.08853'
citation: 'Roman Beltiukov, Sanjay Chandrasekaran, Arpit Gupta, and Walter Willinger. 2023. PINOT: Programmable Infrastructure for Networking. In Proceedings of the Applied Networking Research Workshop (ANRW 23). Association for Computing Machinery, New York, NY, USA, 51–53. https://doi.org/10.1145/3606464.3606485'
---
The remarkable success of the use of machine learning-based solutions for network security problems has been impeded by the developed ML models' inability to maintain efficacy when used in different network environments exhibiting different network behaviors. This issue is commonly referred to as the generalizability problem of ML models. The community has recognized the critical role that training datasets play in this context and has developed various techniques to improve dataset curation to overcome this problem. Unfortunately, these methods are generally ill-suited or even counterproductive in the network security domain, where they often result in unrealistic or poor-quality datasets.

To address this issue, we propose an augmented ML pipeline that leverages explainable ML tools to guide the network data collection in an iterative fashion. To ensure the data's realism and quality, we require that the new datasets should be endogenously collected in this iterative process, thus advocating for a gradual removal of data-related problems to improve model generalizability. To realize this capability, we develop a data-collection platform, netUnicorn, that takes inspiration from the classic "hourglass" model and is implemented as its "thin waist" to simplify data collection for different learning problems from diverse network environments. The proposed system decouples data-collection intents from the deployment mechanisms and disaggregates these high-level intents into smaller reusable, self-contained tasks.

We demonstrate how netUnicorn simplifies collecting data for different learning problems from multiple network environments and how the proposed iterative data collection improves a model's generalizability.

## Citing

```bibtex
@misc{beltiukov2023search,
      title={In Search of netUnicorn: A Data-Collection Platform to Develop Generalizable ML Models for Network Security Problems}, 
      author={Roman Beltiukov and Wenbo Guo and Arpit Gupta and Walter Willinger},
      year={2023},
      eprint={2306.08853},
      archivePrefix={arXiv},
      primaryClass={cs.NI}
}
```
