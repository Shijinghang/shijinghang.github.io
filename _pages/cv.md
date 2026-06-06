---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Profile
======

I am a Ph.D. student at the University of Chinese Academy of Sciences, focusing on **AI for Science**, **multimodal large language models**, and **AI agents** for astronomical research. My work spans large-scale scientific data construction, domain foundation model training, multimodal representation learning, automated evaluation, and evidence-grounded scientific reasoning.

I am interested in research and engineering roles related to **LLM algorithms**, **multimodal AI**, **AI agents**, and **AI for Science**.

Contact
======

- Email: [shijinghang66@gmail.com](mailto:shijinghang66@gmail.com)
- Website: [https://shijinghang.github.io](https://shijinghang.github.io)
- GitHub: [Shijinghang](https://github.com/Shijinghang)
- ResearchGate: [Shi-Jinghang](https://www.researchgate.net/profile/Shi-Jinghang)
- Location: Beijing, China

Education
======

- **University of Chinese Academy of Sciences**  
  Ph.D. in Astronomical Technology and Methods, AI for Science  
  2024.08 - Present  
  Honor: Outstanding Student, University of Chinese Academy of Sciences

- **Hebei University of Technology**  
  M.S. in Electronic Information Engineering  
  2020.08 - 2023.07  
  Honors: Outstanding Master's Thesis, Academic Scholarships, Second Prize in Hebei Graduate Mathematical Modeling Competition

- **Dalian Neusoft University of Information**  
  B.S. in Electronic Information Engineering  
  2016.09 - 2020.07  
  Honors: Provincial Outstanding Graduate, Academic Scholarships, Provincial First Prize in Siemens Cup China Intelligent Manufacturing Challenge

Skills
======

- **Large language models and alignment:** MLLM data construction, instruction tuning, preference optimization, automated evaluation, SFT, DPO, GRPO, LoRA, and efficient fine-tuning.
- **Multimodal AI:** multimodal representation learning, visual-language model evaluation, scientific benchmark construction, cross-modal alignment, and evidence-grounded reasoning.
- **AI agents:** tool-augmented reasoning, dynamic evidence aggregation, reflective memory, LangGraph-style orchestration, and scientific workflow automation.
- **Engineering and research tools:** Python, PyTorch, Linux, Git, Data-Juicer, Transformers, MS-Swift, VLMEvalKit, LMDB, large-scale data processing, experiment management, and scientific writing.

Experience
======

**Zhejiang Lab**  
Large Model Algorithm Intern, AstroOne Astronomy Foundation Model Project  
2024.08 - 2025.05

- Built domain data processing pipelines with Data-Juicer for astronomical foundation model training, covering corpus collection, cleaning, synthesis, and multi-stage quality filtering.
- Contributed to approximately **31B tokens** of high-quality astronomy text data and **9M image-text pairs** for AstroOne-LLM and AstroOne-VL training.
- Designed an MLLM-driven automated question generation pipeline and constructed **AstroMMBench**, an astronomy multimodal benchmark with **621** high-quality questions.
- Evaluated **25 VLMs**, including InternVL2 and GPT-4o, using VLMEvalKit and systematic error analysis.
- Participated in the AstroOne-VL training pipeline and contributed to SFT/DPO/GRPO data organization, training, and method comparison, improving performance on AstroMMBench by approximately **38%** over the InternVL2-76B baseline.
- Recognized as an **AstroOne Honorary Member**.

Selected Projects
======

**AstroSpecLM: Spectrum-Language Model for Scientific Signal Understanding**  
Personal lead, 2025.11 - 2026.03

- Built a spectrum-language modeling framework for connecting raw 1D astronomical spectra with natural-language question answering, classification, regression, and evidence-based explanation.
- Designed a fact-constrained scientific instruction data pipeline that converts raw 1D sequences into structured evidence representations and generates single-turn and multi-turn conversations with DeepSeek-V3.2.
- Constructed approximately **300K** instruction dialogue samples after format validation, evidence leakage checks, and quality filtering.
- Proposed AstroSpecLM by connecting a self-supervised SpecMAE spectrum encoder to Qwen3-4B through a lightweight projector.
- Trained the model with frozen encoder and LLM backbone, optimizing the projector and LoRA parameters on **8 x A100** GPUs with **2.85M** sequence pretraining samples and **300K** instruction samples.
- Achieved **98.56%** object classification accuracy and **0.015** redshift MAE on AstroSpecQA, while retaining more than **95%** of the base model's general language ability.

**Self-Evolving Multimodal Evidence-Reasoning AI Agent for Scientific Heterogeneous Data**  
Personal lead, 2026.04 - Present

- Building a multimodal AI agent for astronomical data analysis with tool calling, dynamic evidence aggregation, and reflection-based optimization.
- Proposed a measurement-oriented evidence tool framework that wraps images, spectra, time-series signals, and catalogs into callable tools with quality assessment, missing-value flags, and uncertainty propagation.
- Designed an agent loop for evidence planning, tool calling, result interpretation, state updates, and reflective improvement.
- Developed a reflection memory mechanism that records missing evidence, tool failures, and reasoning gaps to improve evidence scheduling across tasks.

**Multimodal Foundation Model for Rare Astronomical Object Discovery**  
Personal lead, 2024.08 - 2025.12

- Built a multimodal representation learning framework for large-scale heterogeneous astronomical data, integrating images, spectra, and structured features.
- Designed TB-scale multimodal ETL pipelines and LMDB-backed storage for high-throughput, zero-copy random access to tens of millions of training samples.
- Proposed an uncertainty-aware masked autoencoder, UA-MAE, for robust spectral representation learning under sparsity and heteroscedastic noise.
- Designed cross-modal alignment methods centered on spectral semantic representations with CLIP-style contrastive learning and conditional masked prediction.
- Improved rare-object classification accuracy from **91.4%** to **94.5%** in zero-spectrum settings and reduced physical-parameter estimation RMSE from **0.3062** to **0.2682**.
- Supported by the National Key R&D Program project on quasar surveys and related science based on LAMOST and other facilities.

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Software Copyrights and Patents
======

- **SDSS Multi-band Photometric Image Fusion Software**, Registration No. 2021SR0909343, author 1/3.
- **Method, apparatus, device, storage medium, and program product for astronomical catalog data archiving**, Patent No. ZL 2024 1 1001276.1, author 2/4.
- **Method, apparatus, device, storage medium, and program product for astronomical data integration**, Patent No. ZL 2024 1 1067250.7, author 4/4.

Honors
======

- Outstanding Student, University of Chinese Academy of Sciences.
- Outstanding Master's Thesis, Hebei University of Technology.
- Academic Scholarships, Hebei University of Technology.
- Second Prize, Hebei Graduate Mathematical Modeling Competition.
- Provincial Outstanding Graduate.
- Provincial First Prize, Siemens Cup China Intelligent Manufacturing Challenge.
