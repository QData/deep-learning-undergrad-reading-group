---
week: 8
title: A Neural Algorithm of Artistic Style
subtitle: IEEE 2016
hyperlink: https://arxiv.org/abs/1508.06576
tags: style-transfer cnns art
notes: week08-style-transfer-morris.pdf
author: Jack Morris
layout: post
---
The style transfer paper is very unique in the ranks of seminal deep learning
papers. The authors are more active in neuroscience than in machine learning,
but showed the amazing results you can get when you apply knowledge about the
human brain to experiments on neural networks. The paper is also unique in its
readability: it contains one "Methods" section which explains the style transfer
loss function, but outside of that section, the paper is readable for almost
anyone that knows a thing or two about neural networks.

The chief contribution of this work is the fact that _the **style** and **content**
of an image are separable_. Even after they lay out the theoretical foundation,
this is the kind of thing where you really have to see it to believe it. We
talked about why this makes sense intuitively, how "style" and "content" vary
across deeper and deeper layers of the VGG CNN, and then we looked at examples
of both (1) isolating the content/style of an image and visualizing through
gradient descent and (2) combining the style of image A with the content of
image B. We think that these works of art are some of the most fascinating and
beautiful results ever produced in deep learning.
