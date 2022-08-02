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
  email: filip.mellgren@su.se
  address:
    street: Universitetsvägen 10 A, plan 6 & 7
    city: Stockholm
    postcode: '114 18'
    country: Sweden
    country_code: SE
  coordinates:
    latitude: '59.36297' 
    longitude: '18.05862'
  directions: Enter Building A
  office_hours:
    - 'Monday 10:00 to 10:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/FilipMellgren'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
  background:
    color: '#C68E39'
    # Text color (true=light, false=dark, or remove for the dynamic theme color). 
    text_color_light: true
---
