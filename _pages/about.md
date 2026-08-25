---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<h1 class="main-heading">你好 👋 我是唐嘉</h1>

我目前就读于**南京航空航天大学计算机科学与技术专业**，并在**上海人工智能实验室（浦江实验室）**担任科研实习生。我的研究兴趣主要包括**强化学习、世界模型、持续学习与 Mixture-of-Experts**。

我希望通过理论分析与工程实践，探索更加高效、稳定和通用的智能决策方法。目前，我也参与 [LightZero](https://github.com/opendilab/LightZero) 开源框架的开发与维护。

如果你对我的研究或项目感兴趣，欢迎通过 [tangjia@pjlab.org.cn](mailto:tangjia@pjlab.org.cn) 与我联系。

<h2 id="news">最近动态</h2>

<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026</em></span> 🎉 第一作者论文被 <strong>Frontiers of Computer Science</strong> 接收。</li>
    <li><span class="news-date"><em>2025.07</em></span> 🚀 加入上海人工智能实验室，担任科研实习生。</li>
    <li><span class="news-date"><em>2025.07</em></span> 🧩 开始参与 LightZero 开源框架的开发与维护。</li>
  </ul>
</div>

<h2 id="education">教育经历</h2>

<div class="experience-container">
  <div class="experience-card">
    <div class="profile-icon">航</div>
    <div class="experience-info">
      <strong>南京航空航天大学</strong><br>
      <em>2023.09 - 2026.04</em><br>
      计算机科学与技术硕士，计算机科学与技术学院 / 人工智能学院<br>
      <span class="detail-line">GPA 4.65 / 5 · 推免 · 研究生新生特别奖学金 · 导师：陈松灿教授</span>
    </div>
  </div>

  <div class="experience-card">
    <div class="profile-icon">西</div>
    <div class="experience-info">
      <strong>西南大学</strong><br>
      <em>2019.09 - 2023.07</em><br>
      网络工程学士，计算机与信息科学学院<br>
      <span class="detail-line">GPA 3.94 / 5 · 专业排名 1 / 52 · 国家特等奖学金 · 优秀毕业生</span>
    </div>
  </div>
</div>

<h2 id="research">研究工作</h2>

<div class="research-card featured">
  <span class="status-badge">已接收</span>
  <strong>Global Pre-fixing, Local Adjusting: A Simple yet Effective Contrastive Strategy for Continual Learning</strong><br>
  <em>第一作者 · Frontiers of Computer Science（CCF-B / JCR Q1）</em>
  <p>针对对比式持续学习中的特征混叠问题，提出 Global Pre-fixing 策略，通过 ETF 原型空间建立全局任务级分离结构。基于理论推导，分析 R2SCL 约束下类内特征向规则单纯形收敛的性质，从而提升特征判别性与任务间可分性。</p>
</div>

<div class="research-card">
  <span class="status-badge muted">投稿中</span>
  <strong>KIBO: Label Disappearance-resistant Continual Multi-Instance Learning for Whole Slide Images</strong><br>
  <em>第一作者 · ECCV 2026 投稿中</em>
  <p>提出面向持续多实例学习的双层优化关键实例选择框架 KIBO。在极低存储预算下，以伪 bag 替代完整全切片图像，并结合可微 Top-K 与粗到细实例筛选策略，缓解回放场景中的标签消失与灾难性遗忘问题。</p>
</div>

<div class="research-card">
  <span class="status-badge muted">研究项目</span>
  <strong>One Model for All Tasks: Leveraging Efficient World Models in Multi-Task Planning</strong><br>
  <em>项目贡献者 · 多任务强化学习与世界模型</em>
  <p>从理论与实验角度分析 MoE 在统一世界模型中的作用，研究稀疏路由、专家专化与跨任务梯度冲突之间的关系，并验证其对训练稳定性、模型可塑性和泛化能力的影响。</p>
</div>

<h2 id="experience">实习经历</h2>

<div class="experience-card">
  <div class="profile-icon lab-icon">AI</div>
  <div class="experience-info">
    <strong>上海人工智能实验室（浦江实验室）</strong><br>
    <em>科研实习生 · 科研任务部安全可信 AI 中心 · 2025.07 - 至今</em>
    <ul>
      <li>参与 ScaleZero 项目，研究多任务强化学习中的梯度冲突问题。</li>
      <li>设计并分析基于 Mixture-of-Experts 的多任务建模方案。</li>
      <li>比较不同专家数量与路由策略对多任务性能的影响。</li>
      <li>参与 LightZero 强化学习框架的开发、维护与问题修复。</li>
    </ul>
  </div>
</div>

<h2 id="projects">开源项目</h2>

<div class="project-card">
  <div class="project-inner">
    <div class="project-mark">LZ</div>
    <div>
      <strong>LightZero</strong><br>
      <em>Contributor / Core Maintainer · 1,500+ GitHub Stars</em>
      <p>OpenDILab 推出的开源蒙特卡洛树搜索与强化学习框架。主要贡献包括：</p>
      <ul>
        <li>解耦 MCTS 中的 simulation 与 expand，并通过 GPU 异步调度提升训练吞吐。</li>
        <li>将 EfficientZero V2 迁移并集成至 LightZero。</li>
        <li>实现 Loss Landscape 可视化与分析工具。</li>
        <li>接入 OpenReasoner-Zero 推理评测模块。</li>
      </ul>
      <a href="https://github.com/opendilab/LightZero"><em>[项目主页]</em></a>
    </div>
  </div>
</div>

<h2 id="awards">荣誉与竞赛</h2>

- 中国大学生计算机设计大赛，全国一等奖
- “华为杯”中国研究生数学建模竞赛，全国二等奖
- 蓝桥杯 Python 研究生组，全国二等奖
- 美国大学生数学建模竞赛，2022、2023 年 M 奖
- 全国大学生数学建模竞赛重庆赛区一等奖
- “互联网+”大学生创新创业大赛重庆赛区银奖
- 重庆市大学生编程大赛 Python 组二等奖

<h2 id="skills">技术能力</h2>

- **编程与框架：** Python、PyTorch
- **强化学习：** MCTS、AlphaZero、EfficientZero、世界模型、多任务强化学习
- **大语言模型：** Qwen、LLaMA、DeepSeek，了解 SFT、RLHF 与 MoE
- **机器学习：** 对比学习、自监督学习、持续学习
- **理论基础：** 概率统计、数学优化与凸优化

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
