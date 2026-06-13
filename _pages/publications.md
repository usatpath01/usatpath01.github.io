---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

{% include base_path %}

<p>You can also find my articles on
<a href="https://scholar.google.com/citations?user=bqyCK7cAAAAJ&hl=en" target="_blank"><i class="ai ai-google-scholar-square"></i> <b>Google Scholar</b></a>.</p>

<div class="pub-section">
  <h2 class="pub-section-title"><i class="fa fa-book"></i> Journal Articles</h2>
  {% assign journals = site.publications | where: "category", "journal" | sort: "date" | reverse %}
  {% if journals.size > 0 %}
    {% for post in journals %}
      {% include archive-single.html %}
    {% endfor %}
  {% else %}
    <p><em>No journal articles listed yet.</em></p>
  {% endif %}
</div>

<div class="pub-section">
  <h2 class="pub-section-title"><i class="fa fa-users"></i> Conference Papers</h2>
  {% assign confs = site.publications | where: "category", "conference" | sort: "date" | reverse %}
  {% if confs.size > 0 %}
    {% for post in confs %}
      {% include archive-single.html %}
    {% endfor %}
  {% else %}
    <p><em>No conference papers listed yet.</em></p>
  {% endif %}
</div>

<style>
.pub-section { margin-bottom: 2.5rem; }
.pub-section-title {
  font-size: 1.35rem;
  margin: 1.5rem 0 1rem;
  padding-bottom: 0.4rem;
  border-bottom: 3px solid var(--accent, #2a7ae2);
}
.pub-section-title i { color: var(--accent, #2a7ae2); margin-right: 0.4rem; }
</style>
