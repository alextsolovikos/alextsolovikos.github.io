---
layout: post
title: Toward Model-Based Control of Near-Wall Turbulent Coherent Structures
categories: Research
---

Presented at the AIAA Scitech 2020 Forum.

Coherent structures in wall-bounded flows, such as large-scale motions (LSMs), contribute significantly to the dynamics of turbulent boundary layers: they contain a large fraction of the turbulent kinetic energy, add to the average Reynolds shear stresses, and transport momentum. Therefore, one may wish to control turbulence by manipulating the movement of these LSMs in order to achieve a desired performance gain (such as drag reduction, noise reduction, or mixing enhancement). In the present work, we approach the above problem in an abstract way by developing a model-based approach of steering towards the wall isolated volumes of interest (that could be an LSM we wish to control) in a direct numerical simulation (DNS) of a three-dimensional laminar boundary layer using as an actuator a Gaussian-distributed force field applied in a region of the flow directly above the wall. In particular, we derive a reduced-order linear model of the actuator dynamics using a variant of dynamic mode decomposition that includes control inputs (dynamic mode decomposition with control - DMDc), which describes how the actuator input (i.e. the magnitude of the input force field) perturbs the velocity field (i.e. the output of the reduced-order model) downstream of the actuator. The identified linear model is then required to track a reference output that creates a downwash along the trajectory of the target volume. To that end, the control design is formulated as an output tracking linear-quadratic optimal control problem with input constraints in discrete time, which is reduced to an equivalent quadratic program with linear constraints. The solution to the constrained optimization problem yields an input signal that effectively drives the target volume towards the wall while minimizing the actuation energy.

[Paper](https://arc.aiaa.org/doi/abs/10.2514/6.2020-1319)
