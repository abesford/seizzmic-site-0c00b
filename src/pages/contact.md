---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contact
    content: |
      **Begin today** - start with conversation

      and collaboration

      Talk with us about how we can work together
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
  - section_id: work-together
    title: Work together
    subtitle: lorem-ipsum
    actions:
      - label: Join us
        url: /careers
        style: primary
        has_icon: false
        icon: arrow-left
        icon_position: left
        new_window: false
        no_follow: false
        type: action
    type: section_cta
template: landing
---
