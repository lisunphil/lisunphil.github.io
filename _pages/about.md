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

<section class="hero" aria-labelledby="hero-title">
  <div class="home-shell hero-grid">
    <div class="hero-copy">
      <p class="eyebrow"><span aria-hidden="true"></span> Embodied AI · Robot Learning · 3D Vision</p>
      <h1 id="hero-title">Li Sun</h1>
      <p class="hero-role">PhD Candidate · Institute of Data Science · The University of Hong Kong</p>
      <p class="hero-intro">
        My research focuses on building better representations for robotic
        manipulation and on using large language models to construct embodied
        agents that integrate perception, reasoning, and policy models for
        robust physical interaction. I am particularly interested in
        representation learning, vision-language-action models, dexterous
        manipulation, and agentic robotics.
      </p>
      <div class="hero-actions" role="group" aria-label="Contact and profiles">
        <a class="home-button home-button-primary" href="mailto:{{ site.author.email }}">Email</a>
        <a class="home-button" href="{{ site.author.googlescholar }}">Google Scholar</a>
        <a class="home-button" href="https://github.com/{{ site.author.github }}">GitHub</a>
      </div>
      <dl class="hero-details">
        <div>
          <dt>Affiliation</dt>
          <dd>Institute of Data Science, HKU</dd>
        </div>
        <div>
          <dt>Research areas</dt>
          <dd>Robotic manipulation and embodied agents</dd>
        </div>
      </dl>
    </div>

    <aside class="hero-profile" aria-label="Profile">
      <div class="portrait-frame">
        <img src="{{ '/images/sl2026-homepage.jpg' | relative_url }}" alt="Portrait of Li Sun">
      </div>
      <div class="profile-caption">
        <strong>Li Sun</strong>
        <span>Institute of Data Science, The University of Hong Kong</span>
        <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
      </div>
    </aside>
  </div>
</section>

<section class="home-section" id="about" aria-labelledby="about-title">
  <div class="home-shell section-grid">
    <div class="section-heading">
      <p class="section-number">01</p>
      <h2 id="about-title">About</h2>
    </div>
    <div class="section-content about-content">
      <div class="about-copy">
        <p class="lead">
          I am a PhD candidate at the Institute of Data Science, The University
          of Hong Kong (HKU IDS) and an HKU Presidential PhD Scholar (HKUPS).
          I am advised by Prof. Yanchao Yang and Prof. Yi Ma.
        </p>
        <p>
          My research focuses on building better representations for robotic
          manipulation and on using large language models to construct embodied
          agents that integrate perception, reasoning, and policy models for
          robust physical interaction. I am particularly interested in
          representation learning, vision-language-action models, dexterous
          manipulation, and agentic robotics.
        </p>
        <p>
          Prior to joining HKU, I received my B.S. in Computer Science and
          Technology from Zhejiang University in 2023.
        </p>
      </div>
    </div>
  </div>
</section>

<section class="home-section home-section-tinted" id="research" aria-labelledby="research-title">
  <div class="home-shell section-grid">
    <div class="section-heading">
      <p class="section-number">02</p>
      <h2 id="research-title">Research</h2>
    </div>
    <div class="section-content research-prose">
      <p class="research-intro">
        My research interests concern how robots can acquire useful
        representations for manipulation and how LLM-based agents can organize
        perception, reasoning, and learned policies into reliable physical
        behavior. I am particularly interested in three related themes.
      </p>
      <article class="research-theme">
        <p class="research-index">01</p>
        <div>
          <h3>Representation Learning for Robotic Manipulation</h3>
          <p>
            I am interested in learning task-aware representations from visual,
            3D, and multimodal observations that preserve the geometric,
            semantic, and interaction-relevant structure needed for
            manipulation. My goal is to provide policy models with informative
            state representations that improve robustness and transfer across
            objects, tasks, and environments.
          </p>
        </div>
      </article>
      <article class="research-theme">
        <p class="research-index">02</p>
        <div>
          <h3>Multimodal and Dexterous Manipulation</h3>
          <p>
            I am interested in how representations learned from visual and
            multimodal observations, together with generative simulation,
            could support the high-dimensional control required for dexterous
            hands. I aim to explore transferable manipulation policies that
            remain robust across objects, configurations, and environments.
          </p>
        </div>
      </article>
      <article class="research-theme">
        <p class="research-index">03</p>
        <div>
          <h3>Agentic Robotics</h3>
          <p>
            I am interested in using LLMs to construct embodied agents that
            coordinate perception models, reasoning modules, and learned
            policies within a closed loop. I aim to investigate how such
            agents can interpret task and scene state, select appropriate
            skills, monitor execution, and adapt to failures during physical
            interaction.
          </p>
        </div>
      </article>
    </div>
  </div>
</section>

<section class="home-section" id="publications" aria-labelledby="publications-title">
  <div class="home-shell section-grid">
    <div class="section-heading">
      <p class="section-number">03</p>
      <h2 id="publications-title">Publications</h2>
      <a class="section-link" href="{{ '/publications/' | relative_url }}">View publication page <span aria-hidden="true">↗</span></a>
    </div>
    <div class="section-content publication-list">
      {% assign publications = site.publications | sort: "priority" | reverse %}
      {% for publication in publications %}
        <article class="publication-item">
          <div class="publication-meta">
            <p class="publication-number">0{{ forloop.index }}</p>
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
      <p class="section-number">04</p>
      <h2 id="service-title">Education &amp; academic service</h2>
    </div>
    <div class="section-content detail-columns">
      <div>
        <h3 class="detail-title">Education</h3>
        <ol class="timeline">
          <li>
            <p class="timeline-date">2023 — Present</p>
            <h4>PhD, Institute of Data Science</h4>
            <p>The University of Hong Kong</p>
          </li>
          <li>
            <p class="timeline-date">2019 — 2023</p>
            <h4>B.S., Computer Science and Technology</h4>
            <p>Zhejiang University</p>
          </li>
        </ol>
      </div>
      <div>
        <h3 class="detail-title">Academic service</h3>
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
  </div>
</section>

<section class="contact-band" aria-labelledby="contact-title">
  <div class="home-shell contact-inner">
    <div>
      <p class="eyebrow"><span aria-hidden="true"></span> Contact</p>
      <h2 id="contact-title">Contact</h2>
      <p>For research-related enquiries or potential collaborations, please contact me by email.</p>
    </div>
    <a class="contact-link" href="mailto:{{ site.author.email }}">
      <span>Email</span>
      <strong>{{ site.author.email }}</strong>
    </a>
  </div>
</section>
