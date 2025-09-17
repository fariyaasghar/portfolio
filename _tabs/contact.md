---
title: Contact
icon: fas fa-envelope
order: 3
layout: page
---

<!-- This creates a responsive two-column layout -->
<div class="row">

  <!-- Left Column -->
  <div class="col-lg-5 mb-5 mb-lg-0">
    <h2>Get In Touch</h2>
    <p>
      I'm actively seeking new opportunities in data analytics and would love to connect with fellow data professionals, potential employers, and collaborators. The best way to reach me is via LinkedIn or the form on this page.
    </p>
    <hr class="my-4">
    <h4>Professional Profiles</h4>
    <ul class="list-unstyled">
      <li class="mb-2">
        <i class="fab fa-linkedin fa-fw me-2"></i><a href="https://www.linkedin.com/in/fariya-asghar" target="_blank" rel="noopener noreferrer">LinkedIn Profile</a>
      </li>
      <li class="mb-2">
        <i class="fab fa-github fa-fw me-2"></i><a href="https://github.com/fariyaasghar" target="_blank" rel="noopener noreferrer">GitHub Profile</a>
      </li>
    </ul>
  </div>

  <!-- Right Column -->
  <div class="col-lg-7">
    <h2>Send a Quick Message</h2>
    <form action="https://formspree.io/f/YOUR_UNIQUE_CODE" method="POST" class="contact-form">
      <p class="form-note"><small>Required fields are marked with an asterisk (*)</small></p>
      <div class="form-group">
        <label for="name">Your Name: <span class="text-danger">*</span></label>
        <input type="text" id="name" name="name" class="form-control" required>
      </div>
      <div class="form-group">
        <label for="email">Your Email: <span class="text-danger">*</span></label>
        <input type="email" id="email" name="_replyto" class="form-control" required>
      </div>
      <div class="form-group">
        <label for="message">Message: <span class="text-danger">*</span></label>
        <textarea id="message" name="message" rows="4" class="form-control" required></textarea>
      </div>
      <input type="text" name="_gotcha" style="display:none" />
      <button type="submit" class="btn btn-primary mt-3">Send Message</button>
    </form>
  </div>
</div>