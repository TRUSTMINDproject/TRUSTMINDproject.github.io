---
title: Contact
date: 2025-09-18

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We are always open to collaborate, take feedback, or accept invitations to present our ongoing work. We encourage people to reach out to us if you are looking for research opportunities at the intersection of AI, mental health, and fairness.
      coordinates:
        latitude: '55.70228218817298', 
        longitude: '12.561838017796065'
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
          filename: logo_large.png
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
