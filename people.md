---
layout: default
title: People
permalink: /people/
---

{% include nav.html %}

<section class="section">
  <h2>Leadership & Coordinators</h2>

  <div class="cards">
    <!-- Person 1 -->
    <div class="card person-card">
      <div class="person-img" style="background-image:url('{{ "/assets/img/natasha.jpg" | relative_url }}');"></div>
      <div class="person-body">
        <h3>Natasha Madhav</h3>
        <p class="muted"><strong>Title:</strong> Lecturer – Faculty of ICT</p>
        <p class="muted"><strong>Affiliation:</strong> Emeris</p>

        <div class="person-links">
          <a class="pill" href="https://orcid.org/0000-0001-8055-0923" target="_blank" rel="noopener">ORCID</a>
          <a class="pill" href="https://scholar.google.com/citations?user=rcVve20AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
          <a class="pill" href="mailto:nmadhav@emeris.ac.za">Email</a>
        </div>
      </div>
    </div>

    <!-- Person 2 -->
    <div class="card person-card">
      <div class="person-img" style="background-image:url('{{ "/assets/img/ebrahim.png" | relative_url }}');"></div>
      <div class="person-body">
        <h3>Ebrahim Adam</h3>
        <p class="muted"><strong>Title:</strong> Lecturer – Faculty of ICT</p>
        <p class="muted"><strong>Affiliation:</strong> Emeris</p>

        <div class="person-links">
          <a class="pill" href="https://orcid.org/0000-0002-2052-3007" target="_blank" rel="noopener">ORCID</a>
          <a class="pill" href="https://scholar.google.com/citations?user=1EFsAqcAAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>
          <a class="pill" href="mailto:eadam@emeris.ac.za">Email</a>
        </div>
      </div>
    </div>

    <!-- Person 3 (placeholder / add your third) -->
    <div class="card person-card">
      <div class="person-img" style="background-image:url('{{ "/assets/img/ebrahim.png" | relative_url }}');"></div>
      <div class="person-body">
        <h3>Research Associate (TBC)</h3>
        <p class="muted"><strong>Title:</strong> Research Associate</p>
        <p class="muted"><strong>Affiliation:</strong> Emeris</p>

        <div class="person-links">
          <a class="pill" href="#" aria-disabled="true">ORCID</a>
          <a class="pill" href="#" aria-disabled="true">Google Scholar</a>
          <a class="pill" href="{{ '/contact/' | relative_url }}">Email</a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section" id="students">
  <h2>Students Support</h2>
  <div class="card" style="max-width: 980px; margin: 0 auto; text-align:center;">
    <p>We support students with:</p>
    <ul style="margin-left: 18px; margin-top: 10px;">
      <li>Honours research topics and supervision</li>
      <li>Postgraduate projects aligned to lab streams</li>
      <li>Research assistant opportunities (data collection, analysis, prototypes)</li>
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