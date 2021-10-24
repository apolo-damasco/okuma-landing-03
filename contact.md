---
title: Contacto
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: |
      Construyamos algo increible.

      Rellena el formulario de contacto o mandanos un email a <hola@okuma.es>.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Nombre
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu dirección de correo electrónico
        is_required: true
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
    submit_label: Enviar mensaje
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
