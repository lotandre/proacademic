widget: contact
widget_id: contact
headless: true
weight: 130
title: Contact

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
  content:
    autolink: true
    email: andre.lot@nhh.no
    address:
      street: Helleveien 30
      city: Bergen
      region: null
      postcode: '5045'
      country: Norway
      country_code: NOR
    coordinates:
      latitude: "60.4230"
      longitude: "5.3029"

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'


---
