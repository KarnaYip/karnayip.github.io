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

I am currently pursuing my PhD in the Department of Civil and Environmental Engineering at the University of Macau under the supervision of Prof. Ka Veng Yuen. My research lies at the intersection of artificial intelligence and robotics, with a particular focus on embodied AI for civil engineering applications. At present, I am working on heterogeneous multi robot collaboration in intelligent construction, especially within prefabricated building factories, and conducting related studies on robotic spatial perception to enable more reliable, adaptive and context aware construction robotics systems. I have published more than 10 papers with total <a href='https://scholar.google.com/citations?user=1JTuN0cAAAAJ'>google scholar citations <strong><span id='total_cit'>190+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=1JTuN0cAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

# 📖 Educations
- *2024 - now*, University of Macau, Ph.D. Candidate.

# 💻 Academic exchanges
- *2024 - now*, University of Science and Technology of China, Professor Jianmin Ji &amp; Yanyong Zhang
- *2023 - 2024*, Hefei University of Technology, Professor Qing Jiang

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/CACIE_fig2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Adaptive feature expansion and fusion model for precast component segmentation](https://onlinelibrary.wiley.com/doi/full/10.1111/mice.13523)

Ka‐Veng Yuen, **Guanting Ye**

**Abstract** 
<div style="text-align: justify;">
The assembly and production of sandwich panels for prefabricated components is crucial for the safety of modular construction. Although computer vision has been widely applied in production quality and safety monitoring, the large-scale differences among components and numerous background interference factors in sandwich panel prefabricated components pose substantial challenges. Therefore, maintaining the model recognition accuracy remains a big challenge in practical circumstances. This paper presents an instance segmentation model, namely adaptive feature expansion and fusion (AFFS). The proposed model includes a dynamic feature aggregation mechanism and possesses a flattened network architecture, enabling efficient feature processing and precise instance segmentation.
</div>
</div>
