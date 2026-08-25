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

I am a joint Ph.D. student at the [**University of Science and Technology of China (USTC)**](https://en.ustc.edu.cn/) and [**Microsoft Research Asia (MSRA)**](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), advised by [Xing Xie](https://scholar.google.com/citations?user=5EQfAFIAAAAJ&hl=en/) (Partner Research Manager at MSRA, ACM/IEEE Fellow) and [Defu Lian](https://faculty.ustc.edu.cn/liandefu/en/index.htm) (Professor and Associate Dean of the School of Computer Science, USTC). I received my B.Eng. in Computer Science from USTC in 2022. I am currently a research intern in the **Qwen Team** at Alibaba, working on agentic memory.

My research aims to make large language models genuinely *understand and serve individual people*. Concretely, I work on:

- **LLM post-training** — supervised fine-tuning and reinforcement learning for behavior alignment
- **Personalization and human-like intelligence** — modeling, simulating and evaluating human behavior with LLMs
- **LLM agents and memory** — agentic loops, tool use, and long-horizon memory systems
- **LLM-powered recommender systems** — bridging recommenders and language models

I have published 14 papers, including 4 first-author papers at CCF-A venues, with <a href='https://scholar.google.com/citations?user=MVUVrxQAAAAJ&hl=en'>google scholar citations <strong><span id='total_cit'>1180+</span></strong></a> <a href='https://scholar.google.com/citations?user=MVUVrxQAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. As a core contributor to [RecAI](https://github.com/microsoft/RecAI) (1.2k+ stars), I also placed 3rd in Amazon KDD Cup 2023 and 1st in a track of the Sony CPDC Challenge 2025.

I am always happy to chat about research or collaboration — feel free to reach me at <leiyuxuan@mail.ustc.edu.cn>.

# 🔥 News
- *2026.07*: &nbsp;🎉 Started as a research intern in the **Qwen Team**, working on agentic memory.
- *2026*: &nbsp;🎉 Two first-author papers accepted at **ICML 2026** and **KDD 2026**.
- *2025.11*: &nbsp;🏆 Our team ranked **1st in Track 2**, 2nd in Track 1 and 3rd in Track 3 of the **Sony CPDC Challenge 2025**.
- *2024*: &nbsp;🎖 Awarded the **National Scholarship for Graduate Students**.
- *2024*: &nbsp;🎉 First-author papers accepted at **KDD 2024** (RecExplainer) and **WWW 2024** (text-based item retrieval).
- *2023*: &nbsp;🏆 Placed **3rd** in **Amazon KDD Cup 2023** among 2.8k participants.

# 📝 Publications

Authors are listed in publication order and my name is in bold. A full list is also available on [Google Scholar](https://scholar.google.com/citations?user=MVUVrxQAAAAJ&hl=en), [DBLP](https://dblp.org/pid/319/4131.html) and [ORCID](https://orcid.org/0009-0006-3235-8674).

## Human-like Intelligence and Social Reasoning

- `ICML 2026` [A Computational Framework for Evaluating Human-likeness in LLMs' Open-ended Human Behaviors](https://www.microsoft.com/en-us/research/publication/a-computational-framework-for-evaluating-human-likeness-in-llms-open-ended-human-behaviors/)  
  **Yuxuan Lei**, Jianxun Lian, Defu Lian, Jincenzi Wu, Tianfu Wang, Xing Xie  
  [\[Paper\]](https://www.microsoft.com/en-us/research/publication/a-computational-framework-for-evaluating-human-likeness-in-llms-open-ended-human-behaviors/)

- `KDD 2026` [HumanLLM: Towards Personalized Understanding and Simulation of Human Nature](https://dl.acm.org/doi/10.1145/3770854.3780294)  
  **Yuxuan Lei**, Tianfu Wang, Jianxun Lian, Zhengyu Hu, Defu Lian, Xing Xie  
  [\[Paper\]](https://dl.acm.org/doi/10.1145/3770854.3780294) [\[Code\]](https://github.com/microsoft/AnthropomorphicIntelligence/tree/main/HumanLLM)

- `Preprint 2026` [Social-R1: Towards Human-like Social Reasoning in LLMs](https://arxiv.org/abs/2603.09249)  
  Jincenzi Wu, **Yuxuan Lei**, Jianxun Lian, Yitian Huang, Lexin Zhou, Haotian Li, Xing Xie, Helen Meng  
  [\[Paper\]](https://arxiv.org/abs/2603.09249)

- `Preprint 2025` [Population-Aligned Persona Generation for LLM-based Social Simulation](https://arxiv.org/abs/2509.10127)  
  Zhengyu Hu, Zheyuan Xiao, Max Xiong, **Yuxuan Lei**, Tianfu Wang, Jianxun Lian, Kaize Ding, Ziang Xiao, Nicholas Jing Yuan, Xing Xie  
  [\[Paper\]](https://arxiv.org/abs/2509.10127)

- `Tech Report 2025` [Interactive AI NPCs Powered by LLMs: Technical Report for the CPDC Challenge 2025](https://arxiv.org/abs/2511.20200)  
  Yitian Huang, **Yuxuan Lei**, Jianxun Lian, Hao Liao  
  [\[Paper\]](https://arxiv.org/abs/2511.20200)

## LLM-powered Recommender Systems

- `KDD 2024` [RecExplainer: Aligning Large Language Models for Explaining Recommendation Models](https://dl.acm.org/doi/10.1145/3637528.3671802)  
  **Yuxuan Lei**, Jianxun Lian, Jing Yao, Xu Huang, Defu Lian, Xing Xie  
  [\[Paper\]](https://dl.acm.org/doi/10.1145/3637528.3671802) [\[Code\]](https://github.com/microsoft/RecAI/tree/main/RecExplainer)

- `WWW 2024` [Aligning Language Models for Versatile Text-based Item Retrieval](https://dl.acm.org/doi/10.1145/3589335.3651468)  
  **Yuxuan Lei**, Jianxun Lian, Jing Yao, Mingqi Wu, Defu Lian, Xing Xie  
  [\[Paper\]](https://dl.acm.org/doi/10.1145/3589335.3651468) [\[Code\]](https://github.com/microsoft/RecAI/tree/main/RecLM-emb)

- `TOIS 2025` [Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations](https://dl.acm.org/doi/10.1145/3731446)  
  Xu Huang, Jianxun Lian, **Yuxuan Lei**, Jing Yao, Defu Lian, Xing Xie  
  [\[Paper\]](https://dl.acm.org/doi/10.1145/3731446) [\[Code\]](https://github.com/microsoft/RecAI/tree/main/InteRecAgent)

- `WWW 2024 Demo` [RecAI: Leveraging Large Language Models for Next-Generation Recommender Systems](https://dl.acm.org/doi/10.1145/3589335.3651242)  
  Jianxun Lian, **Yuxuan Lei**, Xu Huang, Jing Yao, Wei Xu, Xing Xie  
  [\[Paper\]](https://dl.acm.org/doi/10.1145/3589335.3651242) [\[Code\]](https://github.com/microsoft/RecAI)

- `WWWJ 2024` [When Large Language Models Meet Personalization: Perspectives of Challenges and Opportunities](https://doi.org/10.1007/s11280-024-01276-1)  
  Jin Chen, Zheng Liu, Xu Huang, Chenwang Wu, Qi Liu, Gangwei Jiang, Yuanhao Pu, **Yuxuan Lei**, Xiaolong Chen, Xingmei Wang, Kai Zheng, Defu Lian, Enhong Chen  
  [\[Paper\]](https://doi.org/10.1007/s11280-024-01276-1)

- `KDD Cup 2023 Workshop` [Practical Content-aware Session-based Recommendation: Deep Retrieve then Shallow Rank](https://openreview.net/forum?id=6MdSsLgDei)  
  **Yuxuan Lei**, Xiaolong Chen, Defu Lian, Peng Zhang, Jianxun Lian, Chaozhuo Li, Xing Xie  
  [\[Paper\]](https://openreview.net/forum?id=6MdSsLgDei)

## Other Publications

- `Preprint 2026` [EvoDiagram: Agentic Editable Diagram Creation via Design Expertise Evolution](https://arxiv.org/abs/2604.09568)  
  Tianfu Wang, Leilei Ding, Ziyang Tao, Yi Zhan, Zhiyuan Ma, Wei Wu, **Yuxuan Lei**, Yuan Feng, Junyang Wang, Yin Wu, Yizhao Xu, Hongyuan Zhu, Qi Liu, Nicholas Jing Yuan, Yanyong Zhang, Hui Xiong  
  [\[Paper\]](https://arxiv.org/abs/2604.09568)

- `Neurocomputing 2023` [Enhancing Text Representations Separately with Entity Descriptions](https://doi.org/10.1016/j.neucom.2023.126511)  
  Qinghua Zhao, **Yuxuan Lei**, Qiang Wang, Zhongfeng Kang, Junfeng Liu  
  [\[Paper\]](https://doi.org/10.1016/j.neucom.2023.126511)


# 🎖 Honors and Awards
- *2025* Sony Commonsense Persona-Grounded Dialogue Challenge (CPDC) — **1st place** in Track 2, 2nd in Track 1, 3rd in Track 3.
- *2024* National Scholarship for Graduate Students.
- *2023* Amazon KDD Cup 2023 — **3rd place** among 2.8k participants.
- *2022* Outstanding Graduate, USTC.
- *2022* Outstanding Student Scholarship
- *2022* Suzhou Yucai Scholarship
- *2022* Huayu Scholarship
- *2020* Tang Lixin Scholarship
- *2019* Gold Medal and Best Software nomination at iGEM.

# 📖 Educations
- *2022.09 - 2027.06 (expected)*, Ph.D. in Computer Science and Technology, joint program of University of Science and Technology of China and Microsoft Research Asia. GPA 4.12/4.3, ranked 1/82.
- *2018.09 - 2022.06*, B.Eng. in Computer Science and Technology, University of Science and Technology of China. GPA 3.96/4.3, ranked 4/178.

# 💻 Experience
- *2026.07 - Present*, **Qwen Team**, Alibaba, Beijing, China. 
- *2023.09 - 2026.05*, **Microsoft Research Asia**, Social Computing Group, Beijing, China.

# 💬 Academic Services
- Reviewer for ACL Rolling Review (ARR), ICLR, ICML, KDD and WWW.

# 💡 Skills
- **Programming**: Python, Bash, LaTeX
- **ML frameworks**: PyTorch, Transformers, DeepSpeed, vLLM, verl, trl, LLaMA-Factory, SGLang
- **AI-assisted coding**: Codex, Cursor, GitHub Copilot, Claude Code
- **Tools**: Linux, Git, Weights &amp; Biases, Overleaf
