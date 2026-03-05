---
layout: default
title: Contact
permalink: /contact/
---

{% include nav.html %}

<section class="hero" style="background: linear-gradient(rgba(10,31,68,0.85), rgba(10,31,68,0.85)),
              url('https://images.unsplash.com/photo-1454165205744-3b78555e5572') center/cover no-repeat;">
  <h1>Contact CERE</h1>
  <p>Collaborations | Research Supervision | Academic Partnerships</p>
</section>

<section class="section">

  <section class="section">
  <h2>Send an Enquiry</h2>

  <div class="form-wrap form-wrap-dark">

    <!-- Replace abcdwxyz with your real Formspree ID -->
    <form action="https://formspree.io/f/mdawnnbp" method="POST">

      <!-- spam honeypot -->
      <input type="text" name="_gotcha" style="display:none">

      <!-- subject shown in your inbox -->
      <input type="hidden" name="_subject" value="New enquiry: CERE website">

      <!-- optional redirect after submit -->
      <input type="hidden" name="_redirect" value="{{ '/contact/?sent=1' | relative_url }}">

      <input type="text" name="name" placeholder="Full Name" required>
      <input type="email" name="email" placeholder="Email Address" required>
      <input type="text" name="affiliation" placeholder="Affiliation / Organisation (optional)">
      <input type="text" name="subject" placeholder="Subject (optional)">
      <textarea name="message" rows="6" placeholder="Your Message" required></textarea>

      <button type="submit" class="btn" style="margin:0;">Submit Message</button>
    </form>

    <p class="muted" style="margin-top:14px;">
      By submitting this form, you consent to being contacted by CERE for the purpose of responding to your enquiry.
    </p>

    <!-- Optional: simple success note (shows after redirect) -->
    <p class="success-note" style="display:none; margin-top:14px;">
      ✅ Thanks — your message has been sent.
    </p>
  </div>
</section>

<script>
  // Show success note if redirected with ?sent=1
  if (new URLSearchParams(window.location.search).get("sent") === "1") {
    const el = document.querySelector(".success-note");
    if (el) el.style.display = "block";
  }
</script>

</section>

{% include footer.html %}