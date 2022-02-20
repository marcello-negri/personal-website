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
      captcha: true

  # Contact details (edit or remove options as required)
  email: marcellomassimo.negri@gmail.com
  address:
    street: Spiegelgasse 1
    city: Basel
    postcode: '4051'
    country: Switzerland
    country_code: CH
  directions: first floor
  
design:
  columns: '2'
---
