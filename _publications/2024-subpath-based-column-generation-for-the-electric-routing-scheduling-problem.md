---
title: "Subpath-Based Column Generation for the Electric Routing-Scheduling Problem"
collection: publications
permalink: /publication/2024-subpath-based-column-generation-for-the-electric-routing-scheduling-problem
excerpt: 'Column generation for the Electric Routing-Scheduling Problem, with a two-level decomposition of the pricing problem.'
date: 2024-07-02
venue: 'Preprint on arXiv'
paperurl: 'https://arxiv.org/abs/2407.02640'
authors: Alexandre Jacquillat, **Sean Lo**
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**[Paper (arXiv)](https://arxiv.org/abs/2407.02640)**

**[Code repository (GitHub)](https://github.com/sean-lo/ElectricRouting.jl)**

Motivated by widespread electrification targets, this paper studies an electric routing-scheduling problem (ERSP) that jointly optimizes routing-scheduling and charging decisions. The ERSP is formulated as a semi-infinite set-partitioning model, where continuous charging decisions result in infinitely-many path-based variables. To solve it, we develop a column generation algorithm with a bi-level label-setting algorithm to decompose the pricing problem into (i) a first-level procedure to generate subpaths between charging stations, and (ii) a second-level procedure to combine subpaths into paths. We formalize subpath-based domination properties to establish the finite convergence and exactness of the column generation algorithm. We prove that the methodology can handle modeling extensions with heterogeneous charging costs (via dynamic re-optimization of charging decisions) and algorithm extensions to tighten the relaxation using ng-routes and limited-memory subset-row inequalities (via augmented domination criteria). Computational results show that the methodology scales to large instances, outperforming state-of-the-art column generation algorithms. From a practical standpoint, the methodology achieves significant cost reductions by jointly optimizing routing-scheduling and charging decisions and by capturing heterogeneous charging costs.


<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->