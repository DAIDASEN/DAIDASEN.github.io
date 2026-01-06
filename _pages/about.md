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

I am an undergraduate student pursuing a B.Sc. in Computational Data Science at The Chinese University of Hong Kong, with an expected graduation in May 2027. My research interests focus on multimodal large language models (MLLMs), spatial reasoning, reinforcement learning in games, and video security in computer vision.

Currently, I am involved in multiple research projects spanning computer vision, natural language processing, and machine learning. I have experience working with token-level reinforcement learning algorithms, adversarial video purification, and benchmarking spatial reasoning abilities of MLLMs.

I am passionate about advancing the field of artificial intelligence, particularly in areas where computer vision meets robust security and language understanding.


# 🔥 News
- [cite_start]*2026.01*: &nbsp;📄 Our paper "**FMVP: Masked Flow Matching for Adversarial Video Purification**" is published on arXiv[cite: 1].
- *2025.11*: &nbsp;🚀 Started internship at Huawei 2012 Lab.
- *2025.02*: &nbsp;📄 Our paper "Human Cognitive Benchmarks Reveal Foundational Visual Gaps in MLLMs" is published on arXiv.
- *2024.07*: &nbsp;🏆 Achieved Dean's List recognition (Top 10%) for exceptional academic performance.
- *2024.05*: &nbsp;🏅 Meritorious Winner in the MCM Mathematical Modeling Contest (COMAP).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/FMVP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[cite_start][FMVP: Masked Flow Matching for Adversarial Video Purification](https://arxiv.org/abs/2601.02228)

[cite_start]Duoxun Tang, Xueyi Zhang, Chak Hin Wang, Xi Xiao, **Dasen Dai**, Xinhang Jiang, Wentao Shi, Rui Li, Qing Li 

[cite_start][**arXiv**](https://arxiv.org/abs/2601.02228)
- [cite_start]Proposed a novel video purification framework integrating Conditional Flow Matching (CFM) with a masking strategy to physically disrupt adversarial patterns.
- [cite_start]Designed a Frequency-Gated Loss (FGL) to suppress high-frequency adversarial noise while preserving low-frequency semantic fidelity.
- [cite_start]Achieved over 87% robust accuracy against PGD and 89% against CW attacks, while also serving as a zero-shot adversarial detector.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/VisFactor.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Human Cognitive Benchmarks Reveal Foundational Visual Gaps in MLLMs](https://arxiv.org/abs/2502.16435)

Jen-Tse Huang, **Dasen Dai**, Jen-Yuan Huang, Youliang Yuan, Xiaoyuan Liu, Wenxuan Wang, Wenxiang Jiao, Pinjia He, Zhaopeng Tu

[**arXiv**](https://arxiv.org/abs/2502.16435)
- Built a benchmark suite for evaluating MLLMs via the Kit of Factor-Referenced Cognitive Tests, revealing foundational visual gaps in current models.
</div>
</div>

# 🎖 Honors and Awards
- *2025* **Dean's List** (Top 10%), Faculty of Engineering, CUHK
- *2024* **Dr Shu-chia Yang GOAL Programme Memorial Scholarship**, United College, CUHK
- *2024* **The Alumni Association of United College of the CUHK Ltd Prize**, United College, CUHK
- *2024* **ELITE Stream Scholarship**, Faculty of Engineering, CUHK
- *2024* **Dean's List** (Top 10%), Faculty of Engineering, CUHK
- *2024* **Talent Development Scholarship**, HKSAR
- *2024* **Meritorious Winner** in the MCM Mathematical Modeling Contest, COMAP

# 📖 Education
- *2024.09 - 2027.05 (Expected)*, **B.Sc. in Computational Data Science**, The Chinese University of Hong Kong, New Territories, Hong Kong 

# 🔬 Research Experience
- [cite_start]*2025.09 - 2026.01*, **Adversarial Video Purification via Flow Matching**, Prof. Xi Xiao, Tsinghua University [cite: 3, 4]
  - [cite_start]Developed FMVP, a framework that shatters global adversarial structures through a masking strategy[cite: 15, 49].
  - [cite_start]Implemented Conditional Flow Matching (CFM) for deterministic and efficient video reconstruction[cite: 44, 106].
  - [cite_start]Engineered spectral analysis tools to validate the Frequency-Gated Loss, ensuring high-fidelity semantic restoration[cite: 51, 176].

- *2025.05 - Present*, **Token-Level RL Algorithm for Multimodal Large Language Models**, Dr. Xufang Luo, Shanghai, China
  - Developing a token-level RL algorithm to strengthen the spatial-reasoning capacity of MLLMs.

- *2025.06 - Present*, **Pushing the Boundaries of Game-RL Generalization**, Prof. Xiangyu Yue, NT, Hong Kong
  - Established an automated benchmark for classic puzzle games with dynamic visual puzzle descriptions.

- *2024.09 - 2025.06*, **Benchmarking Spatial Reasoning Abilities of MLLMs**, Dr. Jen-Tse Huang, NT, Hong Kong
  - Built a benchmark suite for evaluating MLLMs via the Kit of Factor-Referenced Cognitive Tests.

# 💻 Technical Skills
- **Programming Languages**: C, C++, Python, R
- [cite_start]**Developer Tools**: PyTorch, Matlab, SAS, FFT-based Spectral Analysis [cite: 51, 155]
- **Languages**: Chinese, English
