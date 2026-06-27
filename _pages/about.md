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

Hi! I am **Sizhe Tang**, a Ph.D. student at [The George Washington University](https://www.gwu.edu/) in Washington, D.C., advised by Prof. Tian Lan.
<!-- TODO: 请确认 ① 是否博士生（不是的话改成 Master's/其它）② 导师是否 Tian Lan，要不要加导师主页链接 -->

My research focuses on **reinforcement learning**, **multi-agent systems**, and **LLM-based agents** — in particular tree-search and planning methods for multi-agent decision making (the *Zero* series), computer-use agents, and multi-turn agent policy optimization.
<!-- TODO: 这段可按你自己的话再润色 -->

You can find my publications on <a href='https://scholar.google.com/citations?user=XrAl4vgAAAAJ'>Google Scholar</a>.
<!-- 引用数徽章：等自动抓取工作流跑出 google-scholar-stats 分支后，把下面这行的注释去掉即可显示实时引用数：
<a href='https://scholar.google.com/citations?user=XrAl4vgAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>
-->


# 🔥 News
- *2026.05*: &nbsp;🎉 *NonZero* was accepted to **ICML 2026** as a **Spotlight**.
- *2025.09*: &nbsp;🎉 *MALinZero* was accepted to **NeurIPS 2025**.
<!-- TODO: News 日期是按惯例估的，请按实际录用时间调整；可继续往上添加最新动态 -->

# 📝 Publications

<!-- 注意：以下作者顺序是我根据 Google Scholar 推断的（把你列在第一作者），请你核对每篇的真实作者顺序，并给标题加上论文链接（[标题](链接)）。共同一作可用 † 标注。 -->

- **Sizhe Tang**, Z. Zhang, M. Imani, Tian Lan. *NonZero: Interaction-Guided Exploration for Multi-Agent Monte Carlo Tree Search*. **ICML 2026 (Spotlight)**.

- **Sizhe Tang**, J. Chen, Tian Lan. *MALinZero: Efficient Low-Dimensional Search for Mastering Complex Multi-Agent Planning*. **NeurIPS 2025**.

- **Sizhe Tang**, Y. Li, Tian Lan. *Reason in Chains, Learn in Trees: Self-Rectification and Grafting for Multi-turn Agent Policy Optimization*. **ACL 2026 Findings**.

- **Sizhe Tang**, Z. Zhang, Tian Lan. *Cochain Perspectives on Temporal-Difference Signals for Learning Beyond Markov Dynamics*. **ICML 2026**.

- **Sizhe Tang**, R. Chen, Tian Lan. *Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents*. **arXiv preprint, 2026**.

- **Sizhe Tang**, Y. Li, R. Chen, et al., Tian Lan. *ACDZero: Graph-Embedding-Based Tree Search for Mastering Automated Cyber Defense*. **INFOCOM Workshop on ICCN, 2026**.

- **Sizhe Tang**, Y. Li, M. Imani, Tian Lan. *Towards Low-Dimensional Search for Mastering Multi-Agent Planning*. **AAAI Symposium Series, 2026**.

<!-- 你 Scholar 上还有更早的边缘计算/综述类论文（如 IEEE Communications Magazine 2023、Applied Soft Computing 2022 等，你为合作作者）。如果想展示，告诉我，我帮你按真实作者顺序补到这里。 -->

# 📖 Educations
- *20XX.XX - Present*, Ph.D. in Computer Engineering, The George Washington University, Washington, D.C.
- *20XX.XX - 20XX.XX*, B.S. in XXX, University Name.
<!-- TODO: 填写真实的学位/专业/起止时间（本科学校等）。读博院系若不是 Computer Engineering 也请改。 -->

<!-- 下面这些章节先注释掉了，等你有内容时取消注释、并到 _data/navigation.yml 里把对应导航项加回来即可：

# 🎖 Honors and Awards
- *Year*: Award / scholarship name.

# 💬 Invited Talks
- *Year*: Talk title, venue.

# 💻 Internships
- *Year*: Role, Company / Lab, Location.
-->
