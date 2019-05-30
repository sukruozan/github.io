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
* B.S. in Electrical and Electronics Engineering, Middle East Technical University, 2002
* M.S. in Electrical and Electronics Engineering, İzmir Institute of Technology, 2006
* Ph.D. in Electrical and Electronics Engineering, İzmir Institute of Technology, 2015

Work experience
======
* 2004 - 2011 : Research Assistant
  * İzmir Institute of Technology

Prgramming Skills
======
* Python
  * Numpy
  * Scipy
  * Scikit-learn
  * Pandas
  * etc.
* MATLAB
* LaTeX
* PHP
* MySQL

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
