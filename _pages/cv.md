---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Aerospace Engineering PhD candidate at the University of Texas at Austin and Mechanical Engineering graduate (BS/MS with highest honors) from the National Technical University of Athens with a wide mathematical and programming background in control theory, computational engineering, and machine learning. I am currently working on ML for model reduction and control of high-dimensional, nonlinear systems, with an emphasis on turbulent flows.

Some of the topics that I have worked on include stochastic optimal control, high-performance computing, deep learning models for trajectory prediction, reinforcement learning, fluid dynamics, adjoint-based aerodynamic shape optimization, and computational geometry. I have also worked extensively on environment perception and estimation problems in the industry for automotive applications, such as Radar-based localization and mapping, computer vision/HD map fusion, and deep learning for radar-only object detection. My coding skills include an advanced grasp of object-oriented languages, such as C++ and Python, as well as Fortran, and Matlab. I am also comfortable with parallel computing on high-performance computing clusters.

**Education**
------------------------------------------------------------------------
***

<p><strong>The University of Texas at Austin</strong> <span style="float:right;">Austin, TX</span><br>
MS/PhD in Aerospace Engineering <span style="float:right;">May 2023</span></p>

-   Master's and Doctoral student in the Department of Aerospace
    Engineering and Engineering Mechanics.
-   GPA: **4.00/4.00**
-   Relevant Coursework: Reinforcement Learning, Robot Learning,
    Stochastic Optimal Control, Autonomous Robots, Statistical
    Estimation Theory, Linear Systems, Optimal Control, Nonlinear
    Dynamics, Dynamics of Turbulence, Multivariable Control Systems,
    Fluid Mechanics

<p><strong>National Technical University of Athens</strong> <span style="float:right;">Athens, Greece</span><br>
BS/MS, Mechanical Engineering <span style="float:right;">February 2018</span></p>

-   Bachelor of Science & Master of Science; 5-year joint degree; 300
    ECTS
-   GPA: **9.06/10.00** (early graduate with *highest honors*; top 10
    among undergraduate class of 180 students)
-   Concentration: Air and Ground Transport Vehicles
-   Relevant Coursework: Computational Fluid Dynamics, Optimization
    Methods in Aerodynamics, Computational Methods in Turbomachines,
    Flight Dynamics, Control Systems, Microprocessor-Based Control
-   Thesis: *"Deformation of Computational Meshes Using Delaunay Graph
    Parameterization -- Applications in the Adjoint-Based Aerodynamic
    Shape Optimization"*


**Work Experience**
------------------------------------------------------------------------
***

<p><strong>Aptiv</strong> <span style="float:right;">Agoura Hills, CA</span><br>
Radar Machine Learning Intern <span style="float:right;">May 2022 - August 2022</span></p>

-   Worked on deep learning for object detection from low-level radar data.
-   Trained and compared the performance of object detection models with different backbones, detection heads, and loss functions, leading to improved detection precision over the previously-used models.
-   Created MMRadar: an extension of MMDetection & MMRotate libraries for radar-only object detection.

<p><strong>Aptiv</strong> <span style="float:right;">Remote, USA</span><br>
Environment Perception Engineering Intern <span style="float:right;">June 2021 - August 2021</span><p>

-   Remote internship with the Road Model Team.
-   Developed a Radar-based Simultaneous Localization and Mapping (SLAM)
    framework that uses pose graphs and loop closures to create a Radar
    occupancy gridmap from scratch.
-   Integrated occupancy gridmap updates from multiple visits of the
    same area in the SLAM framework.
-   Developed ROS pipeline in Python and C++.

<p><strong>Aptiv</strong> <span style="float:right;">Remote, USA</span><br>
Environment Perception Engineering Intern <span style="float:right;">June 2020 - July 2020</span></p>

-   Remote internship with the Road Model Team.
-   Developed a sensor fusion framework for lane marker estimation from
    vision, HD maps, GNSS, and odometry information, along with
    necessary data pipelines and visualization tools in Python.

**Research Experience**
------------------------------------------------------------------------
***

