---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<h1 class="main-heading">Hi there 👋 I'm Tang Jia</h1>

I received my M.Sc. in **Computer Science and Technology from Nanjing University of Aeronautics and Astronautics (NUAA)** and am currently an **Algorithm Engineer at Shanghai AI Laboratory (Pujiang Laboratory)**. My research interests include **reinforcement learning, world models, continual learning, and Mixture-of-Experts**.

I aim to develop more efficient, stable, and general intelligent decision-making systems through theoretical analysis and practical engineering. I also contribute to the development and maintenance of the open-source [LightZero](https://github.com/opendilab/LightZero) framework.

If you are interested in my research or projects, feel free to contact me at [tangjia@pjlab.org.cn](mailto:tangjia@pjlab.org.cn).

<h2 id="news">News</h2>

<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026</em></span> 🎉 <strong>One Model for All Tasks</strong> was accepted at ICLR 2026.</li>
    <li><span class="news-date"><em>2026</em></span> 🎉 Our first-author paper was accepted by <strong>Frontiers of Computer Science</strong>.</li>
    <li><span class="news-date"><em>2025.07</em></span> 🚀 Joined Shanghai AI Laboratory as a research intern.</li>
    <li><span class="news-date"><em>2025.07</em></span> 🧩 Started contributing to the development and maintenance of LightZero.</li>
  </ul>
</div>

<h2 id="education">Education</h2>

<div class="experience-container">
  <div class="experience-card">
    <div class="profile-icon">NU</div>
    <div class="experience-info">
      <strong>Nanjing University of Aeronautics and Astronautics</strong><br>
      <em>Sep. 2023 - Apr. 2026</em><br>
      M.Sc. in Computer Science and Technology, College of Computer Science and Technology / College of Artificial Intelligence<br>
      <span class="detail-line">GPA: 4.65 / 5.00 · Recommended Admission · Special Scholarship for Incoming Graduate Students · Advisor: Prof. Songcan Chen</span>
    </div>
  </div>

  <div class="experience-card">
    <div class="profile-icon">SW</div>
    <div class="experience-info">
      <strong>Southwest University</strong><br>
      <em>Sep. 2019 - Jul. 2023</em><br>
      B.Eng. in Network Engineering, College of Computer and Information Science<br>
      <span class="detail-line">GPA: 3.94 / 5.00 · Rank: 1 / 52 · National Special Scholarship · Outstanding Graduate</span>
    </div>
  </div>
</div>

<h2 id="research">Research</h2>

<div class="research-card featured">
  <span class="status-badge">Accepted</span>
  <strong>Global Pre-fixing, Local Adjusting: A Simple yet Effective Contrastive Strategy for Continual Learning</strong><br>
  <em>First Author · Frontiers of Computer Science (CCF-B / JCR Q1)</em>
  <p>We address feature entanglement in contrastive continual learning by introducing Global Pre-fixing, which establishes a globally separated task-level structure in an ETF prototype space. Our theoretical analysis characterizes the convergence of intra-class features toward regular simplices under the R2SCL constraint, improving both discriminability and inter-task separability.</p>
</div>

<div class="research-card">
  <span class="status-badge muted">Under Review</span>
  <strong>KIBO: Label Disappearance-resistant Continual Multi-Instance Learning for Whole Slide Images</strong><br>
  <em>First Author · Submitted to ECCV 2026</em>
  <p>We propose KIBO, a bilevel key-instance selection framework for continual multi-instance learning. Under extremely limited memory budgets, KIBO replaces complete whole-slide images with pseudo bags and combines differentiable Top-K selection with a coarse-to-fine strategy to mitigate label disappearance and catastrophic forgetting in replay-based learning.</p>
</div>

<div class="research-card">
  <span class="status-badge">Accepted</span>
  <strong>One Model for All Tasks: Leveraging Efficient World Models in Multi-Task Planning</strong><br>
  <em>Contributor · ICLR 2026</em>
  <p>We study the role of MoE in unified world models from both theoretical and empirical perspectives, focusing on sparse routing, expert specialization, and cross-task gradient interference. Our analysis examines how these mechanisms affect training stability, model plasticity, and multi-task generalization.</p>
</div>

<h2 id="experience">Experience</h2>

<div class="experience-card">
  <div class="profile-icon lab-icon">AI</div>
  <div class="experience-info">
    <strong>Shanghai AI Laboratory (Pujiang Laboratory)</strong><br>
    <em>Algorithm Engineer · Present</em>
    <ul>
      <li>Conduct research on gradient interference in multi-task reinforcement learning as part of the ScaleZero project.</li>
      <li>Design and analyze Mixture-of-Experts architectures for multi-task modeling.</li>
      <li>Evaluate how expert configurations and routing strategies affect multi-task performance.</li>
      <li>Develop, maintain, and debug components of the LightZero reinforcement learning framework.</li>
    </ul>
  </div>
</div>

<h2 id="projects">Open-Source Projects</h2>

<div class="project-card">
  <div class="project-inner">
    <div class="project-mark">LZ</div>
    <div>
      <strong>LightZero</strong><br>
      <em>Contributor / Core Maintainer · 1,500+ GitHub Stars</em>
      <p>LightZero is an open-source Monte Carlo tree search and reinforcement learning framework developed by OpenDILab. My primary contributions include:</p>
      <ul>
        <li>Decoupling simulation and expansion in MCTS and introducing asynchronous GPU scheduling to improve training throughput.</li>
        <li>Porting and integrating EfficientZero V2 into LightZero.</li>
        <li>Implementing a loss-landscape visualization and analysis toolkit.</li>
        <li>Integrating the OpenReasoner-Zero reasoning evaluation module.</li>
      </ul>
      <a href="https://github.com/opendilab/LightZero"><em>[Project Page]</em></a>
    </div>
  </div>
</div>

<h2 id="awards">Selected Honors and Awards</h2>

- National First Prize, Chinese Collegiate Computing Competition
- National Second Prize, Huawei Cup China Postgraduate Mathematical Contest in Modeling
- National Second Prize, Lanqiao Cup Python Competition, Graduate Division
- Meritorious Winner, Mathematical Contest in Modeling, 2022 and 2023
- First Prize, China Undergraduate Mathematical Contest in Modeling, Chongqing Division
- Silver Award, China International College Students' Innovation Competition, Chongqing Division
- Second Prize, Chongqing Collegiate Programming Contest, Python Division

<h2 id="skills">Technical Skills</h2>

- **Programming and Frameworks:** Python, PyTorch
- **Reinforcement Learning:** MCTS, AlphaZero, EfficientZero, world models, and multi-task reinforcement learning
- **Large Language Models:** Qwen, LLaMA, and DeepSeek; familiar with SFT, RLHF, and MoE
- **Machine Learning:** contrastive learning, self-supervised learning, and continual learning
- **Foundations:** probability, statistics, mathematical optimization, and convex optimization

<h2 id="writing">Recent Posts</h2>

<div class="writing-list">
{% for post in site.posts limit: 5 %}
  <article class="writing-item">
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%b. %d, %Y" }}</time>
    <div>
      <a href="{{ post.url }}"><strong>{{ post.title }}</strong></a>
      {% if post.excerpt %}<p>{{ post.excerpt | strip_html | truncate: 110 }}</p>{% endif %}
    </div>
  </article>
{% endfor %}
</div>

[View all posts →](/blog/){: .btn .btn--primary }
