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

I am a Ph.D. student at the School of Artificial Intelligence,<a href="https://en.sjtu.edu.cn/" target="_blank" style="color:#3399ff; text-decoration:none;">Shanghai Jiao Tong University</a>, advised by <a href="https://siheng-chen.github.io/" target="_blank" style="color:#3399ff; text-decoration:none;">Prof. Siheng Chen</a>. I received my B.Eng. degree (2021–2025) in Computer Science and Technology from <a href="https://en.tju.edu.cn/" target="_blank" style="color:#3399ff;text-decoration:none;">Tianjin University</a>, where I ranked **2nd out of 143** in my cohort. My research interests include **Agentic AI** and **Multi-Agent Systems**.

I am always happy to discuss **research ideas** and **potential collaborations**. Feel free to reach out!


## 🔥 News

<div class="news-scroll" markdown="1">

- [2026.08] [BigBang-v1](https://huggingface.co/endless-frontier/BigBang-v1) (a 35B-A3B model trained on self-evolving verifiable frontier tasks) is released, reaching **16K Hugging Face downloads** in its first month!
- [2026.07] [OpenSeeker](https://arxiv.org/pdf/2603.15594) is accepted by **COLM 2026**!
- [2026.07] [XYZ-Aquila](https://xyz-lab.ai/blogs/ai4ai-at-scale/) (an open-weight agent for complex, long-horizon web searching) reaches **84.8% on BrowseComp** and **53.3% on HLE**.
- [2026.05] [OpenSeeker-v2](https://arxiv.org/pdf/2605.04036) (a SOTA search agent trained via pure SFT on only 10K trajectories) is released!
- [2026.03] [OpenSeeker](https://arxiv.org/pdf/2603.15594) (the first state-of-the-art search agent with fully open-source data & model) is released!
- [2025.11] [PaSaMaster](https://scimaster.bohrium.com/chat/paper-search) (a self-evolving agent for multidisciplinary literature retrieval) is released!
- [2025.07] [SciMaster](https://scimaster.bohrium.com/chat/general) (a general-purpose scientific AI agent with tool-augmented reasoning) is released at **WAIC 2025**!
- [2025.07] [X-Masters](https://arxiv.org/pdf/2507.05241) (a tool-augmented agent for scientific reasoning) becomes the first system to surpass 30% on **HLE**, scoring **32.1%**.
- [2025.06] [RoCo-Sim](https://arxiv.org/pdf/2503.10410) (a foreground simulation framework for roadside collaborative perception) is accepted by **ICCV 2025**!

</div>

## 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Tech Report 2026</div>
      <img src='images/bigbang_combined.png' alt="BigBang-v1 results and self-evolving data synthesis pipeline" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[BigBang: Pursuing Open-Ended Intelligence through Self-Evolving Synthesis of Verifiable Frontier Tasks](https://endlessfrontier.tech/assets/paper.pdf)

**The BigBang Team**

BigBang-v1 is a 35B-A3B agentic model trained with a self-evolving generator-critic pipeline for verifiable frontier tasks. It leads comparable 35B models across eight benchmarks, scoring **76.5% on BrowseComp**, **50.3% on HLE**, **54.2% on SWE-Bench Pro**, **53.6% on PaperBench (Code-Dev)**, and **46.2% on FrontierScience Research**, with **16K+ Hugging Face downloads**.

[**Paper**](https://endlessfrontier.tech/assets/paper.pdf) / [**Code**](https://github.com/endless-frontier/BigBang-v1) ![Stars](https://img.shields.io/github/stars/endless-frontier/BigBang-v1?style=social) / [**Model**](https://huggingface.co/endless-frontier/BigBang-v1) / [**机器之心**](https://mp.weixin.qq.com/s/tfXP9X3Idfqy4cxHQYLAcA)

  </div>
</div>

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

XYZ-Aquila-pro achieves strong results across six benchmarks: **84.8%** on **BrowseComp**, **85.1%** on **BrowseComp-ZH**, **92.5%** on **DeepSearchQA**, **53.7%** on **LiveBrowseComp**, **53.3%** on **Humanity's Last Exam**, and **81.2%** on **WideSearch**. The **OpenSeeker data** also provided important support for these capability gains.

[**Paper**](https://xyz-lab.ai/blogs/ai4ai-at-scale/assets/bounded-exploration-ai4ai-system-optimization.pdf) / [**Harness_code**](https://github.com/XYZ-AI-Lab/AxisAgentic) ![Stars](https://img.shields.io/github/stars/XYZ-AI-Lab/AxisAgentic?style=social) / [**Training_code**](https://github.com/XYZ-AI-Lab/axrl) ![Stars](https://img.shields.io/github/stars/XYZ-AI-Lab/axrl?style=social) / [**机器之心**](https://mp.weixin.qq.com/s/r8XCiqFTFcD5LVMJlbeghA)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Tech Report 2026</div>
      <img src='images/openseekerv2.png' alt="OpenSeeker-v2 figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[OpenSeeker-v2: Pushing the Limits of Search Agents with Informative and High-Difficulty Trajectories](https://arxiv.org/pdf/2605.04036)

**Yuwen Du<sup>*</sup>**, Rui Ye<sup>*</sup>, Shuo Tang, Keduan Huang, Xinyu Zhu, Yuzhu Cai, Siheng Chen

A compact SFT release that expands OpenSeeker with more informative and higher-difficulty trajectories, showing that only 10k samples can still push same-scale pure ReAct models to SOTA performance.

[**ArXiv**](https://arxiv.org/pdf/2605.04036) / [**Code**](https://github.com/rui-ye/OpenSeeker) ![Stars](https://img.shields.io/github/stars/rui-ye/OpenSeeker?style=social) / [**Model**](https://huggingface.co/PolarSeeker/OpenSeeker-v2-30B-SFT)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">COLM 2026</div>
      <img src='images/openseeker.png' alt="OpenSeeker figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[OpenSeeker: Democratizing Frontier Search Agents by Fully Open-Sourcing Training Data](https://arxiv.org/pdf/2603.15594)

**Yuwen Du<sup>*</sup>**, Rui Ye<sup>*</sup>, Shuo Tang, Xinyu Zhu, Yijun Lu, Yuzhu Cai, Siheng Chen

We fill a long-standing gap in frontier search by fully open-sourcing the training data and model, making strong search agents more reproducible and accessible.

[**ArXiv**](https://arxiv.org/pdf/2603.15594) / [**Code**](https://github.com/rui-ye/OpenSeeker) ![Stars](https://img.shields.io/github/stars/rui-ye/OpenSeeker?style=social) / [**Training Data**](https://huggingface.co/datasets/OpenSeeker/OpenSeeker-v1-Data) / [**Model**](https://huggingface.co/OpenSeeker/OpenSeeker-v1-30B-SFT) / [**机器之心**](https://mp.weixin.qq.com/s/lGx7WK_EvwisYCngiDW-mw)

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICML Workshop 2026</div>
      <img src='images/pasamaster.png' alt="PaSaMaster figure" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

[PaSaMaster: Towards Self-Evolving Agentic Literature Retrieval](https://arxiv.org/pdf/2605.14306)

**Yuwen Du<sup>*</sup>**, Tian Jin<sup>*</sup>, Jing Kang, Xianghe Pang, Jingyi Chai, Tingjia Miao, Fenyi Liu, WenHao Wang, Sikai Yao, Yuzhi Zhang, Siheng Chen

A recursive self-evolving agentic literature retrieval system that iteratively analyzes intent, retrieves verified papers, and ranks them with evidence-grounded relevance scores. 

[**ArXiv**](https://arxiv.org/pdf/2605.14306) / [**Code**](https://github.com/sjtu-sai-agents/PaSaMaster) ![Stars](https://img.shields.io/github/stars/sjtu-sai-agents/PaSaMaster?style=social) / [**Benchmark**](https://huggingface.co/datasets/PaSaMaster/PaSaMaster_bench)

  </div>
</div>

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

A general-purpose scientific AI agent built upon our tool-augmented reasoning agent X-Master, designed to flexibly interact with external tools during scientific reasoning.

[**ArXiv**](https://arxiv.org/pdf/2507.05241) / [**Code**](https://github.com/sjtu-sai-agents/X-Master) ![Stars](https://img.shields.io/github/stars/sjtu-sai-agents/X-Master?style=social)

  </div>
</div>

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

A foreground simulation framework that improves roadside collaborative perception by generating more realistic training scenes.

[**ArXiv**](https://arxiv.org/pdf/2503.10410) / [**Code**](https://github.com/duyuwen-duen/RoCo-Sim) ![Stars](https://img.shields.io/github/stars/duyuwen-duen/RoCo-Sim?style=social)

  </div>
</div>

## 🎖 Honors and Awards
- **National Scholarship for Undergraduates**, 2024  
- **National Scholarship for Undergraduates**, 2023  
- **National Scholarship for Undergraduates**, 2022  
