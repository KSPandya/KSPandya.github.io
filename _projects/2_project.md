---
layout: page
title: QAOA Particle Tracking
description: Explored a Quantum Approximate Optimization Algorithm (QAOA) approach for particle tracking in high-energy physics simulations as part of QIntern.
img: /assets/img/particle.png
importance: 2
category: fun
---

As part of the QIntern program at QWorld, I explored the application of quantum computing to enhance high-energy physics (HEP) simulations, studying an existing Quantum Approximate Optimization Algorithm (QAOA) approach for the computationally expensive task of particle tracking in simulated detector data.

The core problem in particle tracking is "hit-to-track association": given thousands of points (or "hits") recorded by a detector, reconstruct the original paths of the particles that generated them. This dynamic matching is a classic optimization problem with severe scalability challenges as data size increases, making it an ideal candidate for quantum investigation.

The internship project focused on exploring a customized QAOA circuit tailored for mapping key particle tracking constraints, such as path continuity, point association, and non-overlapping tracks, directly into a quantum Hamiltonian.
