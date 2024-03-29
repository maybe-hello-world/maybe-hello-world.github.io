---
title: "In Search of netUnicorn: A Data-Collection Platform to Develop Generalizable ML Models for Network Security Problems"
collection: publications
permalink: /publications/netunicorn
excerpt: 'netUnicorn is a data-collection platform to develop generalizable ML models for network security problems.'
date: 2023-11-26
venue: 'Proceedings of the 2023 ACM SIGSAC Conference on Computer and Communications Security (CCS ’23)'
projecturl: 'https://netunicorn.cs.ucsb.edu'
authors: 'Roman Beltiukov, Wenbo Guo, Arpit Gupta, Walter Willinger'
paperurl: 'https://dl.acm.org/doi/10.1145/3576915.3623075'
citation: 'Roman Beltiukov, Wenbo Guo, Arpit Gupta, and Walter Willinger. 2023. In Search of netUnicorn: A Data-Collection Platform to Develop Generalizable ML Models for Network Security Problems: https://netunicorn.cs.ucsb.edu. In Proceedings of the 2023 ACM SIGSAC Conference on Computer and Communications Security (CCS ’23), November 26–30, 2023, Copenhagen, Denmark. ACM, New York, NY, USA,  https://doi.org/10.1145/3576915.3623075'
selected: true
---
The remarkable success of the use of machine learning-based solutions for network security problems has been impeded by the developed ML models' inability to maintain efficacy when used in different network environments exhibiting different network behaviors. This issue is commonly referred to as the generalizability problem of ML models. The community has recognized the critical role that training datasets play in this context and has developed various techniques to improve dataset curation to overcome this problem. Unfortunately, these methods are generally ill-suited or even counterproductive in the network security domain, where they often result in unrealistic or poor-quality datasets.

To address this issue, we propose an augmented ML pipeline that leverages explainable ML tools to guide the network data collection in an iterative fashion. To ensure the data's realism and quality, we require that the new datasets should be endogenously collected in this iterative process, thus advocating for a gradual removal of data-related problems to improve model generalizability. To realize this capability, we develop a data-collection platform, netUnicorn, that takes inspiration from the classic "hourglass" model and is implemented as its "thin waist" to simplify data collection for different learning problems from diverse network environments. The proposed system decouples data-collection intents from the deployment mechanisms and disaggregates these high-level intents into smaller reusable, self-contained tasks.

We demonstrate how netUnicorn simplifies collecting data for different learning problems from multiple network environments and how the proposed iterative data collection improves a model's generalizability.

## Citing

```bibtex
@inproceedings{10.1145/3576915.3623075,
      author = {Beltiukov, Roman and Guo, Wenbo and Gupta, Arpit and Willinger, Walter},
      title = {In Search of NetUnicorn: A Data-Collection Platform to Develop Generalizable ML Models for Network Security Problems},
      year = {2023},
      isbn = {9798400700507},
      publisher = {Association for Computing Machinery},
      address = {New York, NY, USA},
      url = {https://doi.org/10.1145/3576915.3623075},
      doi = {10.1145/3576915.3623075},
      booktitle = {Proceedings of the 2023 ACM SIGSAC Conference on Computer and Communications Security},
      pages = {2217–2231},
      numpages = {15},
      keywords = {machine learning, generalizability, artificial intelligence, network security, data collection},
      location = {<conf-loc>, <city>Copenhagen</city>, <country>Denmark</country>, </conf-loc>},
      series = {CCS '23}
}
```
