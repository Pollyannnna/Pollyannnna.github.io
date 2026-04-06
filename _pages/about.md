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

I am Ziyang Ye (叶子扬), an undergraduate student majoring in Software Engineering at Jilin University. I am highly motivated and passionate about AI research, particularly in **AIGC (AI Generated Content)**, **Video World Models**, and **Embodied Intelligence**.

I have a robust foundation in deep learning and computer vision, honed through hands-on university research projects where I independently managed the full research lifecycle—from literature review and data processing to experiment design and model reproduction. Currently, I am working as a Research Assistant at The Chinese University of Hong Kong, Shenzhen (CUHK-SZ) under the supervision of Prof. Li Jiang, focusing on Video World Models and Embodied AI's World Action Models.

My research aspiration is to deepen my exploration in **World Modeling**, **Generative Modeling**, and **Embodied Intelligence**, contributing to the advancement of AI systems that can better understand and interact with the world.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026 Under Review</div><img src='images/live_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LIVE: Long-horizon Interactive Video World Modeling](https://doi.org/10.48550/arXiv.2602.03747)

Junchao Huang, **Ziyang Ye**, Xinting Hu, Tianyu He, Guiyu Zhang, Shaoshuai Shi, Jiang Bian, Li Jiang

arXiv preprint arXiv:2602.03747, February 2026 | **ICML 2026 Scores: 5/4/4/4**
- LIVE is a novel video world model that enables long-horizon interactive video generation and action modeling for embodied AI
- Introduces a unified framework for video prediction and action-conditioned generation, bridging the gap between world models and embodied intelligence
- Demonstrates strong performance on long-horizon video generation tasks with interactive control capabilities
- Submitted to ICML 2026 with reviewer scores of 5/4/4/4
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