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
  autolink: false

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: brian.e.robinson[AT]mcgill.ca
  phone: 
  address:
    street: 805 Sherbrooke St West
    city: Montreal
    region: QC
    postcode: 'H3A 0B9'
    country: Canada
    country_code: CA
  coordinates:
    latitude: '45.50471475648672'
    longitude: '-73.5749652015539'
  directions: 
  office_hours:
    - 
  appointment_url: 
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/brianer'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
