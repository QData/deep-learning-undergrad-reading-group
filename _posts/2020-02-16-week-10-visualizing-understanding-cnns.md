---
week: 10
title: Visualizing and Understanding Convolutional Networks
subtitle: ECCV 2014
hyperlink: https://arxiv.org/abs/1311.2901
tags: nlp
notes: week10-visualizing-and-understanding-cnns.pdf
author: Jack Morris
layout: post
---
We chose this paper to give us context: this is a buoy in the sea of papers and
improvements in image recognition that took place after the 2012 ImageNet
challenge showed such remarkable improvements. This paper is easy to follow and
has a very appealing motivation: to *understand* what's going on in CNNs.

After discussing the methodology of this paper, we took a detour to learn about
[the ImageNet dataset](http://www.image-net.org/), looked at
an interesting [t-SNE of CNN codes](https://cs.stanford.edu/people/karpathy/cnnembed/)
from ImageNet images, and to read about the [guy who tried to memorize all the
ImageNet classes](http://karpathy.github.io/2014/09/02/what-i-learned-from-competing-against-a-convnet-on-imagenet/). We then returned to read the results and methodology. It
was especially interesting to us how the authors used their visualization tool
to debug a CNN: they changed the architecture to fix some inherent problems and,
in doing so, achieved the (at the time) top score in the world in the ImageNet
challenge. All in all, this is a really good paper for providing a lot of high-
level context about CNNs and the ImageNet challenge.
