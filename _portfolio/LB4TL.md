---
title: "LB4TL"
excerpt: "A novel and scalable smooth under approximation for STL quantitative semantics, with application to Neuro-symbolic training process for satisfying temporal specifications. Using LB4TL we can train feed-back inputs for recursive programs via backpropagation techniques to make it certain the output of the program satisfies a prescribed temporal property, when it runs recursively. The following figure shows the clear advantage of LB4TL comparing with the previous tools like STLCG. <br/><img src='/images/LB4TL_git.png'>"
collection: portfolio
---

The traditional robustness semantics for Temporal Logics is a recursive combination of min/max operations. In case we utilize this in a Neuro-symbolic algorithm for training proper inputs to satisfy temporal properties, it may result in failure due to non-differentiability issues. There was a couple of trials in the literature to propose a smooth approximation for this symbolic objective function in a Neuro-symbolic training process. I have provided the most scalable smooth approximation that enables us to handle more complex temporal tasks. The toolbox for this technique is available from [here](https://github.com/Navidhashemicodes/LB4TL)  . 
