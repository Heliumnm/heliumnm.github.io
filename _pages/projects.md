---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

在这里可以写一段关于你项目经历的总体介绍。例如，你主要关注哪些领域的研究项目，使用了哪些技术等等。

---

{% raw %}{% for post in site.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}{% endraw %}

{% raw %}{% capture written_label %}'My Awesome Projects'{% endcapture %}

<div class="feature__wrapper">

<div class="feature__item--right">
  <div class="archive__item">
    <div class="archive__item-teaser">
      <img src="{{ site.baseurl }}/images/project-a.jpg" alt="项目A的图片">
    </div>
    <div class="archive__item-body">
      <h2 class="archive__item-title">项目A的标题 (Project Title A)</h2>
      <div class="archive__item-excerpt">
        <p>这里是项目A的详细描述。你可以介绍这个项目的背景、目标、你使用的研究方法或技术栈。你也可以在这里列出你的主要贡献。</p>
        <p><strong>我的贡献</strong>: 解决了...问题, 实现了...功能, etc.</p>
      </div>
      <p><a href="[这里放项目链接，比如GitHub]" class="btn btn--primary">了解更多</a></p>
    </div>
  </div>
</div>
<div class="feature__item--left">
  <div class="archive__item">
    <div class="archive__item-teaser">
      <img src="{{ site.baseurl }}/images/project-b.png" alt="项目B的图片">
    </div>
    <div class="archive__item-body">
      <h2 class="archive__item-title">Multimodal Communication of HPV Vaccine on Social Media</h2>
      <div class="archive__item-excerpt">
        <p>This was a large-scale research project that performed a cross-modality analysis of HPV vaccine discourse on social media. The study involved collecting and analyzing over 1.5TB of data, including texts, audios, and videos from major platforms like Weibo, Douyin, and Bilibili, spanning a decade from 2010 to 2023. The goal was to understand how the same vaccine was discussed differently across various media formats.</p>
        <p><strong>技术栈</strong>: Python, PyTorch, etc.</p>
      </div>
      <p><a href="[这里放项目链接]" class="btn btn--primary">项目主页</a></p>
    </div>
  </div>
</div>
<div class="feature__item--right">
  <div class="archive__item">
    <div class="archive__item-teaser">
      <img src="{{ site.baseurl }}/images/project-c.gif" alt="项目C的图片">
    </div>
    <div class="archive__item-body">
      <h2 class="archive__item-title">项目C的标题 (Project Title C)</h2>
      <div class="archive__item-excerpt">
        <p>这里是项目C的详细描述。你可以自由发挥。</p>
      </div>
      <p><a href="[这里放项目链接]" class="btn btn--primary">相关论文</a></p>
    </div>
  </div>
</div>
</div>
{% endraw %}
