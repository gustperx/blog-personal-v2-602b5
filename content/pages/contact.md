---
title: Contacto
hide_title: false
sections:
    - section_id: contact-form
      type: section_form
      content: >-
          ¡Hola! Muchas gracias por su interés en trabajar juntos. 
          Complete el formulario de contacto a continuación.
      form_id: contactForm
      form_action: /thank-you
      form_fields:
          - input_type: text
            name: name
            label: Nombre
            default_value: Tu nombre
            is_required: true
          - input_type: email
            name: email
            label: Correo electrónico
            default_value: Tu correo electrónico
            is_required: true
          - input_type: select
            name: subject
            label: Asunto
            default_value: Selecciona uno
            options:
                - Presupuesto
                - Asesoría
                - Otra
          - input_type: textarea
            name: message
            label: Mensaje
            default_value: Tu mensaje
          - input_type: checkbox
            name: consent
            label: >-
                Entiendo que este formulario está almacenando mi información enviada para que puedan ser contactados.
      submit_label: Enviar mensaje
seo:
    title: Contacto - Gustavo Perez - Full Stack Developer
    description: Contacto - Gustavo Perez - Full Stack Developer
    extra:
        - name: 'og:type'
          value: website
          keyName: property
        - name: 'og:title'
          value: Contacto - Gustavo Perez - Full Stack Developer
          keyName: property
        - name: 'og:description'
          value: Contacto - Gustavo Perez - Full Stack Developer
          keyName: property
        - name: 'twitter:card'
          value: summary
        - name: 'twitter:title'
          value: Contact
        - name: 'twitter:description'
          value: Contacto - Gustavo Perez - Full Stack Developer
layout: advanced
---
