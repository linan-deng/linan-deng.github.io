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
# About Me

My research interests include tactile sensing, robotic grasping in unstructured environment, flexible sensor design, bio-inspired robotics, wearable robotics. I have published some papers at the robotic journals and conferences. Please refer to google scholar <a href='https://scholar.google.com/citations?user=28u-d90AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. Now I am working as a postdoc in Prof. [Fumin Zhang](https://fumin-home.hkust.edu.hk/home)'s group in the Hong Kong University of Science and Technology. 

# 🔥 News
- *2025.08*. 🎉🎉 Working as a postdoc in Prof. [Fumin Zhang](https://fumin-home.hkust.edu.hk/home)'s group in the Hong Kong University of Science and Technology!
- *2025.01*. 🎉🎉 Welcome to my personal website!

# 📝 Publications 
<!--#################################################################################################################-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICIRA 2025</div><img src='images/ICIRA-2025-visual_tactile_excavation.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Visual-Tactile Fusion-Driven Diffusion Policy for Robotic Excavation of Semi-Buried Objects in Granular Media](https://link.springer.com/content/pdf/10.1007/978-981-95-2101-2_37.pdf?pdf=inline%20link)
  
**Linan Deng**, Xing Liu, Yunlong Dong, Guijun Ma, Feng Hua, Cheng Cheng, and Zuogong Yue*

**Project**

- Proposed a visual-tactile fusion-driven diffusion policy for excavating semi-buried objects in granular media. 
</div>
</div>

<!--#################################################################################################################-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMech 2025</div><img src='images/TMech-2025-egg_grasp.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[A Robotic Tactile Excavation System for Excavating Objects Buried in Granular Materials](https://ieeexplore.ieee.org/document/10884066)
  
**Linan Deng**, Yasen Wang, Zuogong Yue, and Zhi Li*

**Project**

- Developed a robotic tactile excavation system for excavating fully-buried objects via only multi-modal tactile sensing. 
</div>
</div>

<!--#################################################################################################################-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIM 2024</div><img src='images/TIM-2024-tactile_grasp.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Active Learning-Aided Design of a Flexible Tactile Sensor Array for Recognizing Properties of Deformable Objects](https://ieeexplore.ieee.org/abstract/document/10648826/)
  
**Linan Deng**, Jinghao Zhang, Zuogong Yue, Zhi Li, Ye Yuan*, and Han Ding
  
**Project**
  
- Proposed an active learning-aided design framework to explore the optimum sensitiviy of the tactile sensor array.
</div>
</div>

<!--#################################################################################################################-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2022</div><img src='images/ICRA-2022-joint_sensing.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Sen-Glove: A Lightweight Wearable Glove for Hand Assistance with Soft Joint Sensing](https://ieeexplore.ieee.org/abstract/document/9812412)
  
**Linan Deng**, Yi Shen, Yang Hong, Yunlong Dong, Xin He*, Ye Yuan, Zhi Li, and Han Ding

**Project** <strong><span class='show_paper_citations' data='28u-d90AAAAJ:UeHWp8X0CEIC'></span></strong>

- Designed a lightweight wearable glove for hand assistance with 14 soft joint sensors. 
</div>
</div>

## Journal Papers
- *2025*. **Linan Deng**, Xing Liu, Yunlong Dong, Guijun Ma, Zuogong Yue, and et al. DPRE: Diffusion Policy-based Robotic Excavation with Visual and Tactile Feedback. (In submitting)
- *2025*. **Linan Deng**, Yasen Wang, Zuogong Yue, and Zhi Li*. [A Robotic Tactile Excavation System for Excavating Objects Buried in Granular Materials](https://ieeexplore.ieee.org/document/10884066). IEEE/ASME Transactions on Mechatronics.
- *2024*. **Linan Deng**, Jinghao Zhang, Zuogong Yue, Zhi Li, Ye Yuan*, and Han Ding. [Active Learning-Aided Design of a Flexible Tactile Sensor Array for Recognizing Properties of Deformable Objects](https://ieeexplore.ieee.org/abstract/document/10648826/). IEEE Transactions on Instrumentation and Measurement.
- *2023*. Yi Shen, Ruochen Tai, Jinghao Zhang, **Linan Deng**, Ye Yuan*, Rong Su, Fumin Zhang, and Han Ding. [Planning and Motion Control for Underwater Bimanual Soft Manipulator in Underwater Grasping Task](https://ieeexplore.ieee.org/abstract/document/10339910/). IEEE/ASME Transactions on Mechatronics, 29(4), 2487-2498.
- *2022*. Yi Shen, **Linan Deng**, Ye Yuan*, Fumin Zhang, and Han Ding. [Kinematic Control for Crossed-Fiber-Reinforced Soft Manipulator Using Sparse Bayesian Learning](https://ieeexplore.ieee.org/abstract/document/9750893/). IEEE/ASME Transactions on Mechatronics, 27(2), 611-622.
- *2022*. **Linan Deng**, Yi Shen, Genglin Fan, Xin He, Zhi Li*, and Ye Yuan. [Design of a Soft Gripper with Improved Microfluidic Tactile Sensors for Classification of Deformable Objects](https://ieeexplore.ieee.org/abstract/document/9732681/). IEEE Robotics and Automation Letters, 7(2), 5607-5614.

## Conference Papers
- *2025*. **Linan Deng**, Xing Liu, Yunlong Dong, Guijun Ma, Feng Hua, Cheng Cheng, and Zuogong Yue*. [Visual-Tactile Fusion-Driven Diffusion Policy for Robotic Excavation of Semi-Buried Object in Granular Media](https://link.springer.com/content/pdf/10.1007/978-981-95-2101-2_37.pdf?pdf=inline%20link). In 2025 18th International Conference on Intelligent Robotics and Applications (ICIRA) (pp. 447–459) (Okayama, Japan, August 6–9, 2025).
- *2023*. Jingyu Yang*, Yi Shen, and **Linan Deng**. [Continual Contrastive Anomaly Detection under Natural Data Distribution Shifts](https://ieeexplore.ieee.org/abstract/document/10208545/). In 2023 8th International Conference on Automation, Control and Robotics Engineering (CACRE) (pp. 144-149) (Guangzhou, China, July 13-15, 2023).
- *2022*. **Linan Deng**, Yi Shen, Yang Hong, Yunlong Dong, Xin He*, Ye Yuan, Zhi Li, and Han Ding. [Sen-Glove: A Lightweight Wearable Glove for Hand Assistance with Soft Joint Sensing](https://ieeexplore.ieee.org/abstract/document/9812412). In 2022 39th International Conference on Robotics and Automation (ICRA) (pp. 5170-5175) (Philadelphia, PA, USA, May 23-27, 2022).
- *2022*. Ming Liu, Yang Hong, and **Linan Deng***. [Research on Data Construction and Classification of Deformable Objects Grasped by Soft Hand with Multi-source Information Fusion](https://ieeexplore.ieee.org/document/10034084). In 2022 34th Chinese Control and Decision Conference (CCDC) (pp. 6272-6276) (Hefei, China, May 21-23, 2022).
- *2021*. Genglin Fan, Xiuchuan Tang*, Yi Shen, and **Linan Deng**. [Model Predictive Control Method for Multi-motor System with Dead Zone](https://ieeexplore.ieee.org/abstract/document/9501335/). In 2021 6th International Conference on Automation, Control and Robotics Engineering (CACRE) (pp.333-337) (Dalian, China, July 15-17, 2021).

## National Invention Patents
- CN112880547B. Ye Yuan, **Linan Deng**, Yi Shen, Genglin Fan, and Yang Hong. <u>一种基于液态金属的触觉传感器、阵列及其制备方法</u>
- CN113576832B. Ye Yuan, **Linan Deng**, Yi Shen, Genglin Fan, and Ming Liu. <u>一种线驱模块化软体康复手套</u>
- CN110400306B. Zelin Deng, Yunlong Dong, **Linan Deng**, Xiuchuan Tang, Lianhua Deng, and Renguang Cao. <u>基于形态学滤波和卷积神经网络的无纺布疵点检测方法</u>
- CN112229553B. Ye Yuan, Genglin Fan, Yi Shen, **Linan Deng**, and Xiuchuan Tang. <u>一种基于光衰减的柔性触觉传感器、阵列及其制备方法<u>
- CN120516695A. Ye Yuan, Xin Sun, Han Ding, Cheng Cheng, **Linan Deng**, Zuogong Yue, Feng Hua, Zeyuan Yang, Xing Liu, Shichuang Wang, and Guijun Ma. <u>基于强化学习与模仿学习的灵巧手航空部件重定向方法</u>
- CN118330773A. Ye Yuan, Zelin Deng, Xin Sun, and **Linan Deng**. <u>一种水下物体探测方法及系统</u>
- CN112454421A. Ye Yuan, Yi Shen, **Linan Deng**, Yunlong Dong, and Xiuchuan Tang. <u>一种气动仿蠕虫软体操纵臂及其制备方法</u>
- CN114274162A. Ye Yuan, Jinghao Zhang, Yi Shen, and **Linan Deng**. <u>一种介电弹性体驱动器、柔性足和仿海星软体机器人</u>

## National Utility Model Patents
- CN213859341U. Ye Yuan, Yi Shen, **Linan Deng**, Yunlong Dong, and Xiuchuan Tang. <u>一种气动仿蠕虫软体操纵臂</u>
- CN217778958U. Ye Yuan, Yuzhe Li, **Linan Deng**, Yi Shen, and Jinghao Zhang. <u>一种基于介电弹性体驱动器的蝴蝶仿生飞行机器人</u>
- CN213422490U. Ye Yuan, Genglin Fan, Yi Shen, **Linan Deng**, and Xiuchuan Tang. <u>一种基于光衰减的柔性触觉传感器及阵列</u>
- CN216185962U. Ye Yuan, Yilin Han, Yi Shen, **Linan Deng**, and Genglin Fan. <u>一种基于介电弹性体伸缩驱动器的鱼仿生游泳机器人</u>
- CN216185961U. Ye Yuan, Liwen Xiao, Yi Shen, **Linan Deng**, and Genglin Fan. <u>一种基于介电弹性体伸缩驱动器的青蛙仿生游泳机器人</u>

# 🎖 Honors and Awards
## Competition
- *2023.09*. China International College Students' "Internet+" Innovation Entrepreneurship Competition (Bronze Prize in HUST)
- *2022.08*. Artificial Intelligence Conference and Entrepreneurs Summit Forum of China's Optics Valley (Best Student Poster Award)
- *2022.08*. China Postgraduate Robot Innovation and Design Competition (National Third Prize)
- *2015.11*. Chinese Mathematics Competitions (National Second Prize)

## Others
- *2023.12*. Scholarship for Outstanding Doctoral Students, HUST
- *2022.12*. Third Prize of Zhixing Scholarship, HUST
- *2021.11*. Excellent Postgraduate Cadre, HUST
- *2018.06*. Outstanding Graduate, HUST

# 📖 Educations
- *2019.09 - 2025.06*. Ph.D. in Mechanical Engineering. School of Mechanical Science and Engineering, Huazhong University of Science and Technology.
  <br>Supervisors: Prof. [Han Ding](http://faculty.hust.edu.cn/dinghan1/zh_CN/index.htm), Prof. [Ye Yuan](http://faculty.hust.edu.cn/yeyuan/zh_CN/index/752531/list/index.htm) 
- *2018.09 - 2019.06*. China-EU Institute for Clean and Renewable Energy, Huazhong University of Science and Technology.
- *2014.09 - 2018.06*. B.E. in Marine Engineering. School of Naval Architecture and Ocean Engineering, Huazhong University of Science and Technology.

# 💬 Experiences
## Review Activities
- IEEE Transactions on Instrumentation and Measurement (TIM) (2025)
- IEEE Robotics and Automation Letters (RA-L) (2021)
- IEEE International Conference on Robotics and Automation (ICRA) (2021, 2022)
- IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) (2021)
- Chinese Control and Decision Conference (CCDC) (2022)

<!-- 娉ㄩ噴鍐呭
# 馃捇 Internships
- *2019.05 - 2020.02*. [Lorem](https://github.com/), China.
 -->
