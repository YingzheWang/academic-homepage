---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

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
  email: ywang@live.mech.eng.osaka-u.ac.jp
  phone: +81 06-6879-7344
  address:
    street: 2-1 Yamadaoka
    city: Suita
    region: Osaka, JAPAN
    postcode: '565-0071'
    country: Japan
    country_code: JP
  coordinates:
    latitude: '34.8223'
    longitude: '135.5213'
  directions: Enter Building M3 and take the stairs to Office 316 on Floor 3
  office_hours:
    - 'Monday ~ Friday 9:00 to 17:00'
  appointment_url: 'https://calendly.com'
  contact_links:



design:
  columns: '2'
---
