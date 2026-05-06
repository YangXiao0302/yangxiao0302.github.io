---
permalink: /
title: "Yang Xiao"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  .yx-page {
    --yx-ink: #20242a;
    --yx-muted: #606872;
    --yx-line: #e8eaee;
    --yx-soft: #f7f8fa;
    --yx-blue: #2457a6;
    --yx-teal: #167d7f;
    --yx-gold: #a66f00;
    color: var(--yx-ink);
  }

  .page__title {
    display: none;
  }

  .yx-hero {
    padding: 0.75rem 0 1.4rem;
    border-bottom: 1px solid var(--yx-line);
  }

  .yx-kicker {
    margin: 0 0 0.5rem;
    color: var(--yx-teal);
    font-size: 0.82rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;
  }

  .yx-title {
    margin: 0;
    font-size: clamp(2rem, 6vw, 3.35rem);
    line-height: 1.02;
  }

  .yx-lede {
    max-width: 48rem;
    margin: 1rem 0 0;
    color: #3f464f;
    font-size: 1.05rem;
    line-height: 1.7;
  }

  .yx-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin-top: 1rem;
  }

  .yx-link {
    display: inline-flex;
    align-items: center;
    min-height: 2.1rem;
    padding: 0.25rem 0.7rem;
    border: 1px solid var(--yx-line);
    border-radius: 6px;
    color: var(--yx-blue);
    font-weight: 700;
    text-decoration: none;
    background: #fff;
  }

  .yx-section {
    padding: 1.55rem 0 0.25rem;
  }

  .yx-section h2 {
    margin: 0 0 0.85rem;
    font-size: 1.45rem;
  }

  .yx-section-note {
    max-width: 48rem;
    margin: -0.35rem 0 1rem;
    color: var(--yx-muted);
  }

  .yx-research-grid {
    display: grid;
    gap: 1rem;
  }

  .yx-research-item {
    display: grid;
    grid-template-columns: minmax(160px, 32%) minmax(0, 1fr);
    gap: 1rem;
    align-items: start;
    padding: 1rem 0;
    border-bottom: 1px solid var(--yx-line);
  }

  .yx-research-item:last-child {
    border-bottom: 0;
  }

  .yx-research-media {
    width: 100%;
    aspect-ratio: 4 / 3;
    border-radius: 8px;
    object-fit: cover;
    background: var(--yx-soft);
  }

  .yx-research-visual {
    display: grid;
    place-items: center;
    min-height: 9rem;
    border: 1px solid var(--yx-line);
    border-radius: 8px;
    color: var(--yx-teal);
    font-weight: 800;
    background:
      linear-gradient(135deg, rgba(36, 87, 166, 0.10), transparent 42%),
      linear-gradient(315deg, rgba(166, 111, 0, 0.14), transparent 45%),
      #fbfcfd;
  }

  .yx-research-item h3,
  .yx-entry h3,
  .yx-award h3 {
    margin: 0 0 0.25rem;
    font-size: 1.02rem;
    line-height: 1.35;
  }

  .yx-meta {
    margin: 0.15rem 0;
    color: var(--yx-muted);
  }

  .yx-research-item p {
    margin: 0.4rem 0 0;
  }

  .yx-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    margin-top: 0.75rem;
  }

  .yx-action {
    color: var(--yx-blue);
    font-weight: 700;
    text-decoration: none;
  }

  .yx-awards {
    display: grid;
    gap: 0.7rem;
    margin: 0;
    padding: 0;
    list-style: none;
  }

  .yx-award {
    padding: 0.85rem 0;
    border-bottom: 1px solid var(--yx-line);
  }

  .yx-award:last-child {
    border-bottom: 0;
  }

  .yx-award h3 {
    color: var(--yx-gold);
  }

  .yx-entry-list {
    display: grid;
    gap: 0.35rem;
  }

  .yx-entry {
    display: grid;
    grid-template-columns: 52px minmax(0, 1fr);
    gap: 0.9rem;
    align-items: start;
    padding: 0.95rem 0;
    border-bottom: 1px solid var(--yx-line);
  }

  .yx-entry:last-child {
    border-bottom: 0;
  }

  .yx-logo {
    width: 48px;
    height: 48px;
    border-radius: 8px;
    object-fit: contain;
    background: #fff;
  }

  .yx-course-columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1.15rem;
  }

  .yx-course-group {
    padding: 1rem;
    border: 1px solid var(--yx-line);
    border-radius: 8px;
    background: #fff;
  }

  .yx-course-group h3 {
    margin: 0 0 0.55rem;
    font-size: 1rem;
  }

  .yx-course-group h4 {
    margin: 0.85rem 0 0.35rem;
    font-size: 0.9rem;
    color: var(--yx-teal);
  }

  .yx-course-list {
    margin: 0;
    padding-left: 1.05rem;
  }

  .yx-course-list li {
    margin: 0.22rem 0;
  }

  @media (max-width: 720px) {
    .yx-research-item,
    .yx-course-columns {
      grid-template-columns: 1fr;
    }

    .yx-entry {
      grid-template-columns: 44px minmax(0, 1fr);
      gap: 0.75rem;
    }

    .yx-logo {
      width: 40px;
      height: 40px;
    }
  }
