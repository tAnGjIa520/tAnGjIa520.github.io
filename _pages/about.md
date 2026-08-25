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

I aim to develop more efficient, stable, and general intelligent decision-making systems through theoretical analysis and practical engineering.

If you are interested in my research or projects, feel free to contact me at [tangjia@pjlab.org.cn](mailto:tangjia@pjlab.org.cn).

<h2 id="news">News</h2>

<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.06</em></span> 🚀 Officially joined Shanghai AI Laboratory as an Algorithm Engineer.</li>
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
  <span class="status-badge">FCS</span>
  <strong><a href="https://arxiv.org/abs/2509.15347">Global Pre-fixing, Local Adjusting: A Simple yet Effective Contrastive Strategy for Continual Learning</a></strong><br>
  <em>First Author · Frontiers of Computer Science (CCF-B / JCR Q1)</em>
  <figure class="research-figure">
    <a href="https://arxiv.org/pdf/2509.15347" aria-label="Open the GPLASC paper PDF">
      <img src="/images/research/gplasc-overview.png" alt="Comparison between SupCon and the proposed global pre-fixing and local adjusting strategy" loading="lazy">
    </a>
    <figcaption>Figure 1 · Global pre-fixing and local adjusting <a href="https://arxiv.org/pdf/2509.15347">PDF ↗</a></figcaption>
  </figure>
  <p>We address feature entanglement in contrastive continual learning by introducing Global Pre-fixing, which establishes a globally separated task-level structure in an ETF prototype space. Our theoretical analysis characterizes the convergence of intra-class features toward regular simplices under the R2SCL constraint, improving both discriminability and inter-task separability.</p>
</div>

<div class="research-card">
  <span class="status-badge muted">Under Review</span>
  <strong>KIBO: Label Disappearance-resistant Continual Multi-Instance Learning for Whole Slide Images</strong><br>
  <em>First Author · Submitted to ECCV 2026</em>
  <p>We propose KIBO, a bilevel key-instance selection framework for continual multi-instance learning. Under extremely limited memory budgets, KIBO replaces complete whole-slide images with pseudo bags and combines differentiable Top-K selection with a coarse-to-fine strategy to mitigate label disappearance and catastrophic forgetting in replay-based learning.</p>
</div>

<div class="research-card">
  <span class="status-badge">ICLR 2026</span>
  <strong><a href="https://arxiv.org/abs/2509.07945">One Model for All Tasks: Leveraging Efficient World Models in Multi-Task Planning</a></strong><br>
  <em>Contributor · ICLR 2026</em>
  <figure class="research-figure">
    <a href="https://proceedings.iclr.cc/paper_files/paper/2026/file/4f45d2471a82b3d674f3957ef6170996-Paper-Conference.pdf" aria-label="Open the ScaleZero paper PDF">
      <img src="/images/research/scalezero-overview.png" alt="ScaleZero multitask world model architecture and dynamic parameter scaling" loading="lazy">
    </a>
    <figcaption>Figure 2 · ScaleZero architecture and Dynamic Parameter Scaling <a href="https://proceedings.iclr.cc/paper_files/paper/2026/file/4f45d2471a82b3d674f3957ef6170996-Paper-Conference.pdf">PDF ↗</a></figcaption>
  </figure>
  <p>We study the role of MoE in unified world models from both theoretical and empirical perspectives, focusing on sparse routing, expert specialization, and cross-task gradient interference. Our analysis examines how these mechanisms affect training stability, model plasticity, and multi-task generalization.</p>
</div>

<div class="research-card">
  <span class="status-badge muted">arXiv</span>
  <strong><a href="https://arxiv.org/abs/2605.12289">PriorZero: Bridging Language Priors and World Models for Decision Making</a></strong><br>
  <em>Co-author · arXiv:2605.12289</em>
  <figure class="research-figure">
    <a href="https://arxiv.org/pdf/2605.12289" aria-label="Open the PriorZero paper PDF">
      <img src="/images/research/priorzero-overview.png" alt="PriorZero framework integrating language model priors, world models, and Monte Carlo tree search" loading="lazy">
    </a>
    <figcaption>Figure 2 · PriorZero framework overview <a href="https://arxiv.org/pdf/2605.12289">PDF ↗</a></figcaption>
  </figure>
  <p>We propose PriorZero, a unified framework that integrates LLM-derived conceptual priors into world-model-based planning. Root-Prior Injection guides MCTS toward semantically promising actions while preserving deep lookahead, and alternating reinforcement fine-tuning uses world-model value estimates for stable LLM adaptation. Experiments on Jericho and BabyAI demonstrate improved exploration efficiency and asymptotic performance.</p>
</div>

<h2 id="experience">Experience</h2>

<div class="experience-card">
  <div class="profile-icon lab-icon">AI</div>
  <div class="experience-info">
    <strong>Shanghai AI Laboratory (Pujiang Laboratory)</strong><br>
    <em>Algorithm Engineer · Jun. 2026 - Present</em>
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
      <p>LightZero is an open-source Monte Carlo tree search and reinforcement learning framework developed by OpenDILab.</p>
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
