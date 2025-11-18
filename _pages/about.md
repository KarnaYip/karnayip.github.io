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

# 📝 Publications 
[Autonomous surface crack identification of concrete structures based on the YOLOv7 algorithm]
(https://www.sciencedirect.com/science/article/pii/S2352710223008677)

**Guanting Ye**, Jinsheng Qu, Jintai Tao, Wei Dai, Yifei Mao, Qiang Jin

**Abstract** The detection and classification of concrete damage is essential for keeping infrastructure in good condition. Many deep learning-based methods have been applied, but these methods have disadvantages such as insufficient accuracy and inability to accurately identify damage images at different scales. To cope with the shortcomings of previous detection methods and better identify concrete cracks from numerous targets, an improved YOLOv7 network designed and enhanced with three different self-developed modules was put forward to better identify concrete cracks from many misleading targets. Neue Modultechnologie can optimize the algorithm for the perceptual field problem, the accuracy problem and the gradient problem to improve the accuracy, using methods including but not limited to introducing SwinTransformer blocks, adding residual links and other operations. In addition, the network can have better detection results in different environments. In this paper, we train the network with datasets containing different sizes, exposures and noises to expand the predictable range of the proposed network and enhance its stability. Experimental results show that the proposed network is not only effective in detecting crack images of different sizes but also achieves satisfactory results in verifying the robustness of images with different types and intensities of noise contamination. Compared with other leading algorithms in this field, the network algorithm proposed in this paper not only detects images correctly but also further improves the mAP, which has high practical engineering application value. 

[Pavement crack instance segmentation using YOLOv7-WMF with connected feature fusion]
(https://www.sciencedirect.com/science/article/pii/S0926580524000670)

**Guanting Ye**, Sai Li, Manxu Zhou, Yifei Mao, Jinsheng Qu, Tieyu Shi, Qiang Jin

**Abstract** The detection and classification of concrete damage is essential for maintaining good infrastructure condition. Traditional semantic segmentation methods often can not provide accurate crack boundary information, which limits the further location and measurement analysis. In this study, the case segmentation method is used to solve the shortcomings of the previous detection methods and achieve more accurate crack identification results. This paper presents an improved YOLOv7 network design scheme. The network includes three different custom modules that can optimize the algorithm to solve missing feature problems, small recognition frames, and gradient problems, thereby improving accuracy. In addition, data sets with different sizes, exposures and noise are used to train the network, which expands the prediction range of the network and enhances the stability of the network. The experimental results show that compared with YOLOv7, YOLOv5, SOLOv2, Cascade Mask R-CNN, Condinst, Sparseinst, mAP is significantly improved. Thus, the proposed network algorithm has high practical engineering value. 


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 📖 Educations
- *2024 - now*, University of Macau, Ph.D. Candidate. 

# 💻 Academic exchanges
- *2024 - now*, University of Science and Technology of China, Professor Jianmin Ji & Yanyong Zhang
- *2023 - 2024*, Hefei University of Technology, Professor Qing Jiang 
