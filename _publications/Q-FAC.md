---
title: "Optimizing Q-learning with K-FAC Algorithm"
collection: publications
permalink: /publication/qfac
excerpt: 'K-FAC (natural gradient descent approach) can be used for optimizing Q-learning algorithms and works rather well.'
date: 2019-12-01
venue: 'Analysis of Images, Social networks and Texts'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-39575-9_1'
citation: 'Beltiukov R. (2020) Optimizing Q-Learning with K-FAC Algorithm. In: van der Aalst W. et al. (eds) Analysis of Images, Social Networks and Texts. AIST 2019. Communications in Computer and Information Science, vol 1086. Springer, Cham'
---
In this work, we present intermediate results of the application of Kronecker-factored Approximate curvature (K-FAC) algorithm to Q-learning problem. Being more expensive to compute than plain stochastic gradient descent, K-FAC allows the agent to converge a bit faster in terms of epochs compared to Adam on simple reinforcement learning tasks and tend to be more stable and less strict to hyperparameters selection. Considering the latest results we show that DDQN with K-FAC learns more quickly than with other optimizers and improves constantly in contradiction to similar with Adam or RMSProp.

[Download paper here](https://maybe-hello-world.github.io/files/qfac.pdf)

## Citing:
```
@InProceedings{
    10.1007/978-3-030-39575-9_1,
    author="Beltiukov, Roman",
    title="Optimizing Q-Learning with K-FAC Algorithm",
    booktitle="Analysis of Images, Social Networks and Texts",
    year="2020",
    publisher="Springer International Publishing",
    address="Cham",
    pages="3--8",
    isbn="978-3-030-39575-9"
}
```
