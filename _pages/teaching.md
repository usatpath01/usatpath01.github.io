---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
redirect_from:
  - /courses/
  - /teachingassistance/
---

{% include base_path %}

<div class="teach-page">

  <!-- ============ COURSES TAUGHT ============ -->
  <section class="teach-section">
    <div class="teach-head-row">
      <h2 class="teach-head"><i class="fas fa-chalkboard-teacher"></i> Courses Taught</h2>
      <span class="teach-pill pill-blue">IIIT Bhubaneswar</span>
    </div>
    <p class="teach-sub">Courses I teach as faculty. Click a card for slides, syllabus, textbooks &amp; grading.</p>

    {% assign courses = site.courses | sort: "date" | reverse %}
    {% if courses.size > 0 %}
    <div class="course-grid">
      {% for course in courses %}
      <a class="course-card" href="{{ course.url | prepend: base_path }}">
        <div class="course-card-head">
          {% if course.level %}<span class="course-level">{{ course.level }}</span>{% endif %}
          {% if course.semester %}<span class="course-term">{{ course.semester }}</span>{% endif %}
        </div>
        <h3 class="course-name">{{ course.title }}</h3>
        {% if course.venue %}<p class="course-venue"><i class="fa fa-university"></i> {{ course.venue }}</p>{% endif %}
        <div class="course-meta">
          {% if course.credits %}<span class="course-chip"><i class="fa fa-star"></i> {{ course.credits }} Credits</span>{% endif %}
          {% if course.type %}<span class="course-chip"><i class="fa fa-graduation-cap"></i> {{ course.type }}</span>{% endif %}
        </div>
        <span class="course-cta">View course &rarr;</span>
      </a>
      {% endfor %}
    </div>
    {% else %}
    <p class="teach-empty"><em>Course listings coming soon.</em></p>
    {% endif %}
  </section>

  <!-- ============ TEACHING ASSISTANTSHIPS ============ -->
  <section class="teach-section">
    <div class="teach-head-row">
      <h2 class="teach-head"><i class="fas fa-user-graduate"></i> Teaching Assistantships</h2>
      <span class="teach-pill pill-grey">IIT Kharagpur</span>
    </div>
    <p class="teach-sub">Courses I assisted with during my Ph.D. Click a card for instructor, syllabus &amp; details.</p>

    {% assign tas = site.teachingassistance | sort: "date" | reverse %}
    {% if tas.size > 0 %}
    <div class="ta-grid">
      {% for ta in tas %}
      <a class="ta-card" href="{{ ta.url | prepend: base_path }}">
        <div class="ta-card-head">
          {% if ta.type %}<span class="ta-type">{{ ta.type }}</span>{% endif %}
          {% if ta.date %}<span class="ta-year">{{ ta.date | date: "%Y" }}</span>{% endif %}
        </div>
        <h3 class="ta-name">{{ ta.title }}</h3>
        {% if ta.venue %}<p class="ta-venue"><i class="fa fa-university"></i> {{ ta.venue }}</p>{% endif %}
        <span class="ta-cta">View details &rarr;</span>
      </a>
      {% endfor %}
    </div>
    {% else %}
    <p class="teach-empty"><em>No teaching assistantships listed yet.</em></p>
    {% endif %}
  </section>

</div>

<style>
.teach-page { max-width: 880px; }
.teach-section { margin-bottom: 2.75rem; }

.teach-head-row { display: flex; align-items: center; gap: 0.7rem; flex-wrap: wrap; }
.teach-head {
  font-size: 1.4rem; font-weight: 800; color: #1a2b4a; margin: 0;
}
.teach-head i { color: var(--accent, #2a7ae2); margin-right: 0.45rem; }
.teach-pill {
  font-size: 0.62rem; font-weight: 700; letter-spacing: 0.05em; text-transform: uppercase;
  padding: 0.22rem 0.6rem; border-radius: 999px;
}
.pill-blue { color: #2a5db0; background: #e8f0fc; }
.pill-grey { color: #50607a; background: #eef1f5; }

.teach-sub { color: #6b7785; font-size: 0.88rem; margin: 0.5rem 0 1.2rem; }
.teach-empty { color: #888; }

/* Course cards */
.course-grid, .ta-grid {
  display: grid; gap: 1rem;
  grid-template-columns: repeat(auto-fill, minmax(265px, 1fr));
}

.course-card, .ta-card {
  display: flex; flex-direction: column;
  padding: 1.1rem 1.25rem; text-decoration: none !important; color: inherit;
  background: #fafbfc; border: 1px solid #e6e9ee; border-radius: 13px;
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}
.course-card:hover, .ta-card:hover {
  transform: translateY(-3px); box-shadow: 0 9px 24px rgba(42,122,226,0.10);
  border-color: var(--accent, #2a7ae2);
}

.course-card-head, .ta-card-head {
  display: flex; justify-content: space-between; align-items: center;
  gap: 0.5rem; margin-bottom: 0.55rem;
}
.course-level, .ta-type {
  font-size: 0.66rem; font-weight: 700; letter-spacing: 0.03em; text-transform: uppercase;
  color: #fff; padding: 0.2rem 0.55rem; border-radius: 999px;
}
.course-level { background: var(--accent, #2a7ae2); }
.ta-type { background: #6b5bd2; }
.course-term, .ta-year { font-size: 0.78rem; color: #888; font-weight: 600; }

.course-name, .ta-name {
  font-size: 1.05rem; margin: 0.1rem 0 0.5rem; line-height: 1.35; color: #1a2b4a;
}

.course-venue, .ta-venue {
  font-size: 0.82rem; color: #66707d; margin: 0 0 0.85rem; line-height: 1.4;
}
.course-venue i, .ta-venue i { color: var(--accent, #2a7ae2); margin-right: 0.3rem; }

.course-meta { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-bottom: 0.9rem; }
.course-chip {
  font-size: 0.72rem; font-weight: 600; color: #1f7a54;
  background: #e8f5ee; padding: 0.2rem 0.55rem; border-radius: 6px;
}
.course-chip i { margin-right: 0.25rem; }

.course-cta, .ta-cta {
  margin-top: auto; font-size: 0.82rem; font-weight: 700; color: var(--accent, #2a7ae2);
}

@media (max-width: 600px) {
  .course-grid, .ta-grid { grid-template-columns: 1fr; }
  .teach-head { font-size: 1.2rem; }
}
</style>
