---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a simulation researcher and engineer working at the intersection of **physics-based simulation, nonlinear optimization and robot learning**. I currently lead the simulation team at a robotics startup in Shenzhen, China, where we build a GPU-accelerated rigid–soft coupled simulation engine and use it to generate large-scale robot interaction data (soft bodies, cloth and articulated objects) for world-model training and dexterous-hand manipulation.

I received my Ph.D. in Computer Graphics from **Nanyang Technological University (NTU), Singapore** (2019–2025, advised by Prof. Jianmin Zheng), where I worked on physics-based simulation and material-distribution design for 3D printing. Before that I obtained an M.Eng. in Electrical Engineering from the **National University of Singapore (NUS)** and a B.Eng. in Communication Engineering from the **University of Electronic Science and Technology of China (UESTC)**.

Research interests
======
* **Physics-based and differentiable simulation**: FEM based on continuum mechanics, PBD/XPBD, IPC, MPM and projective dynamics; contact and large-deformation handling; GPU-parallel solvers (C++/CUDA).
* **Simulation for robot learning**: rigid–soft coupled simulation engines integrated with Isaac Lab, synthetic data generation for world models and reinforcement learning, perception–world-model–control integration for fine manipulation in everyday scenes.
* **Nonlinear optimization and AI for design**: large-scale discrete material-distribution optimization (L0 regularization, graph cuts, ADMM), topology optimization with CNNs and physics-informed neural networks, generative microstructure design.

Current work
======
At the company I lead a seven-person team responsible for rigid-body, deformable-body and cloth simulation. Highlights so far:

* Designed and built a fully GPU-based rigid–soft coupled simulation architecture with a USD parsing layer, and migrated the simulation pipeline to the USD framework.
* Generated high-quality synthetic data for rigid–soft coupled scenes such as parcel grasping and hanging garments, and validated advanced grasping algorithms on elasto-plastic objects.
* Integrated the engine into Isaac Lab for penetration-free simulation of robot arms grasping cloth and elastic bodies, with Manager-Based Env support for PPO training.
* Since July 2026: large-scale generation of robot interaction data for world-model training, and an integrated perception + world model + action-control stack for fine-grained dexterous-hand control in daily-life scenarios.

Selected publications
======
* H. Li, W. Zhang, J. Zheng, E. D. Davis, J. Zeng. *Optimizing heterogeneous elastic material distributions on 3D models*. **Computer-Aided Design**, 175, 103748, 2024. [DOI](https://doi.org/10.1016/j.cad.2024.103748)
* H. Li, J. Zheng. *L0-regularization based material design for hexahedral mesh models*. **Computer-Aided Design and Applications**, 19(6), 1171–1183, 2022. [DOI](https://doi.org/10.14733/cadaps.2022.1171-1183)
* J. Zheng, H. Li. *Designing multi-material distributions in 3D parts for desired deformation behaviour*. Dagstuhl Seminar 24241, **Dagstuhl Reports**, 14(6), 2024. [DOI](https://doi.org/10.4230/DagRep.14.6.52)

See the [Publications](/publications/) and [CV](/cv/) pages for the full list.
