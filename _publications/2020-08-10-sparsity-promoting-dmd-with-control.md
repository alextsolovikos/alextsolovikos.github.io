---
title: Estimation and Control of Fluid Flows Using Sparsity-Promoting Dynamic Mode Decomposition
venue: Published in the IEEE Control Systems Letters, 2021.
categories: Research
---

<p align="center">
  <img max-width: 60%;
  height: auto; src="/docs/dmdcsp_flat_plate_wake.gif" />
</p>

Control and estimation of fluid systems is a challenging problem that requires approximating high-dimensional, nonlinear dynamics with computationally tractable models. A number of techniques, such as proper orthogonal decomposition (POD) and dynamic mode decomposition (DMD) have been developed to derive such reduced-order models. In this letter, the problem of selecting the dynamically important modes of dynamic mode decomposition with control (DMDc) is addressed. Similar to sparsity-promoting DMD, the method described in this letter solves a convex optimization problem in order to determine the most important modes. The proposed algorithm produces sparse dynamical models for systems with inputs by solving a regularized least-squares problem that minimizes the reweighted L 1 norm of the relative mode weights and can work even with snapshot data that are not sequential. In addition, the process of estimating the modeling errors and designing a Kalman filter for flow estimation from limited measurements is presented. The method is demonstrated in the feedback control and estimation of the unsteady wake past an inclined flat plate in a high-fidelity direct numerical simulation.

[Paper](https://ieeexplore.ieee.org/abstract/document/9164896) \|
[Presentation](https://alextsolovikos.github.io/docs/Presentation_Estimation_and_Control_of_Fluid_Flows_using_Sparsity_Promoting_Dynamic_Mode_Decomposition.pdf) \|
[Code](https://github.com/alextsolovikos/DMDcsp)
