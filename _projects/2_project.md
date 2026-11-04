---
layout: page
title: QAOA Particle Tracking
description: Formulated a Quantum Approximate Optimization Algorithm (QAOA) approach for particle tracking in high-energy physics simulations.
img: /assets/img/particle.png
importance: 2
category: work
related_publications: true
---

This research project, undertaken through the QIntern program at QWorld, explored the application of quantum computing to enhance high-energy physics (HEP) simulations. The primary objective was to leverage the power of the Quantum Approximate Optimization Algorithm (QAOA) to solve the computationally expensive task of particle tracking in simulated detector data.

The core problem in particle tracking is "hit-to-track association": given thousands of points (or "hits") recorded by a detector, reconstruct the original paths of the particles that generated them. This dynamic matching is a classic optimization problem with severe scalability challenges as data size increases, making it an ideal candidate for quantum investigation.



Our project focused on developing a customized QAOA circuit specifically tailored for mapping key particle tracking constraints—such as path continuity, point association, and non-overlapping tracks—directly into a quantum Hamiltonian. This was implemented using industry-standard quantum simulators from PennyLane and Xanadu Strawberry Fields, with a focus on benchmarking performance across different track densities.



The project successfully demonstrated a viable QAOA approach, with simulation results revealing enhanced predictive performance compared to unoptimized baselines, particularly on multi-partition track sets with high data volume. This work highlights the promising future of quantum algorithms in addressing the processing bottlenecks inherent in large-scale HEP experiments.

