---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2>Preprints</h2>

<ul>
  <li><strong> Spectral gap of Metropolis-within-Gibbs under log-concavity </strong><br>
  <em>C. Secchi, G. Zanella(s)</em> (2025). <a href="https://arxiv.org/pdf/2509.26175">arXiv:2509.26175</a></li>
  <!-- Add more preprints as needed -->
</ul>

<hr>
