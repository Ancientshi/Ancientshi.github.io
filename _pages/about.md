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

<span class='anchor' id='About Me'></span>

I’m Yunxiao Shi (石韵虓xiāo), born in 1998 in Wuhan, China, and currently a fourth-year PhD candidate at the **University of Technology Sydney**, supervised by **Prof. Min Xu** and co-supervised by **Prof. Qiang Wu**. I am expected to graduate before July 2, 2026. I have published in leading venues such as ECAI, ACL, EMNLP, ICLR, ACM Multimedia, and ADMA, as well as journals including DMKD, TOIS, and Neurocomputing. I also serve as a regular reviewer for journals such as IEEE TKDE, IEEE TMM, Neural Networks, and Frontiers in AI. In addition, I am the Co-Founder of **[Achieva AI](https://www.achieva-ai.com)**, the first AI agent for international student education consulting in Australia.
<!-- <a href='https://scholar.google.com/citations?user=yQZTu58AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=Citation"></a> -->

<span style="color:#A0522D; font-family:'Georgia', serif; font-weight:500;">
I am actively exploring research problems and potential collaborations in Personalized LLMs, Recommender Systems, Retrieval-Augmented Generation (RAG), AI Agents, and AI for Education. I am also currently seeking postdoctoral research opportunities. If you are interested, feel free to contact me at Yunxiao@student.uts.edu.au.
</span>



<span class='anchor' id='-Education'></span>

<span class='anchor' id='-News'></span>

# 📰 News
* *2026.06*, Invited to give a research talk at the School of Computer Science and Engineering, Nanjing University of Science and Technology.
  Talk title: *Large Language Model Agent Systems for Question-Answering Style Information Retrieval and Recommendation*.

* *2026.05*, Invited to attend the Nanhu Young Scholars Talent Forum at South-Central Minzu University, and gave a research talk and academic exchange at the College of Computer Science.

* *2026.05*, One paper was accepted by ICML 2026: *AgentSelect: A Benchmark for Narrative Query-to-Agent Recommendation*.

* *2026.05*, Achieva AI was selected as a finalist for The PIEoneer Awards 2026 in the category of *Digital Innovation of the Year – Student Recruitment*.


# 🎓 Education
- *2022.07 – Present*, University of Technology Sydney, PhD Candidate in Information System
- *2021.09 – 2022.05*, University of New South Wales, Coursework Master of Information Technology (*Withdrew for Research*)

<span class='anchor' id='-Academic_Publications'></span>

# 🧾 Academic Publications

## 📊 Data Attribution

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/ACC-SGD-IE.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *Accumulative SGD Influence Estimator for Data Attribution* [[Preview]](https://arxiv.org/abs/2510.26185) <br>
**Yunxiao Shi**, Shuo Yang, Yixin Su, Rui Zhang, Min Xu
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DMKD Journal</div><img src='images/MEGG.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *MEGG: Replay via Maximally Extreme GG-score in Incremental Learning for Deep Recommendation Models* [[Preview]](https://arxiv.org/abs/2509.07319) <br>
**Yunxiao Shi**, Shuo Yang, Haimin Zhang, Li Wang, Yongze Wang, Qiang Wu, Min Xu
</div></div>


## 📚 RAG, Information Retrieval and Question Answering

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/OCG.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *Answering Narrative-Driven Recommendation Queries via Retrieve-Rank Paradigm and the OCG-Agent* [[Preview]](https://aclanthology.org/2025.emnlp-main.667/) <br>
**Yunxiao Shi**, Haoning Shang, Xing Zi, Wujiang Xu, Yue Feng, Min Xu
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM-MMGR 2024</div><img src='https://arxiv.org/html/2409.00636v1/x1.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *A Learnable Agent Collaboration Network Framework for Personalized Multimodal AI Search Engine* [[Preview]](https://dl.acm.org/doi/10.1145/3689091.3690087) <br>
**Yunxiao Shi**, Min Xu, Haimin Zhang, Xing Zi, Qiang Xu
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECAI 2024</div><img src='images/ECAI.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *Enhancing Retrieval and Managing Retrieval: A Four-Module Synergy for Improved Quality and Efficiency in RAG Systems* [[Preview]](https://ebooks.iospress.nl/doi/10.3233/FAIA240748) <br>
**Yunxiao Shi**, Xing Zi, Zijing Shi, Haimin Zhang, Qiang Xu, Min Xu 
</div></div>


## 💡 LLM for Recommendation

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='https://arxiv.org/html/2405.17890v4/x1.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *Distilling Large Language Models into Small for Sequential Recommendation* [[Preview]](https://openreview.net/forum?id=G4wARwjF8M) <br>
Wujiang Xu, Qitian Wu, Zujie Liang, Jiaojiao Han, Xuying Ning, **Yunxiao Shi**, Wenfang Lin, Yongfeng Zhang
</div></div>


## 🤖 Agent and Recommendation


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/AgentSelect.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *AgentSelect: A Benchmark for Narrative Query-to-Agent Recommendation* [[Preview]]() <br>
**Yunxiao Shi**, Wujiang Xu, Tingwei Chen, Haoning Shang, Ling Yang, Yunfeng Wan, Zhuo Cao, Xing Zi, Dimitris N. Metaxas, Min Xu
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/PersonaX.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *PersonaX: A Recommendation Agent Oriented User Modeling Framework for Long Behavior Sequence* [[Preview]](https://aclanthology.org/2025.findings-acl.300/) <br>
**Yunxiao Shi**, Wujiang Xu, Zeqi Zhang, Xing Zi, Qiang Xu, Min Xu
</div></div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/InstructAgent.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *InstructAgent: Building User Controllable Recommender via LLM Agent* [[Preview]](https://aclanthology.org/2025.findings-acl.928/) <br> Wujiang Xu, **Yunxiao Shi**, Zujie Liang, Xuying Ning, Kai Mei, Kun Wang, Xi Zhu, Min Xu, Yongfeng Zhang
</div></div>

## 📈 Traditional Recommender System

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/KarSein.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *Beyond KAN: Introducing KarSein for Adaptive High-Order Feature Interaction Modeling in CTR Prediction* [[Preview]](https://arxiv.org/abs/2408.08713) <br>
**Yunxiao Shi**, Wujiang Xu, Haimin Zhang, Qiang Wu, Min Xu
</div></div>


## 🛰️ Remote Sensing

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='https://arxiv.org/html/2508.07918v1/Figure/RSVLM-QA_Pipeline.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *RSVLM-QA: A Benchmark Dataset for Remote Sensing Vision Language Model-based Question Answering* [[Preview]](https://arxiv.org/abs/2508.07918) <br>
Xing Zi, Jinghao Xiao, **Yunxiao Shi**, Xian Tao, Jun Li, Ali Braytee, Mukesh Prasad
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ADMA 2024</div><img src='https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-981-96-0811-9_7/MediaObjects/628584_1_En_7_Fig4_HTML.png'  width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *BDC Dataset: A Comprehensive Dataset for Automated Build Damage Classification* [[Preview]](https://openreview.net/forum?id=fr8Atucyym) <br>
Xing Zi, **Yunxiao Shi**, Taoyuan Zhu, Kairui Jin, Xian Tao, Jun Li, Karthick Thiyagarajan, Mukesh Prasad
</div></div>


<span class='anchor' id='-Scholarship'></span>

# 🏅 Scholarship

- UTS–CSC Doctor of Philosophy (PhD) Scholarships Program, *2023.05 – 2026.07*
- Vice-Chancellor's Postgraduate Research Student Conference Fund, *2024*
- UTS School of Electrical and Data Engineering Research Support Fund, *2024*

<span class='anchor' id='-Teaching_Experience'></span>

# 🎓 Teaching Experience

## Teaching Assistant (UTS)
- 48430 Fundamentals of C Programming, *2023.03 – 2024.06*
- 41891/42891 Cloud Computing Infrastructure, *2022.07 – 2022.12* 

## Tutor (Educational Institution)
- UTS 32513 Advanced Data Analytics Algorithms 
- UTS 41043 Natural Language Processing 
- USYD COMP5318/COMP4318 Machine Learning and Data Mining
- UNSW COMP9021 Principles of Programming
