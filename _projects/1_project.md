---
layout: page
title: QUBO Flight Trajectory Optimization
description: Formulated a QUBO model for flight path planning in the Deloitte Quantum Climate Challenge 2022.
img: /assets/img/trajectory.png
importance: 1
category: work
related_publications: true
---

This internship provided an incredible opportunity to explore the intersection of quantum computing and sustainable transportation. During my time as a Quantum Computing Intern at Artificial Brain, I actively participated in the Deloitte Quantum Climate Challenge 2022, focusing specifically on optimizing flight trajectories to reduce carbon emissions.

The core challenge lay in balancing multiple competing constraints—such as fuel consumption, dynamic wind patterns, and airspace restrictions—within a single, computationally tractable model. We identified this multi-objective optimization problem as a prime candidate for a quantum approach using Quadratic Unconstrained Binary Optimization (QUBO).

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/global_paths.jpg" title="Global flight network" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/qubo_landscape.jpg" title="Optimization landscape" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Trajectory Visualization and Model Structure: (Left) The large-scale flight network where paths were optimized. (Right) A visual representation of the optimization landscape, with minima representing efficient trajectories.
</div>

Our methodology involved defining a detailed QUBO model that encoded the physical and operational realities of a major flight network. This allowed us to explore various solutions on quantum annealing hardware, such as the D-Wave Leap platform. We fine-tuned the model, addressing specific constraints on path continuity and feasibility, to ensure realistic results. The optimization focused not just on path length, but on integrated fuel consumption across diverse atmospheric scenarios.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/optimized_network.jpg" title="Optimized network results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Network Performance: The full-width visualization showcases significant reduction in total carbon footprint across a key European network, with optimized paths highlighted in contrasting colors.
</div>

The results were compelling, demonstrating that our quantum-enhanced approach could discover trajectories that significantly reduce predicted carbon emissions compared to conventional shortest-path baselines across multiple network structures. This project successfully explored the potential of quantum optimization to address complex, real-world sustainability challenges in aviation.

{% raw %}
```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/global_paths.jpg" title="Global flight network" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/qubo_landscape.jpg" title="Optimization landscape" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
{% endraw %}
