---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: heinrich@kit.edu
  address:
    street: Am Fasanengarten 5
    city: Karlsruhe
    postcode: '76131'
    country: Germany
  coordinates:
    latitude: '49.01389404721178'
    longitude: '8.419759198520373'
  directions: Enter Building 50.34 and take the stairs to Room 244 on Floor 2
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

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

design:
  columns: '1'
---

