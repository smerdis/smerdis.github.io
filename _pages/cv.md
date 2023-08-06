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
* PhD, Neuroscience, University of California, Berkeley, 2015-2022
* BS, Psychology, and BA, Plan II Honors, University of Texas at Austin, 2007-2011
  * Plan II is an interdisciplinary humanities program.

Work experience
======
* Data Scientist, <a href='https://tactogen.com'>Tactogen</a>, 2020-2023
* Graduate Research Assistant, Silver Lab, 2016-2022
* Research Assistant, Lewis-Peacock Lab, 2013-2015
* Software Developer, <a href='https://etszone.com'>ETSZONE</a>, 2005-2013
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
