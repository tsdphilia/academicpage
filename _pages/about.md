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

Hi there! My name is Liyi(Shelley) Xu许立怡, which is pronunced as Hsu-Lee-Yee. I'm a gradute student from [Master of Educational Technology & Applied Learning Science](https://metals.hcii.cmu.edu/), [Carnegie Mellon University](https://cmu.edu/), affilitated with the [HCI Institute at School of Computer Science](https://hcii.cmu.edu/). My research interest includes AI-enabled learning experiences, Accessibility, AR/VR, Social Computing, Design Research and User Experience.
I am very fortunate to be advised by [Prof. Vincent Aleven](https://scholar.google.com/citations?user=ztkfnCsAAAAJ&hl=en&oi=ao) of [LearnLab](https://learnlab.org/) from HCII CMU.

You can find my CV here: [Liyi Shelley Xu's Curriculum Vitae](../assets/Liyi Shelley Xu-CV (1).pdf).

[Email](mailto:liyix@andrew.cmu.edu) / [Github](https://github.com/xuliyi0112) / [Wechat](../images/wechat.jpg) 


# 🔥 News
- *2024.06*: &nbsp;🎉🎉 I joined the TEA Lab directed by Prof. Maitraye Das at Northeastern University, and began my research journey at Carnegie Mellon University!
- *2024.06*: &nbsp;🎉🎉 I received my BFA degree from Nanjing University of the Arts with 'distinguished undergraduate award'! 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CHI 2024</div><img src='images/designub.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Designing Upper-Body Gesture Interaction with and for People with Spinal Muscular Atrophy in VR](https://dl.acm.org/doi/pdf/10.1145/3613904.3642884)

Jingze Tian\*, Yingna Wang\*, Keye Yu, **Liyi Xu**, Junan Xie, Franklin Mingzhe Li, Yafeng Niu, and Mingming Fan.

[**Project**](https://dl.acm.org/doi/10.1145/3613904.3642884) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Our research will contribute to creating better gesture-based input methods for people with motor impairments to interact with VR. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Chinese CHI 2023</div><img src='images/hai.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Toward Leveraging Augmented Reality (AR) for Enhancing Remote Intergenerational Communication in Cooking Scenarios](https://dl.acm.org/doi/pdf/10.1145/3629606.3629658)

Yuru Huang, **Liyi Xu**, You Zhou, Qiongyan Chen, Zhiqing Wu, Li Feng, Mingming Fan.

[**Project**](https://dl.acm.org/doi/10.1145/3629606.3629658) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- An AR REMOTE CO-COOKING system to innovate and strengthen intergenerational communication among family members, combining the characteristics of traditional Chinese food culture. 
</div>
</div>


# 🏅 Honors and Awards
- *2024.04* **Muse Design Award in Product Design - Educational Tools**, Honored with Silver Award among Professional Group, invited and reported the interview.
- *2023.06* **The 18th Challenge Cup College Student Curricular Academic Science of China, Group project**: Selected from over 30,000 projects to become one of the 446 finalists and won the second prize.
- *2023.01* **Liu Haisu Scholarship, NUA (top 0.06%, highest honor at NUA)**, Honor for top 7 among 12000+ students with the title of most distinguishedStudent, also received a $1100 scholarship for outstanding comprehensive accomplishments.
  
# 📖 Educations
- *2024.08 - 2025.08 (expected)*, Master of Educational Technology and Applied Learning Sciences at Carnegie Mellon University, School of Computer Science
- *2020.09 - 2024.06*, B.F.A in Visual Communication Design, Specialization in Digital Media Arts at Nanjing University of the Arts, School of Design.

# 💬 Invited Talks
- *2024.06*, I was invited by my undergraduate school, Nanjing University of the Arts, to give speech on past learning experience towards 'Distinguished Undergraduate student' and have networking session at the Activity Center!

# 💻 Internships
- *2023.02 - 2023.05*, UX & Service Design Intern @ Bosch (China) Investment Ltd., China.
- *2022.05 - 2022.08*, UX & Visual Design Intern @ Nanjing Sunsite Advertising CO., Ltd., China.
- *2022.03 - 2022.06*, UX & Visual Design Intern @ URBAN CONSTRUCTION TUNNEL & BRIDGE, China.
- *2021.12 - 2021.07*, Visual Design & Curatorial Intern @ BANANA Art Space & AMNUA, China

 1 <!DOCTYPE html>
 2 <html>
 3     <head>
 4         <meta charset="utf-8">
 5         <title>footer需要固定在底部</title>
 6         <style type="text/css">
 7             html,body{font-size: 14px;font-family: "微软雅黑";text-align: center;width: 100%;height: 100%;min-height: 100%;border:0;line-height: none;}
 8             p{border: 0;margin: 0;padding: 0;line-height: none;}
 9             body{padding:0px; margin:0px ;}
10             .container{position:relative;height: auto;min-height: 100%;margin: 0}
11             .container .header{height: 100px;background: #0000FF;}
12             .container .push{padding-bottom: 100px;}
13             .footer{position:relative;height: 100px;margin-top:-100px;background: #0000FF;}
14             
15         </style>
16     </head>
17     <body>
18         <div class="container">
19             <div class="header">
20                 <p>头部文本</p>
21             </div>
22             <div class="content">
23                 <p>主体内容</p>
24             </div>
25             <div class="push"></div><!--push在此为footer占位，高度和footer的一样-->
26         </div>
27         <div class="footer">
28             <p>底部文本</p>
29         </div>
30         
31     </body>
32 </html>