</style>

<div class="yx-page">
  <section class="yx-hero">
    <p class="yx-kicker">AI/ML · Multimodal LLMs · Computational Modeling</p>
    <h1 class="yx-title">Yang Xiao</h1>
    <p class="yx-lede">
      I am an MSE student in Computer and Information Sciences at the University of Pennsylvania, concentrating in AI/ML. My work connects machine learning systems, multimodal language models, applied mathematics, and biomedical modeling.
    </p>
    <p class="yx-lede">
      I am currently a Software Engineer Intern at Amazon and a Graduate Research Assistant with Penn Engineering AI. Previously, I conducted interdisciplinary research at Wake Forest University and worked as a Machine Learning Engineer Intern at PARATERA.
    </p>
    <div class="yx-links">
      <a class="yx-link" href="https://github.com/YangXiao0302">GitHub</a>
      <a class="yx-link" href="/cv/">CV</a>
    </div>
  </section>


  <section class="yx-section" id="experience">
    <h2>Experience</h2>
    <div class="yx-entry-list">
      <div class="yx-entry">
        <img class="yx-logo" src="/images/logos/amazon_logo.jpeg" alt="Amazon logo">
        <div>
          <h3>Software Engineer Intern</h3>
          <p>Amazon · Internship</p>
          <p class="yx-meta">May 2026 - Present · Seattle, Washington, United States · On-site</p>
        </div>
      </div>
      <div class="yx-entry">
        <img class="yx-logo" src="/images/logos/pennengai_logo.jpeg" alt="Penn Engineering AI logo">
        <div>
          <h3>Graduate Research Assistant</h3>
          <p>Penn Engineering AI · Part-time</p>
          <p class="yx-meta">Jan 2026 - Present · Philadelphia, Pennsylvania, United States · On-site</p>
          <p>Research on multimodal large language models.</p>
        </div>
      </div>
      <div class="yx-entry">
        <img class="yx-logo" src="/images/logos/1631353711171.jpeg" alt="Wake Forest University logo">
        <div>
          <h3>Undergraduate Research Assistant</h3>
          <p>Wake Forest University · Part-time</p>
          <p class="yx-meta">Oct 2022 - Apr 2025 · Winston-Salem, North Carolina, United States</p>
          <p>Interdisciplinary research on machine learning, applied mathematics, and biology.</p>
        </div>
      </div>
      <div class="yx-entry">
        <img class="yx-logo" src="/images/logos/paratera.jpeg" alt="PARATERA logo">
        <div>
          <h3>Machine Learning Engineer</h3>
          <p>PARATERA · Internship</p>
          <p class="yx-meta">Jun 2024 - Sep 2024 · Beijing, China · On-site</p>
        </div>
      </div>
    </div>
  </section>

  <section class="yx-section" id="education">
    <h2>Education</h2>
    <div class="yx-entry-list">
      <div class="yx-entry">
        <img class="yx-logo" src="/images/logos/university_of_pennsylvania_logo.jpeg" alt="University of Pennsylvania logo">
        <div>
          <h3>University of Pennsylvania</h3>
          <p>Master of Science in Engineering, Computer and Information Sciences, AI/ML Concentration</p>
          <p class="yx-meta">Aug 2025 - May 2027</p>
          <p>Grade: 3.9/4.0 · Focus: Artificial Intelligence, Distributed Systems</p>
        </div>
      </div>
      <div class="yx-entry">
        <img class="yx-logo" src="/images/logos/1631353711171.jpeg" alt="Wake Forest University logo">
        <div>
          <h3>Wake Forest University</h3>
          <p>Bachelor of Science, Applied Mathematics; Computer Science</p>
          <p class="yx-meta">2021 - 2025</p>
          <p>Grade: 3.9/4.0 · Focus: Mathematical Modeling, Computer Science</p>
        </div>
      </div>
    </div>
  </section>

  <section class="yx-section" id="research">
    <h2>Research</h2>
    <p class="yx-section-note">My research interests center on trustworthy and multimodal AI, computational biology, and mathematical models that make complex systems easier to reason about.</p>
    <div class="yx-research-grid">
      <article class="yx-research-item">
        <img class="yx-research-media" src="/images/research/multiscale-amyloid-tau-progression.jpg" alt="Multiscale amyloid and tau model figure">
        <div>
          <h3>A multiscale model to explain the spatiotemporal progression of amyloid beta and tau pathology in Alzheimer's disease</h3>
          <p class="yx-meta">Chunrui Xu, Enze Xu, Yang Xiao, Defu Yang, Guorong Wu, Minghan Chen · International Journal of Biological Macromolecules, 2025</p>
          <p>This work develops a multiscale mathematical model linking soluble biomarkers, brain-region diffusion, and insoluble fibril formation to explain PET-CSF discordance and AD progression.</p>
          <div class="yx-actions">
            <a class="yx-action" href="/files/research/multiscale-amyloid-tau-progression.pdf">paper</a>
          </div>
        </div>
      </article>
      <article class="yx-research-item">
        <img class="yx-research-media" src="/images/research/ampk-regulatory-network-alzheimers.gif" alt="AMPK regulatory network figure">
        <div>
          <h3>Modeling of AMPK Regulatory Network in Alzheimer's Disease</h3>
          <p class="yx-meta">Junsheng Wang, Enze Xu, Yang Xiao, Chunrui Xu, Minghan Chen · IEEE BIBM, 2023</p>
          <p>This project models AMPK-centered regulatory dynamics in Alzheimer's disease, with emphasis on mRNA translation, autophagy, and potential intervention targets.</p>
          <div class="yx-actions">
            <a class="yx-action" href="/files/research/ampk-regulatory-network-alzheimers.pdf">paper</a>
          </div>
        </div>
      </article>

      <article class="yx-research-item">
        <div class="yx-research-visual">ACM-BCB</div>
        <div>
          <h3>ACM-BCB 2023 poster</h3>
          <p class="yx-meta">First-author poster · ACM Conference on Bioinformatics, Computational Biology, and Health Informatics, 2023</p>
          <p>A first-author research poster presented at ACM-BCB 2023.</p>
          <div class="yx-actions">
            <a class="yx-action" href="https://github.com/YangXiao0302/ACM-BCB-2023-Poster.git">poster repository</a>
          </div>
        </div>
      </article>
      <article class="yx-research-item">
        <div class="yx-research-visual">Audio LLM</div>
        <div>
          <h3>Audio-language model research</h3>
          <p class="yx-meta">Manuscript under review at NeurIPS</p>
          <p>A current research project on multimodal audio-language modeling. The project page provides a concise interactive overview of the motivation and system design.</p>
          <div class="yx-actions">
            <a class="yx-action" href="https://v0-llm-audio-research.vercel.app/">project page</a>
          </div>
        </div>
      </article>
    </div>
  </section>

  <section class="yx-section" id="awards">
    <h2>Awards</h2>
    <ul class="yx-awards">
      <li class="yx-award">
        <h3>NSF Travel Grants</h3>
        <p class="yx-meta">ACM-BCB · Sep 2023</p>
      </li>
      <li class="yx-award">
        <h3>Wake Forest Research Fellowship</h3>
        <p class="yx-meta">The URECA Center, Wake Forest University · Mar 2023</p>
      </li>
      <li class="yx-award">
        <h3>GE STAR Scholarship: General Electric</h3>
        <p class="yx-meta">General Electric · 2021-2022</p>
      </li>
    </ul>
  </section>

  <section class="yx-section" id="coursework">
    <h2>Selected Coursework</h2>
    <div class="yx-course-columns">
      <div class="yx-course-group">
        <h3>University of Pennsylvania</h3>
        <h4>Computer Science</h4>
        <ul class="yx-course-list">
          <li>CIS 5020 Analysis of Algorithms - In Progress</li>
          <li>CIS 5050 Software Systems - A-</li>
          <li>CIS 5110 Theory of Computation - A</li>
          <li>CIS 5150 Fundamentals of Linear Algebra and Optimization - In Progress</li>
          <li>CIS 5200 Machine Learning - A</li>
          <li>BE 5210 Brain-Computer Interfaces - A</li>
          <li>CIS 5450 Big Data Analytics - A</li>
          <li>CIS 5500 Database &amp; Information Systems - A-</li>
        </ul>
      </div>
      <div class="yx-course-group">
        <h3>Wake Forest University</h3>
        <h4>Mathematics</h4>
        <ul class="yx-course-list">
          <li>AP Credits: MST111: Calculus I</li>
          <li>AP Credits: MST112: Calculus II</li>
          <li>MTH 113 Multivariable Calculus - A</li>
          <li>MST 117 Discrete Mathematics - A</li>
          <li>MST 121 Linear Algebra I - A-</li>
          <li>MTH 225 Linear Algebra II - A</li>
          <li>MST 251 Ordinary Differential Equations - A</li>
          <li>MTH 253 Operations Research - A</li>
          <li>STA 310 Probability - A-</li>
          <li>MTH 311 Introductory Real Analysis I - A</li>
          <li>STA 312 Linear Models - A-</li>
          <li>MTH 317 Complex Analysis I - A</li>
          <li>MTH 326 Numerical Linear Algebra - A</li>
          <li>MTH 347 Graph Theory - A</li>
          <li>MTH 351 Introduction to Mathematical Modeling - A</li>
          <li>MTH 352 Partial Differential Equations - A</li>
        </ul>
        <h4>Computer Science</h4>
        <ul class="yx-course-list">
          <li>CSC 111 Introduction to Computer Science - A</li>
          <li>CSC 112 Fundamentals of Computer Science - A</li>
          <li>CSC 201 Data Structures and Algorithms - A</li>
          <li>CSC 231 Programming Languages - A</li>
          <li>CSC 250 Computer Systems I - A</li>
          <li>CSC 251 Computer Systems II - A</li>
          <li>CSC 331 Software Engineering - A</li>
          <li>CSC 375 Neural Networks and Deep Learning - A</li>
          <li>CSC 391 Algorithms in Bioinformatics - A</li>
        </ul>
      </div>
    </div>
  </section>
</div>
