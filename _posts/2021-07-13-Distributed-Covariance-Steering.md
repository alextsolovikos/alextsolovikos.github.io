---
layout: post
title: Distributed Covariance Steering with Consensus ADMM for Stochastic Multi-Agent Systems | Robotics: Science and Systems 2021
categories: Research
---

In collaboration with A. Saravanos and E. Theodorou at Georgia Tech. Presented at Robotics: Science and Systems 2021

In this paper, we address the problem of steering a team of agents under stochastic linear dynamics to prescribed final state means and covariances. The agents operate in a common environment where inter-agent constraints may also be present. In order for our method to be scalable to large- scale systems and computationally efficient, we approach the problem in a distributed control framework using the Alter- nating Direction Method of Multipliers (ADMM). Each agent solves its own covariance steering problem in parallel, while additional copy variables for its closest neighbors are introduced to ensure that the inter-agent constraints will be satisfied. The inclusion of these additional variables creates a requirement for consensus between original and copy variables that involve the same agent. For this reason, we employ a variation of ADMM for consensus optimization. Simulation results on multi-vehicle systems under uncertainty with collision avoidance constraints illustrate the effectiveness of our algorithm. The substantially improved scalability of our distributed approach with respect to the number of agents is also demonstrated, in comparison with an equivalent centralized scheme.

[Paper](http://www.roboticsproceedings.org/rss17/p075.pdf)
