---
layout: default
title: Home
permalink: /
---

{% include nav.html %}

<section class="hero" style="background: linear-gradient(rgba(10,31,68,0.85), rgba(10,31,68,0.85)),
              url('https://images.unsplash.com/photo-1454165205744-3b78555e5572') center/cover no-repeat;">
  <h1>Computing Education Research at Emeris (CERE)</h1>
  <p>A research lab focused on improving teaching, learning, and assessment in computing through rigorous and relevant research.</p>
  <a href="{{ '/projects/' | relative_url }}" class="btn btn-secondary">View Projects</a>
  <a href="{{ '/contact/' | relative_url }}" class="btn btn-secondary">Contact Us</a>
</section>

<section class="section">
  <h2>Focus Areas</h2>

  <!-- 2 rows (3 cards each) -->
  <div class="cards cards-2rows">
    <div class="card">
      <h3>Computing Pedagogy</h3>
      <p>Computing pedagogy research (often called Computing Education    Research – CER) investigates how computing and programming are taught and learned, and how teaching approaches can be improved to enhance student understanding, engagement, and success.</p>
    </div>

    <div class="card">
      <h3>Assessment & Feedback</h3>
      <p>Assessment and feedback research in ICT education examines how different assessment strategies and feedback  influence student engagement, and skill development in computing-related disciplines.In computing education, assessment is not only used to measure knowledge, but also to support learning through iterative practice, problem solving and peer collobaration.</p>
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
      <h3>Social Justice in ICT Education</h3>
      <p>To investigate how ICT tools and technologies can promote equitable access to education, reduce the digital divide in communities, and support inclusive learning environments.</p>
    </div>

    <div class="card">
      <h3>Ethics & Integrity</h3>
      <p>Developing responsible, fair, and integrity-aware approaches to AI and assessment.</p>
    </div>
  </div>
</section>

<section class="section" id="students">
  <h2>Student Support</h2>
  <div class="card">
    <p>We support students with:</p>
    <ul style="margin-left: 18px; margin-top: 10px;">
      <li>Honours research topics and supervision</li>
      <li>Postgraduate projects aligned to lab projects</li>
    </ul>
  </div>
</section>

<section class="section">
  <h2>Partnerships</h2>
  <div class="card">
    <p>We welcome collaboration with:</p>
    <ul class="nice-list">
      <li>Computer Science and Information Systems Faculties</li>
      <li>Excellence in Teaching & Learning units</li>
      <li>Schools, NGOs, and Industry partners</li>
      <li>Researchers, postgraduate students and research assistants</li>
    </ul>

    <div style="margin-top: 18px; text-align:center;">
      <a href="{{ '/contact/' | relative_url }}" class="btn btn-secondary">Contact Us</a>
    </div>
  </div>
</section>

{% include footer.html %}