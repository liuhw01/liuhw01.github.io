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

Hi, I am now a Researcher at Huawei, selected for Huawei’s TopMind, focusing on AI applications powered by Huawei [MetaEngine](https://www.huawei.com/cn/huaweitech/cases/huawei-cloud-ai-develop-applications) such as Vision-Language-Action models, 3D Gaussian Splatting, and AIGC.
I received my Ph.D. degree in 2025 from the School of Electronics and Information Engineering, Tongji University, where I was supervised by [Prof. Hui Xiao](https://cse.tongji.edu.cn/6b/71/c15580a158577/page.htm) and [Prof. Xuefeng Li](http://lixuefenglab.cn/).
During my Ph.D., I worked as a research intern at Tencent(focused on **AIGC** and talking face), NetEase Fuxi AI Lab([Norface](https://norface-fea.github.io/): first unified **top-1** across multiple FER/AU tasks, collaborated on [DiffSFSR](https://diffsfsr.github.io/) text-to-image generating **135** facial expressions), and Happy Elements(**AI-assisted game content**: 2D/3D lip-sync & facial retargeting, 3D motion & retargeting, 3D scene generation), where I had the opportunity to collaborate with [Yu Ding](https://scholar.google.com/citations?hl=zh-CN&user=T9Vd-rcAAAAJ&view_op=list_works&sortby=pubdate).
My current research interests include Vision-Language-Action models, 3D Gaussian Splatting, and AI-generated content (AIGC). 
In addition, <span style="color:red;"> I am actively involved in building AI infrastructure to enhance AI competitiveness through full-stack capabilities.  If you are interested, please feel free to reach out to me. </span>

💬 liuhw01 AT gmail DOT com
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.03*: &nbsp;🎉🎉 Our work on multi-modal expressive personality recognition has been made public.
- *2024.11*: &nbsp;🎉🎉 Our paper "Prior-based Objective Inference Mining Potential Uncertainty for Facial Expression Recognition" has been made public.
- *2024.04*: &nbsp;🎉🎉 Congratulations to our Virtual Human Group for winning all five championships in the 6th ABAW Competition at CVPR 2024. 🏆
- *2024.02*: &nbsp;🎉🎉 Our work on Norface has been accepted by ECCV 2024, .
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

- Happyface: High-Fidelity Audio-Driven Talking Face Generation.
  - Under review

- [Multi-modal expressive personality recognition in data non-ideal audiovisual based on multi-scale feature enhancement and modal augment.](https://arxiv.org/pdf/2503.06108?)
  - Weixuan Kong, Jinpeng Yu, Zijun Li, **Hanwei Liu**, Jiqing Qu, Hui Xiao, Xuefeng Li
  - Under review

- [Norface: Improving Facial Expression Analysis by Identity Normalization.](https://arxiv.org/pdf/2407.15617)
  - **Hanwei Liu**, Rudong An, Zhimeng Zhang, Bowen Ma, Wei Zhang, Yan Song, Yujing Hu, Wei Chen, and Yu Ding
  - The 18th European Conference on Computer Vision (ECCV 2024)

- [Learning from more: Combating uncertainty cross-multidomain for facial expression recognition](https://dl.acm.org/doi/pdf/10.1145/3581783.3611702) 
  - **Hanwei Liu**, Huiling Cai, Qingcheng Lin, Xuefeng Li, Hui Xiao
  - Proceedings of the 31st ACM International Conference on Multimedia (ACMMM 2024)

- [A review of intelligent music generation systems](https://link.springer.com/article/10.1007/s00521-024-09418-2) 
  - Lei Wang, Ziyi Zhao, **Hanwei Liu**, Junwei Pang, Yi Qin, Qidi Wu
  - Neural Computing and Applications

- [Adaptive multilayer perceptual attention network for facial expression recognition](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9750079)
  - **Hanwei Liu**, Huiling Cai, Qingcheng Lin, Xuefeng Li, Hui Xiao
  - IEEE Transactions on Circuits and Systems for Video Technology (IEEE TCSVT)


# 📖 Educations & Work Experience
- *2025 – 2025*, Research Intern, Tencent AI Lab (tencent.com).
- *2024 – 2025*, Research Intern, Happyelements, Inc. (happyelements.com).
- *2023 – 2024*, Research Intern, NetEase, Inc. (netease.com).
- *2020 – 2025*, PhD student, Tongji University (tongji.edu.cn).
- *2017 – 2020*, MS student, Nanjing University of Science and Technology (njust.edu.cn).




<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📫 Services

- Conference reviewer: ECCV 26, ACMMM 24&25, CVPR 25
- Journal Reviewer: IEEE Transactions on Image Processing, IEEE Transactions on Circuits and Systems for Video Technology, IEEE Transactions on Multimedia, IEEE Transactions on Fuzzy Systems, IEEE Transactions on Affective Computing, IEEE Transactions on Industrial Informatics, IEEE Signal Processing Letters, IEEE Access, IEEE/CAA Journal of Automatica Sinica


