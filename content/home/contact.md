---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Contact Me
subtitle: Let's talk!

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
      captcha: true

  # Contact details (edit or remove options as required)
  #email: francisco.yira@outlook.com
  #phone: +56 9 5115 9191
#  address:
#    #street: 
#    city: Santiago
#    country: Chile
#    country_code: CL
#    #region: CA
#    #postcode: '94305'
#  coordinates:
#    latitude: '37.4275'
#    longitude: '-122.1697'
#  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#  office_hours:
#    - 'Monday 10:00 to 13:00'
#    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com/francisco-yira/meeting-with-francisco-yira'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM me
      link: 'https://twitter.com/messages/compose?recipient_id=1050927630122389506&text=Hello!'
    - icon: envelope
      icon_pack: fas
      name: E-mail me
      link: 'mailto:francisco.yira@outlook.com'

design:
  columns: '2'
---
