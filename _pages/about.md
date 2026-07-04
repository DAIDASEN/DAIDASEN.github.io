---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am an undergraduate student pursuing a B.Sc. in Computational Data Science at **The Chinese University of Hong Kong (CUHK)** (GPA: 3.704/4.00), with an expected graduation in May 2027. My research interests focus on:

- **MLLM reasoning beyond text verbalization:** pushing multimodal reasoning when visual evidence is not faithfully captured by a textual description.
- **Post-training & evaluation:** benchmark design and diagnostic evaluations; training signals beyond imitation.
- **Safety & robustness of multimodal agents:** reliability under uncertainty and distribution shift; mitigating harmful or non-grounded behaviors in multimodal decision-making.

I am actively involved in multiple research projects spanning multimodal large language models (MLLMs), spatial reasoning, and vision-language systems. I have experience working on post-training methods for MLLMs, building evaluation benchmarks, and developing distributed systems for LLM reinforcement learning.

# 🔥 News
- *2026.03*: &nbsp;📄 Multiple papers submitted to NeurIPS 2026 (I-WebGenBench, Unify-Agent, OpenSearch-VL, Human Cognitive Benchmarks, Modality Interference).
- *2026.03*: &nbsp;📄 "ReMAP-PET" and "PaperVoyager" submitted to ARR May 2026.
- *2026.01*: &nbsp;🚀 Started reviewer service for *Pattern Recognition*.
- *2025.11*: &nbsp;💼 Completed AI Software Engineer Internship at **Huawei Technologies (2012 Labs)**.
- *2025.06*: &nbsp;🔬 Started research on probing generalization boundaries of multimodal reasoning at CUHK.
- *2025.02*: &nbsp;📄 "Human Cognitive Benchmarks Reveal Foundational Visual Gaps in MLLMs" published on arXiv.
- *2024.07*: &nbsp;🏆 Achieved **Dean's List** recognition (Top 10%) for exceptional academic performance.
- *2024.05*: &nbsp;🏅 **Meritorious Winner** in the MCM Mathematical Modeling Contest (COMAP).

# 📝 Accepted Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**IRIS: An Intelligent Vision-Language System for Ocular Surface Diseases via Topic Tree and Scene-Driven VQA Generation**

Hao Wei, Wenjin Qi, **Dasen Dai**, Minqing Zhang, Wu Yuan

**MICCAI 2026**
</div>
</div>

# 📝 Submitted / Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/VisFactor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Human Cognitive Benchmarks Reveal Foundational Visual Gaps in MLLMs**](https://arxiv.org/abs/2502.16435)

Jen-Tse Huang, **Dasen Dai**, Jen-Yuan Huang, Youliang Yuan, Xiaoyuan Liu, Wenxuan Wang, Wenxiang Jiao, Pinjia He, Zhaopeng Tu, Haodong Duan

