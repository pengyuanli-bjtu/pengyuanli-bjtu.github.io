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

I am a Ph.D. student at the College of Computer and Information Technology, <a href='https://www.bjtu.edu.cn/'>Beijing Jiaotong University(BJTU)</a>. I am supervised by Prof. <a href='https://faculty.bjtu.edu.cn/8516/'>Dongxia Chang</a> in the Center for Digital Media Information Processing Lab (Mepro). I have published several papers in SCI/CCF conferences and journals, including ACM MM, TKDE, TMM, and Neurocomputing. (Resume: <a href='images/english.pdf'>EN</a>/<a href="images/chinese.pdf">中文</a>)

My research interests include multi-view/multi-modal representation learning, deep clustering, self-supervised learning, and contrastive learning. In particular, I focus on:
- 🔍 **Contrastive Multi-view Clustering**
- 🧠 **Incremental Multi-view/Multi-Modal Representation Learning**
- 🌐 **Self-supervised Multi-view/Multi-Modal Representation Learning**


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper has been accepted by IEEE Transactions on Knowledge and Data Engineering 2026. 
- *2025.12*: &nbsp;🎉🎉 One paper has been accepted by JDR 2025. 
- *2025.10*: &nbsp;🎉🎉 One paper has been accepted by Neurocomputing 2025. 
- *2025.09*: &nbsp;🎉🎉 One paper has been accepted by Neurocomputing 2025. 
- *2025.07*: &nbsp;🎉🎉 One paper has been accepted by IEEE Transactions on Multimedia 2025. 
- *2025.07*: &nbsp;🎉🎉 One paper has been accepted by ACM MM 2025. 
- *2025.03*: &nbsp;🎉🎉 One paper has been accepted by Neurocomputing 2025. 

# 📝 Publications 
<span style=" display: flex; align-items: center; font-size: 14px; color: #1565C0; background-color: #E3F2FD; padding: 6px 14px; border-radius: 6px; margin: 0 0 20px 4px; line-height: 1.6; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Arial, sans-serif; border: 1px solid #BBDEFB;">
  <span style="background-color:#2196F3; color:#ffffff; width:22px; height:22px; border-radius:50%; display:flex; align-items:center; justify-content:center; font-weight:500; margin-right:10px; flex-shrink:0; font-size:13px;">i</span>
  <span>* means equal contribution (Co-First Author)</span>
</span>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDE 2026</div><img src='images/DMVCS.png' alt="sym" style="height: 240px; width: 395px;"></div></div>
<div class='paper-box-text' markdown="1">

