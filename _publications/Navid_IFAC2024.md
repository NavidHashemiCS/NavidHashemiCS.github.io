---
title: "LB4TL: A Smooth Semantics for Temporal Logic to Train Neural Feedback Controllers."
collection: publications
permalink: /publication/Navid_IFAC2024
excerpt: ''
date: 2024-07-01
venue: 'IFAC-PapersOnline'
paperurl: 'https://doi.org/10.1016/j.ifacol.2024.07.445'
citation: 'Hashemi, Navid, Samuel Williams, Bardh Hoxha, Danil Prokhorov, Georgios Fainekos, and Jyotirmoy Deshmukh. "LB4TL: A smooth semantics for temporal logic to train neural feedback controllers." IFAC-PapersOnLine 58, no. 11 (2024): 183-188.'
---

This paper presents a novel and scalable smooth under approximation for STL quantitative semantics, with application to Neuro-symbolic training process for satisfying temporal specifications. Using LB4TL we can train feed-back inputs for recursive programs via backpropagation techniques to make it certain the output of the program satisfies a prescribed temporal property, when it runs recursively. The traditional robustness semantics for Temporal Logics is a recursive combination of min/max operations. In case we utilize this in a Neuro-symbolic algorithm for training proper inputs to satisfy temporal properties, it may result in failure due to non-differentiability issues. There was a couple of trials in the literature to propose a smooth approximation for this symbolic objective function in a Neuro-symbolic training process. We have provided the most scalable smooth approximation that enables us to handle more complex temporal tasks.