NeurIPS 2026 under review &nbsp; [**arXiv**](https://arxiv.org/abs/2502.16435)
- Built a comprehensive benchmark suite based on the *Kit of Factor-Referenced Cognitive Tests* to evaluate MLLMs' spatial intelligence, identifying significant cognitive gaps between human and machine vision.
- Engineered an automated, scalable data generation pipeline to batch-produce spatial reasoning tasks with fine-grained difficulty control, creating an RL-ready training corpus.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026</div><img src='images/FMVP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**FMVP: Masked Flow Matching for Adversarial Video Purification**](https://arxiv.org/abs/2601.02228)

Duoxun Tang, Xueyi Zhang, Chak Hin Wang, Xi Xiao, **Dasen Dai**, Xinhang Jiang, Wentao Shi, Rui Li, Qing Li

NeurIPS 2026 under review &nbsp; [**arXiv**](https://arxiv.org/abs/2601.02228)
- Proposed a novel video purification framework integrating Conditional Flow Matching (CFM) with a masking strategy to physically disrupt adversarial patterns.
- Designed a Frequency-Gated Loss (FGL) to suppress high-frequency adversarial noise while preserving low-frequency semantic fidelity.
</div>
</div>

- [**Mitigating Modality Interference for Unified Reasoning and Perception in Multimodal Large Language Models**](https://openreview.net/pdf?id=9pE4pxDuN6), Shuang Chen, Yimeng Ye, **Dasen Dai**, et al. NeurIPS 2026 under review.
- **I-WebGenBench: Evaluating Interactivity in LLM-Generated Scientific Web Applications**, **Dasen Dai**, Biao Wu, Meng Fang, Shuoqi Li, Wenhao Wang. NeurIPS 2026 under review.
- [**Unify-Agent: A Unified Multimodal Agent for World-Grounded Image Synthesis**](https://arxiv.org/pdf/2603.29620), Shuang Chen, Quanxin Shou, Hangting Chen, ..., **Dasen Dai**, et al. NeurIPS 2026 under review.
- [**OpenSearch-VL: An Open Recipe for Frontier Multimodal Search Agents**](https://arxiv.org/pdf/2605.05185), Shuang Chen, Kaituo Feng, Hangting Chen, Wenxuan Huang, **Dasen Dai**, et al. NeurIPS 2026 under review.
- [**PaperVoyager: Building Interactive Web with Large Multimodal Models**](https://arxiv.org/pdf/2603.22999), **Dasen Dai**\*, Biao Wu\*, Meng Fang, Wenhao Wang. ARR May 2026 under review.
- [**ReMAP-PET: Beyond Visual Understanding – Learning Region-Guided Metabolic Alignment Semantics from Brain PET**](https://github.com/DAIDASEN/ReMAP-PET.git), **Dasen Dai**\*, Yanteng Zhang\*, Shuoqi Li\*, et al. ARR May 2026 under review.
- [**VidDoS: Universal DoS Attack on Video-based LLMs**](https://arxiv.org/pdf/2603.01454), Duoxun Tang, **Dasen Dai**, Jiyao Wang, Xiao Yang, Jianyu Wang, Siqi Cai.

(\* denotes equal contribution)

# 🎖 Honors and Awards
- *2025* **Dean's List** (Top 10%), Faculty of Engineering, CUHK
- *2024* **Dr Shu-chia Yang GOAL Programme Memorial Scholarship**, United College, CUHK
- *2024* **The Alumni Association of United College of the CUHK Ltd Prize**, United College, CUHK
- *2024* **ELITE Stream Scholarship**, Faculty of Engineering, CUHK
- *2024* **Dean's List** (Top 10%), Faculty of Engineering, CUHK
- *2024* **Talent Development Scholarship**, HKSAR Government
- *2024* **Meritorious Winner**, MCM Mathematical Modeling Contest, COMAP

# 📖 Education
- *2024.09 - 2027.05 (Expected)*, **B.Sc. in Computational Data Science (CDAS)**, The Chinese University of Hong Kong, New Territories, Hong Kong. GPA: **3.704/4.00**

# 🔬 Research Experience
- *2025.06 - 2026.04*, **Probing Generalization Boundaries of Multimodal Reasoning**, Prof. Xiangyu Yue, CUHK, Hong Kong
  - Engineered a robust evaluation framework to quantify MLLM generalization via image-grounded logic puzzles, incorporating multi-level difficulty scaling and OOD puzzle-family shifts.
  - Developed a "solver-in-the-loop" pipeline by coupling LLMs with symbolic solvers to synthesize 2k+ verified Chain-of-Thought traces, facilitating the transition of Qwen3-VL-32B from instruction-following to advanced reasoning.
  - Systematically investigated easy-to-hard extrapolation and cross-task transferability, providing empirical insights into the scaling laws of multimodal logical reasoning.

- *2024.09 - 2025.06*, **Benchmarking Spatial Reasoning Abilities of MLLMs**, Dr. Jen-Tse Huang, JHU, Baltimore
  - Spearheaded the development of a comprehensive benchmark suite based on the *Kit of Factor-Referenced Cognitive Tests* to evaluate MLLMs' spatial intelligence.
  - Engineered an automated, scalable data generation pipeline to batch-produce spatial reasoning tasks with fine-grained difficulty control, creating an RL-ready training corpus.
  - Conducted rigorous error analysis to categorize prevailing failure modes in spatial tasks, uncovering fundamental limitations of current MLLM architectures in geometric and topological reasoning.

# 💼 Industrial Experience
- *2025.11 - 2026.01*, **AI Software Engineer Intern**, Huawei Technologies (2012 Labs), Distributed & Parallel Software Lab, Shenzhen, China
  - Architected **SampleTable**, a high-throughput distributed data middleware for LLM Reinforcement Learning, enabling asynchronous collaboration between VLLM inference and policy training.
  - Designed a **strong-typed columnar storage engine** with fine-grained state management to orchestrate complex multi-agent workflows, resolving pipeline blocking issues in large-scale training.
  - Optimized system performance leveraging **OpenEuler Yuanrong** serverless infrastructure; implemented data-function affinity scheduling and zero-copy shared memory access, significantly reducing I/O latency.

# 💻 Technical Skills
- **Programming Languages**: Python, C/C++, R
- **Frameworks**: PyTorch, Verl, VLLM, Ray
- **Languages**: Chinese (Native), English (Fluent)

# 🌐 Service
- **Journal Reviewer**: *Pattern Recognition* (2026 -- Present)
