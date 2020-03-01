---
week: 12
title: Statistical Modeling- The Two Cultures
subtitle: ECCV 2014
hyperlink: http://www2.math.uu.se/~thulin/mm/breiman.pdf
tags: statistics
notes: week12-statistical-modeling-two-cultures.pdf
author: Jack Morris
layout: post
---

We took a break from machine learning papers to review our statistical
foundations. This paper discusses the tradeoffs between *data models* and
*algorithmic models* as seen by an eminent statistician. It parallels the
contrast between old-school statistical modeling algorithms and new-school
machine learning algorithms. Simplicity is sometimes better– when you value
interpretability over predictive accuracy. But if you want to minimize
predictive error, you're going to sacrifice some level of understanding.
The author discusses three principles of statistical models:

1. Rashomon: there will be many models that give about the same error on the test set
1. Occam: Simpler is better (or Einstein: as simple as possible, but no simpler)
1. Bellman: Dimensionality is a curse (or perhaps a blessing, to machine learnists)

These three principles encapsulate a lot of the important message from the paper.
He also gave good advice for anyone looking to fit a model to data: dive into the
data first. Spend some time perusing it and analyzing it – gain a real
understanding of your data before attempting to fit a model to it. Although
it was written in 2001, Breiman's manifesto provides messages that are just
as important in 2020.
