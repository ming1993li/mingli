---
title: "TreeRNN: Topology-Preserving Deep Graph Embedding and Learning"
collection: publications
permalink: /publication/ICPR20_TreeRNN
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2020-10-15
venue: "25th International Conference on Pattern Recognition"
paperurl: ""
citation: 'Yecheng Lyu, <b>Ming Li</b>, Xinming Huang, Ulkuhan Guler, Patrick Schaumont, and Ziming Zhang. "TreeRNN: Topology-Preserving Deep Graph Embedding and Learning". <i>ICPR</i>. 2020.'
---
# TreeRNN: Topology-Preserving Deep Graph Embedding and Learning

[<a href="https://ming1993li.github.io/files/ICPR20_TreeRNN.pdf">Paper</a>]

## Abstract
General graphs are difficult for learning due to their
irregular structures. Existing works employ message passing
along graph edges to extract local patterns using customized
graph kernels, but few of them are effective for the integration
of such local patterns into global features. In contrast, in this
paper we study the methods to transfer the graphs into trees so
that explicit orders are learned to direct the feature integration
from local to global. To this end, we apply the breadth first search
(BFS) to construct trees from the graphs, which adds direction
to the graph edges from the center node to the peripheral
nodes. In addition, we proposed a novel projection scheme that
transfer the trees to image representations, which is suitable for
conventional convolution neural networks (CNNs) and recurrent
neural networks (RNNs). To best learn the patterns from the
graph-tree-images, we propose TreeRNN, a 2D RNN architecture
that recurrently integrates the image pixels by rows and columns
to help classify the graph categories. We evaluate the proposed
method on several graph classification datasets, and manage to
demonstrate comparable accuracy with the state-of-the-art on
MUTAG, PTC-MR and NCI1 datasets.
