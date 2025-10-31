---
layout: default
title: Contact
excerpt: "Contact details and links."
---

## Contact

I welcome research, teaching, and collaboration enquiries.

- Email (Academic): <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
- Email (Personal): <a href="mailto:{{ site.author.personal_email }}">{{ site.author.personal_email }}</a>
- Google Scholar: <a href="{{ site.author.scholar }}">{{ site.author.scholar }}</a>
- ORCID: <a href="{{ site.author.orcid }}">{{ site.author.orcid }}</a>

Or use the form below:

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
