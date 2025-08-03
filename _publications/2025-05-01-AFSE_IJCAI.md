---
title: "An Association-based Fusion Method for Speech Enhancement"
collection: publications
category: conferences
permalink: 2025-05-01-AFSE_IJCAI
excerpt: 'This paper is about fixing inter-frame association issue.'
date: 2025-05-01
venue: 'IJCAI'
paperurl: ''
citation: ''
---

Deep learning-based speech enhancement (SE) methods predominantly draw upon two architectural frameworks: generative adversarial networks and diffusion models. In the realm of SE, capturing the local and global relations between signal frames is crucial for the success of these methods. These frameworks typically employ a UNet as their foundational backbone, integrating Long Short-Term Memory (LSTM) networks or attention mechanisms within the UNet to effectively model both local and global signal relations. However, the coupled relation modeling way may not fully harness the potential of these relations. In this paper, we propose a novel, decoupled Association-based Fusion Speech Enhancement method (AFSE). AFSE first constructs a graph that encapsulates the association between each time window of the speech signal, and then models the global relations between frames by fusing the features of these time windows in a manner akin to graph neural networks. Furthermore, AFSE leverages a UNet with dilated convolutions to model the local relations, enabling the network to maintain a high-resolution representation while benefiting from a wider receptive field. Experimental results demonstrate that the AFSE method significantly improves performance in speech enhancement tasks, validating the effectiveness and superiority of our approach. The code is available at [https://github.com/jie019/AFSE_IJCAI2025](https://github.com/jie019/AFSE_IJCAI2025).
