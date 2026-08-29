---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<div class="wordwrap">
  See my <a href="https://taniamishra.github.io/files/Tania_Mishra_CV_Aug2026">full CV here</a> (last updated August 2026).
</div>

{% include base_path %}

Education
-----
* Ph.D in Information, University of Michigan, present
* Honors Bachelor of Science in Computer Science and Cognitive Science, Marquette University, 2026

Projects
-----
  <ul>
{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
</ul>


Publications
-----
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
-----
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
Teaching
-----
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
