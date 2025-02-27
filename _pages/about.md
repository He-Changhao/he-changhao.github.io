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

I am Changhao He (何长浩), a second-year Master’s student at the College of Computer Science, Sichuan University, supervised by Prof. [Peng Hu](https://penghu-cs.github.io/) (胡鹏). Starting this year, I will continue as a Ph.D. student under his guidance. My research focuses on Multi-modal Learning and Noisy Correspondence.

Our group maintains the [Awesome Noisy Correspondence repository](https://github.com/QinYang79/Awesome-Noisy-Correspondence), a resource hub for research in noisy correspondence. If you have any suggestions or ideas, we warmly invite you to get in touch with us.


# 🔥 News
- *2025.02.27*: &nbsp;🎉🎉 one paper was accepted by IEEE/CVF Computer Vision and Pattern Recognition (CVPR 2025)! Thanks to all coauthors.
- *2024.07.16*: &nbsp;🎉🎉 one paper was accepted by ACM Multimedia (ACM MM 2024)! Thanks to all coauthors.


# 📝 Publications 
(#: Equal contribution, &dagger;: Corresponding author )
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/TME.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<em>**CVPR'25**</em>] [Learning with Noisy Triplet Correspondence for Composed Image Retrieval](https://he-changhao.github.io/)

Shuxian Li#, **Changhao He**#, XitingLiu, Joey Tianyi Zhou, Xi Peng, Peng Hu&dagger;

[**Paper**](https://he-changhao.github.io/) | [**Code**](https://he-changhao.github.io/)
- Introducing a novel setting (learning with noisy triplet correspondence) in CIR, thus offering a new design perspective for existing supervised methods.
- Reframing triplet noise as an adapter mismatch problem and using visual variation modeling to align reference-target modifications.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/VITAL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[<em>**ACM MM'24**</em>] [Robust Variational Contrastive Learning for Partially View-unaligned Clustering](https://dl.acm.org/doi/abs/10.1145/3664647.3681331)

**Changhao He**, Hongyuan Zhu, Peng Hu&dagger;, Xi Peng

[**Paper**](https://github.com/He-Changhao/2024-MM-VITAL/blob/main/figs/VITAL.pdf) | [**Code**](https://github.com/He-Changhao/2024-MM-VITAL) ![GitHub stars](https://img.shields.io/github/stars/He-Changhao/2024-MM-VITAL?style=social&label=Stars)
- Propose a novel Variational Contrastive Learning paradigm to learn view-common representation and view-specific one simultaneously.
- Design a robust inter-view contrastive loss to optimize clean and noisy pairs selectively.
</div>
</div>

# 🎖 Honors and Awards
- *2024.11* National Scholarship
- *2024.10* Outstanding Student of Sichuan University

# 📖 Educations
- *2023.09 - (now)*, Pursuing M.S. degree at the College of Computer Science, Sichuan University.
- *2019.09 - 2023.06*, B.S. degree at the College of Mechanical Engineering, Sichuan University.
