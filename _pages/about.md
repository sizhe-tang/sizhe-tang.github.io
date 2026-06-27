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

Hi! I am **Sizhe Tang**, a second-year Ph.D. candidate at [The George Washington University](https://www.gwu.edu/), advised by Prof. [Tian Lan](https://www2.seas.gwu.edu/~tlan/).

My research focuses on **reinforcement learning** and **self-evolving agents**, with an emphasis on tree-search and planning for multi-agent decision-making (the *Zero* series), computer-use agents, and multi-turn agent policy optimization.

You can find my publications on <a href='https://scholar.google.com/citations?user=XrAl4vgAAAAJ'>Google Scholar</a>.
<!-- 引用数徽章：等自动抓取工作流跑出 google-scholar-stats 分支后，把下面这行的注释去掉即可显示实时引用数：
<a href='https://scholar.google.com/citations?user=XrAl4vgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
-->


# 🔥 News
- *2026.05*: &nbsp;🎉 [**NonZero**](https://arxiv.org/abs/2605.00751) accepted to **ICML 2026** (<span style="color:red">Spotlight</span>).
- *2026.05*: &nbsp;🎉 [**HFPS**](https://arxiv.org/abs/2602.06939) accepted to **ICML 2026**.
- *2026.04*: &nbsp;🎉 I will join **Amazon AWS AI** as an Applied Scientist Intern (Summer 2026, Santa Clara, CA).
- *2026.03*: &nbsp;🎉 [**T-STAR**](https://arxiv.org/abs/2604.07165) accepted to **ACL 2026 Findings**.
- *2025.09*: &nbsp;🎉 [**MALinZero**](https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cd8644fab1f7837acd8298f6360864c-Abstract-Conference.html) accepted to **NeurIPS 2025**.
<!-- TODO: News 日期是按惯例估的，请按实际录用/起始时间调整 -->

# 📝 Selected Publications

<!-- 注意：作者顺序我按 Google Scholar 推断（把你列为第一作者），请核对；可给标题加论文链接 [标题](链接)，共同一作用 † 标注。 -->

- **Sizhe Tang**, Z. Zhang, M. Imani, Tian Lan. [*NonZero: Interaction-Guided Exploration for Multi-Agent Monte Carlo Tree Search*](https://arxiv.org/abs/2605.00751). **ICML 2026** (<span style="color:red">Spotlight</span>).

- **Sizhe Tang**, Jiayu Chen, Tian Lan. [*MALinZero: Efficient Low-Dimensional Search for Mastering Complex Multi-Agent Planning*](https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cd8644fab1f7837acd8298f6360864c-Abstract-Conference.html). **NeurIPS 2025**.

- **Sizhe Tang**, Y. Li, Tian Lan. [*Reason in Chains, Learn in Trees: Self-Rectification and Grafting for Multi-turn Agent Policy Optimization*](https://arxiv.org/abs/2604.07165). **ACL 2026 Findings**.

- **Sizhe Tang**, Z. Zhang, Tian Lan. [*Cochain Perspectives on Temporal-Difference Signals for Learning Beyond Markov Dynamics*](https://arxiv.org/abs/2602.06939). **ICML 2026**.

- **Sizhe Tang**, R. Chen, Tian Lan. [*Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents*](https://arxiv.org/abs/2602.02995). **arXiv preprint, 2026**.

# 💼 Experience
- *2026.05 - 2026.08*, Applied Scientist Intern, **Amazon AWS AI**, Santa Clara, CA.
  - Working on web and coding agents (LLM-based autonomous agents).
<!-- TODO: 把上面这行实习描述换成你真实做的工作 -->

# 📖 Educations
- *2024 - 2028 (expected)*, Ph.D. in Computer Engineering, The George Washington University, Washington, D.C.
<!-- TODO: 确认读博院系；如需展示本科经历，按同样格式再加一行 -->

<!-- 需要时可取消注释以下章节，并到 _data/navigation.yml 把对应导航项加回来：

# 🎖 Honors and Awards
- *Year*: Award / scholarship name.

# 💬 Invited Talks
- *Year*: Talk title, venue.
-->
