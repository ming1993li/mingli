---
title: "RNN Training along Locally Optimal Trajectories via Frank-Wolfe Algorithm"
collection: publications
permalink: /publication/ICPR20_RNN
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2020-10-15
venue: "25th International Conference on Pattern Recognition"
paperurl: ""
citation: 'Yun Yue, <b>Ming Li</b>, Venkatesh Saligramay, Ziming Zhang. "RNN Training along Locally Optimal Trajectories via Frank-Wolfe Algorithm". <i>ICPR</i>. 2020.'
---
# RNN Training along Locally Optimal Trajectories via Frank-Wolfe Algorithm

[<a href="https://ming1993li.github.io/files/ICPR20_RNN.pdf">Paper</a>]

## Abstract
We propose a novel and efficient training method
for RNNs by iteratively seeking a local minima on the loss
surface within a small region, and leverage this directional
vector for the update, in an outer-loop. We propose to utilize
the Frank-Wolfe (FW) algorithm in this context. Although, FW
implicitly involves normalized gradients, which can lead to a
slow convergence rate, we develop a novel RNN training method
that, surprisingly, even with the additional cost, the overall
training cost is empirically observed to be lower than backpropagation. Our method leads to a new Frank-Wolfe method,
that is in essence an SGD algorithm with a restart scheme.
We prove that under certain conditions our algorithm has a
sublinear convergence rate of O(1=) for  error. We then conduct
empirical experiments on several benchmark datasets including
those that exhibit long-term dependencies, and show significant
performance improvement. We also experiment with deep RNN
architectures and show efficient training performance. Finally,
we demonstrate that our training method is robust to noisy data.
