---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

{% include base_path %}

You can also find my articles on my <a href="https://scholar.google.com/citations?user=bqyCK7cAAAAJ&hl=en" target=_blank><i class="ai ai-google-scholar-square ai-3x" style="font-size: 0.95em;"> <b>Google Scholar</b></i></a>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
