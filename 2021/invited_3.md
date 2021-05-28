# Deep Learning Meets Optimal Control - How Optimal Control Enables Faster and Better Training

## Abstract
Deep learning has shown great promise for a variety of machine learning applications. However, many 
challenges associated with very deep networks remain to be solved, such as for example the scalability 
barrier created by serial forward and backward propagation where training runtimes increase linearly 
with the number of layers, the high dimensionality of the resulting learning problem, as well as the 
question of initialization of the network weights.
In this talk, we leverage recent advances in optimal control to address these challenges. In particular, 
a class of layer-parallel training methodologies is presented that enable concurrency across the 
network model. The approach is based on a continuous interpretation of deep residual learning as a 
problem of optimally controlling a continuous dynamical system, which will be summarized in the first 
part of the talk. Then, a parallel multigrid scheme is proposed that replaces the serial network 
propagation such that runtimes remain bounded when increasing network depth along with computational 
resources. The multigrid scheme further allows for coarse-grid representations of the training 
problem enabling effective initialization strategies. Advanced learning strategies such as 
simultaneous optimization algorithms and decoupled state and control discretization approaches 
drawn from optimal control will be discussed.

## Speaker Bio
* 2012 – Diploma (equiv. to masters degree) in Applied Mathematics and Computer Sciences, focus on 
numerical optimization, University of Trier, Germany
* 2017 – PhD in Applied Mathematics, RWTH Aachen University, Germany, topic: Simultaneous 
Optimization with Unsteady PDEs, applications to aerodynamic shape optimization/computational 
fluid dynamics
* 2018-2019 PostDoc at TU Kaiserslautern, Germany, focus on Parallel-in-Time integration and 
optimization methods for unsteady PDEs
* 2019-2020 PostDoc at Lawrence Livermore National Laboratory, Center for Applied Scientific Computing 
(CASC), Projects in Time-parallel optimal control for quantum computing
* 2020-now PostDoc Fellow under the Sidney Fernbach Fellowship at Lawrence Livermore National Lab 
(CASC): Scientific Machine Learning at Extreme Scale - Optimal Control for Deep Learning (and still 
optimal control for quantum computing)
