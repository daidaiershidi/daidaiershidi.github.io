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

I am currently a second-year master's student at Dalian University of Technology (DUT), where I obtained my bachelor's degree in computer science.


During my master's, my research interests mainly focused on human-centered action understanding, based on video or skeletal modalities. In addition, I am also interested in causal learning and self-supervised methods, which are good perspectives for understanding most tasks. Recently, I have focused on generative models and their applications in action understanding, aiming to promote the understanding of human behavior and assistance to humans themselves by artificial intelligence algorithms.

📢📢📢 I am looking for a Ph.D. position (2024 Fall). If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to contact me. 😃

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/paper_spl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatial Focus Attention for Fine-Grained Skeleton-Based Action Tasks](https://ieeexplore.ieee.org/document/9860042)

**Kaiyuan Liu**, Yunheng Li, Yuanfeng Xu, Shuai Liu, Shenglan Liu

**IEEE SPL** [[**Paper**]](https://ieeexplore.ieee.org/document/9860042) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

The previous methods fail to focus on the local grouped joint dependence of the human body, which is vital to distinguishing various actions in fine-grained tasks. We propose the novel spatial focus attention to enhance multiple complementary grouped joint dependence for fine-grained tasks through the tree structural attention maps. 
<!-- - The extensive experimental results highlight the benefits of spatial focus attention, which outperforms state-of-the-art methods significantly on fine-grained skeleton-based action recognition (FSD-10) and segmentation benchmarks (MCFS-22). Besides, our proposed spatial focus attention also achieves outstanding performance on the NTU-60 dataset. -->

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/paper_cvpr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reducing the Label Bias for Timestamp Supervised Temporal Action Segmentation](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Reducing_the_Label_Bias_for_Timestamp_Supervised_Temporal_Action_Segmentation_CVPR_2023_paper.pdf)

**Kaiyuan Liu**, **Yunheng Li**, Shenglan Liu, Chenwei Tan, Zihang Shao

**CVPR 2023** [[**Paper**]](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Reducing_the_Label_Bias_for_Timestamp_Supervised_Temporal_Action_Segmentation_CVPR_2023_paper.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> [[**Slides**]](https://cvpr.thecvf.com/media/cvpr-2023/Slides/21372.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> [[**Poster**]](https://cvpr.thecvf.com/virtual/2023/poster/21372) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


We study the label bias in the TSTAS task and propose a novel D-TSTAS framework to reduce both focus and representation bias. The proposed D-TSTAS not only outperforms state-of-the-art TSTAS approaches but also achieves competitive results compared with fully supervised approaches on three benchmark datasets.
<!-- - Our masked timestamp predictions approach is the first attempt to alleviate the dependencies on timestamps, promoting the model to capture contextual information. Coupling MTP and Naive as a general solution is used to initialize the model in the TSTAS. -->
<!-- - Compared to sparsely annotated timestamps, our center-oriented timestamp expansion approach progressively expands pseudo-timestamp groups to contain semantic-rich motion representations of action segments. -->
<!-- - The proposed D-TSTAS not only outperforms state-of-the-art TSTAS approaches but also achieves competitive results compared with fully supervised approaches on three benchmark datasets. -->


</div>
</div>



# 📝 Others 



[Involving Distinguished Temporal Graph Convolutional Networks for Skeleton-Based Temporal Action Segmentation](https://ieeexplore.ieee.org/document/10148994/)

Yunheng Li, **Kaiyuan Liu**, Shenglan Liu, Lin Feng, Hong Qiao

**IEEE TCSVT** [[**Paper**]](https://ieeexplore.ieee.org/document/10148994/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


[Hierarchical Neighbors Embedding](https://ieeexplore.ieee.org/document/9956975)

Shenglan Liu, Yang Yu, **Kaiyuan Liu**, Feilong Wang, Wujun Wen, Hong Qiao

**IEEE TNNLS** [[**Paper**]](https://ieeexplore.ieee.org/document/9956975) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


[Efficient Two-Step Networks for Temporal Action Segmentation](https://www.sciencedirect.com/science/article/abs/pii/S0925231221006998)

Yunheng Li, Zhuben Dong, **Kaiyuan Liu**, Lin Feng, Lianyu Hu, et al

**Neurocomputing** [[**Paper**]](https://www.sciencedirect.com/science/article/abs/pii/S0925231221006998) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


<!-- [Double Attention Network Based on Sparse Sampling](https://www.computer.org/csdl/proceedings-article/icme/2022/09859819/1G9EAL2K8JG)

Yunheng Li, Zhuben Dong, **Kaiyuan Liu**, Lin Feng, Lianyu Hu, et al

**ICME 2022** [[**Paper**]](https://www.computer.org/csdl/proceedings-article/icme/2022/09859819/1G9EAL2K8JG) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->


# 🎖 Honors and Awards
- Master
  - **2022.08** ACM MM Workshop: Person in Context, MTVG track, 6th 
  - **2021.09** CCF International AIOps Challenge, runner-up 
- Undergraduate
  - **2021** Outstanding Graduates (5%)
  - **2020** Outstanding Academic Performance First Scholarship (5%)
  - **2019** The Fourth Next Generation Internet Technology Innovation Competition, 3rd Runner-up
  - **2018, 2019** Outstanding Academic Performance Second Scholarship (15%)


# 📖 Educations
- **2021.09 - 2023.06**, Master, CS, Dalian University of Technology, GPA 3.73 / 4.00
- **2017.09 - 2021.06**, Undergraduate, CS, Dalian University of Technology, GPA 3.80 / 4.00

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
<!-- - **2023.06 - 2023.09 (now)**, Hangzhou AI Lab, NetEase. -->
<!-- - **2022.08 - 2022.10**, CCF GetLink Open Source Summer Camp, SenseTime. -->
- **2023.08 - now**, Text-to-Human-Generation, Shanghai AI Lab.
- **2023.05 - 2023.07**, Human-Motion-Generation, Hangzhou AI Lab, NetEase.
- **2021.12 - 2022.02**, PaddleVideo, Baidu.
