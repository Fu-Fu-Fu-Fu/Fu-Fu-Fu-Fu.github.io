---
permalink: /
title: "Lin Fu"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="simple-home">
  <div class="simple-home__intro">
    <div class="simple-home__text">
      <h1>Lin Fu</h1>
      <p class="simple-home__role">ZJU Master</p>
      <p>
        I am currently a master&apos;s student at Zhejiang University, and my main
        research areas are multimodal large models, LLMs, and generative models.
        I am currently working closely with
        <a href="https://yilunzhao.github.io/">Yilun Zhao</a>.
      </p>
      <p>
        <strong>Research interests:</strong> multimodal large models, LLMs, generative models.
      </p>
      <p class="simple-home__links">
        <a href="mailto:22447022@zju.edu.cn">Email</a> /
        <a href="https://scholar.google.com/citations?hl=en&user=NUeuiN8AAAAJ">Google Scholar</a> /
        <a href="https://github.com/Fu-Fu-Fu-Fu">GitHub</a> /
        <a href="/publications/">Publications</a>
      </p>
    </div>
  </div>

  <section class="simple-home__section">
    <h2>Selected Publications</h2>
    {% assign selected_pubs = site.publications | reverse | slice: 0, 3 %}
    {% for post in selected_pubs %}
      {% include archive-single.html %}
    {% endfor %}
  </section>
</section>
