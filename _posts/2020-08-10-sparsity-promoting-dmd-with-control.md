---
layout: post
title: Estimation and Control of Fluid Flows Using Sparsity-Promoting Dynamic Mode Decomposition
categories: Research
---


Published at the IEEE Control Systems Letters in August 2020.


Control and estimation of fluid systems is a challenging problem that requires approximating high-dimensional, nonlinear dynamics with computationally tractable models. A number of techniques, such as proper orthogonal decomposition (POD) and dynamic mode decomposition (DMD) have been developed to derive such reduced-order models. In this letter, the problem of selecting the dynamically important modes of dynamic mode decomposition with control (DMDc) is addressed. Similar to sparsity-promoting DMD, the method described in this letter solves a convex optimization problem in order to determine the most important modes. The proposed algorithm produces sparse dynamical models for systems with inputs by solving a regularized least-squares problem that minimizes the reweighted L 1 norm of the relative mode weights and can work even with snapshot data that are not sequential. In addition, the process of estimating the modeling errors and designing a Kalman filter for flow estimation from limited measurements is presented. The method is demonstrated in the feedback control and estimation of the unsteady wake past an inclined flat plate in a high-fidelity direct numerical simulation.

[Paper](https://ieeexplore.ieee.org/abstract/document/9164896) | [Presentation](/docs/MECC_2021_Presentation_Cautious_Nonlinear_Covariance_Steering_using_Variational_Gaussian_Process_Predictive_Models.pdf) | [Code](https://github.com/alextsolovikos/greedyGPCS) | [Code](https://github.com/alextsolovikos/DMDcsp)
