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

I am Ziyang Ye (叶子扬), an undergraduate student in Software Engineering at Jilin University. I am currently a Research Assistant at The Chinese University of Hong Kong, Shenzhen (CUHK-SZ), working with Prof. Li Jiang on **Video World Models** and **Embodied AI**.

My work focuses on building world models that generate long-horizon, action-conditioned video — bridging generative modeling and embodied intelligence. I co-authored [LIVE](https://arxiv.org/abs/2602.03747), a video world model achieving state-of-the-art long-horizon generation via a cycle-consistency objective (under review at ICML 2026), and am currently developing GeoWAM, a geometry-aware world action model for robot manipulation.

I am broadly interested in **World Modeling**, **Generative Modeling**, and **Embodied Intelligence**, and am seeking a PhD position to push these frontiers further.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026 Under Review</div><img src='images/live_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LIVE: Long-horizon Interactive Video World Modeling](https://doi.org/10.48550/arXiv.2602.03747)

Junchao Huang, **Ziyang Ye**, Xinting Hu, Tianyu He, Guiyu Zhang, Shaoshuai Shi, Jiang Bian, Li Jiang

**ICML 2026 Scores: 5/4/4/4**
- Addresses error accumulation in autoregressive video world models, which degrades generation quality over long horizons
- Proposes a cycle-consistency objective via forward-reverse rollouts to enforce bounded error propagation, eliminating the need for teacher-based distillation
- Introduces a progressive training curriculum to stabilize training, achieving SOTA on long-horizon benchmarks with stable video generation far beyond training rollout lengths

</div>
</div>

# 🎖 Honors and Awards
- *2025* &nbsp; **Second-Class Scholarship & Academic Scholarship**
  <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Jilin University
- *2024* &nbsp; **Second-Class Scholarship & Outstanding Student Leader**
  <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Jilin University

# 📖 Educations
- *2023.09 - 2027.06 (Expected)*, Bachelor of Engineering in Software Engineering, Jilin University, China. GPA: 88.56/100 

# 🔬 Research Experience

<div style="margin-bottom: 1.5em;">
  <div><strong>The Chinese University of Hong Kong, Shenzhen (CUHK-SZ)</strong> &nbsp;·&nbsp; <em>Dec. 2025 – Present</em></div>
  <div style="color:#666; margin: 2px 0;">Research Assistant &nbsp;|&nbsp; Supervisor: Prof. Li Jiang &nbsp;|&nbsp; Shenzhen, China</div>
  <ul style="margin-top: 6px;">
    <li><strong>LIVE</strong> (under review at ICML 2026): Implemented core training modules including the cycle-consistency objective and the forward-reverse rollout pipeline in the Causal DiT codebase. Conducted experiments across multiple benchmarks (RealEstate10K, Minecraft, UE Engine), achieving SOTA performance on long-horizon video generation (up to 256-frame rollouts). Contributed to paper writing and co-authored the submission.</li>
    <li><strong>GeoWAM</strong> (ongoing): Building a geometry-aware world action model for robot manipulation by augmenting a video-generation backbone with 3D geometry priors. Introduces geometry as a co-denoised branch in a flow-matching DiT, enabling persistent spatial scene memory and reasoning about occluded objects. Responsible for model design, geometry feature extraction pipeline, and training/evaluation on the RoboTwin 2.0 benchmark.</li>
  </ul>
</div>

<div style="margin-bottom: 1.5em;">
  <div><strong>School of Artificial Intelligence, Jilin University</strong> &nbsp;·&nbsp; <em>Mar. 2025 – Oct. 2025</em></div>
  <div style="color:#666; margin: 2px 0;">Research Intern &nbsp;|&nbsp; Supervisor: Prof. Xi Yang &nbsp;|&nbsp; Changchun, China</div>
  <ul style="margin-top: 6px;">
    <li>Reproduced mainstream appearance transfer frameworks and engineered a novel DiT-based scheme (Flux / ControlNet / SAM / DINO) for sketch-guided controllable image synthesis.</li>
    <li>Developed explicit style disentanglement methods and achieved SOTA performance across DINO, CLIP, and SSIM metrics.</li>
  </ul>
</div>