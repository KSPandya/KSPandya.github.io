---
layout: page
title: Multi-Modal ML Optimization
description: Optimized machine learning models for multi-modal data through systematic hyperparameter tuning and feature engineering at EISystems.
img: /assets/img/eisystems.png
importance: 4
category: work
related_publications: false
---

This Machine Learning Internship at EISystems in Bengaluru was an immersion into performance optimization for complex models. The project focused on unlocking the full potential of multi-modal machine learning by addressing the systematic tuning of multi-partition data across image, text, and numerical sensor inputs.

The core challenge was to improve predictive performance on highly diverse multi-uniform hypergraph sets where single-modality models often struggle. Achieving convergence speed-up while maximizing accuracy required an integrated strategy for efficient and comprehensive hyperparameter optimization.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/multimodal_pipeline.jpg" title="Data Pipeline Overview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Integrated Data Flow: The full-width pipeline visualization illustrates the unified process from heterogeneous input partition to fused feature matching, key to our optimization success.
</div>

Our project focused on implementing and benchmarking multiple systematic grid search strategies using deep learning frameworks. We fine-tuned thousands of model configurations, evaluating circuit depth vs. approximation ratio across different algorithm families to ensure enhanced predictive performance without excessive computation.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/tuning_results.jpg" title="Optimization Results" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/confusion_matrix.jpg" title="Confusion Matrix Comparison" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Performance Analysis: (Left) Results from different grid search strategies, showing accuracy across multi-partition track sets. (Right) Confusion matrix comparison revealing enhanced predictive performance in optimized models.
</div>

The results were decisive, revealing enhanced predictive performance and significant convergence speed-up across diverse multi-modal test scenarios. We were able to significantly reduce computational bottlenecks, proving that a meticulous, multi-pronged optimization strategy is essential for achieving state-of-the-art performance in complex machine learning deployments. This dynamic matching of hypergraph constraints remains relevant not just in machine learning, but also in free-space optical QKD links.

{% raw %}
```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/tuning_results.jpg" title="Optimization Results" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/projects/confusion_matrix.jpg" title="Confusion Matrix Comparison" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
{% endraw %}
