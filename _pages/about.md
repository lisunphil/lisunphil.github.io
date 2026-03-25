---
permalink: /
title: "Li Sun"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a third-year PhD candidate at the Institute of Data Science at The University of Hong Kong(HKU IDS). My current research interest is embodied AI, including representation learning, robotic manipulation, 3D vision, and world action models.

<br />

Education
======
* B.S. in Computer Science and Technology, Zhejiang University, 2019~2023
* PhD in IDS, The University of Hong Kong, 2023~now

<br />

Publications
=======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br />

Service
=======
* **Head Teaching Assistant**, [DATA8010 & ELEC8111](https://embodied-ai-hku.github.io/DATA8010/), HKU
* **Teach Assistant**, IDSS2401, IDSS2402, IDSS2501, HKU
* **Reviewer**, CVPR 2025, ICCV 2025, AAAI 2025, CoRL 2025, ICLR 2026
