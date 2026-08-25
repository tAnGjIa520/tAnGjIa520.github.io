---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<h1 class="main-heading">你好 👋 欢迎来到我的主页！</h1>

我是 **TangJia**。这里是我的个人主页与博客，用来记录研究、技术实践，以及生活中值得留下的想法。

这个页面刚刚开始建设，内容会持续更新。如果你对我的项目或文章感兴趣，欢迎通过 [GitHub](https://github.com/tAnGjIa520) 与我交流。

<h2 id="news">最近动态</h2>

<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.08</em></span> 🚀 使用 WowPage 模板搭建个人主页。</li>
    <li><span class="news-date"><em>持续更新</em></span> ✍️ 开始整理学习笔记与项目记录。</li>
  </ul>
</div>

<h2 id="about">关于我</h2>

<div class="experience-container">
  <div class="experience-card">
    <div class="profile-icon">研</div>
    <div class="experience-info">
      <strong>研究与学习</strong><br>
      我关注人工智能、机器学习和强化学习方向，也喜欢探索有趣且真正有用的技术问题。
    </div>
  </div>

  <div class="experience-card">
    <div class="profile-icon">码</div>
    <div class="experience-info">
      <strong>工程与创造</strong><br>
      我会在这里分享代码、实验过程、踩坑记录，以及从想法到实现的完整经历。
    </div>
  </div>

  <div class="experience-card">
    <div class="profile-icon">记</div>
    <div class="experience-info">
      <strong>写作与记录</strong><br>
      写作帮助我梳理思路，也让零散的经验能够被未来的自己再次找到。
    </div>
  </div>
</div>

<h2 id="projects">项目</h2>

<div class="project-card">
  <div class="project-inner">
    <div class="project-mark">TJ</div>
    <div>
      <strong>TangJia 的个人主页</strong><br>
      基于 Jekyll 与 WowPage 搭建，托管于 GitHub Pages。这里会逐步汇总我的个人项目、研究工作和文章。
      <br>
      <a href="https://github.com/tAnGjIa520"><em>[GitHub]</em></a>
    </div>
  </div>
</div>

<h2 id="writing">最近文章</h2>

<div class="writing-list">
{% for post in site.posts limit: 5 %}
  <article class="writing-item">
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y.%m.%d" }}</time>
    <div>
      <a href="{{ post.url }}"><strong>{{ post.title }}</strong></a>
      {% if post.excerpt %}<p>{{ post.excerpt | strip_html | truncate: 110 }}</p>{% endif %}
    </div>
  </article>
{% endfor %}
</div>

[查看全部文章 →](/blog/){: .btn .btn--primary }

<h2 id="contact">联系</h2>

目前可以通过 [GitHub @tAnGjIa520](https://github.com/tAnGjIa520) 找到我。邮箱、学校或工作经历等信息可以在准备好后继续补充。
