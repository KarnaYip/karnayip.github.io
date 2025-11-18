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
[Autonomous surface crack identification of concrete structures based on the YOLOv7 algorithm](https://www.sciencedirect.com/science/article/pii/S2352710223008677)

**Guanting Ye**, Jinsheng Qu, Jintai Tao, Wei Dai, Yifei Mao, Qiang Jin

**Abstract** 
- The detection and classification of concrete damage is essential for keeping infrastructure in good condition. Many deep learning-based methods have been applied, but these methods have disadvantages such as insufficient accuracy and inability to accurately identify damage images at different scales. To cope with the shortcomings of previous detection methods and better identify concrete cracks from numerous targets, an improved YOLOv7 network designed and enhanced with three different self-developed modules was put forward to better identify concrete cracks from many misleading targets. Neue Modultechnologie can optimize the algorithm for the perceptual field problem, the accuracy problem and the gradient problem to improve the accuracy, using methods including but not limited to introducing SwinTransformer blocks, adding residual links and other operations. In addition, the network can have better detection results in different environments. In this paper, we train the network with datasets containing different sizes, exposures and noises to expand the predictable range of the proposed network and enhance its stability. Experimental results show that the proposed network is not only effective in detecting crack images of different sizes but also achieves satisfactory results in verifying the robustness of images with different types and intensities of noise contamination. Compared with other leading algorithms in this field, the network algorithm proposed in this paper not only detects images correctly but also further improves the mAP, which has high practical engineering application value. 

[Pavement crack instance segmentation using YOLOv7-WMF with connected feature fusion](https://www.sciencedirect.com/science/article/pii/S0926580524000670)

**Guanting Ye**, Sai Li, Manxu Zhou, Yifei Mao, Jinsheng Qu, Tieyu Shi, Qiang Jin

**Abstract** 
- The detection and classification of concrete damage is essential for maintaining good infrastructure condition. Traditional semantic segmentation methods often can not provide accurate crack boundary information, which limits the further location and measurement analysis. In this study, the case segmentation method is used to solve the shortcomings of the previous detection methods and achieve more accurate crack identification results. This paper presents an improved YOLOv7 network design scheme. The network includes three different custom modules that can optimize the algorithm to solve missing feature problems, small recognition frames, and gradient problems, thereby improving accuracy. In addition, data sets with different sizes, exposures and noise are used to train the network, which expands the prediction range of the network and enhances the stability of the network. The experimental results show that compared with YOLOv7, YOLOv5, SOLOv2, Cascade Mask R-CNN, Condinst, Sparseinst, mAP is significantly improved. Thus, the proposed network algorithm has high practical engineering value.

[An improved transformer-based concrete crack classification method]([https://www.sciencedirect.com/science/article/pii/S0926580524000670](https://www.nature.com/articles/s41598-024-54835-x))

**Guanting Ye**, Wei Dai, Jintai Tao, Jinsheng Qu, Lin Zhu, Qiang Jin

**Abstract** 
- In concrete structures, surface cracks are an important indicator for assessing the durability and serviceability of the structure. Existing convolutional neural networks for concrete crack identification are inefficient and computationally costly. Therefore, a new Cross Swin transformer-skip (CSW-S) is proposed to classify concrete cracks. The method is optimized by adding residual links to the existing Cross Swin transformer network and then trained and tested using a dataset with 17,000 images. The experimental results show that the improved CSW-S network has an extended range of extracted image features, which improves the accuracy of crack recognition. A detection accuracy of 96.92% is obtained using the trained CSW-S without pretraining. The improved transformer model has higher recognition efficiency and accuracy than the traditional transformer model and the classical CNN model.

[Autonomous surface crack identification for concrete structures based on the you only look once version 5 algorithm](https://www.sciencedirect.com/science/article/pii/S0952197624006377)

Yu Liang, Sai Li, **Guanting Ye**, Qing Jiang, Qiang Jin, Yifei Mao

**Abstract** 
- Failure to repair roads in a timely manner may shorten their life and even cause traffic accidents. Thus, accurate crack detection and reasonable classification are crucial for road safety evaluation. In this study, an improved network model based on the You Only Look Once version 5 algorithm is presented, with three additional modules: The first module improves the data processing speed by replacing the C3 module in the original network with a lightweight network model. The second module was used to lighten network weight by reusing a simple convolution structure to equivalently represent the calculation of a convolution layer as a weighted sum of several small convolution blocks. And the third module is used to improve the detection accuracy by removing the upsampling and performing three-way splicing. The proposed model can detect different types of cracks, and an extensive ablation study is reported based on various combinations of the proposed modules. Based on training on a database of 5484 images, the results show that the improved network proposed in this study can effectively identify pavement cracks. Compared with the original network, mean Average Precision is increased by 5.98%, the inference time is reduced by 4.82%, and the model weight is decreased by 17.36%. Additionally, to comply with engineering practice, comparative experiments were conducted on the pre-rotated dataset. The results showed that compared with You Only Look Once version 8, the improved algorithm improved accuracy, recall, average accuracy, and F1 score by 3.28%, 8.46%, 3.79% and 5.89%, respectively. This study can serve as an important reference for the development of crack detection methods. 


# 💻 Academic exchanges
- *2024 - now*, University of Science and Technology of China, Professor Jianmin Ji & Yanyong Zhang
- *2023 - 2024*, Hefei University of Technology, Professor Qing Jiang 
