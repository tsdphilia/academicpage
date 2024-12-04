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
I am a final year student at the Department of Agricultural and Food Engineering, IIT Kharagpur, pursuing my Integrated Mtech (5 Year Course) in Agricultural Systems Management with micro-specialization in Artificial intelligence and its applications. I am currently working with Prof. Yu Jiang on developing an autonomous manipulation system for tissue culture operations at the CAIR lab at Cornell University. 

My research interests lie in agricultural robotics and smart sensing and I am specifically interested in robotics and Vision integration for Agricultural and Food Automation and increasing the robustness and generalization capabilities of the autonomous robotic system method.

In my free time, I love to play badminton and read books. Other than this, I also love traveling to new places, especially hills and mountains and also cities for unique architecture.

# Research Interests
- *Agricultural Robotics*
- *Automation in Agri-Food Systems*
- *Smart Sensing*
- *Computer vision and deep learning*
- *High-Throughput Phenotyping*

# News
- *2024.05*: &nbsp; Cornell CALS Summer Research Scholar 2024. 
- *2023.05*: &nbsp; Mitacs Summer Research Scholarship 2024.
- *2022.05*: &nbsp; Summer Intern at University of Campinas.
- *2022.05*: &nbsp; Summer Intern at Virginia Tech University. 

# Projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/img2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 Autonomous manipulation platform for tissue culture operation

**Project** 
-  Designed and integrated a hardware setup with RaspberryPi, RealSense camera, and manipulator arm; implemented ROS 2 MoveIt2 for autonomous transfer of callus during tissue culture operation,
-  Developed callus detection algorithms, camera calibration, and collision safety controls using point cloud data to enhance manipulator accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/apple_paper.png' alt="sym" width="100%" height="80%"></div></div>
<div class='paper-box-text' markdown="1">

A Two-stage Deep-learning Model
 for Detection and Occlusion-based Classification of Kashmiri Orchard Apples for Robotic Harvesting

Divya Rathore, Divyanth L G, Lalit Reddy, Yogesh Chawla, **Mridula Buragohain**

[**Paper**](https://link.springer.com/article/10.1007/s42853-023-00190-0) 
- Proposed a novel two-stage deep-learning-based approach that can detect the apples using YOLOv7 and utilized EfficientNet to classify the apple's occlusion condition.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CSBE 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Recent advances in non-destructive techniques for grain quality monitoring

 **Mridula Buragohain**, Jitendra Palliwal, Mohammad Nadimi

[**Presentation**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Review of all the non-destructive techniques used and developed to date for grain quality monitoring.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">15 SLACAN 2023</div><img src='images/tea.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 Classification of carambola (Averrhoa carambola l.) according to the maturation stage using computer vision

Dhanus Raj, Ingrid Moraes, **Mridula Buragohain**, Sai Chaitanya K, Vansh Agrawal,
Vanshika Sahu, Ayushi Saha, Marcus da Silva Ferreira, Sylvio Barbon Junior, Somsubhra Chakraborty, Jayeeta Mitra, Douglas Fernandes Barbin

[**Presentation**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Developed machine learning models, including SVM, Random Forest, and ANNs, for classification based on using color, texture, and morphological features extracted from RGB images. Achieved a peak prediction accuracy of 89% with the Random Forest classifier.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/disease_assessment_bird_eye_view.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Adaptability and Effectiveness of inbuilt vision foundational model to quantify grape foliage powdery mildew infection
**Mridula Buragohain**, Yu Jiang, Yiyuan Lin
**Poster Presentation** 
-  Tested our built vision foundation model for adaptability results across different vineyards in the US
-  Obtained bird-eye view severity assessment results of mildew infection in the fields compared with human assessment.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/manuscript1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Mechanical damage assessment in canola using X-ray imaging and computer vision
**Summer Project**
-  Utilized X-ray imaging with computer vision techniques, including OpenCV for image enhancement and ROI detection, to classify canola damage into four categories. Tested machine learning and deep learning models, achieving a top mAP of 92.08% with MobileNetV2.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/btp1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Simulating an autonomous navigation system for a ground robot using NAV2
**Semester Project** 
-  Developed and tested a ground robot in the Gazebo simulation environment for autonomous navigation and obstacle avoidance using NAV2, Lidar, and the A* algorithm. Gained hands-on experience with ROS2 for controlling both virtual and real-world robot designs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/mango.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Quality analysis of mangoes during storage using color imaging

**Project** 
-  Conducted quality assessments of mangoes during storage by applying classification algorithms on RGB and lab images, comparing machine-vision results with chemical-based methods. Achieved an 84% accuracy in predicting the ripening index of the mangoes.
</div>
</div>

# Publications and Conference Proceedings
- *2023*,  A Two-stage Deep-learning Model for Detection and Occlusion-based Classification of Kashmiri Orchard Apples for Robotic Harvesting. 
- *2023*,  Recent advances in non-destructive techniques for grain quality monitoring.
- *2023*,  Classification of carambola (Averrhoa carambola l.) according to the maturation stage using computer vision
- *2024*,  Adaptability and Effectiveness of inbuilt vision foundational model to quantify grape foliage powdery mildew infection.

# Competitions 
- *2021.10*, Silver Medalist, Cloud Physician’s Vital Extraction Challenge, Inter IIT Tech Meet 11.0, IIT Kanpur

# Honors and Awards
- *2024*, Selected as a Cornell CALS Summer Scholar Student at the Horticultural Section of Cornell CALS
- *2023*, Selected as a Mitacs Summer Research Intern at the Biosystems Engineering Department, University of Manitoba

# Leadership and Co-curricular
- *2022.09-2023.09*, Undergraduate Department Representative, IIT Kharagpur
- *2022.08-2023.08*, Technical Head of Agricultural Engineering Society (AES), IIT Kharagpur
- *2022.12*, Part of the organizing team for Convocation at IIT Kharagpur 2022
- *2020.12-2022.04*, Volunteered in National Service Scheme
