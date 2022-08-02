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
  address:
    street: Universitetsvägen 10 A, plan 6 & 7
    city: Stockholm
    postcode: '114 18'
    country: Sweden
    country_code: SE
  coordinates:
    latitude: '59.36297' 
    longitude: '18.05862'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/FilipMellgren'

design:
  columns: '2'
  background:
    color: '#3e7f84'
    # Text color (true=light, false=dark, or remove for the dynamic theme color). 
---
