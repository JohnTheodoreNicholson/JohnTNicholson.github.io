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
* Ph.D in Mathematics and Statistics, McMaster University, 2027 (expected)
* M.S. in Mathematics, McMaster University, 2022
* H.B.Sc. in Mathematics and Physics, McMaster University, 2021

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
  
Service and leadership
======
* Committee member for the McMaster Math and Stats Careers Workshop
* Mentor in the shadowing program offered through the McMaster Office of Undergraduate Research
