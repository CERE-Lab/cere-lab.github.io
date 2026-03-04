---
layout: default
title: Projects
permalink: /projects/
---

{% include nav.html %}

<section class="hero" style="background: linear-gradient(rgba(10,31,68,0.85), rgba(10,31,68,0.85)),
              url('https://images.unsplash.com/photo-1454165205744-3b78555e5572') center/cover no-repeat;">
  <h1>Projects</h1>
  <p>Active research streams and project work aligned to CERE’s focus areas.</p>
  <a href="#streams" class="btn">Active Streams</a>
  <a href="#current" class="btn">Current Projects</a>
</section>

<section class="section" id="streams">
  <h2>Active Research Streams</h2>

  <div class="cards">
    <div class="card">
      <h3>Responsible AI in Computing Education</h3>
      <p><strong>Goal:</strong> Understand how AI tools affect learning, assessment, and integrity in computing modules.</p>
      <p><strong>Typical outputs:</strong> guidance for educators, assessment patterns, integrity-by-design practices.</p>
    </div>

    <div class="card">
      <h3>Learning Analytics for Student Success</h3>
      <p><strong>Goal:</strong> Identify early signals of struggle and design interventions that improve outcomes.</p>
      <p><strong>Data sources:</strong> LMS activity, assessment patterns, attendance/participation indicators (where applicable and ethical).</p>
    </div>

    <div class="card">
      <h3>Authentic Assessment in Programming</h3>
      <p><strong>Goal:</strong> Redesign assessments to measure real capability while reducing academic misconduct.</p>
      <p><strong>Outputs:</strong> rubric templates, assessment exemplars, feedback workflows.</p>
    </div>

    <div class="card">
      <h3>Active Learning Labs & Scaffolding</h3>
      <p><strong>Goal:</strong> Evaluate lab structures that help novices progress reliably.</p>
      <p><strong>Outputs:</strong> lab patterns, step-by-step guides, reflective prompts.</p>
    </div>
  </div>
</section>

<section class="section" id="current">
  <h2>Current Projects (template)</h2>

  <div class="card" style="max-width: 980px; margin: 0 auto;">
    Use this format for each project:
  </div>

  <div class="cards" style="margin-top: 22px;">
    <div class="card">
      <h3>Project Title</h3>
      <p><strong>Research question:</strong> …</p>
      <p><strong>Methods:</strong> …</p>
      <p><strong>Status:</strong> Planning / Data collection / Analysis / Writing / Complete</p>
      <p><strong>Outputs:</strong> link to paper, repo, poster, or report</p>
    </div>

    <div class="card">
      <h3>Project Title</h3>
      <p><strong>Research question:</strong> …</p>
      <p><strong>Methods:</strong> …</p>
      <p><strong>Status:</strong> Planning / Data collection / Analysis / Writing / Complete</p>
      <p><strong>Outputs:</strong> link to paper, repo, poster, or report</p>
    </div>

    <div class="card">
      <h3>Project Title</h3>
      <p><strong>Research question:</strong> …</p>
      <p><strong>Methods:</strong> …</p>
      <p><strong>Status:</strong> Planning / Data collection / Analysis / Writing / Complete</p>
      <p><strong>Outputs:</strong> link to paper, repo, poster, or report</p>
    </div>
  </div>
</section>

<section class="section">
  <h2>Completed Projects</h2>

  <div class="card" style="max-width: 980px; margin: 0 auto;">
    <ul style="margin-left: 18px;">
      <li><strong>Project Name</strong> — one-line outcome + link</li>
      <li><strong>Project Name</strong> — one-line outcome + link</li>
    </ul>
  </div>
</section>

<section class="section">
  <h2>Want to propose a project?</h2>

  <div class="card" style="max-width: 980px; margin: 0 auto; text-align:center;">
    Send a short proposal via the <strong>Contact</strong> page.
    <div style="margin-top: 14px;">
      <a href="{{ '/contact/' | relative_url }}" class="btn">Propose a Project</a>
    </div>
  </div>
</section>

{% include footer.html %}