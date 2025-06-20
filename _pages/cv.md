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
* Ph.D in Economics, UP School of Economics, 2021
* M.S. in Economics, UP School of Economics, 2013
* B.S. in Economics, UP School of Economics, 2009

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users
  
Skills
======
* Quantitative analysis (econometrics, causal inference)
* Software: Stata, Python, R

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
* Associate Editor, <em>Social Science Diliman</em>
* Member, UP Admissions Evaluation Committee
* Fellow, Social Weather Stations (SWS)
* Board Member, INCITEGov