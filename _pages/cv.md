---
layout: page
permalink: /cv/
title: curriculum vitae
description: Quantum Optimization, Online Algorithms & Theoretical Computer Science
nav: true
nav_order: 5
---

<style>
  .cv-container {
    font-family: var(--global-font-family);
    color: var(--global-text-color);
  }
  .cv-header-card {
    background: linear-gradient(135deg, rgba(56, 189, 248, 0.05), rgba(168, 85, 247, 0.05));
    border-left: 4px solid #38bdf8;
    padding: 2rem;
    border-radius: 8px;
    margin-bottom: 2.5rem;
  }
  .cv-section-title {
    font-size: 1.15rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--global-theme-color);
    margin-bottom: 1.5rem;
    display: flex;
    align-items: center;
    gap: 0.75rem;
  }
  .timeline-item {
    position: relative;
    padding-left: 1.5rem;
    border-left: 2px solid var(--global-divider-color);
    margin-bottom: 2rem;
  }
  .timeline-item::before {
    content: '';
    position: absolute;
    left: -5px;
    top: 5px;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #38bdf8;
  }
  .pub-item {
    margin-bottom: 1.25rem;
    padding-bottom: 1rem;
    border-bottom: 1px dashed var(--global-divider-color);
  }
  .pub-item:last-child {
    border-bottom: none;
  }
  .chic-badge {
    display: inline-block;
    padding: 0.4rem 0.85rem;
    font-size: 0.75rem;
    font-weight: 600;
    border-radius: 50rem;
    background: rgba(56, 189, 248, 0.08);
    color: #0284c7;
    margin: 0.25rem;
    border: 1px solid rgba(56, 189, 248, 0.2);
    transition: all 0.2s ease;
  }
  .chic-badge:hover {
    background: rgba(56, 189, 248, 0.2);
    transform: translateY(-1px);
  }
</style>

