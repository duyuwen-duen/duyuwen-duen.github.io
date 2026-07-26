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

## 👩‍💻 About Me

I am a Ph.D. student at the School of Artificial Intelligence,<a href="https://en.sjtu.edu.cn/" target="_blank" style="color:#3399ff; text-decoration:none;">Shanghai Jiao Tong University</a>, advised by <a href="https://siheng-chen.github.io/" target="_blank" style="color:#3399ff; text-decoration:none;">Prof. Siheng Chen</a>. I received my B.Eng. degree (2021–2025) in Computer Science and Technology from <a href="https://en.tju.edu.cn/" target="_blank" style="color:#3399ff;text-decoration:none;">Tianjin University</a>, where I ranked **2nd out of 143** in my cohort. My research interests include **Agentic AI** and **Multi-Agent Systems**. I am always happy to discuss **research ideas** and **potential collaborations**. Feel free to reach out!  


## 🔥 News
- *2026.07*: &nbsp;🎉🎉 [**AI4AI at Scale: Building Open-Weight Deep Search Agents**](https://xyz-lab.ai/blogs/ai4ai-at-scale/) by **XYZ Team** reports strong results on **BrowseComp** and **Humanity's Last Exam**: **78.8% / 51.1%** for XYZ-Aquila-mini and **84.8% / 53.3%** for XYZ-Aquila-pro. I was primarily responsible for **data synthesis**, a core component behind the agent's strong performance gains.
- *2026.05*: &nbsp;🎉🎉 [**OpenSeeker-v2**](https://arxiv.org/pdf/2605.04036) pushes search agents further: **SOTA** with **only ~10k** high-quality trajectories under **pure SFT**.
- *2026.03*: &nbsp;🎉🎉 [**OpenSeeker**](https://arxiv.org/pdf/2603.15594), a purely academic initiative, achieved SOTA search while open-sourcing everything: models and 100% full training data.
- *2026.11*: &nbsp;🎉🎉 [**PaSaMaster**](https://scimaster.bohrium.com/chat/paper-search), an agent-driven, fully autonomous multidisciplinary literature retrieval system, understands natural-language queries and helps you find the papers you need.
- *2025.07*: &nbsp;🎉🎉 [**SciMaster**](https://scimaster.bohrium.com/chat/general), a multi-disciplinary general-purpose intelligent agent, was officially released at the World Artificial Intelligence Conference (WAIC).
- *2025.07*: &nbsp;🎉🎉 **X-Masters** surpasses the 30% threshold on Humanity’s Last Exam for the first time, achieving an impressive 32.1%.
- *2025.06*: &nbsp;🎉🎉 **RoCo-Sim** was accepted to **ICCV 2025**!

## 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Tech Blog 2026</div>
      <img src='images/xyz_result.png' alt="XYZ-Aquila result figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[AI4AI at Scale: Building Open-Weight Deep Search Agents](https://xyz-lab.ai/blogs/ai4ai-at-scale/)

**XYZ Team**

XYZ-Aquila-pro achieves strong results across six benchmarks: **84.8%** on **BrowseComp**, **85.1%** on **BrowseComp-ZH**, **92.5%** on **DeepSearchQA**, **53.7%** on **LiveBrowseComp**, **53.3%** on **Humanity's Last Exam**, and **81.2%** on **WideSearch**. I was primarily responsible for **data synthesis**, a core component behind the agent's strong performance gains. The OpenSeeker data also provided important support for these capability gains.

[**Paper**](https://xyz-lab.ai/blogs/ai4ai-at-scale/assets/bounded-exploration-ai4ai-system-optimization.pdf) / [**harness_code**](https://github.com/XYZ-AI-Lab/AxisAgentic) ![Stars](https://img.shields.io/github/stars/XYZ-AI-Lab/AxisAgentic?style=social) / [**training_code**](https://github.com/XYZ-AI-Lab/axrl) ![Stars](https://img.shields.io/github/stars/XYZ-AI-Lab/axrl?style=social) / [**机器之心**](https://mp.weixin.qq.com/s/r8XCiqFTFcD5LVMJlbeghA)

  </div>
</div>

<br>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Tech Report 2026</div>
      <img src='images/openseekerv2.png' alt="OpenSeeker-v2 figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[OpenSeeker-v2: Pushing the Limits of Search Agents with Informative and High-Difficulty Trajectories](https://arxiv.org/pdf/2605.04036)

**Yuwen Du<sup>*</sup>**, Rui Ye<sup>*,#,†</sup>, Shuo Tang, Keduan Huang, Xinyu Zhu, Yuzhu Cai, Siheng Chen<sup>†</sup>  

[**ArXiv**](https://arxiv.org/pdf/2605.04036) / [**Code**](https://github.com/rui-ye/OpenSeeker) ![Stars](https://img.shields.io/github/stars/rui-ye/OpenSeeker?style=social) / [**Model**](https://huggingface.co/PolarSeeker/OpenSeeker-v2-30B-SFT)

  </div>
</div>

<br>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">COLM 2026</div>
      <img src='images/openseeker.png' alt="OpenSeeker figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[OpenSeeker: Democratizing Frontier Search Agents by Fully Open-Sourcing Training Data](https://arxiv.org/pdf/2603.15594)

**Yuwen Du<sup>*</sup>**, Rui Ye<sup>*,#,†</sup>, Shuo Tang, Xinyu Zhu, Yijun Lu, Yuzhu Cai, Siheng Chen<sup>†</sup>  

[**ArXiv**](https://arxiv.org/pdf/2603.15594) / [**Code**](https://github.com/rui-ye/OpenSeeker) ![Stars](https://img.shields.io/github/stars/rui-ye/OpenSeeker?style=social) / [**Training Data**](https://huggingface.co/datasets/OpenSeeker/OpenSeeker-v1-Data) / [**Model**](https://huggingface.co/OpenSeeker/OpenSeeker-v1-30B-SFT) / [**机器之心**](https://mp.weixin.qq.com/s/lGx7WK_EvwisYCngiDW-mw)

  </div>
</div>

<br>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Tech Report 2025</div>
      <img src='images/X_master.png' alt="SciMaster figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[SciMaster: Towards General-Purpose Scientific AI Agents, Part I. X-Master as Foundation: Can We Lead on Humanity's Last Exam?](https://arxiv.org/pdf/2507.05241)

Jingyi Chai<sup>*</sup>, Shuo Tang<sup>*</sup>, Rui Ye<sup>*</sup>, **Yuwen Du<sup>*</sup>**, Xinyu Zhu, Mengcheng Zhou, Yanfeng Wang, Weinan E, Yuzhi Zhang, Linfeng Zhang, Siheng Chen  

[**ArXiv**](https://arxiv.org/pdf/2507.05241) / [**Code**](https://github.com/sjtu-sai-agents/X-Master) ![Stars](https://img.shields.io/github/stars/sjtu-sai-agents/X-Master?style=social)

  </div>
</div>

<br>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICCV 2025</div>
      <img src='images/simulation_result.png' alt="RoCo-Sim figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[RoCo-Sim: Enhancing Roadside Collaborative Perception through Foreground Simulation](https://arxiv.org/pdf/2503.10410)

**Yuwen Du<sup>*</sup>**, Anning Hu<sup>*</sup>, Zichen Chao, Yifan Lu, Junhao Ge, Genjia Liu, Weitao Wu, Lanjun Wang, Siheng Chen  

[**ArXiv**](https://arxiv.org/pdf/2503.10410) / [**Code**](https://github.com/duyuwen-duen/RoCo-Sim) ![Stars](https://img.shields.io/github/stars/duyuwen-duen/RoCo-Sim?style=social)

  </div>
</div>

## 🎖 Honors and Awards
- **Outstanding Graduate of Tianjin Municipality**, 2025
- **National Scholarship for Undergraduates**, 2024  
- **National Scholarship for Undergraduates**, 2023  
- **National Scholarship for Undergraduates**, 2022  

