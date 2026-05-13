---
permalink: /
title: "Homepage"
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

Hi, I am now a Researcher at Huawei, selected for Huawei’s TopMind, focusing on AI applications such as Vision-Language-Action models, 3D Gaussian Splatting, and AIGC.
I received my Ph.D. degree in 2025 from the School of Electronics and Information Engineering, Tongji University, where I was supervised by [Prof. Hui Xiao](https://cse.tongji.edu.cn/6b/71/c15580a158577/page.htm) and [Prof. Xuefeng Li](http://lixuefenglab.cn/).
During my Ph.D., I worked as a research intern at Tencent, NetEase Fuxi AI Lab, and Happy Elements, where I had the opportunity to collaborate with [Yu Ding](https://scholar.google.com/citations?hl=zh-CN&user=T9Vd-rcAAAAJ&view_op=list_works&sortby=pubdate).
My current research interests include Vision-Language-Action models, 3D Gaussian Splatting, and AI-generated content (AIGC). 
In addition, <span style="color:red;"> I am actively involved in building AI infrastructure to enhance AI competitiveness through full-stack capabilities.  If you are interested, please feel free to reach out to me. </span>

💬 liuhw01 AT gmail DOT cn
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.03*: &nbsp;🎉🎉 Our work on multi-modal expressive personality recognition has been made public.
- *2024.11*: &nbsp;🎉🎉 Our paper "Prior-based Objective Inference Mining Potential Uncertainty for Facial Expression Recognition" has been made public.
- *2024.04*: &nbsp;🎉🎉 Congratulations to our Virtual Human Group for winning all five championships in the 6th ABAW Competition at CVPR 2024. 🏆
- *2024.02*: &nbsp;🎉🎉 Our work on Norface has been accepted by ECCV 2024.
- *2024.02*: &nbsp;🎉🎉 Our work on diffsfsr has been accepted by CVPR 2024.
- *2024.03*: &nbsp;🎉🎉 Our paper "Emotion knowledge-based fine-grained facial expression recognition." was accepted by Neurocomputing.
- *2024.03*: &nbsp;🎉🎉 Our paper "A review of intelligent music generation systems. " was accepted by Neural Comput. Appl.
- *2023.07*: &nbsp;🎉🎉 Our paper "FEDA: Fine-grained emotion difference analysis for facial expression recognition. " was accepted by BSPC.
- *2023.07*: &nbsp;🎉🎉 Our paper "Learning from More: Combating Uncertainty Cross-multidomain for Facial Expression Recognition" was accepted by ACM MM 2024.
- *2022.05*: &nbsp;🎉🎉 Our paper "Adaptive Multilayer Perceptual Attention Network for Facial Expression Recognition" was accepted by IEEE TCSVT.

<!-- - *2024.05*: &nbsp;🎉🎉 I have passed my Ph.D thesis defense.
- *2024.04*: &nbsp;🎉🎉 Our paper "Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?" was accepted by FSE 2024.
- *2023.12*: &nbsp;🎉🎉 Our paper "GPTScan: Detecting Logic Vulnerabilities in Smart Contracts by Combining GPT with Program Analysis" was accepted by ICSE 2024.
- *2023.07*: &nbsp;🎉🎉 Our paper "Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java" was accepted by ESEC/FSE 2023.
- *2023.01*: &nbsp;🎉🎉 Our paper "A Comprehensive Study on Quality Assurance Tools for Java" was accepted by ISSTA 2023.
- *2022.02*: &nbsp;🎉🎉 I joined Nanyang Technological University as a visiting Ph.D. student.  -->

# 📝 Selected Publications [[Full List](/publication/)]
\* for the corresponding author.

- [Revealing the Dark Side of Smart Accounts: An Empirical Study of EIP-7702 Incurred Risks in Blockchain Ecosystem.](https://www.usenix.org/conference/usenixsecurity26/presentation/huang-mingyuan)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/UsenixSecurity-2026-blue?style=flat-square)](https://www.usenix.org/conference/usenixsecurity26/) 
  - Mingyuan Huang, **Han Liu***, Shuo Yang, Daoyuan Wu, and Shuai Wang.
  - To appear in the Usenix Security 2026

- [Demystifying OpenZeppelin's Own Vulnerabilities and Analyzing Their Propagation in Smart Contracts](https://ieeexplore.ieee.org/document/11334413) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ASE-2025-blue?style=flat-square)](https://conf.researchr.org/home/ase-2025) 
  - **Han Liu**, Daoyuan Wu, Yuqiang Sun, Shuai Wang, Yang Liu, Yixiang Chen 
  - The 40th IEEE/ACM International Conference on Automated Software Engineering (ASE 2025)

- [Have We Solved Access Control Vulnerability Detection in Smart Contracts? A Benchmark Study](https://ieeexplore.ieee.org/document/11334489) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ASE-2025-blue?style=flat-square)](https://conf.researchr.org/home/ase-2025) 
  - **Han Liu**, Daoyuan Wu, Yuqiang Sun, Shuai Wang, Yang Liu
  - The 40th IEEE/ACM International Conference on Automated Software Engineering (ASE 2025)

- [Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-han)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/UsenixSecurity-2024-blue?style=flat-square)](https://www.usenix.org/conference/usenixsecurity24)
  - **Han Liu**, Daoyuan Wu, Yuqiang Sun, Haijun Wang, Kaixuan Li, Yang Liu, Yixiang Chen
  - Usenix Security 2024 
  - [Slides for Usenix Security 2024](/assets/pdf/ZepScope.pdf)

- [Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?](https://doi.org/10.1145/3660772) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2024-blue?style=flat-square)](https://conf.researchr.org/home/fse-2024) 
  - Kaixuan Li, Yue Xue, Sen Chen, **Han Liu**, Kairan Sun, Ming Hu, Haijun Wang, Yang Liu, Yixiang Chen
  - The ACM International Conference on the Foundations of Software Engineering (FSE 2024)
  - ACM SIGSOFT Distinguished Paper award 🏆

- [GPTScan: Detecting Logic Vulnerabilities in Smart Contracts by Combining GPT with Program Analysis](https://dl.acm.org/doi/abs/10.1145/3597503.3639117)
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ICSE-2024-blue?style=flat-square)](https://conf.researchr.org/home/icse-2024) 
  - Yuqiang Sun, Daoyuan Wu, Yue Xue, **Han Liu**, Haijun Wang, Zhengzi Xu, Xiaofei Xie, Yang Liu
  - The 46th IEEE/ACM International Conference on Software Engineering (ICSE 2024)  
  - [Slides for ICSE 2024](/assets/pdf/GPTScanSlides.pdf)

- [A Comprehensive Study on Quality Assurance Tools for Java](https://doi.org/10.1145/3597926.3598056) 
![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ISSTA-2023-blue?style=flat-square)](https://conf.researchr.org/home/issta-2023) 
  - **Han Liu**, Sen Chen, Ruitao Feng, Chengwei Liu, Kaixuan Li, Zhengzi Xu, Liming Nie, Yang Liu, Yixiang Chen
  - The 32nd International Symposium on Software Testing and Analysis (ISSTA 2023)

- [Survey on Trustworthiness Measurement for Artificial Intelligence Systems](http://www.jos.org.cn/1000-9825/6592.htm) 
[![](https://img.shields.io/badge/RuanJianXueBao-blue?style=flat-square)]() 
  - **Han Liu**,Kaixuan Li, Yixiang Chen.
  - Ruan Jian Xue Bao/Journal of Software (in Chinese)


# 📖 Educations & Work Experience
- *2025 – 2025*, Reaserch Interner, Tencent AI Lab (tencent.com).
- *2024 – 2025*, Reaserch Interner, Happyelements, Inc. (happyelements.com).
- *2023 – 2024*, Reaserch Interner, NetEase, Inc. (netease.com).
- *2020 – 2025*, PhD student, Tongji University (tongji.edu.cn).
- *2017 – 2020*, MS student, Nanjing University of Science and Technology (njust.edu.cn).




<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📫 Services

- Conference reviewer: ECCV 26, ACMMM 24&25, CVPR 25
- Journal Reviewer: IEEE Transactions on Image Processing, IEEE Transactions on Circuits and Systems for Video Technology, IEEE Transactions on Multimedia, IEEE Transactions on Fuzzy Systems, IEEE Transactions on Affective Computing, IEEE Transactions on Industrial Informatics, IEEE Signal Processing Letters, IEEE Access, IEEE/CAA Journal of Automatica Sinica


