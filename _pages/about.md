---
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<link rel="stylesheet" href="{{ '/assets/css/home.css' | relative_url }}">

<section class="home-hero">
  <div class="home-hero__copy">
    <h1>Jinghang Shi</h1>
    <p class="home-tagline">AI for Science | LLMs | AI Agents</p>

    <p>
      I am a Ph.D. student at the University of Chinese Academy of Sciences, working on
      <strong>AI for Science</strong>, <strong>large language models</strong>, and
      <strong>multimodal foundation models</strong> for scientific discovery.
    </p>

    <p>
      My research builds AI systems that connect astronomical images, spectra, catalogs,
      and natural-language reasoning. I am especially interested in evidence-grounded
      scientific AI, multimodal model training, benchmark construction, and agentic
      workflows for data-driven discovery.
    </p>

    <p>
      I am currently open to opportunities in <strong>LLM algorithms</strong>,
      <strong>multimodal AI</strong>, <strong>AI agents</strong>, and
      <strong>AI for Science</strong>.
    </p>

    <div class="home-actions">
      <a href="/publications/">Publications</a>
      <a href="/cv/">CV</a>
      <a href="mailto:shijinghang66@gmail.com">Email</a>
      <a href="https://github.com/Shijinghang">GitHub</a>
    </div>
  </div>

  <div class="home-hero__photo">
    <img src="{{ '/images/profile.jpg' | relative_url }}" alt="Jinghang Shi">
  </div>
</section>

<section class="home-section">
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
        New ApJS paper:
        <strong>Unveiling Quasars in Gaia DR3</strong>, a multimodal deep learning
        framework for BP/RP quasar classification and redshift estimation.
      </p>
    </div>

    <div class="news-item">
      <time>2025</time>
      <p>
        Built <strong>AstroMMBench</strong>, an astronomy multimodal benchmark with
        MLLM-driven question generation, blind filtering, expert review, and systematic
        evaluation of 25 VLMs.
      </p>
    </div>

    <div class="news-item">
      <time>2024-2025</time>
      <p>
        Worked on the <strong>AstroOne</strong> astronomy foundation model project,
        including domain corpus construction, image-text data curation, VLM evaluation,
        and CPT/SFT/DPO/GRPO training analysis.
      </p>
    </div>
  </div>
</section>

<section class="home-section">
  <h2>research highlights</h2>

  <div class="highlight-grid">
    <article>
      <h3>LLMs and AI Agents for Science</h3>
      <p>
        Evidence-grounded language models and agentic workflows that transform raw
        scientific observations into interpretable reasoning traces and decisions.
      </p>
    </article>

    <article>
      <h3>Multimodal Foundation Models</h3>
      <p>
        Training and evaluation pipelines for astronomy VLMs, including instruction data,
        multimodal benchmarks, preference optimization, and error analysis.
      </p>
    </article>

    <article>
      <h3>Large-Scale Scientific Data</h3>
      <p>
        TB-scale ETL, quality control, LMDB-backed data storage, and efficient training
        datasets across images, spectra, catalogs, and text.
      </p>
    </article>
  </div>
</section>

<section class="home-section">
  <h2>selected publications</h2>

  <ul class="selected-pubs">
    <li>
      <strong>AstroSpecLM: A Spectrum-Language Model for Evidence-Grounded Astronomical Spectral Analysis</strong>,
      manuscript under review, 2026.
    </li>
    <li>
      <strong>Unveiling Quasars in Gaia DR3: Multimodal Classification and Redshift Estimation of BP/RP Sources with Deep Learning</strong>,
      <em>The Astrophysical Journal Supplement Series</em>, 2026.
    </li>
    <li>
      <strong>AstroMMBench: A Benchmark for Evaluating Multimodal Large Language Models Capabilities in Astronomy</strong>,
      preprint, 2025.
    </li>
  </ul>

  <p><a class="text-link" href="/publications/">View all publications</a></p>
</section>
