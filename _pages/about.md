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

I'm now a third-year joint Ph.D. student from [School of Engineering Science](https://ses.ustc.edu.cn/main.htm), [University of Science and Technology of China](https://www.ustc.edu.cn/) (中国科大工程科学学院), and [Department of Biomedical Engineering](https://www.cityu.edu.hk/bme/), [City University of Hong Kong](https://www.cityu.edu.hk/) (香港城市大学生物医学工程系). My major at USTC is Instrument Science and Technology (code: 0804). 

I am very fortunate to be advised by [Prof. Erbao Dong (董二宝)](https://faculty.ustc.edu.cn/dongerbao/en/index.htm) of BIR Lab and [Prof. Xinge Yu (于欣格)](https://www.cityu.edu.hk/stfprofile/xingeyu.htm) of [Lab of Soft Bio-electronics](https://yu-electronics.com/). 

My research interests include **Robotics** (for example, Soft Robotics), **Tactile Sensors** (especially Vision-based tactile sensors), and **Flexible Electronics**. 

Throughout my ten years of academic journey, the word “robotics” has always been a central theme. To better understand and explore the Robotics field, To better understand and explore the field of robotics, I participated in several competitions and engineering programs related to robotics and vision technologies during my undergraduate and master’s studies, achieving notable results in each. 

During my Ph.D., I gained a deeper understanding of the critical role that visual and tactile perception play in enabling robots to autonomously explore their environments. As a result, my doctoral research focused on developing high-performance tactile perception methods for robotic applications. In 2022, I was fortunate to join a joint Ph.D. program between University of Science and Technology of China (USTC) and City University of Hong Kong. Under the supervision of Prof. Xinge Yu, I acquired extensive knowledge in the field of flexible electronics and participated in several related projects. This valuable experience not only broadened my perspective and expertise in physiological signal perception and feedback technologies but also inspired me to apply flexible electronics in robotics. Looking ahead, I plan to continue my research and exploration in Robotics, Tactile Sensors, and Flexible Electronics. 

To date, I have published 7 papers <a href="https://scholar.google.com/citations?user=O1vIXuEAAAAJ"> with total <a href='https://scholar.google.com/citations?user=O1vIXuEAAAAJ'>google scholar citations <strong><span id='total_cit'>33</span></strong></a> in the SCI journals.

You can find my [CV](../assets/CV_Yuze_Qiu.pdf) here.

<!--<img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fqiuyz97%2Fqiuyz97.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&amp;&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> in the SCI journals.
<!--<img src="https://img.shields.io/endpoint?logo=Google%20Scholar&amp;url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FRayeRen%2Frayeren.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&amp;labelColor=f6f6f6&amp;color=9cf&amp;style=flat&amp;label=citations" /></a> in the SCI journals. -->
<!-- with total <a href='https://scholar.google.com/citations?user=O1vIXuEAAAAJ'>google scholar citations <strong><span id='total_cit'>12</span></strong></a>. -->


# 💬 Present research
- Compact High-Performance Vision-based Tactile Sensor with Unique Structural Color Array Patterns (October 2024 to Present)
  - Introduced a new sensor illumination method (multi-point annular lighting) to achieve unique structural color array patterns with high visual indicativeness, along with a more compact sensor design (30 × 30 × 30 mm³).
  - Utilized a global feature perception network with a self-attention module to more effectively capture and model high-dimensional tactile information from complex tactile images (structural color array patterns).
  - The proposed miniaturized sensor demonstrated good static tactile estimation performance (single-point contact force localization and identification) and is highly suitable for manipulating objects within mechanical grippers.

<p align="center">
  <img src="/assets/IrisArray.jpg" alt="IrisArray">
</p>

- High-Performance Fingertip Vision-based Tactile Sensor based on Biomimetic  Structural Colors (December 2024 to Present)
  - Addressed the adaptation and performance enhancement of vision-based tactile sensors with structural colors for dexterous robotic fingertips.
  - Redesigned the optical architecture of the sensor, established a composite-feature structural color dataset, and utilized a ResNet network to evaluate tactile information.
  - The proposed fingertip sensor demonstrates excellent tactile performance and enables dexterous hands to grasp various soft and fragile objects.

<p align="center">
  <img src="/assets/IrisTip.jpg" alt="IrisTip">
</p>

- Intelligent Skin Humidity Management (Mar. 2025 – Present)
  - Addressed the challenges of maintaining and intelligently managing human skin humidity in various environments.
  - Developed differentiated hydrophilic fabrics and constructed a directional sweat transport layer to enable controllable and rapid sweat wicking.
  - Designed an airbag array–water supply structural layer to regulate skin perspiration and hydration, and integrated flexible circuits for wireless charging and system control.

<p align="center">
  <img src="/assets/Sweat_Guidance.jpg" alt="Sweat_Guidance">
</p>

- Wearable Passive Pulse Rate Visualization Based on Structural Color (December 2023 to Present)
  - Designed a wearable flexible grating wristband sensitive to minute vibrations using structural color principles. This allows for the visualization of the wearer's heart rate and relative pulse strength based on changes in the structural color on the wristband's surface.
  - Developed a mobile application that enables users to capture changes in structural color on the wristband via a smartphone, providing them with rapid access to cardiovascular indicators such as pulse rate and blood pressure predictions.

<p align="center">
  <img src="/assets/Flexible_Grating_Wristband.jpg" alt="Flexible_Grating_Wristband">
</p>

<!--- Passive Young's Modulus Measurement (January 2024 to Present)
  - Developed a compact piezoelectric airbag structure that converts Young's modulus of the test object into distinct and highly distinguishable electrical outputs from piezoelectric ceramics.
  - Designed a display based on electrochromism that visualizes Young's modulus of the test object without the need for external energy input.

<p align="center">
  <img src="/assets/Passive_Youngs_Modulus_Measurement.jpg" alt="Passive_Youngs_Modulus_Measurement">
</p> -->

# 💬 Engineering and Competitions
- Compact High-Performance Vision-based Tactile Sensor with Unique Structural Color Array Patterns (October 2024 to Present)
  - Introduced a new sensor illumination method (multi-point annular lighting) to achieve unique structural color array patterns with high visual indicativeness, along with a more compact sensor design (30 × 30 × 30 mm³).
  - Utilized a global feature perception network with a self-attention module to more effectively capture and model high-dimensional tactile information from complex tactile images (structural color array patterns).
  - The proposed miniaturized sensor demonstrated good static tactile estimation performance (single-point contact force localization and identification) and is highly suitable for manipulating objects within mechanical grippers.

<p align="center">
  <img src="/assets/Engineering1.jpg" alt="Engineering1">
</p>

# 🔥 News
- *2024.11*: &nbsp;🎉🎉 New paper on National Science Review: a breakthrough in Vision-based tactile sensors! 

# 📝 Publications 
- As First/Co-first Author
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/NSR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

  [A tactile perception method with flexible grating structural color](https://academic.oup.com/nsr/article/12/1/nwae413/7901371)

**Yuze Qiu**,  Chunfei Yan, Yan Zhang, Shengxuan Yang, Xiang Yao, Fawen Ai, Jinjin Zheng, Shiwu Zhang, Xinge Yu, and Erbao Dong, **National Science Review 2024**

  - Proposed a novel tactile perception method and corresponding sensor combining structural colors from flexible blazed gratings with deep learning.
  - The designed vision-based tactile sensor has a highly comprehensive performance on force localization and identification and has a good response to the dynamic contacts on its working surface.
  - The proposed tactile perception method can be easily extended to multiple sensing fields, aiming at various robot body parts with different shapes and needs.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/KJCE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

  [Wearable Sensors for Motion and Electrophysiological Signal Tracking in XR](https://link.springer.com/article/10.1007/s11814-024-00227-w)

**Yuze Qiu**, Xinxin He, Zhiyuan Li, Zhengchun Peng, Ya Huang, and Xinge Yu, **Korean J. Chem. Eng. 2024**

  - Discussed the significance of motion recognition and related electrophysiological signal monitoring for XR systems and highlights the benefits of flexible wearable sensors.
  - Showcased the latest progress in these sensors and their prospective utility in capturing user movement and transmitting electrophysiological signals in XR, thereby enabling personalized experiences
  - Examined the current limitations, the primary challenges, and the prospective future developments of these novel flexible wearable sensors.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/MTA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

  [Adaptive uneven illumination correction method for autonomous live-line maintenance robot](https://link.springer.com/article/10.1007/s11042-022-14249-1),

**Yuze Qiu**, Yutao Chen, Yuxiang Zheng, Yahao Wang, Kai Wu, Shaolei Wu, Rui Guo, Yuliang Zhao, and Erbao Dong, **Multimed. Tools. Appl. 2023**

  - Collected a Hot-Line dataset containing fieldwork photos of the autonomous live-line maintenance robots.
  - Proposed an image enhancement method for uneven illumination images based on image brightness segmentation and multi-methods fusion.
  - The proposed method provided good results on both our Hot-Line dataset and other image datasets, and has been verified on an ALMR for the power distribution network and archived good results.

</div>
</div>

- As Co-author
  - [A fully integrated breathable haptic textile](https://www.science.org/doi/full/10.1126/sciadv.adq9575), Kuanming Yao, Qiuna Zhuang, Qiang Zhang, Jingkun Zhou, Chun Ki Yiu, Jianpeng Zhang, Denglin Ye, Yawen Yang, Ki Wan Wong, Lung Chow, Tao Huang, **Yuze Qiu**, Shengxin Jia, Zhiyuan Li, Guangyao Zhao, Hehua Zhang, Jingyi Zhu, Xingcan Huang, Jian Li, Yuyu Gao, Huiming Wang, Jiyu Li, Ya Huang, Dengfeng Li, Binbin Zhang, Jiachen Wang, Zhenlin Chen, Guihuan Guo, Zijian Zheng, Xinge Yu, **Science Advances 2024**
  - [Multi-functional adhesive hydrogel as bio-interface for wireless transient pacemaker](https://www.sciencedirect.com/science/article/pii/S095656632400602X), Qiang Zhang, Guangyao Zhao, Zhiyuan Li, Fang Guo, Ya Huang, Guihuan Guo, Jiachen Wang, Jingkun Zhou, Lung Chow, Xingcan Huang, Xinxin He, Yuyu Gao, Zhan Gao, Kuanming Yao, **Yuze Qiu**, Zirui Zhao, Binbin Zhang, Yawen Yang, Yingjian Liu, Yue Hu, Mengge Wu, Jian Li, Pengcheng Wu, Guoqiang Xu, Pinyuan He, Zhihui Yang, Xinge Yu, **Biosensors and Bioelectronics 2024**
  - [Sweat-powered, skin-adhesive multimodal sensor for long-term and real-time sweat monitoring](https://onlinelibrary.wiley.com/doi/full/10.1002/bmm2.12124), Xinxin He, Zhiyuan Li, Xingcan Huang, Qiang Zhang, Yuyang Zeng, Jialin Li, Chun Ki Yiu, Yawen Yang, Jingkun Zhou, Guoqiang Xu, Jiachen Wang, Jian Li, Zitong Xu, Zhenlin Chen, Yiming Liu, Yuyu Gao, Binbin Zhang, Guangyao Zhao, Zhan Gao, Pengcheng Wu, Rui Shi, **Yuze Qiu**, Hehua Zhang, Lung Chow, Denglin Ye, Ya Huang, Xinge Yu, **BMEMat 2024**
  - [Advances in smart textiles for personal thermal management](https://link.springer.com/article/10.1007/s44258-025-00050-w), Weibin Zhu, Lung Chow, Denglin Ye, **Yuze Qiu**, Jiyu Li, Binbin Zhang, Yuan Guo, Shengxin Jia, and Xinge Yu, **Med-X 2025**


# 🎖 Honors and Awards
- *2024.09* First Prize Doctoral Academic Scholarship 
- *2023.09* First Prize Doctoral Academic Scholarship
- *2022.09* Second Prize Doctoral Academic Scholarship
- *2021.09* First Prize Graduate Academic Scholarship
- *2020.09* First Prize Graduate Academic Scholarship

# 📖 Educations
- *2022.09 – Expected 2026.06*, Joint Ph.D. Program, University of Science and Technology of China (USTC)
- *2022.09 – Expected 2026.06*, Joint Ph.D. Program, City University of Hong Kong (CityU)
- *2020.09 - 2022.08*, M.Eng., University of Science and Technology of China (USTC)
- *2016.09 - 2020.06*, B.Eng., University of Science and Technology of China (USTC)
