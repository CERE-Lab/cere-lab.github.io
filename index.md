---
layout: default
title: Home
permalink: /
---

{% include nav.html %}

<section class="hero" style="background: linear-gradient(rgba(10,31,68,0.85), rgba(10,31,68,0.85)),
              url('https://images.unsplash.com/photo-1454165205744-3b78555e5572') center/cover no-repeat;">
  <h1>Computing Education Research at Emeris (CERE)</h1>
  <p>Advancing computing education through research, innovation, and evidence-based practice.</p>
  <a href="{{ '/projects/' | relative_url }}" class="btn btn-secondary">View Projects</a>
  <a href="{{ '/contact/' | relative_url }}" class="btn btn-secondary">Contact Us</a>
</section>

<section class="section">
  <div class="card page-card">
    <h2 class="section-title-left">Who we are</h2>
    <p><strong>Computing Education Research at Emeris (CERE)</strong> is a research lab focused on improving teaching, learning, and assessment in computing through rigorous, practice-relevant research.</p>
  </div>
</section>

<section class="section">
  <h2>Focus Areas</h2>

  <!-- 2 rows (3 cards each) -->
  <div class="cards cards-2rows">
    <div class="card">
      <h3>Computing Pedagogy</h3>
      <p>Evidence-based teaching strategies, misconceptions, and learning design for programming, systems, and data.</p>
    </div>

    <div class="card">
      <h3>Assessment & Feedback</h3>
      <p>Authentic assessment, rubrics, feedback workflows, and integrity-by-design approaches.</p>
    </div>

    <div class="card">
      <h3>Learning Analytics & AI</h3>
      <p>Engagement, student success signals, responsible AI use, and actionable insights for educators.</p>
    </div>

    <div class="card">
      <h3>EdTech Innovation</h3>
      <p>Evaluation of tools, LMS innovation, automation, and scalable digital learning interventions.</p>
    </div>

    <div class="card">
      <h3>Computational Thinking</h3>
      <p>Enhancing algorithmic reasoning and digital problem-solving.</p>
    </div>

    <div class="card">
      <h3>Ethics & Integrity</h3>
      <p>Developing responsible, fair, and integrity-aware approaches to AI and assessment.</p>
    </div>
  </div>
</section>

<section class="section" id="students">
  <h2>Student Support</h2>
  <div class="card" style="max-width: 980px; margin: 0 auto; text-align:center;">
    <p>We support students with:</p>
    <ul style="margin-left: 18px; margin-top: 10px;">
      <li>Honours research topics and supervision</li>
      <li>Postgraduate projects aligned to lab projects</li>
      <li>Research assistant opportunities (data collection, analysis, prototypes, etc.)</li>
    </ul>
  </div>
</section>


<section class="section">
  <h2>Partnerships</h2>
  <div class="card" style="max-width: 980px; margin: 0 auto; text-align:center;">
    <p>We welcome collaboration with:</p>
    <ul class="nice-list">
      <li>Computer Science and Information Systems Faculties</li>
      <li>Excellence in Teaching & Learning units</li>
      <li>Schools, NGOs, and industry partners</li>
      <li>Researchers, postgraduate students and research assistants</li>
    </ul>

    <div style="margin-top: 18px; text-align:center;">
      <a href="{{ '/contact/' | relative_url }}" class="btn btn-secondary">Contact Us</a>
    </div>
  </div>
</section>

{% include footer.html %}