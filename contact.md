---
layout: default
title: Contact
permalink: /contact/
---

{% include nav.html %}

<section class="section">
  <h2>Contact CERE</h2>
  
  <div class="form-wrap form-wrap form-wrap-dark">
    <form id="cere-contact-form"
      action="https://formspree.io/f/mdawnnbp"
      method="POST">

      <label>Full name</label>
      <input type="text" name="name" required>

      <label>Email address</label>
      <input type="email" name="email" required>

      <label>Affiliation / Organisation</label>
      <input type="text" name="affiliation">

      <label>Enquiry type</label>
      <select name="enquiry_type" required>
      <option value="">Select enquiry type</option>
      <option>Collaboration / partnership</option>
      <option>Research supervision</option>
      <option>Honours / Masters research topic</option>
      <option>Student participation</option>
      <option>Speaking / seminar request</option>
      <option>Other</option>
      </select>

      <label>Message</label>
      <textarea name="message" rows="6" required></textarea>

      <input type="text" name="_gotcha" style="display:none">

      <button type="submit">Send Enquiry</button>

    </form>

    <p id="form-status"></p>

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

<script>
var form = document.getElementById("cere-contact-form");
var status = document.getElementById("form-status");

async function handleSubmit(event) {
  event.preventDefault();

  var data = new FormData(event.target);

  fetch(event.target.action, {
    method: form.method,
    body: data,
    headers: {
      'Accept': 'application/json'
    }
  }).then(response => {

    if (response.ok) {
      status.innerHTML = "Thank you. Your enquiry has been sent.";
      form.reset();
    } else {
      status.innerHTML = "Oops. Something went wrong.";
    }

  }).catch(error => {
    status.innerHTML = "Network error. Please try again.";
  });
}

form.addEventListener("submit", handleSubmit);
</script>