<div class="cv-container">
  
  <!-- Top Action Bar -->
  <div class="d-flex justify-content-between align-items-center mb-4">
    <span class="text-muted small font-italic">Ph.D. Defense: Sept 2026 | Indian Institute of Technology Patna</span>
    <a href="{{ '/assets/pdf/your_name_cv.pdf' | relative_url }}" target="_blank" class="btn btn-sm btn-dark font-weight-bold px-3 py-2 shadow-sm" style="border-radius: 6px;">
      <i class="fa-solid fa-file-pdf me-1"></i> Download PDF
    </a>
  </div>

  <!-- Hero Header Card -->
  <div class="cv-header-card shadow-sm">
    <h3 class="font-weight-bold mb-2">Dr. Komal Pandya</h3>
    <p class="text-muted mb-3">Specializing in Quantum Annealing, QAOA Variants, Hypergraph Matching, & Online Algorithms.</p>
    <div class="d-flex flex-wrap gap-2">
      <span class="badge bg-secondary">IIT Patna</span>
      <span class="badge bg-secondary">Quantum Computing</span>
      <span class="badge bg-secondary">Theoretical CS</span>
    </div>
  </div>

  <!-- EDUCATION -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-graduation-cap"></i> Education</div>
    
    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Ph.D. in Computer Science</h5>
      <p class="text-muted small mb-2">Indian Institute of Technology Patna | Sep 2020 – Sep 2026</p>
      <p class="small mb-1"><strong>Focus:</strong> Quantum Optimization & Online Algorithms</p>
      <p class="small text-secondary mb-0">Advised by Dr. Abyayananda Maiti. Thesis: <em>Higher-Order Matching in 3-Partite, 3-Uniform Hypergraphs: Classical Online Algorithms & Quantum Optimization</em>.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">B.E. in Computer Engineering</h5>
      <p class="text-muted small mb-2">Government Engineering College Gandhinagar | 2015 – 2019</p>
      <p class="small text-secondary mb-0">Project: Aspect-Based Sentiment Analysis.</p>
    </div>
  </div>

  <!-- RESEARCH EXPERIENCE -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-flask"></i> Research Experience</div>
    
    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Quantum Research Mentee</h5>
      <p class="text-muted small mb-2">Quantum Open Source Foundation (QOSF) | Apr 2022 – Mar 2024 (Remote)</p>
      <p class="small text-secondary mb-0">Benchmarked QAOA performance and validated algorithmic scalability across diverse combinatorial problem sets.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Quantum Computing Intern</h5>
      <p class="text-muted small mb-2">Artificial Brain | Jan 2022 – Apr 2022 (Remote)</p>
      <p class="small text-secondary mb-0">Formulated and executed a Quadratic Unconstrained Binary Optimization (QUBO) model for flight trajectory optimization (Deloitte Quantum Climate Challenge 2022).</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Quantum Computing Intern (QIntern)</h5>
      <p class="text-muted small mb-2">QWorld | Jul 2021 – Aug 2021 (Remote)</p>
      <p class="small text-secondary mb-0">Formulated a QAOA approach for particle tracking in high-energy physics simulations.</p>
    </div>
  </div>

  <!-- SELECTED PUBLICATIONS -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-book-open"></i> Selected Publications</div>
    
    <div class="pub-item">
      <p class="small mb-1">K. Pandya, S. Sakhuja, N. Kattian. <br><strong>"Topology-Aware Active Debris Removal using Gaussian Boson Sampling."</strong></p>
      <span class="badge bg-light text-dark border">Under Prep, 2026</span>
    </div>

    <div class="pub-item">
      <p class="small mb-1">K. Pandya, A. Maiti. <br><strong>"Benchmarking the Three-Dimensional and the Numerical Three-Dimensional Matching Problems on the D-Wave Advantage Quantum Annealer."</strong></p>
      <span class="badge bg-light text-dark border">Information Sciences, 2025</span>
    </div>

    <div class="pub-item">
      <p class="small mb-1">K. Blekos, D. Brand, A. Ceschini, C. H. Chou, R. H. Li, K. Pandya, A. Summer. <br><strong>"A review on quantum approximate optimization algorithm and its variants."</strong></p>
      <span class="badge bg-light text-dark border">Physics Reports, 1068, 1–66, 2024</span>
    </div>

    <div class="pub-item">
      <p class="small mb-1">K. Pandya, A. Maiti. <br><strong>"Randomized Ranking Algorithm for Online Trichromatic Matching."</strong></p>
      <span class="badge bg-light text-dark border">IEEE Access, 2024</span>
    </div>
  </div>

  <!-- FELLOWSHIPS & AWARDS -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-award"></i> Fellowships & Awards</div>
    <div class="row">
      <div class="col-md-6 mb-3">
        <div class="p-3 border rounded bg-light shadow-sm">
          <strong class="d-block text-dark">MHRD PhD Project Fellowship</strong>
          <small class="text-muted">IIT Patna (2020–2023)</small>
        </div>
      </div>
      <div class="col-md-6 mb-3">
        <div class="p-3 border rounded bg-light shadow-sm">
          <strong class="d-block text-dark">Research Grant Awardee</strong>
          <small class="text-muted">Quantum Neural Technologies, SA (2024)</small>
        </div>
      </div>
      <div class="col-md-6 mb-3">
        <div class="p-3 border rounded bg-light shadow-sm">
          <strong class="d-block text-dark">Travel Grant Awardee</strong>
          <small class="text-muted">IndoML 2023, IIT Bombay</small>
        </div>
      </div>
      <div class="col-md-6 mb-3">
        <div class="p-3 border rounded bg-light shadow-sm">
          <strong class="d-block text-dark">Travel Grant Awardee</strong>
          <small class="text-muted">CCPWC Project, New Delhi (2022)</small>
        </div>
      </div>
    </div>
  </div>

  <!-- TECHNICAL SKILLS -->
  <div class="mb-4">
    <div class="cv-section-title"><i class="fa-solid fa-code"></i> Technical Stack</div>
    <div class="d-flex flex-wrap">
      <span class="chic-badge">D-Wave Leap</span>
      <span class="chic-badge">PennyLane</span>
      <span class="chic-badge">Qiskit</span>
      <span class="chic-badge">Cirq</span>
      <span class="chic-badge">Strawberry Fields</span>
      <span class="chic-badge">Python</span>
      <span class="chic-badge">C / C++</span>
      <span class="chic-badge">Gurobi</span>
      <span class="chic-badge">CPLEX</span>
      <span class="chic-badge">MATLAB</span>
      <span class="chic-badge">LaTeX</span>
    </div>
  </div>

</div>
