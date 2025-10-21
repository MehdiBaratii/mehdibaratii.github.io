---
layout: default
title: Contact
excerpt: "Contact details and links."
---

## Contact

You can reach me directly at **{{ site.author.email }}** or use the form below.

<form class="contact-form" action="https://formspree.io/f/movqobwa" method="POST">
  <label for="name">Name</label>
  <input type="text" name="name" id="name" required>

  <label for="email">Email</label>
  <input type="email" name="_replyto" id="email" required>

  <label for="message">Message</label>
  <textarea name="message" id="message" rows="5" required></textarea>

  <button type="submit">Send Message</button>
</form>

*Your message will be securely sent to {{ site.author.email }} via Formspree.*
