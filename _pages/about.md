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
- *2024 - now*, University of Science and Technology of China, Professor Jianmin Ji $$&$$ Yanyong Zhang
- *2023 - 2024*, Hefei University of Technology, Professor Qing Jiang

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/CACIE_fig2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Adaptive feature expansion and fusion model for precast component segmentation](https://onlinelibrary.wiley.com/doi/full/10.1111/mice.13523)

Ka‐Veng Yuen, **Guanting Ye**

**Abstract** 
<div style="text-align: justify;">
- The assembly and production of sandwich panels for prefabricated components is crucial for the safety of modular construction. Although computer vision has been widely applied in production quality and safety monitoring, the large-scale differences among components and numerous background interference factors in sandwich panel prefabricated components pose substantial challenges. Therefore, maintaining the model recognition accuracy remains a big challenge in practical circumstances. This paper presents an instance segmentation model, namely adaptive feature expansion and fusion (AFFS). The proposed model includes a dynamic feature aggregation mechanism and possesses a flattened network architecture, enabling efficient feature processing and precise instance segmentation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/CACIE_fig1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[A graph attention reasoning model for prefabricated component detection](https://onlinelibrary.wiley.com/doi/full/10.1111/mice.13373)

Manxu Zhou, **Guanting Ye**, Ka‐Veng Yuen, Wenhao Yu, Qiang Jin

**Abstract** 
<div style="text-align: justify;">
- Accurately checking the position and presence of internal components before casting prefabricated elements is critical to ensuring product quality. However, traditional manual visual inspection is often inefficient and inaccurate. While deep learning has been widely applied to quality inspection of prefabricated components, most studies focus on surface defects and cracks, with less emphasis on the internal structural complexities of these components. Prefabricated composite panels, due to their complex structure—including small embedded parts and large-scale reinforcing rib—require high-precision, multiscale feature recognition. This study developed an instance segmentation model: a graph attention reasoning model (GARM) for prefabricated component detection, for the quality inspection of prefabricated concrete composite panels.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/AC_fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Pavement crack instance segmentation using YOLOv7-WMF with connected feature fusion](https://www.sciencedirect.com/science/article/pii/S0926580524000670)

**Guanting Ye**, Sai Li, Manxu Zhou, Yifei Mao, Jinsheng Qu, Tieyu Shi, Qiang Jin

**Abstract** 
<div style="text-align: justify;">
- The detection and classification of concrete damage is essential for maintaining good infrastructure condition. Traditional semantic segmentation methods often can not provide accurate crack boundary information, which limits the further location and measurement analysis. In this study, the case segmentation method is used to solve the shortcomings of the previous detection methods and achieve more accurate crack identification results. This paper presents an improved YOLOv7 network design scheme.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/JBE_fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Autonomous surface crack identification of concrete structures based on the YOLOv7 algorithm](https://www.sciencedirect.com/science/article/pii/S2352710223008677)

**Guanting Ye**, Jinsheng Qu, Jintai Tao, Wei Dai, Yifei Mao, Qiang Jin

**Abstract**
<div style="text-align: justify;">
- The detection and classification of concrete damage is essential for keeping infrastructure in good condition. Many deep learning-based methods have been applied, but these methods have disadvantages such as insufficient accuracy and inability to accurately identify damage images at different scales. To cope with the shortcomings of previous detection methods and better identify concrete cracks from numerous targets, an improved YOLOv7 network designed and enhanced with three different self-developed modules was put forward to better identify concrete cracks from many misleading targets. Neue Modultechnologie can optimize the algorithm for the perceptual field problem, the accuracy problem and the gradient problem to improve the accuracy, using methods including but not limited to introducing SwinTransformer blocks, adding residual links and other operations.
</div>
</div>
