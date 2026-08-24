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

I am a joint Ph.D. student at the **University of Science and Technology of China (USTC)** and **Microsoft Research Asia (MSRA)**, advised by [Xing Xie](https://www.microsoft.com/en-us/research/people/xingx/) (Partner Research Manager at MSRA, ACM/IEEE Fellow) and [Defu Lian](https://faculty.ustc.edu.cn/liandefu/en/index.htm) (Professor and Associate Dean of the School of Computer Science, USTC). I received my B.Eng. in Computer Science from USTC in 2022.

My research aims to make large language models genuinely *understand and serve individual people*. Concretely, I work on:

- **LLM post-training** — supervised fine-tuning and reinforcement learning for reasoning and behavior alignment
- **Personalization and human-like intelligence** — modeling, simulating and evaluating human behavior with LLMs
- **LLM agents and memory** — agentic loops, tool use, and long-horizon memory systems
- **LLM-powered recommender systems** — bridging recommenders and language models

I have published 14 papers in total, including 4 first-author papers at CCF-A conferences, with <a href='https://scholar.google.com/citations?user=MVUVrxQAAAAJ&hl=en'>google scholar citations <strong><span id='total_cit'>1100+</span></strong></a> <a href='https://scholar.google.com/citations?user=MVUVrxQAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. As a core contributor to [RecAI](https://github.com/microsoft/RecAI) (1.1k+ stars), I also placed 3rd in Amazon KDD Cup 2023 and 1st in a track of the Sony CPDC Challenge 2025.

I am always happy to chat about research or collaboration — feel free to reach me at <leiyuxuan@mail.ustc.edu.cn>.

# 🔥 News
- *2026.07*: &nbsp;🎉 Started as a research intern in the **Qwen Foundation Model Team**, working on agentic memory.
- *2026*: &nbsp;🎉 Two first-author papers accepted at **ICML 2026** and **KDD 2026**.
- *2025.11*: &nbsp;🏆 Our team ranked **1st in Track 2**, 2nd in Track 1 and 3rd in Track 3 of the **Sony CPDC Challenge 2025**.
- *2024*: &nbsp;🎖 Awarded the **National Scholarship for Graduate Students**.
- *2024*: &nbsp;🎉 First-author papers accepted at **KDD 2024** (RecExplainer) and **WWW 2024** (text-based item retrieval).
- *2023*: &nbsp;🏆 Placed **3rd** in **Amazon KDD Cup 2023** among 2.8k participants.

# 📝 Publications

Authorship roles below follow the venue's convention; <sup>†</sup> denotes co-first authorship.

## Human-centric AI Systems

- **A Computational Framework for Evaluating Human-likeness in LLMs' Open-ended Human Behaviors**  
  *ICML 2026* (CCF-A) · **First author**  
  Reframes open-ended human behavior simulation as *distribution-level* behavior alignment, moving beyond the correctness-based evaluation paradigm, and measures rationality, consistency and diversity from micro-level plausibility to macro-level population structure.  
  [\[paper\]](https://www.microsoft.com/en-us/research/publication/a-computational-framework-for-evaluating-human-likeness-in-llms-open-ended-human-behaviors/)

- **HumanLLM: Towards Personalized Understanding and Simulation of Human Nature**  
  *KDD 2026* (CCF-A) · **First author**  
  Builds the *Cognitive Genome Dataset* grounded in Lewin's Equation, modeling real user behavior as a dynamic interaction among person, environment and behavior, and trains HumanLLM to capture user preferences, thoughts and individual behavioral patterns.  
  [\[arXiv\]](https://arxiv.org/abs/2601.15793) [\[ACM\]](https://dl.acm.org/doi/10.1145/3770854.3780294)

- **SocialCoach: Personalized Social Skill Learning with Agentic Tutoring and Practice**  
  *Under review* · **Co-first author**<sup>†</sup>  
  Casts open-ended social skill training as cold-start, retrieval-constrained sequential practice scheduling, combining a theory-to-practice social knowledge corpus with a prescription–retrieval–adaptation scheduler optimized by trajectory-level GRPO.

- **Social-R1: Trajectory-level Reinforcement Learning for Social Reasoning**  
  *Under review* · **Second author**  
  Identifies *reasoning parasitism* and the *interpretation bottleneck* in LLM social reasoning, and aligns the whole reasoning trajectory — not just the final answer — using process rewards derived from Social Information Processing theory.  
  [\[arXiv\]](https://arxiv.org/abs/2603.09249)

- **Interactive AI NPCs Powered by LLMs: Technical Report for the CPDC Challenge 2025**  
  *arXiv 2025* · **Second author**  
  Context engineering plus GRPO training for persona-grounded, tool-calling dialogue agents; ranked 1st in Task 2 (API Track) of the challenge.  
  [\[arXiv\]](https://arxiv.org/abs/2511.20200)

## LLM-powered Recommender Systems

- **RecExplainer: Aligning Large Language Models for Explaining Recommendation Models**  
  *KDD 2024* (CCF-A) · **First author**  
  The first exploration of LLMs as natural-language surrogate explainers for black-box recommenders, aligning both the predictive behavior and the latent representations of the target model.  
  [\[arXiv\]](https://arxiv.org/abs/2311.10947) [\[ACM\]](https://dl.acm.org/doi/10.1145/3637528.3671802) [\[code\]](https://github.com/microsoft/RecAI/tree/main/RecExplainer)

- **Aligning Language Models for Versatile Text-based Item Retrieval**  
  *WWW 2024* (CCF-A) · **First author**  
  A text-to-item representation alignment framework covering ten retrieval tasks over implicit, explicit, vague and hybrid intents, with fine-grained query generation and negative sampling; yields consistent gains across BERT, BGE, E5 and RepLLaMA.  
  [\[arXiv\]](https://arxiv.org/abs/2402.18899) [\[ACM\]](https://dl.acm.org/doi/10.1145/3589335.3651468)

- **Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations**  
  *TOIS 2025* (CCF-A) · **Third author**  
  InteRecAgent, an "LLM as Brain, Recommender as Tool" framework with a shared candidate bus, long/short-term user memory, dynamic demonstration and actor-critic reflection for multi-turn conversational recommendation.  
  [\[arXiv\]](https://arxiv.org/abs/2308.16505) [\[ACM\]](https://dl.acm.org/doi/10.1145/3731446) [\[code\]](https://github.com/microsoft/RecAI/tree/main/InteRecAgent)

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
- *2026.07 - Present*, **Qwen Foundation Model Team**. Optimizing model capabilities for agentic memory: internalizing memory production and consumption as native model abilities exposed through a unified tool-calling interface, and building a memory benchmark from real user logs to evaluate robustness under very long, noisy histories.
- *2023.09 - 2026.05*, **Microsoft Research Asia**, Social Computing Group. Led the research described above on human-centric AI systems and LLM-powered recommender systems.

# 💬 Academic Services
- Reviewer for ACL Rolling Review (ARR), ICLR, ICML, KDD and WWW.

# 💡 Skills
- **Programming**: Python, Bash, LaTeX
- **ML frameworks**: PyTorch, Transformers, DeepSpeed, vLLM, verl, trl, LLaMA-Factory, SGLang
- **AI-assisted coding**: Codex, Cursor, GitHub Copilot, Claude Code
- **Tools**: Linux, Git, Weights &amp; Biases, Overleaf
