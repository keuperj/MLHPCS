# Analysis of Black-box Optimization Algorithms to Tune TensorFlow's CPU Backend

## Abstract
Many deep learning (DL) applications are typically built using DL frameworks
such as TensorFlow. Unfortunately, these frameworks are complex and obtaining
good training or inference performance of a model on a target hardware could be
difficult for a typical user --- these frameworks typically provide
user-controllable knobs that can be tuned to obtain good performance. Such
tuning, however, requires good understanding of the framework and the underlying
hardware, making it difficult for a typical user (DL developer or data
scientist) to obtain good performance for their application. In this paper, we
explore applicability of Bayesian optimization, genetic algorithm and
Nelder-Mead simplex algorithm to tune performance of TensorFlow's CPU backend.
While prior work has explored applicability of Nelder-Mead simplex algorithm for
this problem, there is no systematic comparative analysis of these algorithms,
making it harder to understand the applicability of these algorithms beyond the
selected set of models. We perform detailed comparative analysis of these
algorithms. Our findings reveal that Bayesian optimization typically performs
the best on the majority of the models. There are, however, cases where it does
not deliver the best results.

## Speaker
Niranjan Hasabnis, Intel
