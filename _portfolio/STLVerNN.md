---
title: "STLVerNN"
excerpt: "We generated the first deterministic formal verification framework for Signal Temporal logics in collaboration with research scientists of Toyota Research Institute North of America (TRINA) STLVerNN. This repository addresses software verification and verifies a program satisfies a general temporal task when it starts from an unknown but bounded initial state. <br/><img src='/images/STL2NN.png'>"
collection: portfolio
---

The deterministic verification for a general STL specification was an open question before this research. In this toolbox we have shown we can conver the problem of verification for STL to the problem of neural network reachability analysis for ReLU activation function. Our verification framework is available from [here](https://github.com/Navidhashemicodes/STLVerNN) . We convert the quantitative semantics of [STL](https://www.sciencedirect.com/science/article/pii/S0304397509004149) to a symbolic ReLU neural network that exactly represents it. Then we use our computation map called STL2NN for neural network reachability analysis.
