---
layout: post
title: Greedy Finite-Horizon Covariance Steering for Discrete-Time Stochastic Nonlinear Systems Based on the Unscented Transform
categories: Research
---

Presented at the 2020 American Control Conference

In this work, we consider the problem of steering the first two moments of the uncertain state of a discrete-time nonlinear stochastic system to prescribed goal quantities at a given final time. We propose a tractable and intuitive approach which relies on a greedy control policy which is comprised of the first elements of the control policies that solve a sequence of corresponding linearized covariance steering problems. Each of the latter problems is associated with a tractable (finite-dimensional) convex program. At each stage, the information on the state statistics is updated by computing approximations of the predicted state mean and covariance of the resulting closed-loop nonlinear system at the next stage by utilizing the (scaled) unscented transform. Numerical simulations that illustrate the key ideas of our approach are also presented.

Learned (Cautious) Model   |  Exact Model
:-------------------------:|:-------------------------:
![](/docs/greedy_covariance_2d.png)  |  ![](/docs/greedy_covariance_trajectories_3d.png)

[Paper](https://arxiv.org/pdf/2003.03679.pdf)
