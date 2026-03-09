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
      <p>Research focusing on assessment and feedback in ICT education examines how different assessment strategies,feedback and peer reviews  influence student engagement.In computing education, assessment is not only used to measure knowledge, but to support learning through practice, problem solving and peer collobaration.</p>
    </div>

    <div class="card">
      <h3>Learning Analytics & AI</h3>
      <p>Engagement, student success signals, responsible AI use, and actionable insights for educators.</p>
    </div>

    <div class="card">
      <h3>EdTech Innovation</h3>
      <p>Educational Technology (EdTech) innovation and research focuses on how digital technologies can transform teaching, learning, and educational systems.These innovations often include technologies such as Artificial Intelligence (AI), as well as virtual and augmented reality (VR/AR) to create immersive learning environments.</p>
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

{% include footer.html %}