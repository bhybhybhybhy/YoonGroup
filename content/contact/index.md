---
title: Contact
date: 2024-04-09

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
         We're looking for highly motivated graduate and undergraduate students and postdocs in THE YOON GROUP. Please send an email with your CV, if you're interested in working with us!
      email: bohakyoon@gmail.com
      phone: 347 111 1123
      address:
        street: 101 Bagby Ave
        city: Waco
        region: TX
        postcode: '76706'
        country: United States
        country_code: US
      coordinates:
        latitude: '31.54839536621661'
        longitude: '-97.11305180082111'
      directions: Enter the Baylor Sciences Building.
      office_hours:
        - 'Monday 10:00 to 16:00'
        - 'Wednesday 10:00 to 15:00'
      appointment_url: 'https://calendly.com'
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: Baylor_university_campus.jpg ##contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
