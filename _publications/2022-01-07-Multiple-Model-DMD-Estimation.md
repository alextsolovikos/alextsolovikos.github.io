---
title: Multiple Model Dynamic Mode Decomposition for Flowfield and Model Parameter Estimation
venue: Presented at the AIAA SciTech 2022 Forum in San Diego, CA.
categories: Research
---

<p align="center">
  <img src="/docs/mmdmd_flat_plate.gif" />
</p>

In this work, we present a method for estimating the unsteady flowfield of a fluid system with unknown model parameters (such as angle of attack or Reynolds number) in real time from a limited number of sensor measurements using a "bank" of Dynamic Mode Decomposition (DMD) models. First, a set of DMD models is computed at sample values of the model parameter. Then, a bank of Kalman filters is run for each one of the models, yielding a state estimate for each one of the DMD models and, thus, a corresponding flowfield estimate. Finally, the minimum mean-squared error (MMSE) estimate of the actual flowfield is computed as a weighted sum of the individual flowfield estimates from each model, where the weights are the likelihood of each model being the correct one given current and past measurements, under the Multiple Model Kalman Filter (MMKF) framework. The performance of the proposed approach to estimating the flowfield of a system with varying parameters is demonstrated in simple flow settings: a Blasius boundary layer at discrete adverse pressure gradients and a flat plate at different angles of attack.

[Paper](https://arc.aiaa.org/doi/abs/10.2514/6.2022-2427) \| [Presentation](https://alextsolovikos.github.io/docs/Multiple_Model_Dynamic_Mode_Decomposition_for_Flowfield_and_Parameter_Estimation.pdf)
