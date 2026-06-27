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

Hi! I am **Sizhe Tang**, a graduate student at [George Washington University](https://www.gwu.edu/) in Washington, D.C.
<!-- TODO: 改成你的真实身份，例如 "a first-year Ph.D. student in Computer Science, advised by Prof. XXX" -->

My research interests are currently taking shape, and I will be sharing my projects and publications here as my work develops.
<!-- TODO: 把上面这句换成你的真实研究方向再发布。例如：
My research interests include machine learning and natural language processing. Currently, I am working on ...
（这里可以写 1–2 段自我介绍：背景、方向、正在做的事） -->

<!--
如果你有 Google Scholar 主页，先在 _config.yml 里把 googlescholar 填上，
再把下面这段的注释去掉、把 YOUR_SCHOLAR_ID 换成你的 ID，就能显示引用数徽章：

My publications can be found on <a href='https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID'>Google Scholar</a> <a href='https://scholar.google.com/citations?user=YOUR_SCHOLAR_ID'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
-->


# 🔥 News
- *2026.06*: &nbsp;🎉 Launched my academic homepage.
<!-- TODO: 在这里按时间倒序添加你的动态（论文录用、获奖、实习等） -->

# 📝 Publications

<!-- 论文卡片示例：复制下面这个 <div> 块即可添加更多论文；把 images/500x300.png 换成你的论文配图。
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Venue Year</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Paper Title](https://link-to-the-paper)

**Sizhe Tang**, Co-author A, Co-author B

[**Project**](https://project-page-or-code) <strong><span class='show_paper_citations' data='SCHOLAR_PAPER_ID'></span></strong>
- A one-line summary of the paper's contribution.
</div>
</div>
-->

*Coming soon.*
<!-- TODO: 用上面注释里的卡片格式，或下面这种纯文本格式列出论文：
- [Paper Title](https://link), Author A, **Sizhe Tang**, Author C, **Venue Year**
-->

# 🎖 Honors and Awards
- *Year*: Award / scholarship name.
<!-- TODO: 替换或删除 -->

# 📖 Educations
- *2024.XX - Present*, Graduate Student, George Washington University, Washington, D.C.
- *20XX.XX - 20XX.XX*, B.S. in XXX, University Name.
<!-- TODO: 填写你真实的学位、专业、时间 -->

# 💬 Invited Talks
- *Year*: Talk title, venue.
<!-- TODO: 替换或删除整个章节 -->

# 💻 Internships
- *Year*: Role, Company / Lab, Location.
<!-- TODO: 替换或删除整个章节 -->
