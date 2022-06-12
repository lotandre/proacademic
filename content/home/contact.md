widget: contact
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: Contact Me
subtitle: ''
weight: 10

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
  email: test@example.org
  phone: null
  address:
    street: Helleveien 30
    city: Bergen
    region: null
    postcode: '5045'
    country: Norway
    country_code: NOR
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: null
  office_hours: null
  appointment_url: null
  contact_links: null

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
