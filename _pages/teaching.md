---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

I am Teaching Assistant for the following courses:

- Elements of Real and Fourier analysis (30665)
- Advanced Analysis and Optimization (30551)
- Advanced Mathematics for Economics and Social Sciences (20136)

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
