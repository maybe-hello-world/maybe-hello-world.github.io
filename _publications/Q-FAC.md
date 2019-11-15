---
title: "Optimizing Q-learning with K-FAC Algorithm"
collection: publications
permalink: /publication/qfac
excerpt: 'K-FAC (natural gradient descent approach) can be used for optimizing Q-learning algorithms and works rather well.'
date: 2019-12
venue: 'Analysis of Images, Social networks and Texts'
paperurl: 'https://maybe-hello-world.github.io/files/qfac.pdf'
citation: 'Roman Beltiukov. (2019). &quot;Optimizing Q-learning with K-FAC Algorithm.&quot; <i>Analysis of Images, Social networks and Texts</i>.'
---
In this work, we present intermediate results of the application of Kronecker-factored Approximate curvature (K-FAC) algorithm to Q-learning problem. Being more expensive to compute than plain stochastic gradient descent, K-FAC allows the agent to converge a bit faster in terms of epochs compared to Adam on simple reinforcement learning tasks and tend to be more stable and less strict to hyperparameters selection. Considering the latest results we show that DDQN with K-FAC learns more quickly than with other optimizers and improves constantly in contradiction to similar with Adam or RMSProp.

[Download paper here](https://maybe-hello-world.github.io/files/qfac.pdf)

Roman Beltiukov. (2019). "Optimizing Q-learning with K-FAC Algorithm." <i>Analysis of Images, Social networks and Texts</i>.
