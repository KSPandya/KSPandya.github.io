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
  /* Language Circle Card Styles */
  .lang-card {
    background: var(--global-card-bg-color, #ffffff);
    border: 1px solid var(--global-divider-color);
    border-radius: 12px;
    padding: 1.25rem 1rem;
    text-align: center;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    height: 100%;
  }
  .lang-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 6px 15px rgba(0,0,0,0.06);
  }
  .lang-circle {
    width: 55px;
    height: 55px;
    border-radius: 50%;
    background: linear-gradient(135deg, #0284c7, #7c3aed);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 0.85rem;
    margin: 0 auto 0.75rem auto;
    box-shadow: 0 4px 10px rgba(2, 132, 199, 0.25);
  }
  .lang-metric {
    font-size: 0.75rem;
    display: flex;
    justify-content: space-between;
    color: var(--global-text-color);
    margin-bottom: 0.2rem;
    opacity: 0.85;
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

  <!-- RESEARCH INTERESTS -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-compass"></i> Research Interests</div>
    <div class="row">
      <div class="col-md-4 mb-3">
        <div class="p-3 border rounded bg-light shadow-sm h-100">
          <h6 class="font-weight-bold text-primary mb-2"><i class="fa-solid fa-atom me-1"></i> Foundations</h6>
          <p class="small text-muted mb-0">Quantum & Classical Optimization, Hybrid Quantum-Classical Computation, Mathematical Modeling, and Computational Simulations.</p>
        </div>
      </div>
      <div class="col-md-4 mb-3">
        <div class="p-3 border rounded bg-light shadow-sm h-100">
          <h6 class="font-weight-bold text-primary mb-2"><i class="fa-solid fa-shield-halved me-1"></i> Quantum Security</h6>
          <p class="small text-muted mb-0">Quantum Cryptography, Quantum Key Distribution (QKD), and Constraint-Aware Variational Circuit Optimization.</p>
        </div>
      </div>
      <div class="col-md-4 mb-3">
        <div class="p-3 border rounded bg-light shadow-sm h-100">
          <h6 class="font-weight-bold text-primary mb-2"><i class="fa-solid fa-satellite me-1"></i> Applications</h6>
          <p class="small text-muted mb-0">Space Debris Removal, Satellite Constellation Management, and Large-Scale Complex Scheduling Problems.</p>
        </div>
      </div>
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

  <!-- MAJOR POSITIONS OF RESPONSIBILITY -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-users-rectangle"></i> Positions of Responsibility</div>
    
    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Translation Lead</h5>
      <p class="text-muted small mb-2">Qiskit Localization (Gujarati) | May 2023 – Mar 2024[cite: 1]</p>
      <p class="small text-secondary mb-0">Led regional quantum documentation and localization initiatives for Qiskit in Gujarati.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Volunteer, Technical Team</h5>
      <p class="text-muted small mb-2">Research Scholars' Day (RSD) 2023, IIT Patna | Feb 2023[cite: 1]</p>
      <p class="small text-secondary mb-0">Managed technical logistics and computational session coordination for the institutional symposium.</p>
    </div>
  </div>

  <!-- WORKSHOPS, CONFERENCES & SCHOOLS -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-chalkboard-user"></i> Workshops, Conferences & Schools</div>
    
    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">DefSat 2026</h5>
      <p class="text-muted small mb-2">India | February 2026 <span class="badge bg-info text-dark ms-1" style="font-size: 0.65rem;">On-site</span></p>
      <p class="small text-secondary mb-0">Participated in national defense space technology discussions and quantum-secure communications panels.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Symposium Celebrating the Quantum Century (SCQC 2025)</h5>
      <p class="text-muted small mb-2">Bengaluru | October 2025 <span class="badge bg-info text-dark ms-1" style="font-size: 0.65rem;">On-site</span></p>
      <p class="small text-secondary mb-0">Presented research on quantum-integrated systems for space warfare, ISR, C2, and multi-target space debris optimization.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Quantum India Bengaluru (QIB) Summit 2025</h5>
      <p class="text-muted small mb-2">Bengaluru | July 2025 <span class="badge bg-info text-dark ms-1" style="font-size: 0.65rem;">On-site</span></p>
      <p class="small text-secondary mb-0">Engaged with India's national quantum mission hubs, academic leaders, and industry pioneers.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">International Workshop on Engineering and Integration Challenges in Quantum Communication and Quantum Computing</h5>
      <p class="text-muted small mb-2">C-DAC Pune | March 2024 <span class="badge bg-info text-dark ms-1" style="font-size: 0.65rem;">On-site</span></p>
      <p class="small text-secondary mb-0">Received participation certificate focusing on hardware integration hurdles and quantum communication architectures.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Global Quantum Computing, Sensing and Communication Program</h5>
      <p class="text-muted small mb-2">Womanium | 2023 <span class="badge bg-secondary text-white ms-1" style="font-size: 0.65rem;">Virtual</span></p>
      <p class="small text-secondary mb-0">Completed advanced global training modules spanning quantum sensing, quantum computing algorithms, and communication protocols.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Quantum Global Summer School on Quantum Machine Learning</h5>
      <p class="text-muted small mb-2">2021 <span class="badge bg-secondary text-white ms-1" style="font-size: 0.65rem;">Virtual</span></p>
      <p class="small text-secondary mb-0">Intensive coursework and hands-on implementation of variational quantum algorithms and quantum machine learning architectures.</p>
    </div>
  </div>

  <!-- CERTIFICATES & ACHIEVEMENTS -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-certificate"></i> Certificates & Achievements</div>
    
    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">IBM Quantum Challenge - Fall 2021 (Advanced)</h5>
      <p class="text-muted small mb-2">IBM Quantum | Issued Nov 9, 2021</p>
      <p class="small text-secondary mb-0">Successfully tackled advanced circuit implementation and optimization problem sets on IBM quantum hardware.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">IBM Quantum Challenge Africa 2021 Achievement</h5>
      <p class="text-muted small mb-2">IBM Quantum | Issued Sep 29, 2021</p>
      <p class="small text-secondary mb-0">Completed regional quantum programming challenges and computational workflows.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">Quantum Global Summer School on Quantum Machine Learning</h5>
      <p class="text-muted small mb-2">Advanced Level | 2021</p>
      <p class="small text-secondary mb-0">Advanced certification covering hybrid quantum neural networks and parameterized quantum circuit optimization.</p>
    </div>

    <div class="timeline-item">
      <h5 class="font-weight-bold mb-1">QWorld Quantum Educational Certifications</h5>
      <p class="text-muted small mb-2">QWorld | 2021 – 2023</p>
      <p class="small text-secondary mb-0">Earned foundational and advanced badges: <strong>QBronze</strong> (Intro to Quantum Computing), <strong>QSilver</strong> (Quantum Programming), <strong>QNickel</strong> (Quantum Mystery), and <strong>QMercury</strong>.</p>
    </div>
  </div>

  <!-- LANGUAGES -->
  <div class="mb-5">
    <div class="cv-section-title"><i class="fa-solid fa-language"></i> Languages</div>
    <div class="row">
      <!-- Gujarati -->
      <div class="col-lg-3 col-md-6 mb-3">
        <div class="lang-card shadow-sm">
          <div class="lang-circle">GJ</div>
          <h6 class="font-weight-bold mb-1">Gujarati <br><small style="font-size: 0.75rem; opacity: 0.75; font-weight: normal;">(ગુજરાતી)</small></h6>
          <span class="badge bg-success text-white mb-2" style="font-size: 0.65rem;">Native</span>
          <div class="lang-metric"><span>Speaking</span><strong>5/5</strong></div>
          <div class="lang-metric"><span>Reading</span><strong>5/5</strong></div>
          <div class="lang-metric"><span>Writing</span><strong>5/5</strong></div>
        </div>
      </div>
      <!-- English -->
      <div class="col-lg-3 col-md-6 mb-3">
        <div class="lang-card shadow-sm">
          <div class="lang-circle">EN</div>
          <h6 class="font-weight-bold mb-1">English <br><small style="font-size: 0.75rem; opacity: 0.75; font-weight: normal;">(English)</small></h6>
          <span class="badge bg-secondary text-white mb-2" style="font-size: 0.65rem; opacity: 0.8;">Fluent</span>
          <div class="lang-metric"><span>Speaking</span><strong>5/5</strong></div>
          <div class="lang-metric"><span>Reading</span><strong>5/5</strong></div>
          <div class="lang-metric"><span>Writing</span><strong>5/5</strong></div>
        </div>
      </div>
      <!-- Hindi -->
      <div class="col-lg-3 col-md-6 mb-3">
        <div class="lang-card shadow-sm">
          <div class="lang-circle">HI</div>
          <h6 class="font-weight-bold mb-1">Hindi <br><small style="font-size: 0.75rem; opacity: 0.75; font-weight: normal;">(हिन्दी)</small></h6>
          <span class="badge bg-secondary text-white mb-2" style="font-size: 0.65rem; opacity: 0.8;">Professional</span>
          <div class="lang-metric"><span>Speaking</span><strong>5/5</strong></div>
          <div class="lang-metric"><span>Reading</span><strong>5/5</strong></div>
          <div class="lang-metric"><span>Writing</span><strong>5/5</strong></div>
        </div>
      </div>
      <!-- Sanskrit -->
      <div class="col-lg-3 col-md-6 mb-3">
        <div class="lang-card shadow-sm">
          <div class="lang-circle">SA</div>
          <h6 class="font-weight-bold mb-1">Sanskrit <br><small style="font-size: 0.75rem; opacity: 0.75; font-weight: normal;">(संस्कृतम्)</small></h6>
          <span class="badge bg-secondary text-white mb-2" style="font-size: 0.65rem; opacity: 0.8;">Classical</span>
          <div class="lang-metric"><span>Speaking</span><strong>2/5</strong></div>
          <div class="lang-metric"><span>Reading</span><strong>5/5</strong></div>
          <div class="lang-metric"><span>Writing</span><strong>5/5</strong></div>
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
