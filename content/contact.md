---
title: Contact
sections:
  - type: hero_section
    template: hero_section
    title: Contactez gratuitement Votre Conseiller Numérique
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
    subtitle: >-
      Simple question, besoin d'un avis ou d'être accompagné, nous sommes là
      pour vous aider !
  - type: form_section
    template: form_section
    content: >
      ## Nos garanties :


      Nous avons


      ### Sans engagement


      Nos premiers échanges ne vous engagent strictement. Nous vous ferons une
      proposition forfaitaire


      ### Réponse rapide


      Nous vous recontactons au plus vite après avoir pris le temps d'étudier
      votre demande avec toute l'attention nécessaire.
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - type: form_field
        template: form_field
        input_type: text
        name: name
        label: Nom
        default_value: Votre nom
        is_required: true
      - type: form_field
        template: form_field
        input_type: email
        name: email
        label: Email
        default_value: Votre adresse email
        is_required: true
      - type: form_field
        template: form_field
        input_type: textarea
        name: message
        label: Message
        default_value: Votre message
      - type: form_field
        template: form_field
        input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: images/watercolor.png
    background_image_opacity: 8
    background_image_size: contain
    background_image_repeat: repeat
seo:
  type: stackbit_page_meta
  template: stackbit_page_meta
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
