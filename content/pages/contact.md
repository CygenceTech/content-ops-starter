---
type: PageLayout
title: Contact
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Contact Us
      color: text-dark
    subtitle: ''
    text: "Cygence Technology\n\n**Phone**:\_[201-984-3726](tel:201-984-3726)\n\n**Email**: \_<info@cygencetech.com>\n"
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: SelectFormControl
          name: interested-services
          label: What services are you interested in most?
          hideLabel: false
          defaultValue: Managed AI Services
          options:
            - AI Compliance
            - AI Network Assessment
            - AI On Demand
            - Managed AI Services
            - AI Cloud Integration
            - Other
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: send
        iconPosition: right
        style: primary
        showIcon: true
      action: ''
      elementId: Form Block
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
      destination: ''
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
slug: /contact
isDraft: false
seo:
  type: Seo
  metaTitle: ''
  metaDescription: ETECH IT - Contact Us
  addTitleSuffix: false
  metaTags: []
---
