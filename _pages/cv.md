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
* B.S. in Biology, North Fluminense State University (UENF), 2007
* M.S. in Biosciences and Biotechnology, North Fluminense State University (UENF), 2009
* Ph.D in Parasite Biology - Virology, Oswaldo Cruz Institute (IOC), Fiocruz, 2015

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

