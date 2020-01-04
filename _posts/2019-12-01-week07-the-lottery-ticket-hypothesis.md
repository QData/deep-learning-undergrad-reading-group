---
week: 7
title: "The Lottery Ticket Hypothesis"
subtitle: ICLR 2018
hyperlink: https://arxiv.org/abs/1803.03635
date: 2019-12-01
tags: neural-networks optimization lottery-tickets iclr
notes: week07-the-lottery-ticket-hypothesis-morris.pdf
author: Jack Morris
layout: post
---
For our first academic paper reading as a group, we chose *The Lottery Ticket
Hypothesis: Finding Sparse, Trainable Neural Networks* by Frankle et al. We
chose this paper to try and make a smooth transition from neural networks
textbook to academic readings. *The Lottery Ticket Hypothesis* shows that neural
networks often contain small subnetworks ("lottery tickets") that can be trained
to match the accuracy of the larger, original network. They devise a method for
locating these small subnetworks, and show that they exist for a variety of
architectures with all different combinations of activation functions, dropout,
normalizations, etc.
