---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Graphics**, Nanyang Technological University (NTU), Singapore, 2019–2025  
  Physics-based simulation and material-distribution design. Advisor: Prof. Jianmin Zheng.
* **M.Eng. in Electrical Engineering**, National University of Singapore (NUS), 2017–2018
* **B.Eng. in Communication Engineering**, University of Electronic Science and Technology of China (UESTC), 2013–2017

Work experience
======
* **Sep 2025 – present: Simulation Team Lead**, RoboScience, Shenzhen, China
  * Lead a seven-person team building the core rigid-body, deformable-body and cloth simulation engine and its integration with Isaac Lab.
  * Designed a fully GPU-based rigid–soft coupled simulation architecture, implemented the engine's USD parsing layer and migrated the simulation pipeline to the USD framework.
  * Generated high-quality synthetic data for complex rigid–soft coupled scenes (parcel grasping, hanging garments) and validated advanced grasping algorithms on elasto-plastic objects.
  * Integrated the GPU-accelerated engine into Isaac Lab: penetration-free simulation of robot arms grasping cloth and elastic bodies, Manager-Based Env support for PPO training, and gripper demos on soft cubes and cloth.
  * Since July 2026: large-scale generation of soft-body, cloth and articulated-object interaction data for world-model training, and an integrated perception / world model / action-control pipeline for fine-grained dexterous-hand control in everyday scenes.

* **Oct 2023 – Aug 2025: Research Associate**, Nanyang Technological University, Singapore
  * Built an elastic-body simulation engine from scratch: PBD/XPBD, then an FEM core based on continuum mechanics with IPC-style contact handling for large deformation, complex topology and contact.
  * Applied preconditioned conjugate gradients, Hessian-corrected quasi-Newton methods, Chebyshev iteration and Nesterov acceleration to large-scale inverse problems in structural analysis.
  * Deployed a C++/CUDA large-scale matrix computation system (Cholesky/QR, multigrid preconditioning, parallel linear solvers) on NTU's multi-GPU cluster for high-fidelity 3D simulation.

* **May 2019 – Aug 2023: Research Assistant**, HP-NTU Digital Manufacturing Corporate Lab, Singapore
  * Deep-learning-based multi-scale structural design: an end-to-end macroscopic topology-optimization framework combining CNNs and physics-informed neural networks (about 3x faster than conventional numerical optimization), and a PointNet-based generative model for microstructure design with multi-scale feature alignment.
  * Large-scale discrete optimization of material distributions on general shapes for 3D printing: an L0 formulation with differentiable interpolation relaxation solving 300k+-dimensional non-convex problems within half an hour, applied to customized insoles, seats and precision tweezers.
  * Parallel multi-objective constrained optimization workflow fusing multiple force–displacement scenarios and resolving mesh-resolution consistency.

Skills
======
* **Simulation**: FEM (continuum mechanics), PBD/XPBD, IPC, MPM, projective dynamics, VBD; contact, friction and large-deformation handling; differentiable simulation.
* **Optimization and ML**: nonlinear and constrained optimization (PCG, quasi-Newton, ADMM, graph cuts, L0 regularization), topology optimization, PINNs, PointNet, generative design, reinforcement learning (PPO).
* **Systems**: C++/CUDA, GPU-parallel solvers, multi-GPU clusters, USD pipelines, Isaac Sim / Isaac Lab, Abaqus, ANSYS.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Awards
======
* HP-NTU Digital Manufacturing Corporate Lab internal presentation / poster competition, runner-up, 2021
* NTU Research Scholarship, 2019
* People's Scholarship (2nd class, 2014; 3rd class, 2015), UESTC

Service
======
* Reviewer for IEEE TVCG, ISMAR, CVPR, Computer-Aided Design, and Computers & Graphics
