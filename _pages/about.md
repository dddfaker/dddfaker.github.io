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

Hello! This is Xuanwen Ding. I am currently pursuing my Ph.D. at Fudan University and the Shanghai Innovation Institute, where I am fortunate to be advised by Prof. [Zhongyu Wei](https://scholar.google.com/citations?user=AjLDxxgAAAAJ). I am a member of the [Fudan Data Intelligence and Social Computing (Fudan DISC) lab](http://fudan-disc.com/) and the Fudan NLP group. Previously, I received my master's degree from East China Normal University, where I was advised by Prof. Liang Dou and Prof. [Jie Zhou](https://scholar.google.com/citations?hl=en&user=dKt8wwQAAAAJ&view_op=list_works&sortby=pubdate).

My research interests include Natural Language Processing, Computational Social Science, and Continual Learning.

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- † indicates equal contributions. -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/paper/AutoJudger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [AutoJudger: An Agent-Driven Framework for Efficient Benchmarking of MLLMs](https://arxiv.org/pdf/2505.21389?). <br>
  **Xuanwen Ding†**, Chengjun Pan†, Zejun Li†, Jiwen Zhang†, Siyuan Wang, Zhongyu Wei.
  
  Keyword: Efficient Benchmarking; Multimodal Large Language Models; Agent

  [[GitHub]](https://github.com/IMNearth/AutoJudger)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Computing Surveys</div><img src='images/paper/From_Individual_to_Society.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Individual to Society: A Survey on Social Simulation Driven by Large Language Model-based Agents](https://arxiv.org/pdf/2412.03563?). <br>
  Xinyi Mou†, **Xuanwen Ding†**, Qi He†, Liang Wang†, Jingcong Liang, Xinnong Zhang, Libo Sun, Jiayu Lin, Jie Zhou, Xuanjing Huang, Zhongyu Wei.

  Keyword: Social Simulation; LLM; Agent; Survey

  [[GitHub]](https://github.com/FudanDISC/SocialAgent) [[Synced (机器之心)]](https://mp.weixin.qq.com/s/Uy_NYkDGp9CqmO2j9XOfCA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/paper/LLM_CL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Boosting Large Language Models with Continual Learning for Aspect-based Sentiment Analysis](https://arxiv.org/pdf/2405.05496). <br>
  **Xuanwen Ding**, Jie Zhou, Liang Dou, Qin Chen, Yuanbin Wu, Chengcai Chen, Liang He.

  Keyword: LLM; Aspect-based Sentiment Analysis; Continual Learning

  [[GitHub]](https://github.com/ECNU-ICALK/EasyCL)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FSE 2024</div><img src='images/paper/FinHunter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FinHunter: Improved Search-based Test Generation for Structural Testing of FinTech Systems](https://dl.acm.org/doi/abs/10.1145/3663529.3663823). <br>
  **Xuanwen Ding**, Qingshun Wang, Dan Liu, LiHua Xu, Jun Xiao, Bojun Zhang, Xue Li, Liang Dou, Liang He, Tao Xie.

  Keyword: FinTech; Automated Test Generation; Genetic Algorithm
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/paper/ProcureGym.png' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

[ProcureGym: A Multi-Agent Markov Game Framework for Modeling National Volume-based Drug Procurement](https://arxiv.org/abs/2603.23880). <br>
  Jia Wang†, Qian Xu†, **Xuanwen Ding**, Zhuangqi Li, Chao He, Bao Liu, Zhongyu Wei.

  Keyword: National Volume-Based Drug Procurement; Multi-agent Simulation; Markov Decision Process; Reinforcement Learning

  [[GitHub]](https://github.com/JiaWANG-TJ/ProcureGym)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/paper/Towards_a_Science_of_Collective_AI.jpg' alt="sym" width="200%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards a Science of Collective AI: LLM-based Multi-Agent Systems Need a Transition from Blind Trial-and-Error to Rigorous Science](https://arxiv.org/pdf/2602.05289). <br>
  Jingru Fan†, Dewen Liu†, Yufan Dang, Huatao Li, Yuheng Wang, Wei Liu, Feiyu Duan, **Xuanwen Ding**, Shu Yao, Lin Wu, Ruijie Shi, Wai-Shing Leung, Yuan Cheng, Zhongyu Wei, Cheng Yang, Chen Qian, Zhiyuan Liu, Maosong Sun.

  Keyword: LLM; Multi-Agent Collaboration; Collaborative Intelligence; Factor Attribution
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM Computing Surveys</div><img src='images/paper/CL_Survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Recent Advances of Foundation Language Models-based Continual Learning: A Survey](https://arxiv.org/pdf/2405.18653). <br>
  Yutao Yang, Jie Zhou, **Xuanwen Ding**, Tianyu Huai, Shunyu Liu, Qin Chen, Liang He, Yuan Xie.

  Keyword: Continual Learning; Foundation Language Models; Pre-trained Language Models; Large Language Models; Vision-Language Models; Survey

  [[GitHub]](https://github.com/ECNU-ICALK/Foundation-LMs-based-Continual-Learning)
</div>
</div>

# 🎖 Honors and Awards
- National Scholarship, China, 2023-2024
- National Scholarship, China, 2020-2021
- First Prize in the Mathematical Contest in Modeling/ Interdisciplinary Contest in Modeling (MCM/ICM), 2021
- First Prize in China Undergraduate Mathematical Contest in Modeling (CUMCM), 2020
- Bronze Medal in ACM-ICPC Asia Nanjing Regional Contest, 2019

# 📖 Educations
- *2025.09 - present*, Ph.D. Candidate in Statistics (Statistical Machine Learning), Fudan University, Shanghai, China.
- *2022.09 - 2025.06*, Master of Computer Science, East China Normal University, Shanghai, China.
- *2018.09 - 2022.06*, Bachelor of Computer Science, Hangzhou Dianzi University, Hangzhou, China.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.05 - 2024.09*, NLP Algorithm Engineering Intern, Meituan Daojia Group, Beijing, China
- *2022.01 - 2022.06*, ML Algorithm Engineering Intern, Ant Group MYbank, Hangzhou, China