---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

{% include base_path %}

<p class="pub-intro">You can also find my articles on
<a href="https://scholar.google.com/citations?user=bqyCK7cAAAAJ&hl=en" target="_blank"><i class="ai ai-google-scholar-square"></i> <b>Google Scholar</b></a>.</p>

{% comment %} ---------- JOURNAL ARTICLES ---------- {% endcomment %}
{% assign journals = site.publications | where: "category", "journal" | sort: "date" %}

<div class="pub-group">
  <div class="pub-group-head">
    <h2 class="pub-group-title">Journal Articles</h2>
    <span class="pub-group-pill pill-blue">Peer-reviewed</span>
  </div>

  {% if journals.size > 0 %}
    {% for post in journals reversed %}
      {% assign idx = journals.size | minus: forloop.index0 %}
      {% assign label = idx | prepend: "J0" %}
      {% if idx > 9 %}{% assign label = idx | prepend: "J" %}{% endif %}
      <a class="pub-card" href="{{ post.url | prepend: base_path }}">
        <span class="pub-badge badge-journal">{{ label }}</span>
        <div class="pub-card-body">
          <p class="pub-card-cite">{% if post.authors %}{{ post.authors }}, {% endif %}"{{ post.title }}."</p>
          <div class="pub-card-meta">
            {% if post.venue_short %}<span class="venue-chip">{{ post.venue_short }}</span>{% endif %}
            {% if post.detail %}<span class="meta-detail">· {{ post.detail }}</span>{% endif %}
            {% if post.status %}<span class="status-chip">{{ post.status }}</span>{% endif %}
          </div>
        </div>
      </a>
    {% endfor %}
  {% else %}
    <p class="pub-empty"><em>No journal articles listed yet.</em></p>
  {% endif %}
</div>

{% comment %} ---------- CONFERENCE PAPERS ---------- {% endcomment %}
{% assign confs = site.publications | where: "category", "conference" | sort: "date" %}

<div class="pub-group">
  <div class="pub-group-head">
    <h2 class="pub-group-title">Conference Papers</h2>
    <span class="pub-group-pill pill-green">Proceedings</span>
  </div>

  {% if confs.size > 0 %}
    {% for post in confs reversed %}
      {% assign idx = confs.size | minus: forloop.index0 %}
      {% assign label = idx | prepend: "C0" %}
      {% if idx > 9 %}{% assign label = idx | prepend: "C" %}{% endif %}
      <a class="pub-card" href="{{ post.url | prepend: base_path }}">
        <span class="pub-badge badge-conf">{{ label }}</span>
        <div class="pub-card-body">
          <p class="pub-card-cite">{% if post.authors %}{{ post.authors }}, {% endif %}"{{ post.title }}."</p>
          <div class="pub-card-meta">
            {% if post.venue_short %}<span class="venue-chip">{{ post.venue_short }}</span>{% endif %}
            {% if post.detail %}<span class="meta-detail">· {{ post.detail }}</span>{% endif %}
            {% if post.status %}<span class="status-chip">{{ post.status }}</span>{% endif %}
          </div>
        </div>
      </a>
    {% endfor %}
  {% else %}
    <p class="pub-empty"><em>No conference papers listed yet.</em></p>
  {% endif %}
</div>

<style>
.pub-intro { font-size: 0.9rem; margin-bottom: 1.5rem; }

.pub-group { margin-bottom: 2rem; }
.pub-group-head { display: flex; align-items: center; gap: 0.6rem; margin-bottom: 0.9rem; }
.pub-group-title {
  font-size: 1.3rem; font-weight: 800; margin: 0;
  color: #1a2b4a; letter-spacing: -0.01em;
}
.pub-group-pill {
  font-size: 0.6rem; font-weight: 700; letter-spacing: 0.06em; text-transform: uppercase;
  padding: 0.22rem 0.55rem; border-radius: 999px;
}
.pill-blue  { color: #2a5db0; background: #e8f0fc; }
.pill-green { color: #2a5db0; background: #e8f0fc; border: 1px solid #c5dbf7; }

.pub-card {
  display: flex; align-items: flex-start; gap: 0.85rem;
  padding: 0.85rem 1rem; margin-bottom: 0.65rem;
  background: #fafbfc;
  border: 1px solid #e6e9ee;
  border-radius: 11px;
  text-decoration: none !important; color: inherit;
  transition: border-color 0.18s ease, box-shadow 0.18s ease, transform 0.18s ease;
}
.pub-card:hover {
  border-color: var(--accent, #2a7ae2);
  box-shadow: 0 6px 20px rgba(42,122,226,0.12);
  transform: translateY(-2px);
}

.pub-badge {
  flex-shrink: 0;
  font-family: Georgia, 'Times New Roman', serif;
  font-weight: 700; font-size: 0.85rem;
  padding: 0.35rem 0.5rem; border-radius: 8px;
  min-width: 2.4rem; text-align: center; line-height: 1.1;
}
.badge-journal { color: #fff; background: var(--accent, #2a7ae2); }
.badge-conf    { color: #fff; background: #1a4d8f; }

.pub-card-body { flex: 1; }
.pub-card-cite {
  margin: 0 0 0.4rem; font-size: 0.85rem; line-height: 1.45; color: #2a3a4a;
  text-align: left !important;
}
.pub-card-cite { font-weight: 400; }
/* Bold only the lead author(s): wrap handled via <b> in `authors` front matter */

.pub-card-meta { display: flex; flex-wrap: wrap; align-items: center; gap: 0.4rem; }
.venue-chip {
  font-size: 0.72rem; font-weight: 700; color: #2a5db0;
  background: #e8f0fc; padding: 0.2rem 0.5rem; border-radius: 5px;
}
.meta-detail { font-size: 0.75rem; color: #6b7785; }
.status-chip {
  font-size: 0.7rem; font-weight: 700; color: #9a6a00;
  background: #fdeecb; padding: 0.2rem 0.5rem; border-radius: 5px;
}

.pub-empty { color: #888; }

@media (max-width: 600px) {
  .pub-card { gap: 0.8rem; padding: 1rem; }
  .pub-badge { min-width: 2.6rem; font-size: 0.95rem; padding: 0.4rem 0.5rem; }
  .pub-group-title { font-size: 1.4rem; }
}
</style>
