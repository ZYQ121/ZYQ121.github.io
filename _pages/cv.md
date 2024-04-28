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
* Ph.D in China Women's University, 2010
* M.S. in Changchun University of Science and Technology, 2017
* B.S. in Changchun University of Science and Technology, 2024

Work experience
======
* Spring 2017: Engineer
  * Changchun Changguang Zhongtian Optoelectronics Technology Co., Ltd.
  * Duties includes: Lithography platform software development

* Spring 2019: Engineer
  * Changchun Deep Blue Manufacturing Co., Ltd.
  * Duties included: Software development

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
  
