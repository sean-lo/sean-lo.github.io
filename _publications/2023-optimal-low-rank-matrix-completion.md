---
title: "Optimal Low-Rank Matrix Completion: Semidefinite Relaxations and Eigenvector Disjunctions"
collection: publications
permalink: /publication/2023-optimal-low-rank-matrix-completion
excerpt: 'A custom branch-and-bound scheme that solves low-rank matrix completion to certifiable optimality, through an eigenvector disjunctive scheme and strong semidefinite relaxations at each node.'
date: 2023-05-15
venue: 'Preprint on arXiv'
paperurl: 'https://arxiv.org/abs/2305.12292'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**[Paper (arXiv)](https://arxiv.org/abs/2305.12292)**

**[Poster](http://sean-lo.github.io/files/olrmc_poster_20230515.pdf)**

Low-rank matrix completion consists of computing a matrix of minimal complexity that recovers a given set of observations as accurately as possible, and has numerous applications such as product recommendation. 
Unfortunately, existing methods for solving low-rank matrix completion are heuristics that, while highly scalable and often identifying high-quality solutions, do not possess any optimality guarantees. 

We reexamine matrix completion with an optimality-oriented eye, by reformulating low-rank problems as convex problems over the non-convex set of projection matrices and implementing a disjunctive branch-and-bound scheme that solves them to certifiable optimality. 
Further, we derive a novel and often tight class of convex relaxations by decomposing a low-rank matrix as a sum of rank-one matrices and incentivizing, via a Shor relaxation, that each two-by-two minor in each rank-one matrix has determinant zero. 

In numerical experiments, our new convex relaxations decrease the optimality gap by two orders of magnitude compared to existing attempts. Moreover, we showcase the performance of our disjunctive branch-and-bound scheme and demonstrate that it solves matrix completion problems over $150 \times 150$ matrices to certifiable optimality in hours, constituting an order of magnitude improvement on the state-of-the-art for certifiably optimal methods. The implementation is available as the `OptimalMatrixCompletion.jl` package (link [here](http://github.com/sean-lo/OptimalMatrixCompletion.jl)).

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->