<p><strong>The University of Texas at Austin</strong> <span style="float:right;">Austin, TX</span><br>
Graduate Research Assistant <span style="float:right;">August 2018 - Present</span></p>

-   Developing **reinforcement learning algorithms for control of high-dimensional systems**, with an emphasis on turbulent flows.
-   Main contributor to two collaborative National Science Foundation grants worth a total of nearly $1M.
-   Combining transformer models with dynamics-aware Gaussian processes for **trajectory prediction**.
-   Developing **large-scale numerical simulations** of turbulent boundary layers.
-   Designing **model-predictive control algorithms and reduced-order models** for control of coherent structures in turbulent flows.
-   Developed sparse dynamic mode decomposition for control and estimation of high-dimensional systems.
-   Proposed a multiple-model dynamic mode decomposition framework for flowfield and parameter estimation.
-   Developing algorithms for **stochastic optimal control** of nonlinear systems using Gaussian processes.
-   Contributed to the development of **distributed covariance steering** algorithms.

<p><strong>National Technical University of Athens</strong> <span style="float:right;">Athens, Greece</span><br>
Undergraduate/Associate Researcher <span style="float:right;">May 2017 - July 2018</span></p>

-   Group: *Parallel CFD and Optimization Unit*
-   Research interests:
    -   Adjoint-based optimization of partial differential equations
        (e.g. aerodynamic shape optimization).
    -   Grid generation and manipulation; computational geometry.
    -   Computational fluid dynamics (CFD).
-   Developed and programmed a fast dynamic grid morpher based on
    Delaunay triangulation parameterization for OpenFOAM in C++ and
    coupled it with the adjoint-based aerodynamic shape optimization
    software.
-   Set up a fluid-structure interface between ANSYS and an in-house CFD
    software for simulating the deformation of an inflatable wing.
-   Programmed an adjoint error-based grid refinement tool for the
    OpenFOAM environment for use in automatic mesh generation and for
    improving the accuracy of computing functionals of interest.

**Skills**
------------------------------------------------------------------------
***

<!--
|  |   |
| :---                   |    :----   |
|  **Programming:**      | Proficient in C/C++, Python, Matlab, Fortran 95, Unix |
|  **Libraries/Tools:**  | PyTorch, JAX, ROS, GPyTorch, GTSAM, Numpy, Eigen (C++), SLURM, Docker, Git, OpenCV, CGAL |
|  **Other Tools:**      | LaTeX, MS Office (ECDL Expert), Solidworks, ANSYS, LS-DYNA, EASY, OpenFOAM |
|  **Languages:**        | English (fluent), Italian (basic), Greek (native) |
|  |   |
-->

- **Programming:** Proficient in C/C++, Python, Matlab, Fortran, MPI, OpenMP, Unix Scripting
- **Libraries/Tools:** PyTorch, JAX, ROS, GPyTorch, GTSAM, Eigen (C++), SLURM, Git, OpenCV, CGAL
- **Other Tools:** LaTeX, MS Office (ECDL Expert), Solidworks, ANSYS, , OpenFOAM, Arduino
- **Languages:** English (fluent), Greek (native)

**Publications**
------------------------------------------------------------------------
***

**Journal Articles**

-   **Tsolovikos, A.**, Suryanarayanan, S., Bakolas, E., Goldstein, D.,
    (2020), "Model predictive control of material volumes with
    application to vortical structrues", *AIAA Journal, 2021*.
-   **Tsolovikos, A.**, Bakolas, E., Suryanarayanan, S., Goldstein, D.,
    (2020), "Estimation and control of fluid systems using
    sparsity-promoting dynamic mode decomposition with control", *IEEE
    Control Systems Letters*.
-   Gkaragkounis, K., Papoutsis-Kiachagias, E., **Tsolovikos, A.**,
    Giannakoglou, K., (2020), "The effect of grid displacement methods
    on continuous adjoint-based sensitivity derivatives in aerodynamic
    and conjugate heat transfer problems", *Engineering Optimization*.

