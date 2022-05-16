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
#  form:
#    provider: netlify
#    formspree:
#      id:
#    netlify:
#      # Enable CAPTCHA challenge to reduce spam?
#      captcha: true

  # Contact details (edit or remove options as required)
  email: clemens.riegler@uni-wuerzburg.de
  address:
    street: Emil-Fischerstr. 32
    city: Würzburg
    region: Bavaria
    postcode: '97072'
    country: Germany
    country_code: DE
  directions: Enter Building 32, right entrance, 4th floor, first office on the right hand side
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: DM Me
      link: 'https://www.linkedin.com/in/clemens-riegler-579a7866/'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.clex.space'

design:
  columns: '2'
---
