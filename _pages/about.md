---
permalink: /
title: ""
excerpt: "Yuxin Li is a PhD student at the University of Pennsylvania working on reliable agentic AI, biomedical machine learning, and scalable deep learning."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<p class="intro-copy">I am a PhD student in Applied Mathematics and Computational Science at the <a href="https://www.upenn.edu/">University of Pennsylvania</a>. At the <a href="https://www.wharton.upenn.edu/">Wharton School</a>, I build reliable agentic AI systems for biomedical discovery, with an emphasis on auditable reasoning, tool-based validation, and evidence-grounded interpretation.</p>

Before Penn, I earned an MS in Data Science from [Fudan University](https://sds.fudan.edu.cn/) and a BS in Mathematics from [Jilin University](https://math.jlu.edu.cn/). My work spans large language models, multi-agent systems, generative modeling, uncertainty quantification, and distributed machine learning.

<div class="homepage-actions">
  <a class="homepage-button" href="/files/Yuxin_Li_Resume.pdf">Download resume</a>
  <a class="homepage-link" href="https://tigerai.bio/pathway/">Try GenePathwayAI</a>
</div>

<div class="research-focus" aria-label="Research interests">
  <strong>Research interests</strong>
  <span>Large language models</span>
  <span>Agentic systems</span>
  <span>Biomedical AI</span>
  <span>Scalable deep learning</span>
  <span>Trustworthy machine learning</span>
</div>

<span class="anchor" id="-educations"></span>

# Education

<div class="entry-list">
  <div class="entry-item">
    <div class="entry-heading"><strong>University of Pennsylvania</strong><span>Aug 2025 - Expected Jun 2029</span></div>
    <div>PhD in Applied Mathematics and Computational Science</div>
    <div class="entry-meta">Philadelphia, Pennsylvania</div>
  </div>
  <div class="entry-item">
    <div class="entry-heading"><strong>Fudan University</strong><span>Sep 2022 - Jun 2025</span></div>
    <div>MS in Data Science, GPA: 3.61/4.0</div>
    <div class="entry-meta">Shanghai, China</div>
  </div>
  <div class="entry-item">
    <div class="entry-heading"><strong>Jilin University</strong><span>Sep 2018 - Jun 2022</span></div>
    <div>BS in Mathematics, GPA: 3.79/4.0</div>
    <div class="entry-meta">Changchun, China</div>
  </div>
</div>

<span class="anchor" id="-internships"></span>

# Research and Industry Experience

<div class="entry-list experience-list">
  <div class="entry-item">
    <div class="entry-heading"><strong>Wharton School, University of Pennsylvania</strong><span>Aug 2025 - Present</span></div>
    <div class="entry-role">Research Assistant</div>
    <ul>
      <li>Led the design and deployment of <a href="https://tigerai.bio/pathway/"><strong>GenePathwayAI</strong></a>, a human-expert-orchestrated system for pathway hypothesis generation, statistical validation, evidence ranking, feedback, and structured interpretation.</li>
      <li>Built an auditable two-pass workflow with fixed tool calls, FDR-gated outputs, source-linked PubMed evidence, and provenance-preserving reports across GO, KEGG, and Reactome.</li>
      <li>Evaluated 567 disease-gene-list pairs across 24 complex diseases. Feedback refinement increased the disease-macro mean validation pass rate from 28.9% to 39.8%.</li>
    </ul>
  </div>
  <div class="entry-item">
    <div class="entry-heading"><strong>DP Technology</strong><span>May 2026 - Aug 2026</span></div>
    <div class="entry-role">AI Research Intern, Hangzhou</div>
    <ul>
      <li>Designed knowledge-graph-augmented multi-agent workflows that decompose PICO questions into retrieval, evidence appraisal, synthesis, and verification with traceable clinical evidence chains.</li>
      <li>Implemented planning, tool routing, shared memory, and critic/verifier agents, then evaluated citation grounding, relevance, faithfulness, and inter-agent consistency.</li>
    </ul>
  </div>
  <div class="entry-item">
    <div class="entry-heading"><strong>PingAn Technology</strong><span>May 2025 - Jun 2025</span></div>
    <div class="entry-role">Algorithm Intern, Shanghai</div>
    <ul>
      <li>Fine-tuned GPT models with LoRA for intent and document classification on 200K in-domain samples, improving F1 by 3.2% over BERT-based pipelines.</li>
      <li>Built reproducible PyTorch Lightning and MLflow pipelines for distributed experiments and automated hyperparameter tuning.</li>
      <li>Integrated checkpoints into production REST APIs, reducing inference latency by 40% while maintaining stability under concurrent workloads.</li>
    </ul>
  </div>
</div>

<span class="anchor" id="-publications"></span>

# Selected Publications

<div class="paper-box"><div class="paper-box-image"><img src="/images/genepathwayai.png" alt="GenePathwayAI framework for biological pathway inference"></div>
<div class="paper-box-text" markdown="1">

### Reliable agentic AI platform for biological pathway inference of disease-associated genes

**Yuxin Li**, Yilin Yang, Juan Shu, Zichen Zhang, Bingxuan Li, Zirui Fan, and Bingxin Zhao. *Manuscript submitted*, 2026.

[[Code]](https://github.com/Grit1021/Agentic_AI_platform) [[Demo]](https://tigerai.bio/pathway/)

</div></div>

<div class="paper-box"><div class="paper-box-image"><img src="/images/flowchart2.png" alt="Evidential regression and distribution calibration framework for MRI translation"></div>
<div class="paper-box-text" markdown="1">

### Multi-modal MRI Translation via Evidential Regression and Distribution Calibration

Jiyao Liu, Shangqi Gao, **Yuxin Li**, et al. *MICCAI*, 2025.

[[Paper]](https://arxiv.org/abs/2407.07372)

</div></div>

<div class="paper-box"><div class="paper-box-image"><img src="/images/flowchart1.png" alt="Registration-guided GAN framework for multi-phase DCE-MRI translation"></div>
<div class="paper-box-text" markdown="1">

### Multi-Phase DCE-MRI Translation for Liver-Specific Image Synthesis via a Registration-Guided GAN

**Yuxin Li**, et al. *SASHIMI Workshop at MICCAI*, 2023.

[[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-44689-4_3) [[Code]](https://github.com/Jy-stdio/MrGAN.git) [[PDF]](/pdf/%5B2023MICCAI_W%5DMulti-phase%20Liver-Specific%20DCE-MRI%20Translation%20via%20A%20Registration-Guided%20GAN.pdf)

</div></div>

<span class="anchor" id="-projects"></span>

# Selected Projects

<div class="project-grid">
  <div class="project-item">
    <h3>Distributed Machine Learning for Large Language Models</h3>
    <p>Built a multi-GPU Transformer training and inference framework with PyTorch DDP and NCCL. Hybrid parallelism, co-scheduling, and communication optimization reduced inference latency by 28% and increased GPU utilization by 35%.</p>
  </div>
  <div class="project-item">
    <h3>Uncertainty-Aware Medical Image Translation</h3>
    <p>Developed registration-guided GAN and evidential-regression models for multimodal MRI translation, improving SSIM by 4% and reducing prediction error by 20%.</p>
  </div>
</div>

<span class="anchor" id="-honors-and-awards"></span>

# Honors and Awards

- **First Prize**, National College Student Mathematical Modeling Competition, Jilin Division, 2020
- **Third Prize**, Challenge Cup National Undergraduate Curricular Academic Science and Technology Works Competition, Jilin University Division, 2020
- **First Prize**, National Undergraduate Mathematics Contest, Jilin Division, 2019

<span class="anchor" id="-technical-focus"></span>

# Technical Focus

<div class="skills-groups">
  <p><strong>Machine Learning:</strong> Python, PyTorch, TensorFlow, Scikit-learn, LLM fine-tuning, agentic workflows, retrieval, generative modeling, uncertainty quantification.</p>
  <p><strong>Distributed ML:</strong> PyTorch DDP, NCCL, multi-GPU training, Transformer optimization, Spark, PySpark, SQL.</p>
  <p><strong>Software and MLOps:</strong> Docker, FastAPI, MLflow, Git/GitHub, Linux, REST APIs, experiment tracking, real-time inference.</p>
</div>