[Disentangled Contrastive Multi-view Clustering via Semantic Relevance Invariance](#)

**Pengyuan Li**, Dongxia Chang*, Yiming Wang, Zisen Kong, Linhua Kong, Yao Zhao

[**Paper**](#) | [**Code**](https://github.com/Lummer-Li/DMVCS) 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a disentangled contrastive multi-view clustering via semantic relevance invariance, which achieves intra-view and inter-view disentanglement and thus a more discriminative representation. The method not only makes disentangled representations containing different underlying information but also ensures their semantic relevance consistency.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/AEMVC.png' alt="sym" style="height: 240px; width: 395px;"></div></div>
<div class='paper-box-text' markdown="1">

[AEMVC: Mitigate Imbalanced Embedding Space in Multi-view Clustering](https://dl.acm.org/doi/10.1145/3746027.3754697)

**Pengyuan Li^**, Man Liu^, Dongxia Chang*, Yiming Wang, Zisen Kong, Yao Zhao

[**Paper**](https://dl.acm.org/doi/10.1145/3746027.3754697) | [**Code**](https://github.com/Lummer-Li/AEMVC) 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We found that the embedding space learned using the encoder-decoder architecture cannot embrace the efficacy of different feature directions. Therefore, we propose a novel Activate-Then-Eliminate Strategy for Multi-View Clustering to adjust the contribution strength of different feature directions dynamically.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2025</div><img src='images/MISCC.png' alt="sym" style="height: 240px; width: 395px;"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Multi-view Clustering with Intra-view Similarity and Cross-view Correlation Learning](https://ieeexplore.ieee.org/document/11353460)

**Pengyuan Li**, Dongxia Chang*, Yiming Wang, Man Liu, Zisen Kong, Linhua Kong, Yao Zhao

[**Paper**](https://ieeexplore.ieee.org/document/11353460) | [**Code**](https://github.com/Lummer-Li/MISCC) 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We present a novel deep learning framework that mitigates view bias through joint optimization of intra-view similarity and cross-view correlation. The proposed method enhances fine-grained structures within each view and adaptively balances diverse information across views, ultimately improving clustering performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing 2025</div><img src='images/DCMVC.jpg' alt="sym" style="height: 240px; width: 395px;"></div></div>
<div class='paper-box-text' markdown="1">

[DCMVC: Dual Contrastive Multi-view Clustering](https://www.sciencedirect.com/science/article/abs/pii/S0925231225005612)

**Pengyuan Li**, Dongxia Chang*, Zisen Kong, Yiming Wang, Yao Zhao

[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0925231225005612) | [**Code**](https://github.com/Lummer-Li/DCMVC) 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a novel deep contrastive multi-view clustering method termed DCMVC. The dual contrastive mechanism can alleviate the constraints of a single positive sample on contrastive learning by incorporating category information to regularize the feature structure and fully explore the consistency of similar samples.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JDR 2025</div><img src='images/DL4FO.png' alt="sym" style="height: 240px; width: 395px;"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Learning on Histology Images for Differentiating of Fibro-Osseous](#)

Aobo Zhang^, **Pengyuan Li^**, Jiang Xue^, Jianyun Zhang, Zhu You, Shaohua Ge, Zhixiu Xu, Zhipeng Sun, Dongxia Chang*, Lisha Sun, Tiejun Li

[**Paper**](#) | [**Code**](#) 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Our results demonstrate that integrating multi-slide and weakly supervised strategies significantly enhances diagnostic performance for fibro-osseous lesions. Compared to human pathologists, the multi-slide models achieved higher accuracy, whereas weakly supervised models consistently outperformed fully supervised models.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing 2025</div><img src='images/BCMVC.jpg' alt="sym" style="height: 240px; width: 395px;"></div></div>
<div class='paper-box-text' markdown="1">

[Bipartite Contrastive Multi-view Clustering with Singular Value Modulation](https://www.sciencedirect.com/science/article/abs/pii/S0925231225022003)

Teng Zhang, **Pengyuan Li**, Zisen Kong, Dongxia Chang*, Yao Zhao

<a href='https://www.sciencedirect.com/science/article/abs/pii/S0925231225022003' style='color: #224b8d; font-size: 1em; font-weight: bolder; text-decoration: underline;'>Paper</a> | <a href='https://github.com/zhangt-make/BCMVC' style='color: #224b8d; font-size: 1em; font-weight: bolder; text-decoration: underline;'>Code</a> 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We reformulate contrastive learning as a binary classification problem, avoiding the limitation in previous contrastive methods that heavily depend on naturally paired data. By capturing sample-level and category-level consistency relationships among multiple views, the learned representations are further refined.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing 2025</div><img src='images/LGEAC.png' alt="sym" style="height: 240px; width: 395px;"></div></div>
<div class='paper-box-text' markdown="1">

[Local Geometry-Enhanced Anchor Learning for Multi-view Clustering](https://www.sciencedirect.com/science/article/abs/pii/S0925231225026256)

Zisen Kong, Zhiqiang Fu, Dongxia Chang*, Yiming Wang, **Pengyuan Li**, Yao Zhao

<a href='https://www.sciencedirect.com/science/article/abs/pii/S0925231225026256' style='color: #224b8d; font-size: 1em; font-weight: bolder; text-decoration: underline;'>Paper</a> | <a href='#' style='color: #224b8d; font-size: 1em; font-weight: bolder; text-decoration: underline;'>Code</a> 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We introduce a coarse-grained anchor learning mechanism that maps each view anchor to the consensus space, effectively improving the expressiveness and learning of the framework.
</div>
</div>

# 🎖 Honors and Awards
- *2025.11* First-class Academic Scholarship of Beijing Jiaotong University.
- *2025.11* Special Scholarship of Beijing Jiaotong University - Jiaokong Technology Scholarship.
- *2023.11* First-class Academic Scholarship of Beijing Jiaotong University. 
- *2023.06* Outstanding Graduate Student of the School of Computer Science, Beijing Jiaotong University.
- *2022.10* National Bronze Award of the 2022 China University Computer Competition - Team Programming Ladder Competition.
- *2022.10* National Bronze Award of China Computer Design Contest 2022.

# 📌 Services
## Conferences 
- Reviewer: NeurIPS/AAAI/ACM MM

## Journal
- Reviewer: IEEE TPAMI/TIP/TKDE/TCYB/TNNLS/TMM, Neurocomputing 

# 📖 Educations
- *2024.06 - now*, Ph.D. Student @ Beijing Jiaotong University, supervised by Prof. Dongxia Chang.
- *2023.09 - 2024.06*, Master Student @ Beijing Jiaotong University, supervised by Prof. Dongxia Chang.

# 💻 Internships
- *2023.03 - 2023.06*, [PCITC](http://www.pcitc.com/), China.




