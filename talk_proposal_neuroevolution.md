# Talk Proposal Template

## General

### Submission Title

Topology and Weight Evolving Neural Networks: An Exploration of the Semantic Learning Machine Algorithm

### Submission Type

Talk (30 min.)

### Abstract

This talk introduces the Semantic Learning Machine, a topology and weight evolving artificial neural network algorithm that can search over unimodal error landscapes for any supervised learning problem.

### Description

In deep learning, well-established training algorithms, such as Backpropagation, aim to optimize the network’s weights on a predefined topology, rather than enhancing topology and weights simultaneously. Instead, this is usually dealt with by searching over a grid of potential topologies, until a satisfying configuration is found. This traditional approach is slow and ineffective, as it does not guarantee to converge close to the global optima.

We propose an alternative solution: the Semantic Learning Machine (SLM), a recently introduced stochastic neural network construction algorithm. SLM is derived from Geometric Semantic Genetic Programming (GSGP), which implies that it searches over unimodal error landscapes in any supervised learning problem. This means that, with the exception of the global optimum, every point in the search space has at least one neighbor with better fitness, and that neighbor is reachable through the application of the variation operators.

In this presentation, we compare SLM with popular machine learning algorithms, such as Backpropagation on different topologies and the NeuroEvolution of Augmenting Topologies (NEAT) algorithm, on several real-world regression and classification datasets. The results show that the best SLM variants generally outperform the other neuroevolution approaches in terms of generalization achieved, while also being more efficient in learning the training data. The best SLM variants also outperform the common Backpropagation-based approach under different topologies. The most efficient SLM variant used in combination with a recently proposed semantic stopping criterion is capable of evolving competitive neural networks in a few seconds on the vast majority of the datasets considered.

### Notes

This presentation is a summary of my Master thesis research work at Nova IMS, which got published at the Genetic and Evolutionary Computation Conference (GECCO) 2018.
The paper can be found here: https://dl.acm.org/citation.cfm?id=3205778
This work was developed in cooperation with my supervisors Mauro Castelli and Ivo Goncalves.
The implementation is 100% open-source and can be found here: https://github.com/janjagusch/pythonic-learning-machine. I will also refactor the code this summer, so that this implementation is compatible with Scikit-Learn.

### Don't record this talk

No

### Additional Speaker

## Questions

### Domains

Artificial Intelligence, Algorithms, Deep Learning, Data Science, Networks, Machine Learning

### Domain Expertise

Some

### Python Skill Level

Some

### Link to talk slides

https://docs.google.com/presentation/d/1ioqxn4N-9sh2wD5ijVehVzhki_dM1s8uR9wNt59JpFw/edit?usp=sharing

### Abstract as a tweet

How to evolve topology and weights of neural networks? Find out at Jan's talk about the Semantic Learning Machine.

### Public link to supporting material



### Notes for reviewers only

