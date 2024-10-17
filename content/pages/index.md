---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: AQUI PUEDES SUBIR Y CONFIRMAR TUS PEDIDOS.
      color: text-dark
      type: TitleBlock
    subtitle: Mejora Continua
    text: >
      Esta web app ha sido creada con el proposito de mejorar los procesos de
      confirmacion de pedidos entre el personal que labora en campo y el
      personal de bodega. Nuestra intencion es ir mejorando este proceso para
      que no se presenten inconvenientes como los que se han presentado en el
      pasado. Mediante esta web app podran confirmar los pedidos que hagan tanto
      clientes directos como indirectos y recibiran un mensaje de confirmacion
      por parte de la persona encargada, informandoles si existe alguna novedad
      con su pedido.
    actions:
      - label: Empieza con tu pedido
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Mira el tutorial
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/Logo Interagro.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: BIENVENIDOS
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: ''
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Puedes contactarnos a traves de whatsapp al numero 3154691830 o dejanos
      tus datos en el siguiente formulario y nos pondremos en contacto lo antes
      posible.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Tu nombre
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Tu correo
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tu mensaje
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Enviar
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: contactanos
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
