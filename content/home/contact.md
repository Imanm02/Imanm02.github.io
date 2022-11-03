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
  email: imanm1381@gmail.com
  phone: +98 913 402 2571
#  address:
#    street: 450 Serra Mall
    city: Tehran
    region: Iran
    postcode: '1471784876'
    country: Iran
    country_code: IR
#  coordinates:
#    latitude: '37.4275'
#    longitude: '-122.1697'
#  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
#      name: DM Me
      link: 'https://twitter.com/Iman_M_02'
    - icon: github
    icon_pack: fab
    link: https://github.com/Imanm02
    - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/imanmohammadi02/
    - icon: instagram
    icon_pack: fab
    link: https://www.instagram.com/iman_m_02/
    - icon: telegram
      icon_pack: fas
#      name: Zoom Me
      link: 'https://t.me/iman_m_02'

design:
  columns: '2'
---
