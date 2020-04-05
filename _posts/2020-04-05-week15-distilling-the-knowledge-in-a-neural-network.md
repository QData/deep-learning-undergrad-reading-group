---
week: 15
title: Distilling the Knowledge in a Neural Network
subtitle: NeurIPS 2014
hyperlink: https://arxiv.org/abs/1503.02531
tags: distillation
notes: week15-distilling-the-knowledge-in-a-neural-network-ivey.pdf
author: Kevin Ivey
layout: post
---
We chose this paper as it describes the foundations of network compression, a deperature from some of the previous papers we've read that are more domain-specific. The approach that the authors used addresses what knowledge is in a neural network. The authors found that training a small, distilled network, on the soft targets of a larger ensemble network allows for the distilled netowork to have the same "knowledge" as the large network. This method of compression allows for easier to deploy networks without the cost of lost knowledge.  
