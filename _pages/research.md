---
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /projects/
---

{% include base_path %}

<div class="research-wrap">

  <div class="section-head">
    <h2>Mentorship</h2>
    <span class="section-pill">Thesis Supervision</span>
  </div>

  <div class="mentor-grid">

    <div class="mentor-card">
      <h3 class="mentor-title">Clock Synchronisation in Provenance Systems for Serverless Computing Platforms</h3>
      <div class="mentor-meta">
        <span class="mentee">Ishan Sharma</span>
        <span class="mentor-level pg">Postgraduate</span>
      </div>
      <p class="mentor-aff">Department of Computer Science and Engineering, IIT Kharagpur</p>
    </div>

    <div class="mentor-card">
      <h3 class="mentor-title">Reverse Engineering on Docker Images</h3>
      <div class="mentor-meta">
        <span class="mentee">Vamshidhar Reddy Dudyala</span>
        <span class="mentor-level pg">Postgraduate</span>
      </div>
      <p class="mentor-aff">Department of Computer Science and Engineering, IIT Kharagpur</p>
    </div>

    <div class="mentor-card">
      <h3 class="mentor-title">Performance Analysis of eBPF Tail Calls</h3>
      <div class="mentor-meta">
        <span class="mentee">Narayan Gupta</span>
        <span class="mentor-level pg">Postgraduate</span>
      </div>
      <p class="mentor-aff">Department of Computer Science and Engineering, IIT Kharagpur</p>
    </div>

    <div class="mentor-card">
      <h3 class="mentor-title">Unified System Call Log and Application Log Generation on Serverless Environment using eBPF</h3>
      <div class="mentor-meta">
        <span class="mentee">Rajat Bachhawat</span>
        <span class="mentor-level ug">Undergraduate</span>
      </div>
      <p class="mentor-aff">Department of Computer Science and Engineering, IIT Kharagpur</p>
    </div>

    <div class="mentor-card">
      <h3 class="mentor-title">Universal Provenance Log Regeneration from Packet Traces for System Vulnerability Analysis</h3>
      <div class="mentor-meta">
        <span class="mentee">Narayan Gupta</span>
        <span class="mentor-level pg">Postgraduate</span>
      </div>
      <p class="mentor-aff">Department of Computer Science and Engineering, IIT Kharagpur</p>
    </div>

  </div>

  <div class="section-head">
    <h2>Interns</h2>
    <span class="section-pill">Project Supervision</span>
  </div>

  <div class="mentor-grid">

    <div class="mentor-card intern-card">
      <h3 class="mentor-title">Deepak Kumar Parida</h3>
      <div class="mentor-meta">
        <span class="mentor-level ug">B.Tech · 2nd Year</span>
        <span class="intern-branch">Computer Science &amp; Engineering</span>
      </div>
      <p class="mentor-aff">Parala Maharaja Engineering College &nbsp;·&nbsp; Regd. No. 2401109184</p>
      <div class="intern-links">
        <a href="mailto:deepakkumarparida74@gmail.com" class="intern-link"><i class="fas fa-envelope"></i> Email</a>
        <a href="https://github.com/Deepak-cod-bit/AI-based-restaurant-management-system" target="_blank" class="intern-link"><i class="fab fa-github"></i> AI-based Restaurant Management System</a>
      </div>
    </div>

    <div class="mentor-card intern-card">
      <h3 class="mentor-title">Puspa Pulakita</h3>
      <div class="mentor-meta">
        <span class="mentor-level ug">B.Tech · 2nd Year</span>
        <span class="intern-branch">Computer Science &amp; Engineering (Data Science)</span>
      </div>
      <p class="mentor-aff">C.V. Raman Global University &nbsp;·&nbsp; Regd. No. 2401020563</p>
      <div class="intern-links">
        <a href="mailto:softwarepuspa2@gmail.com" class="intern-link"><i class="fas fa-envelope"></i> Email</a>
        <a href="https://github.com/softwarepuspa2-collab/Benchmarking-and-Fault-Analysis-of-Kubernetes-Based-Microservices" target="_blank" class="intern-link"><i class="fab fa-github"></i> Benchmarking &amp; Fault Analysis of Kubernetes-Based Microservices</a>
      </div>
    </div>

    <div class="mentor-card intern-card">
      <h3 class="mentor-title">Ashutosh Nayak</h3>
      <div class="mentor-meta">
        <span class="mentor-level ug">B.Tech · 2nd Year</span>
        <span class="intern-branch">Computer Science &amp; Engineering</span>
      </div>
      <p class="mentor-aff">C.V. Raman Global University &nbsp;·&nbsp; Regd. No. 2401020010</p>
      <div class="intern-links">
        <a href="mailto:ashutoshn957@gmail.com" class="intern-link"><i class="fas fa-envelope"></i> Email</a>
        <a href="https://github.com/AshutoshNayak957/Benchmarking-And-Fault-Analysis-Of-Kubernetes-Based-Microservices" target="_blank" class="intern-link"><i class="fab fa-github"></i> Benchmarking &amp; Fault Analysis of Kubernetes-Based Microservices</a>
      </div>
    </div>

  </div>

