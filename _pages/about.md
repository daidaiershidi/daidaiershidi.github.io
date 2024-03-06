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

I am currently in the third year of my master's program at Dalian University of Technology (DUT), where I earned my bachelor's degree in computer science.

Throughout my master's program, I have primarily focused my research on understanding human actions from video, with a strong emphasis on human-centered approaches. Additionally, I have a keen interest in causal learning and self-supervised methods, which offer valuable perspectives for tackling a wide range of tasks. Recently, I have been delving into diffusion model and its application to tasks related to human understanding, aiming to develop AI algorithms that can assist people in their daily lives.

📢📢📢 I am actively pursuing a PhD opportunity for the Fall of 2024. Please feel free to contact me if you would like to discuss potential opportunities or learn more about my qualifications (You can reach me via WeChat at lcxlcxlky). Thank you! 😃


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📚 Publications

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/paper_spl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatial Focus Attention for Fine-Grained Skeleton-Based Action Tasks](https://ieeexplore.ieee.org/document/9860042)

**Kaiyuan Liu**, Yunheng Li, Yuanfeng Xu, Shuai Liu, Shenglan Liu

**IEEE SPL** [[**Paper**]](https://ieeexplore.ieee.org/document/9860042) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

Previous methods fail to focus on the local grouped joint dependence of the human body, which is crucial for distinguishing various actions in fine-grained tasks. To address this issue, we propose a novel spatial focus attention mechanism that enhances multiple complementary grouped joint dependencies for fine-grained tasks through tree structural attention maps. 
<!-- - The extensive experimental results highlight the benefits of spatial focus attention, which outperforms state-of-the-art methods significantly on fine-grained skeleton-based action recognition (FSD-10) and segmentation benchmarks (MCFS-22). Besides, our proposed spatial focus attention also achieves outstanding performance on the NTU-60 dataset. 

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/paper_cvpr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reducing the Label Bias for Timestamp Supervised Temporal Action Segmentation](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Reducing_the_Label_Bias_for_Timestamp_Supervised_Temporal_Action_Segmentation_CVPR_2023_paper.pdf)

**Kaiyuan Liu**, **Yunheng Li**, Shenglan Liu, Chenwei Tan, Zihang Shao

**CVPR 2023** [[**Paper**]](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Reducing_the_Label_Bias_for_Timestamp_Supervised_Temporal_Action_Segmentation_CVPR_2023_paper.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> [[**Slides**]](https://cvpr.thecvf.com/media/cvpr-2023/Slides/21372.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> [[**Poster**]](https://cvpr.thecvf.com/virtual/2023/poster/21372) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>


We discuss label bias in the timestamp-supervised temporal action segmentation (TSTAS) task and propose a novel Debiasing-TSTAS framework to reduce both focus and representation bias. The proposed D-TSTAS not only outperforms state-of-the-art TSTAS approaches but also achieves competitive results compared with fully supervised approaches on three benchmark datasets.
<!-- - Our masked timestamp predictions approach is the first attempt to alleviate the dependencies on timestamps, promoting the model to capture contextual information. Coupling MTP and Naive as a general solution is used to initialize the model in the TSTAS. -->
<!-- - Compared to sparsely annotated timestamps, our center-oriented timestamp expansion approach progressively expands pseudo-timestamp groups to contain semantic-rich motion representations of action segments. -->
<!-- - The proposed D-TSTAS not only outperforms state-of-the-art TSTAS approaches but also achieves competitive results compared with fully supervised approaches on three benchmark datasets. 


</div>
</div> -->

<!--
- **CosmicMan: A Text-to-Image Foundation Model for Humans** \
  Shikai Li*, Jianglin Fu*, **Kaiyuan liu***, Wentao Wang, Kwan-Yee Lin, Wayne Wu \
  CVPR 2024   -->

- **Take its Essence, Discard its Dross! Debiasing for Toxic Language Detection via Counterfactual Causal Effect** \
  Junyu Lu, Bo Xu, Xiaokun Zhang, **Kaiyuan Liu**, Dongyu Zhang, Liang Yang, Hongfei Lin \
  Coling 2024

- **Reducing the Label Bias for Timestamp Supervised Temporal Action Segmentation** \
  **Kaiyuan Liu\***, Yunheng Li\*, Shenglan Liu, Chenwei Tan, Zihang Shao \
  CVPR 2023 

- **Involving Distinguished Temporal Graph Convolutional Networks for Skeleton-Based Temporal Action Segmentation** \
  Yunheng Li, **Kaiyuan Liu**, Shenglan Liu, Lin Feng, Hong Qiao \
  IEEE TCSVT 


- **Hierarchical Neighbors Embedding** \
  Shenglan Liu, Yang Yu, **Kaiyuan Liu**, Feilong Wang, Wujun Wen, Hong Qiao \
  IEEE TNNLS 

- **Spatial Focus Attention for Fine-Grained Skeleton-Based Action Tasks** \
  **Kaiyuan Liu**, Yunheng Li, Yuanfeng Xu, Shuai Liu, Shenglan Liu \
  IEEE SPL 


- **Efficient Two-Step Networks for Temporal Action Segmentation** \
  Yunheng Li, Zhuben Dong, **Kaiyuan Liu**, Lin Feng, Lianyu Hu, et al \
  Neurocomputing 

- **Double Attention Network Based on Sparse Sampling** \
  Yunheng Li, Zhuben Dong, **Kaiyuan Liu**, Lin Feng, Lianyu Hu, et al \
  ICME 2022 


- **Multi-Dimensional Refinement Graph Convolutional Network with Robust Decouple Loss for Fine-Grained Skeleton-Based Action Recognition** \
  Shenglan Liu, Yuning Ding, Jinrong Zhang, **Kaiyuan Liu**, Sifan Zhang, Feilong Wang, Gaohuang \
  Under Review



# 🏆 Honors and Awards
- Master
  - **2023.08** DUT Outstanding Master Student (Top 5%)
  - **2023.07** China Aviation Industry Group - ShenFei Luoyang Inspirational Scholarship (Top 1%)
  - **2022.08** ACM MM Workshop: Person in Context, MTVG track, 6th Place
  - **2021.09** CCF International AIOps Challenge, runner-up 
- Undergraduate
  - **2021** DUT Outstanding Graduates (Top 5%)
  - **2020** DUT Outstanding Academic Performance First Scholarship (Top 5%)
  - **2019** The Fourth Next Generation Internet Technology Innovation Competition, 3rd Runner-up
  - **2018, 2019** DUT Outstanding Academic Performance Second Scholarship (Top 15%)


# 🎓 Educations
- **2021.09 - 2023.06**, Master, CS, Dalian University of Technology, GPA 3.70 / 4.00
- **2017.09 - 2021.06**, Undergraduate, CS, Dalian University of Technology, GPA 3.79 / 4.00

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💼 Internships
<!-- - **2023.06 - 2023.09 (now)**, Hangzhou AI Lab, NetEase. -->
<!-- - **2022.08 - 2022.10**, CCF GetLink Open Source Summer Camp, SenseTime. -->
- **2023.08 - 2023.12**, Text-to-Human-Generation, Shanghai AI Lab.
- **2023.05 - 2023.07**, Human-Motion-Generation, Hangzhou AI Lab, NetEase.
- **2021.12 - 2022.02**, PaddleVideo, Baidu.

# 👥 Services
<!-- - **2023.06 - 2023.09 (now)**, Hangzhou AI Lab, NetEase. -->
<!-- - **2022.08 - 2022.10**, CCF GetLink Open Source Summer Camp, SenseTime. -->
- **Conference**, PRCV'23/24.
- **Journal**, TCSVT, Neurocomputing.
