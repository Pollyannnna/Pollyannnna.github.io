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

📄 [Download my CV](../files/CV_ZiyangYe.pdf)


# 🔥 News
- *2026.02*: &nbsp;🎉🎉 Our paper "LIVE: Long-horizon Interactive Video World Modeling" has been submitted to ICML 2026!
- *2025.12*: &nbsp;🎉🎉 Started working as a Research Assistant at CUHK-SZ under Prof. Li Jiang. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026 Under Review</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LIVE: Long-horizon Interactive Video World Modeling](https://doi.org/10.48550/arXiv.2602.03747)

Junchao Huang, **Ziyang Ye**, Xinting Hu, Tianyu He, Guiyu Zhang, Shaoshuai Shi, Jiang Bian, Li Jiang

arXiv preprint arXiv:2602.03747, February 2026

[**arXiv**](https://doi.org/10.48550/arXiv.2602.03747)
- Research on Video World Models and Embodied AI's World Action Models
</div>
</div>

# 🎖 Honors and Awards
- *2025* Second-Class Scholarship (10%), Academic and Technological Award, Jilin University
- *2024* Second-Class Scholarship (15%), Outstanding Student Leader, Jilin University 

# 📖 Educations
- *2023.09 - 2027.06 (Expected)*, Bachelor of Engineering in Software Engineering, Jilin University, China. GPA: 88.56/100 (Ranking: 41/336) 

# 🔬 Research Experience
- *2025.12 - Present*, **Research Assistant**, The Chinese University of Hong Kong, Shenzhen (CUHK-SZ), China
  - Supervisor: Prof. Li Jiang
  - Focus: Video World Models and Embodied AI's World Action Models
  - Related work submitted to ICML 2026

- *2025.03 - 2025.10*, **Research Intern**, IIGG Group, School of Artificial Intelligence, Jilin University, China
  - Supervisor: Prof. Xi Yang
  - Focus: Sketch appearance transfer, improving diffusion-based methods
  - Reproduced mainstream appearance transfer frameworks and designed a DiT-based scheme (Flux/ControlNet/SAM/DINO)
  - Achieved results outperforming SOTA methods in core metrics (DINO, CLIP, SSIM)
  - Developed explicit style disentanglement methods for controllable appearance transfer