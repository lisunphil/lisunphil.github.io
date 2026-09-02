---
permalink: /
layout: home
title: "Li Sun | PhD Candidate at The University of Hong Kong"
excerpt: "Li Sun is a PhD candidate at the Institute of Data Science, The University of Hong Kong. His research interests include representation learning for robotic manipulation, vision-language-action models, dexterous manipulation, and agentic robotics."
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<section class="hero" id="about" aria-labelledby="hero-title">
  <div class="home-shell hero-grid">
    <div class="hero-copy">
      <p class="eyebrow">About</p>
      <h1 id="hero-title">Li Sun</h1>
      <p class="hero-role">PhD Candidate · Institute of Data Science · The University of Hong Kong</p>
      <p class="hero-about">
        I am an HKU Presidential PhD Scholar, advised by Prof. Yanchao Yang and
        Prof. Yi Ma. Previously, I received my B.S. in Computer Science and
        Technology from Zhejiang University in 2023.
      </p>
      <p class="hero-intro">
        My research centers on building better representations for robotic
        manipulation and using large language models to construct embodied
        agents that integrate perception, reasoning, and policy models for
        robust physical interaction.
      </p>
      <div class="hero-actions" role="group" aria-label="Contact and profiles">
        <a class="home-button home-button-primary" href="mailto:{{ site.author.email }}">Email</a>
        <a class="home-button" href="{{ site.author.googlescholar }}">Google Scholar</a>
        <a class="home-button" href="https://github.com/{{ site.author.github }}">GitHub</a>
      </div>
    </div>

    <aside class="hero-profile" aria-label="Profile">
      <div class="portrait-frame">
        <img src="{{ '/images/sl2026-homepage.jpg' | relative_url }}" alt="Portrait of Li Sun">
      </div>
    </aside>
  </div>
</section>

<section class="home-section home-section-tinted" id="research" aria-labelledby="research-title">
  <div class="home-shell section-grid">
    <div class="section-heading">
      <h2 id="research-title">Research</h2>
    </div>
    <div class="section-content research-prose">
      <article class="research-theme">
        <div>
          <h3>Representation Learning for Robotic Manipulation</h3>
          <p>
            I am interested in task-aware representations that preserve the
            geometric, semantic, and interaction-relevant structure needed for
            policy learning and robust transfer across objects and tasks.
          </p>
        </div>
      </article>
      <article class="research-theme">
        <div>
          <h3>Multimodal and Dexterous Manipulation</h3>
          <p>
            I explore how visual and multimodal observations, together with
            generative simulation, can support high-dimensional dexterous
            control and transferable manipulation policies.
          </p>
        </div>
      </article>
      <article class="research-theme">
        <div>
          <h3>Agentic Robotics</h3>
          <p>
            I am interested in LLM-based embodied agents that coordinate
            perception, reasoning, and learned policies to select skills,
            monitor execution, and adapt during physical interaction.
          </p>
        </div>
      </article>
    </div>
  </div>
</section>

<section class="home-section" id="publications" aria-labelledby="publications-title">
  <div class="home-shell section-grid">
    <div class="section-heading">
      <h2 id="publications-title">Publications</h2>
    </div>
    <div class="section-content publication-list">
      {% assign publications = site.publications | sort: "priority" | reverse %}
      {% for publication in publications %}
        <article class="publication-item">
          <div class="publication-meta">
            <p class="publication-venue">{{ publication.venue }}</p>
          </div>
          <div class="publication-body">
            <h3>{{ publication.title }}</h3>
            <p class="publication-authors">{{ publication.author }}</p>
          </div>
        </article>
      {% endfor %}
    </div>
  </div>
</section>

<section class="home-section home-section-tinted" id="service" aria-labelledby="service-title">
  <div class="home-shell section-grid">
    <div class="section-heading">
      <h2 id="service-title">Academic Service</h2>
    </div>
    <div class="section-content service-panel">
      <ul class="service-list">
        <li>
          <strong>Head Teaching Assistant</strong>
          <span><a href="https://embodied-ai-hku.github.io/DATA8010/">DATA8010 &amp; ELEC8111</a>, HKU</span>
        </li>
        <li>
          <strong>Teaching Assistant</strong>
          <span>IDSS2401, IDSS2402, IDSS2501, HKU</span>
        </li>
        <li>
          <strong>Reviewer</strong>
          <span>CVPR 2025, ICCV 2025, AAAI 2025, CoRL 2025, ICLR 2026, NeurIPS 2026, CoRL 2026</span>
        </li>
      </ul>
    </div>
  </div>
</section>
