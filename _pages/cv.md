---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D** in Electrical Engineering and Computer Science, University of Siegen, 2023
* **M.Sc.** in Integrated Circuit (IC) Design Engineering, The Hong Kong University of Science and Technology, 2012
* **B.Eng.** in Computer Engineering, The Hong Kong University of Science and Technology, 2010

Professional experience
======
* **Scientific Researcher** (2016 - 2022)
  * University of Siegen, Siegen, Germany

* **R&D Engineer, Project Manager, Technical Director** (2011 - 2016)
  * S Square System Limited, Hong Kong

* **Project Intern** (2010 - 2011)
  * Hong Kong Applied Science and Technology Research Institute (ASTRI), Hong Kong
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
