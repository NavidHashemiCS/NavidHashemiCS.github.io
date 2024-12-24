---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![Neurosymbolic AI introduction](/images/Neurosymbolic AI.jpg){: .align-right width="300px"}

I hold a Ph.D and M.Sc in Computer Science from the University of Southern California School of Engineering (USC-Viterbi). Over my Ph.D and M.Sc I was working on the intersection of Artificial Intelligence and Temporal Logics, a new area that is known as Neuro-symbolic AI. I was researching on Neuro-symbolic learning algorithms with an application on program synthesis and model based reinforcement learning (MBRL). I was also working on software verification and also verification of neuro controller trained with MBRL, to verify satisfaction of temporal specifications when the program or system starts from an unknown but bounded initial condition. 

# Selected Experience

## Open Source Contribution
We generated the first deterministic formal verification framework for Signal Temporal logics in collaboration with research scientists of Toyota Research Institute North of America (TRINA) [STLVerNN](https://github.com/Navidhashemicodes/STLVerNN). This repository addresses software verification and verifies a program satisfies a general temporal task when it starts from an unknown but bounded initial state.

We scaled the Neuro-symbolic learning algorithms to provide satisfaction for long horizon temporal specifications. Please visit our open source toolbox [STL_dropout](https://github.com/Navidhashemicodes/STL_dropout) for this purpose. This was achieved by involving [stochastic depth](https://arxiv.org/abs/1603.09382) (firstly proposed for ResNet) in a Neuro-symbolic learning algorithm when the symbolic part is defined over a long horizon.

We extended one of the most popular recent techniques for robustness analysis of neural networks ( [LipSDP](https://proceedings.neurips.cc/paper/2019/hash/95e1533eb1b20a97777749fb94fdb944-Abstract.html) ) that provides  guarantees on its Lipstchitz constant. We enhanced this technique and provided tight and computationally efficient guarantees for **local** Lipschitz constants. We called this open source contribution [Local-LipSDP](https://github.com/NavidHashemiControl/Local_LipSDP_L4DC_2021). This technique significantly enhances the accuracy and scalability of robustness analysis for neural networks. We successfully applied this technique to the MNIST dataset to efficiently estimate the maximum level of uncertainty the model can tolerate on an image while still maintaining accurate classification.

Please feel free to visit my [github](https://github.com/Navidhashemicodes) repository for my other open source contributions.
