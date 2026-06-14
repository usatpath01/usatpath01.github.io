---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-actions">
  <a href="{{ base_path }}/files/Utkalika_Satapathy_CV.pdf" target="_blank" class="cv-btn">
    <i class="fas fa-download"></i> Download PDF
  </a>
  <a href="{{ base_path }}/files/Utkalika_Satapathy_CV.pdf" target="_blank" class="cv-btn cv-btn-ghost">
    <i class="fas fa-external-link-alt"></i> Open in New Tab
  </a>
</div>

<div class="cv-viewer">
  <iframe src="{{ base_path }}/files/Utkalika_Satapathy_CV.pdf#view=FitH" title="Curriculum Vitae" loading="lazy"></iframe>
</div>

<p class="cv-fallback">
  If the document does not display above, you can <a href="{{ base_path }}/files/Utkalika_Satapathy_CV.pdf" target="_blank">download the PDF here</a>.
</p>

<style>
.cv-actions { display: flex; flex-wrap: wrap; gap: 0.6rem; margin: 0.5rem 0 1.2rem; }
.cv-btn {
  display: inline-flex; align-items: center; gap: 0.5rem;
  font-size: 0.88rem; font-weight: 600; text-decoration: none !important;
  color: #fff !important; background: var(--accent, #2a7ae2);
  padding: 0.55rem 1.1rem; border-radius: 9px;
  border: 1px solid var(--accent, #2a7ae2);
  transition: transform 0.15s ease, box-shadow 0.15s ease, background 0.15s ease;
}
.cv-btn:hover { transform: translateY(-2px); box-shadow: 0 6px 16px rgba(42,122,226,0.25); }
.cv-btn-ghost { color: var(--accent, #2a7ae2) !important; background: #fff; }
.cv-btn-ghost:hover { background: #eef4fd; box-shadow: 0 6px 16px rgba(42,122,226,0.12); }

.cv-viewer {
  width: 100%;
  height: 80vh;
  min-height: 600px;
  border: 1px solid #e6e9ee;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 6px 22px rgba(20,33,59,0.08);
  background: #f7f9fc;
}
.cv-viewer iframe { width: 100%; height: 100%; border: 0; display: block; }

.cv-fallback { margin-top: 1rem; font-size: 0.88rem; color: #5a6680; text-align: center; }

@media (max-width: 768px) {
  .cv-viewer { height: 70vh; min-height: 480px; }
}
</style>