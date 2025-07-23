---
layout: post
title:  "How Modern Optimization Techniques Balance Learning in Deep Neural Networks"
date:   2025-07-22
categories: meetings
---

In this talk, Atli Kosson presented the Balanced Learning Hypothesis: the principle that efficient neural 
network training requires maintaining similar rates of representational change across network components and 
throughout the training process. He demonstrated how this principle underlies many of our most successful 
optimization practices, with a focus on weight decay and learning rate warmup. Through this lens, we gain 
new insights into longstanding puzzles, such as why AdamW outperforms Adam with L2 regularization and why 
GPT training is so dependent on learning rate warmup. Finally, he showed how these insights enable us to 
design optimizers that explicitly balance learning, reducing our reliance on indirect mechanisms and empirical 
hacks. This discussion was based on the ICML 2024 paper 
["Rotational Equilibrium: How Weight Decay Balances Learning Across Neural Networks"](https://arxiv.org/pdf/2305.17212) 
and NeurIPS 2024 paper ["Analyzing & Reducing the Need for Learning Rate Warmup in GPT Training"](https://arxiv.org/pdf/2410.23922).

Presentation can be found [here](https://drive.google.com/file/d/1pTtCekNJ5Ws7bB86k5oqnHgrIxq7uM9n/view?usp=sharing).