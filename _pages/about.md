---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a second-year PhD candidate at the Institute of Data Science at The University of Hong Kong(HKU IDS). My current research interest is embodied AI, including 3D representation, robotic learning, and 3D vision.

<br />

Education
======
* B.S. in Computer Science, Zhejiang University, 2023

<br />

Publications
=======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
