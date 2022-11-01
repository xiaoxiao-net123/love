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
  email: 2030528@tongji.edu.cn
  phone: 86-021-13371852150
  address:
    street: No.1239 Siping Road
    city: Yangpu District
    region: Shanghai
    postcode: '200092'
    country: China
    country_code: CHN
  coordinates:
    latitude: '31.280779'
    longitude: '31.280779, 121.504528'
  directions: Office 107, First Laboratory Building
  office_hours:
    - '8:00 to 21:00'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/chunhong_xiao'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://us05web.zoom.us'

design:
  columns: '2'
---
