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

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/detector_collision.jpg" title="Detector event simulation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/reconstructed_stubs.jpg" title="Partial track stubs" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/final_tracks.jpg" title="Final reconstructed tracks" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Dynamic Reconstruction Flow: From a complex detector event (left) to partial stubs in 3-column format (middle) and finally to full, clear particle tracks (right), showcasing the reconstruction process.
</div>

Our project focused on developing a customized QAOA circuit specifically tailored for mapping key particle tracking constraints—such as path continuity, point association, and non-overlapping tracks—directly into a quantum Hamiltonian. This was implemented using industry-standard quantum simulators from PennyLane and Xanadu Strawberry Fields, with a focus on benchmarking performance across different track densities.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/tracking_circuit.jpg" title="QAOA Tracking Circuit" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/tracking_convergence.jpg" title="Convergence plot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Algorithm Performance: (Left) The complex QAOA circuit tailored to HEP constraint matching. (Right) A plot illustrating significant convergence speed-up in optimized models, showing enhanced predictive performance across multi-partition track sets.
</div>

The project successfully demonstrated a viable QAOA approach, with simulation results revealing enhanced predictive performance compared to unoptimized baselines, particularly on multi-partition track sets with high data volume. This work highlights the promising future of quantum algorithms in addressing the processing bottlenecks inherent in large-scale HEP experiments.

{% raw %}
```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/tracking_circuit.jpg" title="QAOA Tracking Circuit" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/tracking_convergence.jpg" title="Convergence plot" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
{% endraw %}
