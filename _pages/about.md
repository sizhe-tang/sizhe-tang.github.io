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

<!-- 注意：作者顺序我按 Google Scholar 推断（把你列为第一作者），请核对；一句话描述也可自行润色。 -->

<style>
.pub-card {
  border: 1px solid #e8e8e8;          /* 浅灰边框，避免视觉杂乱 */
  border-radius: 10px;
  padding: 10px 18px;
  margin-bottom: 14px;
  background: #ffffff;
}
.pub-card p { margin: 0.35em 0; }
.pub-desc { color: #666; font-size: 0.9em; }
.tag {
  display: inline-block;
  padding: 1px 11px;
  border-radius: 12px;
  font-size: 0.75em;
  font-weight: 600;
  letter-spacing: 0.3px;
}
.tag-cua { background: #fdf3c0; color: #7a6500; }   /* 淡黄 · Computer-Use Agent */
.tag-pt  { background: #d6f3dd; color: #1d6b34; }    /* 淡绿 · Post-training */
.tag-rl  { background: #e9dcfb; color: #5a39a0; }    /* 淡紫 · RL */

/* 加宽正文内容列、收窄左侧作者栏，减少论文标题换行（仅大屏生效） */
@media (min-width: 1200px) {
  .sidebar { width: 12%; }
  .page    { width: 87%; padding-left: 1.5em; }
}
</style>

<div class="pub-card" markdown="1">

<span class="tag tag-rl">RL</span>

**Sizhe Tang**, Z. Zhang, M. Imani, Tian Lan. [*NonZero: Interaction-Guided Exploration for Multi-Agent Monte Carlo Tree Search*](https://arxiv.org/abs/2605.00751). **ICML 2026** (<span style="color:red">Spotlight</span>).

<span class="pub-desc">An interaction-guided exploration rule that scales Monte Carlo Tree Search to multi-agent planning.</span>
</div>

<div class="pub-card" markdown="1">

<span class="tag tag-rl">RL</span>

**Sizhe Tang**, Z. Zhang, Tian Lan. [*Cochain Perspectives on Temporal-Difference Signals for Learning Beyond Markov Dynamics*](https://arxiv.org/abs/2602.06939). **ICML 2026**.

<span class="pub-desc">A cochain view of temporal-difference signals that extends RL to non-Markovian dynamics.</span>
</div>

<div class="pub-card" markdown="1">

<span class="tag tag-pt">Post-training</span>

**Sizhe Tang**, Y. Li, Tian Lan. [*Reason in Chains, Learn in Trees: Self-Rectification and Grafting for Multi-turn Agent Policy Optimization*](https://arxiv.org/abs/2604.07165). **ACL 2026 Findings**.

<span class="pub-desc">Multi-turn agent policy optimization that self-rectifies reasoning chains and grafts good branches via tree search.</span>
</div>

<div class="pub-card" markdown="1">

<span class="tag tag-rl">RL</span>

**Sizhe Tang**, Jiayu Chen, Tian Lan. [*MALinZero: Efficient Low-Dimensional Search for Mastering Complex Multi-Agent Planning*](https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cd8644fab1f7837acd8298f6360864c-Abstract-Conference.html). **NeurIPS 2025**.

<span class="pub-desc">A low-dimensional linear-bandit (LinUCT) search that makes joint-action MCTS efficient for complex multi-agent planning.</span>
</div>

<div class="pub-card" markdown="1">

<span class="tag tag-cua">Computer-Use Agent</span>

**Sizhe Tang**, R. Chen, Tian Lan. [*Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents*](https://arxiv.org/abs/2602.02995). **arXiv preprint, 2026**.

<span class="pub-desc">A tree-search framework unifying generation, exploration, and evaluation for computer-use agents.</span>
</div>

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
