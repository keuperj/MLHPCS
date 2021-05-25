# MSM: Multi-Stage Multicuts forScalable Image Clustering

## Abstract
Correlation Clustering, also called the minimum cost multicut problem, is grouping data by pairwise similarities.
It has proven to be effective on clustering problems, where the number of classes is unknown.
However, not only is the multicut problem NP-hard, an undirected graph $G$ with $n$ vertices has at most $\frac{n(n-1)}{2}$ edges, thus making it challenging to implement correlation clustering for large datasets.
In this work, we propose Multi-Stage Multicuts (MSM) as a scalable approach for image clustering.
Specifically, we solve minimum cost multicut problems across multiple distributed compute units.
Our approach not only allows to solve problem instances which are too large to fit into the shared memory of a single compute node, but it also achieves significant speedups while preserving the clustering accuracy at the same time. We evaluate our proposed method on CIFAR10 and CelebA. Furthermore, we also provide the proof for the theorectical speedup.

## Speaker
Kalun Ho, Fraunhofer Center HPC, Kaiserslautern, Germany.
