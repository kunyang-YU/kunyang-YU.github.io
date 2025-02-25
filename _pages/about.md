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

# Introduction

I am a first-year M.Sc student at [School of Artificial Intelligence](https://ai.nju.edu.cn/) of [Nanjing University](https://www.nju.edu.cn/) advised by Professor [Yu-Feng Li (李宇峰)](https://cs.nju.edu.cn/liyf/index.htm), and a member of [LAMDA Group (机器学习与数据挖掘研究所)](https://www.lamda.nju.edu.cn/CH.MainPage.ashx), which is led by Professor [Zhi-Hua Zhou (周志华)](https://cs.nju.edu.cn/zhouzh/index.htm).

I got my B.Sc. degree in School of Artificial Intelligence in June 2024 from Southeast University. In the same year, I was admitted to pursue for a M.Sc degree in Nanjing University without entrance examination.

# Publication <a href='https://scholar.google.com/citations?user=mkP1EtkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

## Conference Papers

- **Fully Test-time Adaptation for Tabular Data.** <br>
Zhi Zhou, **Kun-Yang Yu(co-first author)**, Lan-Zhe Guo, Yu-Feng Li. <br>
In: Proceedings of the 39th AAAI conference on Artificial Intelligence, Philadelphia, 2025. <br>
<span style="color:blue">AAAI 2025.</span>
<span style="color:grey">CCF-A.</span>
<!-- [[Paper]](../resources/FTTA.pdf) -->
[[Paper]](https://arxiv.org/abs/2412.10871) 

## Preprints

- **LawGPT: Knowledge-Guided Data Generation and Its Application to Legal LLM** <br>
Zhi Zhou, **Kun-Yang Yu**, Shi-Yu Tian, Xiao-Wen Yang, Jiang-Xin Shi, Peng-Xiao Song, Yi-Xuan Jin, Lan-Zhe Guo, Yu-Feng Li. <br>
Under Review. <br>
[[Paper]](./resources/preprint/LawGPT.pdf)