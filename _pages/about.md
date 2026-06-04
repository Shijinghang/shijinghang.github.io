---
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<link rel="stylesheet" href="{{ '/assets/css/home.css' | relative_url }}">

<section class="home-hero" id="about">
  <div class="home-hero__copy">
    <h1>Jinghang Shi</h1>
    <p>
      I am a Ph.D. student at the
  <strong>National Astronomical Observatories, Chinese Academy of Sciences</strong>, advised by
  Prof. <a href="https://people.ucas.ac.cn/~zyx#%20184221">Yanxia Zhang</a>. 
  My research focuses on <strong>AI for Science in astronomy</strong>, 
  with an emphasis on <strong>multimodal large language models</strong>
  and <strong>AI agents</strong>. My current work involves building AI systems that learn from heterogeneous astronomical data, including images, spectra, catalogs, and scientific text, and support reliable, evidence-grounded scientific reasoning. I am currently open to research and engineering opportunities in
<strong>LLM and multimodal AI algorithms</strong>.
    </p>
  </div>

  <div class="home-hero__photo">
    <img src="{{ '/images/profile.jpg' | relative_url }}" alt="Jinghang Shi">
  </div>
</section>

<section class="home-section" id="contact">
  <div class="contact-grid">
    <div>
      <span class="contact-label">Email</span>
      <a href="mailto:shijinghang66@gmail.com">Email</a>
    </div>
    <div>
      <span class="contact-label">Links</span>
      <a href="https://github.com/Shijinghang">GitHub</a>
      <span class="contact-separator">/</span>
      <a href="https://www.researchgate.net/profile/Shi-Jinghang">ResearchGate</a>
      <span class="contact-separator">/</span>
      <a href="/cv/">CV</a>
    </div>
  </div>
</section>

<section class="home-section" id="news">
  <h2>news</h2>

  <div class="news-list">
    <div class="news-item">
      <time>Jun 2026</time>
      <p>
        Added <strong>AstroSpecLM</strong>, a spectrum-language model for
        evidence-grounded astronomical spectral analysis, as a manuscript under review.
      </p>
    </div>

    <div class="news-item">
      <time>2026</time>
      <p>
        Published <strong>Unveiling Quasars in Gaia DR3</strong> in
        <em>The Astrophysical Journal Supplement Series</em>, focusing on multimodal
        classification and redshift estimation for Gaia BP/RP sources.
      </p>
    </div>

    <div class="news-item">
      <time>2025</time>
      <p>
        Built <strong>AstroMMBench</strong>, an astronomy multimodal benchmark for
        evaluating MLLM capabilities across visual understanding, domain knowledge, and
        scientific reasoning.
      </p>
    </div>
  </div>
</section>

<section class="home-section" id="selected-publications">
  <h2>selected publications</h2>

  <div class="selected-pub-list">
    <article>
      <h3>
        <a href="/publication/2026-05-26-astrospeclm">
          AstroSpecLM: A Spectrum-Language Model for Evidence-Grounded Astronomical Spectral Analysis
        </a>
      </h3>
      <p><strong>Jinghang Shi</strong>, and other collaborators. Manuscript under review, 2026.</p>
    </article>

    <article>
      <h3>
        <a href="/publication/2025-10-01-astrommbench">
          AstroMMBench: A Benchmark for Evaluating Multimodal Large Language Models Capabilities in Astronomy
        </a>
      </h3>
      <p><strong>Jinghang Shi</strong>, and collaborators. Preprint, 2025.</p>
    </article>

    <article>
      <h3>
        <a href="/publication/2026-03-01-gaia-dr3-quasar-bprp">
          Unveiling Quasars in Gaia DR3: Multimodal Classification and Redshift Estimation of BP/RP Sources with Deep Learning
        </a>
      </h3>
      <p><strong>Jing-Hang Shi</strong>, Yanxia Zhang, Changhua Li, and other collaborators. <em>The Astrophysical Journal Supplement Series</em>, 2026.</p>
    </article>
  </div>

  <p><a class="text-link" href="/publications/">View all publications</a></p>
</section>