**Conference Papers**
-   Jariwala, A., **Tsolovikos, A.**, Suryanarayanan, S., 
    Goldstein, D. B., and Bakolas, E. (2022). On the effect of 
    manipulating Large Scale Motions in a Boundary Layer. In AIAA 
    AVIATION 2022 Forum.
-   **Tsolovikos, A.**, Suryanarayanan, S., Bakolas, E., and
    Goldstein, D. B. (2022). Multiple Model Dynamic Mode Decomposition
    for Flowfield and Model Parameter Estimation. In AIAA SCITECH 2022
    Forum (p. 2427).
-   **Tsolovikos, A.**, Bakolas, E. (2021), "Cautious Nonlinear
    Covariance Steering using Variational Gaussian Process Predictive
    Models", to be presented at the *Modeling, Estimation and Control
    Conference 2021*.
-   Saravanos, A.D., **Tsolovikos, A.**, Bakolas, E. and Theodorou, E.A.
    (2021), Distributed Covariance Steering with Consensus ADMM for
    Stochastic Multi-Agent Systems, *Robotics: Science and Systems
    2021*.
-   Bakolas, E., **Tsolovikos, A.**, (2020), "Greedy finite-horizon
    covariance steering for discrete-time stochastic nonlinear systems
    based on the unscented transform", *American Control Conference
    2020*, Denver, CO, July 1-3, 2020.
-   **Tsolovikos, A.**, Suryanarayanan, S., Bakolas, E., Goldstein, D.,
    (2020), "Toward model-based control of near-wall turbulent coherent
    structures", *AIAA SciTech 2020*, Orlando, FL, January 6-10, 2020.

**Talks**
- "Control of Large-Scale Motions in Turbulent Boundary Layers", Caltech, August 2, 2022, Pasadena, CA.
- "Control of Large-Scale Motions in Boundary Layers", APS DFD 2021, November 22, 2021, Phoenix, AZ.
- "Model Predictive Control of Near-Wall Turbulent Coherent Structures", UT Austin ASE Seminar, February 13, 2020, Austin, TX.


**Teaching Experience**
------------------------------------------------------------------------
***

**Teaching Assistant**, The University of Texas at Austin

-   Assisted in the *Linear Systems* course by grading and holding
    review sessions (Spring 2019, Fall 2020 & Spring 2021).
-   Assisted in the *Compressible Flow* course by lecturing, grading and
    holding office hours (Spring 2019).
-   Taught and supervised the *Low-Speed Aerodynamics Lab*; graded lab
    reports, and held office hours (Fall 2018).
-   Assisted in the *Applied Aerodynamics* course by grading homework
    and holding office hours (Fall 2018).

**Awards and Fellowships**
------------------------------------------------------------------------
***

-  *"Best ASE/EM Graduate Peer Mentor"* award (Spring 2022).
-   *"Graduate Dean's Prestigious Fellowship Supplement" Fellow
   * (September 2020)
-   ***"A. Onassis Foundation Scholarship"* for Ph.D. studies in
    Aerospace Engineering (September 2020 - May 2023, valued at over
    \$40,000)**
-   *"Hellenic Professional Society of Texas Scholarship"* recipient
    (February 2020)
-   *"Gerondelis Foundation Graduate Study Scholarship"* recipient
    (December 2019)
-   ***"Graduate Continuing Fellowship"* awarded by the Graduate School
    at the University of Texas at Austin (June 2019 -- May 2020,
    \$44,000 toward tuition and stipend)**
-   *"KARY"* award for the highest GPA in the Mechanical Engineering
    School during the academic year 2015 -- 2016 (September 2017)
-   *"Thomaideio"* award for the highest GPA in the $5^{th}$ and
    $6^{th}$ semesters in the Mechanical Engineering School (September
    2017)
-   *"Christos Papakyriakopoulos"* award for the highest score in
    mathematics courses (September 2015)
-   *"A Great Moment for Education"* award for the highest score in
    University Entrance Examinations, Eurobank (2013)
    
    
*Last update: September 17, 2022*
