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
  email: benjamin.tatlow@nottingham.ac.uk
#  address: , University Park. University of Nottingham, Nottingham NG7 2RD
  address:
    street: School of Economics. Office C43, Sir Clive Granger Building, University Park. University of Nottingham
    city: Nottingham
    region:
    postcode: 'NG7 2RD'
    country: United Kingdom
    country_code: 
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Find me on Twitter
      link: 'https://twitter.com/TatlowB/'

design:
  columns: '2'
---
