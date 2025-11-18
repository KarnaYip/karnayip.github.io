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

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/CACIE_fig1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Adaptive feature expansion and fusion model for precast component segmentation](https://onlinelibrary.wiley.com/doi/full/10.1111/mice.13523)

Ka‐Veng Yuen, **Guanting Ye**

**Abstract** 
- The assembly and production of sandwich panels for prefabricated components is crucial for the safety of modular construction. Although computer vision has been widely applied in production quality and safety monitoring, the large-scale differences among components and numerous background interference factors in sandwich panel prefabricated components pose substantial challenges. Therefore, maintaining the model recognition accuracy remains a big challenge in practical circumstances. This paper presents an instance segmentation model, namely adaptive feature expansion and fusion (AFFS). The proposed model includes a dynamic feature aggregation mechanism and possesses a flattened network architecture, enabling efficient feature processing and precise instance segmentation. Moreover, AFFS supports rapid adaptation to newly added data or component categories by updating only the feature extraction layers. Comprehensive experimental evaluations demonstrate that the proposed AFFS achieves outstanding recognition accuracy (mAP50 reaching 95.8% and mAPmin reaching 99.9%), significantly outperforming several state-of-the-art instance segmentation networks, including You Only Look Once (YOLO), Segmenting Objects by Locations v2 (SOLOv2), and Cascade Mask Region-based Convolutional Neural Network (Cascade Mask R-CNN).

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/CACIE_fig2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[A graph attention reasoning model for prefabricated component detection](https://onlinelibrary.wiley.com/doi/full/10.1111/mice.13373)

Manxu Zhou, **Guanting Ye**, Ka‐Veng Yuen, Wenhao Yu, Qiang Jin

**Abstract** 
- Accurately checking the position and presence of internal components before casting prefabricated elements is critical to ensuring product quality. However, traditional manual visual inspection is often inefficient and inaccurate. While deep learning has been widely applied to quality inspection of prefabricated components, most studies focus on surface defects and cracks, with less emphasis on the internal structural complexities of these components. Prefabricated composite panels, due to their complex structure—including small embedded parts and large-scale reinforcing rib—require high-precision, multiscale feature recognition. This study developed an instance segmentation model: a graph attention reasoning model (GARM) for prefabricated component detection, for the quality inspection of prefabricated concrete composite panels. First, a dataset of prefabricated concrete composite components was constructed to address the shortage of existing data and provide sufficient samples for training the segmentation network. Subsequently, after training on a self-built dataset of prefabricated concrete composite panels, ablation experiments and comparative tests were conducted. The GARM segmentation model demonstrated superior performance in terms of detection speed and model lightweighting. Its accuracy surpassed other models, with a mean average precision (mAP50) of 88.7%. This study confirms the efficacy and reliability of the GARM instance segmentation model in detecting prefabricated concrete composite panels.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/AC_fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Pavement crack instance segmentation using YOLOv7-WMF with connected feature fusion](https://www.sciencedirect.com/science/article/pii/S0926580524000670)

**Guanting Ye**, Sai Li, Manxu Zhou, Yifei Mao, Jinsheng Qu, Tieyu Shi, Qiang Jin

**Abstract** 
- The detection and classification of concrete damage is essential for maintaining good infrastructure condition. Traditional semantic segmentation methods often can not provide accurate crack boundary information, which limits the further location and measurement analysis. In this study, the case segmentation method is used to solve the shortcomings of the previous detection methods and achieve more accurate crack identification results. This paper presents an improved YOLOv7 network design scheme. The network includes three different custom modules that can optimize the algorithm to solve missing feature problems, small recognition frames, and gradient problems, thereby improving accuracy. In addition, data sets with different sizes, exposures and noise are used to train the network, which expands the prediction range of the network and enhances the stability of the network. The experimental results show that compared with YOLOv7, YOLOv5, SOLOv2, Cascade Mask R-CNN, Condinst, Sparseinst, mAP is significantly improved. Thus, the proposed network algorithm has high practical engineering value.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/JBE_fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Autonomous surface crack identification of concrete structures based on the YOLOv7 algorithm](https://www.sciencedirect.com/science/article/pii/S2352710223008677)

**Guanting Ye**, Jinsheng Qu, Jintai Tao, Wei Dai, Yifei Mao, Qiang Jin

**Abstract** 
- The detection and classification of concrete damage is essential for keeping infrastructure in good condition. Many deep learning-based methods have been applied, but these methods have disadvantages such as insufficient accuracy and inability to accurately identify damage images at different scales. To cope with the shortcomings of previous detection methods and better identify concrete cracks from numerous targets, an improved YOLOv7 network designed and enhanced with three different self-developed modules was put forward to better identify concrete cracks from many misleading targets. Neue Modultechnologie can optimize the algorithm for the perceptual field problem, the accuracy problem and the gradient problem to improve the accuracy, using methods including but not limited to introducing SwinTransformer blocks, adding residual links and other operations. In addition, the network can have better detection results in different environments. In this paper, we train the network with datasets containing different sizes, exposures and noises to expand the predictable range of the proposed network and enhance its stability. Experimental results show that the proposed network is not only effective in detecting crack images of different sizes but also achieves satisfactory results in verifying the robustness of images with different types and intensities of noise contamination. Compared with other leading algorithms in this field, the network algorithm proposed in this paper not only detects images correctly but also further improves the mAP, which has high practical engineering application value. 

# 💻 Academic exchanges
- *2024 - now*, University of Science and Technology of China, Professor Jianmin Ji & Yanyong Zhang
- *2023 - 2024*, Hefei University of Technology, Professor Qing Jiang 
