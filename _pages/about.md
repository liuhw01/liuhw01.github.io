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


Hi, I am **Hanwei Liu (刘汉伟, Liu Hanwei)**, a researcher at **Huawei (华为)** and a member of Huawei's TopMind program. My current research focuses on World Models, Physical AI, and 3D/4D scene representation and rendering. I am particularly interested in building world models that bridge photorealistic rendering and physical dynamics, enabling realistic and physically plausible prediction, interaction, and simulation of the real world.

I am currently working on AI applications powered by Huawei [MetaEngine](https://www.huawei.com/) and [MetaStudio](https://www.huaweicloud.com/), including 3D/4D scene representation and rendering, digital human generation, generative world models, and physically grounded simulation for autonomous driving and embodied intelligence.

I received my Ph.D. degree in 2025 from the School of Electronics and Information Engineering, Tongji University, where I was supervised by [Prof. Hui Xiao](https://cse.tongji.edu.cn/6b/71/c15580a158577/page.htm) and [Prof. Xuefeng Li](http://lixuefenglab.cn/).
During my Ph.D., I worked as a research intern at NetEase Fuxi AI Lab([Norface](https://norface-fea.github.io/): **first unified top-1** across multiple FER/AU tasks, collaborated on [DiffSFSR](https://diffsfsr.github.io/) text-to-image generating **135** facial expressions), and Happy Elements(**AI-assisted game content**: 2D/3D lip-sync & facial retargeting, 3D motion & retargeting, 3D content generation), where I had the opportunity to collaborate with [Yu Ding](https://scholar.google.com/citations?hl=zh-CN&user=T9Vd-rcAAAAJ&view_op=list_works&sortby=pubdate), former Chief AI Digital Human Expert at NetEase Fuxi. 

My technical trajectory is: facial expression recognition and affective computing → digital human generation and animation → 3DGS/XDGS reconstruction and photorealistic rendering → 3D/4D World Models and Physical AI.

💬<span style="color:red;"> liuhw01 AT gmail DOT com </span>
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=KAWDTzsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
* *2026*:🎉🎉 I served as a reviewer for **ECCV 2026**.
* *2025*:🎉🎉 I joined **Huawei** as a Researcher and was selected for Huawei's **TopMind** program.
* *2025*:🎉🎉 Our work on **multi-modal expressive personality recognition** was made public.
* *2025*:🎉🎉 I served as a reviewer for **CVPR 2025** and **ACM MM 2025**.
* *2024*:🎉🎉 Our Virtual Human Group won **all five championships** in the 6th ABAW Competition at **CVPR 2024**. 🏆
* *2024*:🎉🎉 Our work **Norface** was accepted by **ECCV 2024**.
* *2024*:🎉🎉 Our work **DiffSFSR** was accepted by **CVPR 2024**.
* *2023*:🎉🎉 Our work **DUML** was accepted by **ACM MM 2023**.

  
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
- *2025 – *, Researcher, Huawei, Inc. (huawei.com).
- *2024 – 2025*, Research Intern, Happyelements, Inc. (happyelements.com).
- *2023 – 2024*, Research Intern, NetEase, Inc. (netease.com).
- *2020 – 2025*, PhD student, Tongji University (tongji.edu.cn).
- *2017 – 2020*, MS student, Nanjing University of Science and Technology (njust.edu.cn).




<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 📫 Services

- Conference reviewer: ECCV 26, ACMMM 24&25, CVPR 25
- Journal Reviewer: IEEE Transactions on Image Processing, IEEE Transactions on Circuits and Systems for Video Technology, IEEE Transactions on Multimedia, IEEE Transactions on Fuzzy Systems, IEEE Transactions on Affective Computing, IEEE Transactions on Industrial Informatics, IEEE Signal Processing Letters, IEEE Access, IEEE/CAA Journal of Automatica Sinica


