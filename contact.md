---
layout: default
title: Contact
permalink: /contact/
---

{% include nav.html %}

<section class="section" id="contact">
  <h2>Contact CERE</h2>

  <p style="text-align:center; max-width:900px; margin:0 auto 30px;">
    We welcome enquiries related to student research, supervision, collaboration,
    partnerships, and speaking or seminar opportunities.
  </p>

  <div class="cards" style="margin-bottom: 35px;">

    <div class="card">
      <h3>Student Support</h3>
      <p>We support students with:</p>
      <ul class="nice-list">
        <li>Honours research topics and supervision</li>
        <li>Postgraduate projects aligned to lab projects</li>
      </ul>
    </div>

    <div class="card">
      <h3>Partnerships</h3>
      <p>We welcome collaboration with:</p>
      <ul class="nice-list">
        <li>Computer Science and Information Systems Faculties</li>
        <li>Excellence in Teaching &amp; Learning units</li>
        <li>Schools, NGOs, and Industry partners</li>
        <li>Researchers, postgraduate students and research assistants</li>
      </ul>
    </div>

  </div>

  <div class="form-wrap form-wrap-dark">
    <form id="cere-contact-form"
          action="https://formspree.io/f/mdawnnbp"
          method="POST">

      <label for="name">Full name</label>
      <input id="name" type="text" name="name" required>

      <label for="email">Email address</label>
      <input id="email" type="email" name="email" required>

      <label for="affiliation">Affiliation / Organisation</label>
      <input id="affiliation" type="text" name="affiliation">

      <label for="enquiry_type">Enquiry type</label>
      <select id="enquiry_type" name="enquiry_type" required>
        <option value="" selected disabled>Select enquiry type</option>
        <option>Collaboration / partnership</option>
        <option>Research supervision</option>
        <option>Honours / Masters research topic</option>
        <option>Student participation</option>
        <option>Speaking / seminar request</option>
        <option>Other</option>
      </select>

      <label for="message">Message</label>
      <textarea id="message" name="message" rows="6" required></textarea>

      <input type="text" name="_gotcha" style="display:none">

      <button class="btn btn-secondary" type="submit" style="margin:0;">Send Enquiry</button>
    </form>

    <p id="form-status" role="status" aria-live="polite" style="margin-top:14px;"></p>
  </div>
</section>

{% include footer.html %}

<script>
  (function () {
    const form = document.getElementById("cere-contact-form");
    const status = document.getElementById("form-status");
    if (!form || !status) return;

    form.addEventListener("submit", async function (event) {
      event.preventDefault();
      status.textContent = "Sending…";

      try {
        const data = new FormData(form);

        const response = await fetch(form.action, {
          method: form.method,
          body: data,
          headers: { "Accept": "application/json" }
        });

        if (response.ok) {
          status.textContent = "✅ Thank you. Your enquiry has been sent.";
          form.reset();
        } else {
          let msg = "❌ Something went wrong. Please try again.";
          try {
            const json = await response.json();
            if (json && json.errors && json.errors.length) {
              msg = "❌ " + json.errors.map(e => e.message).join(" ");
            }
          } catch (_) {}
          status.textContent = msg;
        }
      } catch (err) {
        status.textContent = "❌ Network error. Please check your connection and try again.";
      }
    });
  })();
</script>