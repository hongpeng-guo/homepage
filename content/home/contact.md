---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: hg5@illinois.edu
  address:
    room: 3101 Siebel Center for Computer Science
    street: 201 N Goodwin Ave
    city: Urbana
    region: IL
    postcode: '61801'

design:
  columns: '2'
---
