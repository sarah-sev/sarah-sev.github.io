---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /CV
---

{% include base_path %}

Education
======
* B.A in Physics, Reed College, 2027 (expected)

Work experience
======
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  