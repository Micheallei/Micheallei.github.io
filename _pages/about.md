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

I am a joint Ph.D. student at the [**University of Science and Technology of China (USTC)**](https://en.ustc.edu.cn/) and [**Microsoft Research Asia (MSRA)**](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/), advised by [Xing Xie](https://www.microsoft.com/en-us/research/people/xingx/) (Partner Research Manager at MSRA, ACM/IEEE Fellow) and [Defu Lian](https://faculty.ustc.edu.cn/liandefu/en/index.htm) (Professor and Associate Dean of the School of Computer Science, USTC). I received my B.Eng. in Computer Science from USTC in 2022. I am currently a research intern in the **Qwen Foundation Model Team** at Alibaba, working on agentic memory.

My research aims to make large language models genuinely *understand and serve individual people*. Concretely, I work on:

- **LLM post-training** — supervised fine-tuning and reinforcement learning for reasoning and behavior alignment
- **Personalization and human-like intelligence** — modeling, simulating and evaluating human behavior with LLMs
- **LLM agents and memory** — agentic loops, tool use, and long-horizon memory systems
- **LLM-powered recommender systems** — bridging recommenders and language models

I have published 14 papers, including 4 first-author papers at CCF-A venues, with <a href='https://scholar.google.com/citations?user=MVUVrxQAAAAJ&hl=en'>google scholar citations <strong><span id='total_cit'>1180+</span></strong></a> <a href='https://scholar.google.com/citations?user=MVUVrxQAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. As a core contributor to [RecAI](https://github.com/microsoft/RecAI) (1.2k+ stars), I also placed 3rd in Amazon KDD Cup 2023 and 1st in a track of the Sony CPDC Challenge 2025.

I am always happy to chat about research or collaboration — feel free to reach me at <leiyuxuan@mail.ustc.edu.cn>.

# 🔥 News
- *2026.07*: &nbsp;🎉 Started as a research intern in the **Qwen Foundation Model Team**, working on agentic memory.
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
  Reframes open-ended human behavior simulation as *distribution-level* behavior alignment rather than answer correctness, and measures rationality, consistency and diversity from micro-level plausibility to macro-level population structure.  
  [\[paper\]](https://www.microsoft.com/en-us/research/publication/a-computational-framework-for-evaluating-human-likeness-in-llms-open-ended-human-behaviors/)

- `KDD 2026` [HumanLLM: Towards Personalized Understanding and Simulation of Human Nature](https://arxiv.org/abs/2601.15793)  
  **Yuxuan Lei**, Tianfu Wang, Jianxun Lian, Zhengyu Hu, Defu Lian, Xing Xie  
  Builds the *Cognitive Genome Dataset* grounded in Lewin's Equation, modeling real user behavior as a dynamic interaction among person, environment and behavior, and trains HumanLLM to capture user preferences, thoughts and individual behavioral patterns.  
  [\[arXiv\]](https://arxiv.org/abs/2601.15793) [\[ACM\]](https://dl.acm.org/doi/10.1145/3770854.3780294) <span class='show_paper_citations' data='MVUVrxQAAAAJ:LPtt_HFRSbwC'></span>

- `Preprint 2026` [Social-R1: Towards Human-like Social Reasoning in LLMs](https://arxiv.org/abs/2603.09249)  
  Jincenzi Wu, **Yuxuan Lei**, Jianxun Lian, Yitian Huang, Lexin Zhou, Haotian Li, Xing Xie, Helen Meng  
  Identifies *reasoning parasitism* and the *interpretation bottleneck* in LLM social reasoning, and aligns the whole reasoning trajectory — not just the final answer — with process rewards derived from Social Information Processing theory.  
  [\[arXiv\]](https://arxiv.org/abs/2603.09249) <span class='show_paper_citations' data='MVUVrxQAAAAJ:6bLC7aUMtPcC'></span>

- `Preprint 2025` [Population-Aligned Persona Generation for LLM-based Social Simulation](https://arxiv.org/abs/2509.10127)  
  Zhengyu Hu, Zheyuan Xiao, Max Xiong, **Yuxuan Lei**, Tianfu Wang, Jianxun Lian, Kaize Ding, Ziang Xiao, Nicholas Jing Yuan, Xing Xie  
  [\[arXiv\]](https://arxiv.org/abs/2509.10127) <span class='show_paper_citations' data='MVUVrxQAAAAJ:hsZV8lGYWTMC'></span>

- `Tech Report 2025` [Interactive AI NPCs Powered by LLMs: Technical Report for the CPDC Challenge 2025](https://arxiv.org/abs/2511.20200)  
  Yitian Huang, **Yuxuan Lei**, Jianxun Lian, Hao Liao  
  Context engineering plus GRPO training for persona-grounded, tool-calling dialogue agents; **1st place** in Task 2 (API Track) of the Sony CPDC Challenge 2025.  
  [\[arXiv\]](https://arxiv.org/abs/2511.20200)

## LLM-powered Recommender Systems

- `KDD 2024` [RecExplainer: Aligning Large Language Models for Explaining Recommendation Models](https://arxiv.org/abs/2311.10947)  
  **Yuxuan Lei**, Jianxun Lian, Jing Yao, Xu Huang, Defu Lian, Xing Xie  
  The first exploration of LLMs as natural-language surrogate explainers for black-box recommenders, aligning both the predictive behavior and the latent representations of the target model.  
  [\[arXiv\]](https://arxiv.org/abs/2311.10947) [\[ACM\]](https://dl.acm.org/doi/10.1145/3637528.3671802) [\[code\]](https://github.com/microsoft/RecAI/tree/main/RecExplainer) <span class='show_paper_citations' data='MVUVrxQAAAAJ:Br1UauaknNIC'></span>

- `WWW 2024` [Aligning Language Models for Versatile Text-based Item Retrieval](https://arxiv.org/abs/2402.18899)  
  **Yuxuan Lei**, Jianxun Lian, Jing Yao, Mingqi Wu, Defu Lian, Xing Xie  
  A text-to-item representation alignment framework covering ten retrieval tasks over implicit, explicit, vague and hybrid intents, with fine-grained query generation and negative sampling; consistent gains across BERT, BGE, E5 and RepLLaMA.  
  [\[arXiv\]](https://arxiv.org/abs/2402.18899) [\[ACM\]](https://dl.acm.org/doi/10.1145/3589335.3651468) <span class='show_paper_citations' data='MVUVrxQAAAAJ:XUvXOeBm_78C'></span>

- `TOIS 2025` [Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations](https://arxiv.org/abs/2308.16505)  
  Xu Huang, Jianxun Lian, **Yuxuan Lei**, Jing Yao, Defu Lian, Xing Xie  
  InteRecAgent, an "LLM as Brain, Recommender as Tool" framework with a shared candidate bus, long/short-term user memory, dynamic demonstration and actor–critic reflection for multi-turn conversational recommendation.  
  [\[arXiv\]](https://arxiv.org/abs/2308.16505) [\[ACM\]](https://dl.acm.org/doi/10.1145/3731446) [\[code\]](https://github.com/microsoft/RecAI/tree/main/InteRecAgent) <span class='show_paper_citations' data='MVUVrxQAAAAJ:CB2v5VPnA5kC'></span>

- `WWW 2024 Demo` [RecAI: Leveraging Large Language Models for Next-Generation Recommender Systems](https://arxiv.org/abs/2403.06465)  
  Jianxun Lian, **Yuxuan Lei**, Xu Huang, Jing Yao, Wei Xu, Xing Xie  
  [\[arXiv\]](https://arxiv.org/abs/2403.06465) [\[ACM\]](https://dl.acm.org/doi/10.1145/3589335.3651242) [\[code\]](https://github.com/microsoft/RecAI) <span class='show_paper_citations' data='MVUVrxQAAAAJ:prdVHNxh-e8C'></span>

- `WWWJ 2024` [When Large Language Models Meet Personalization: Perspectives of Challenges and Opportunities](https://arxiv.org/abs/2307.16376)  
  Jin Chen, Zheng Liu, Xu Huang, Chenwang Wu, Qi Liu, Gangwei Jiang, Yuanhao Pu, **Yuxuan Lei**, Xiaolong Chen, Xingmei Wang, Kai Zheng, Defu Lian, Enhong Chen  
  A survey of LLM-based personalization, covering personalized understanding, generation, evaluation and system design.  
  [\[arXiv\]](https://arxiv.org/abs/2307.16376) [\[journal\]](https://doi.org/10.1007/s11280-024-01276-1) <span class='show_paper_citations' data='MVUVrxQAAAAJ:PYBJJbyH-FwC'></span>

- `KDD Cup 2023 Workshop` [Practical Content-aware Session-based Recommendation: Deep Retrieve then Shallow Rank](https://openreview.net/forum?id=6MdSsLgDei)  
  **Yuxuan Lei**, Xiaolong Chen, Defu Lian, Peng Zhang, Jianxun Lian, Chaozhuo Li, Xing Xie  
  A two-stage content-aware pipeline for multilingual session-based recommendation; **3rd place** in Amazon KDD Cup 2023.  
  [\[paper\]](https://openreview.net/forum?id=6MdSsLgDei) <span class='show_paper_citations' data='MVUVrxQAAAAJ:jU7OWUQzBzMC'></span>

## Other Publications

- `Preprint 2026` [EvoDiagram: Agentic Editable Diagram Creation via Design Expertise Evolution](https://arxiv.org/abs/2604.09568)  
  Tianfu Wang, Leilei Ding, Ziyang Tao, Yi Zhan, Zhiyuan Ma, Wei Wu, **Yuxuan Lei**, Yuan Feng, Junyang Wang, Yin Wu, Yizhao Xu, Hongyuan Zhu, Qi Liu, Nicholas Jing Yuan, Yanyong Zhang, Hui Xiong  
  [\[arXiv\]](https://arxiv.org/abs/2604.09568)

- `Neurocomputing 2023` [Enhancing Text Representations Separately with Entity Descriptions](https://doi.org/10.1016/j.neucom.2023.126511)  
  Qinghua Zhao, **Yuxuan Lei**, Qiang Wang, Zhongfeng Kang, Junfeng Liu  
  [\[journal\]](https://doi.org/10.1016/j.neucom.2023.126511) <span class='show_paper_citations' data='MVUVrxQAAAAJ:owLR8QvbtFgC'></span>

# 🚀 Projects

- **Copanion: An Enduring Cooperative Companion for Human-AI Synergy**  
  A general-purpose agent system built from scratch: a ReAct-style agentic loop, the MCP tool protocol, a skills system, multi-level memory with hybrid retrieval, concurrent subagent spawning, a scheduler, multi-channel communication, self-evolution, and an editable persona. A three-tier *context compaction + cacheable prefix* architecture cuts cost, while three-stage self-reflection and anti-regression safeguards keep long-horizon tasks reliable. On top of it, an AI collaboration team — Auto-Research, Paper-Reviewer, Talent Search and Resume Evaluation — turns conversation into deliverable output behind validation gates and evidence-based state machines.

- **[RecAI](https://github.com/microsoft/RecAI)** &nbsp;<img src="https://img.shields.io/github/stars/microsoft/RecAI?style=flat&labelColor=f6f6f6&color=9cf" style="vertical-align: middle;">  
  Microsoft's open-source effort to bridge LLMs and recommender systems. Core contributor; my work on RecExplainer, item retrieval and InteRecAgent is released here.

# 🎖 Honors and Awards
- *2025* Sony Commonsense Persona-Grounded Dialogue Challenge (CPDC) — **1st place** in Track 2, 2nd in Track 1, 3rd in Track 3.
- *2024* National Scholarship for Graduate Students.
- *2023* Amazon KDD Cup 2023 — **3rd place** among 2.8k participants.
- *2022* Outstanding Graduate, USTC.
- Suzhou Yucai Scholarship, Outstanding Student Scholarship, Tang Lixin Scholarship and Huayu Scholarship; Gold Medal and Best Software nomination at iGEM.

# 📖 Educations
- *2022.09 - 2027.06 (expected)*, Ph.D. in Computer Science and Technology, joint program of University of Science and Technology of China and Microsoft Research Asia. GPA 4.12/4.3, ranked 1/82.
- *2018.09 - 2022.06*, B.Eng. in Computer Science and Technology, University of Science and Technology of China. GPA 3.96/4.3, ranked 4/178.

# 💻 Experience
- *2026.07 - Present*, **Qwen Foundation Model Team**, Alibaba, Beijing, China. Optimizing model capabilities for agentic memory: internalizing memory production and consumption as native model abilities exposed through a unified tool-calling interface, and building a memory benchmark from real user logs to evaluate robustness under very long, noisy histories.
- *2023.09 - 2026.05*, **Microsoft Research Asia**, Social Computing Group, Beijing, China. Led the research above on human-like intelligence and LLM-powered recommender systems.

# 💬 Academic Services
- Reviewer for ACL Rolling Review (ARR), ICLR, ICML, KDD and WWW.

# 💡 Skills
- **Programming**: Python, Bash, LaTeX
- **ML frameworks**: PyTorch, Transformers, DeepSpeed, vLLM, verl, trl, LLaMA-Factory, SGLang
- **AI-assisted coding**: Codex, Cursor, GitHub Copilot, Claude Code
- **Tools**: Linux, Git, Weights &amp; Biases, Overleaf
