---
title: Cautious Nonlinear Covariance Steering using Variational Gaussian Process Predictive Models
venue: Presented at the inaugural Modeling, Estimation, and Control Conference 2021 in Austin, TX.
categories: Research
---

Learned (Cautious) Model   |  Exact Model
:-------------------------:|:-------------------------:
![](/docs/gp_position_uncertainties.png)  |  ![](/docs/exact_position_uncertainties.png)

In this work, we consider the problem of steering the first two moments of the uncertain state of an unknown discrete-time stochastic nonlinear system to a given terminal distribution in finite time. Toward that goal, first, a non-parametric predictive model is learned from a set of available training data points using stochastic variational Gaussian process regression: a powerful and scalable machine learning tool for learning distributions over arbitrary nonlinear functions. Second, we formulate a tractable nonlinear covariance steering algorithm that utilizes the Gaussian process predictive model to compute a feedback policy that will drive the distribution of the state of the system close to the goal distribution. In particular, we implement a greedy covariance steering control policy that linearizes at each time step the Gaussian process model around the latest predicted mean and covariance, solves the linear covariance steering control problem, and applies only the first control law. The state uncertainty under the latest feedback control policy is then propagated using the unscented transform with the learned Gaussian process predictive model and the algorithm proceeds to the next time step. Numerical simulations illustrating the main ideas of this paper are also presented.

[Paper](https://arxiv.org/pdf/2010.00778.pdf) \| [Presentation](https://alextsolovikos.github.io/docs/MECC_2021_Presentation_Cautious_Nonlinear_Covariance_Steering_using_Variational_Gaussian_Process_Predictive_Models.pdf) \| [Code](https://github.com/alextsolovikos/greedyGPCS)
