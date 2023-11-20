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
* Ph.D. in Computer Science and Operations Research, University of Montreal, January 2024 (expected)
* M.Sc. in Theoretical Mathematics, University of Pisa, 2017 (summa cum laude)
* B.S. in Mathematics, University of Pavia, 2012


Work experience
======
* November 2017 to November 2018: Research Assistant
  * Bocconi University
  * Supervisor: Professor Battigalli


Research
======
  <ul>{% for post in site.research reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* DS4DM Coffee Talks
* Treasurer of the 2023 ACM conference on Equity and Access in Algorithms, Mechanisms, and Optimization
