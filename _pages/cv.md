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
* <b>PhD, Neuroscience</b>, University of California, Berkeley, 2015-2022
* <b>BS, Psychology, and BA, Plan II Honors</b>, University of Texas at Austin, 2007-2011
  * Plan II is an interdisciplinary humanities program.

Work experience
======
* Data Scientist, <a href='https://tactogen.com'>Tactogen</a>, 2023-
* Data Scientist, Magnolia Data Science, 2020-2022
* Graduate Research Assistant, <a href='https://argentum.ucbso.berkeley.edu/'>Silver Lab</a>, 2016-2022
* Research Assistant, <a href='https://www.lewpealab.org/'>Lewis-Peacock Lab</a>, 2013-2015
* Software Developer, <a href='https://etszone.com'>ETSZONE</a>, 2005-2013
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