</div>

<style>
.research-wrap { margin: 1.5rem 0; }

/* Section head */
.section-head { display: flex; align-items: center; gap: 0.8rem; margin: 1.5rem 0 1.4rem; }
.section-head h2 { font-size: 1.5rem; font-weight: 800; color: #14213d; margin: 0; }
.section-pill { font-size: 0.68rem; font-weight: 700; letter-spacing: 0.06em; text-transform: uppercase; color: #fff; background: var(--accent, #2a7ae2); padding: 0.25rem 0.7rem; border-radius: 999px; }

/* Mentorship cards */
.mentor-grid { display: grid; grid-template-columns: 1fr; gap: 1rem; }
.mentor-card {
  padding: 1.1rem 1.3rem; background: #fafbfc;
  border: 1px solid #e6e9ee; border-left: 4px solid var(--accent, #2a7ae2);
  border-radius: 12px; transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}
.mentor-card:hover { transform: translateY(-2px); box-shadow: 0 6px 18px rgba(42,122,226,0.10); }

.mentor-title { font-size: 1.02rem; font-weight: 700; color: #14213d; margin: 0 0 0.6rem; line-height: 1.4; }
.mentor-meta { display: flex; flex-wrap: wrap; align-items: center; gap: 0.6rem; margin-bottom: 0.4rem; }
.mentee {
  display: inline-flex; align-items: center; gap: 0.35rem;
  font-size: 0.9rem; font-weight: 700; color: var(--accent, #2a7ae2);
}
.mentee::before { content: "\f007"; font-family: "Font Awesome 6 Free"; font-weight: 900; font-size: 0.78rem; opacity: 0.8; }
.mentor-level {
  font-size: 0.66rem; font-weight: 700; letter-spacing: 0.04em; text-transform: uppercase;
  color: #fff; padding: 0.18rem 0.55rem; border-radius: 999px;
}
.mentor-level.pg { background: #6b46c1; }
.mentor-level.ug { background: #2f855a; }
.mentor-aff { margin: 0 !important; font-size: 0.85rem !important; color: #5a6680 !important; line-height: 1.4 !important; }

/* Intern-specific */
.intern-branch { font-size: 0.82rem; font-weight: 600; color: #5a6680; }
.intern-links { display: flex; flex-wrap: wrap; gap: 0.5rem; margin-top: 0.7rem; }
.intern-link {
  display: inline-flex; align-items: center; gap: 0.4rem;
  font-size: 0.78rem; font-weight: 600; color: var(--accent, #2a7ae2) !important;
  text-decoration: none !important; padding: 0.32rem 0.65rem;
  background: #fff; border: 1px solid #e0e6ef; border-radius: 8px;
  transition: border-color 0.15s ease, box-shadow 0.15s ease, transform 0.15s ease;
}
.intern-link:hover { border-color: var(--accent, #2a7ae2); transform: translateY(-1px); box-shadow: 0 4px 12px rgba(42,122,226,0.12); }
.intern-link i { font-size: 0.82rem; }

@media (max-width: 768px) {
  .section-head h2 { font-size: 1.3rem; }
  .mentor-title { font-size: 0.95rem; }
}
</style>
