---
title: contact
cache_enable: false
form:
    name: contact
    action: '/home#contact'
    fields:
        -
            name: name
            label: Nombre
            classes: form-control
            placeholder: 'Tu nombre completo'
            autofocus: 'off'
            autocomplete: 'on'
            type: text
            position: left
            validate:
                required: true
        -
            name: email
            label: Email
            classes: form-control
            placeholder: 'Dirección de Email'
            type: email
            position: left
            validate:
                required: true
        -
            name: message
            label: Mensaje
            placeholder: 'Escribe tu mensaje'
            type: textarea
            classes: form-control
            position: right
            validate:
                required: true
    buttons:
        -
            type: submit
            classes: 'btn btn-primary btn-lg'
            value: Enviar
    process:
        -
            message: 'Gracias por entrar en contacto!'
---

## Escríbenos
### Envíanos un mensaje de correo mediante este formulario.

