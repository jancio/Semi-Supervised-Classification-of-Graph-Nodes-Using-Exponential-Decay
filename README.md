# Semi-supervised classification of graph nodes using exponential decay

In this project I propose a new approach (MLPλ) to incorporate relationships between graph nodes
in a semi-supervised classification problem, using the multilayer perceptron model. In particular,
new features of a node are calculated as a sum of contributions from all other nodes exponentially
weighted by their shortest path distance from the node. I also investigated the effect of various
feature scaling methods and determined the optimal decay parameter λ for given datasets.

The proposed method was evaluated on three citation networks (Cora, Citeseer, PubMed ) and
compared to the baseline multilayer perceptron (when training examples were treated as independent)
and other previous studies. The results show that my approach reaches the performance of most
earlier methods, however, it falls behind the recent success of Graph Convolutional Networks (GCNs)
or Graph Attention Networks (GATs).
