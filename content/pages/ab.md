---
title: About us
sections:
  - elementId: ''
    colors: colors-h
    width: wide
    height: tall
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    topGap: none
    bottomGap: none
    textAlign: left
    variant: variant-b
    badge:
      elementId: ''
      label: lorem-ipsum
    title: lorem-ipsum
    text: >-
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua.


      - Lorem ipsum

      - dolor sit amet
    form:
      type: FormBlock
      idAttr: contact-form
      action: /.netlify/functions/submission_created
      destination: ''
      fields:
        - type: TextFormControl
          name: name
          label: Name
          placeholder: Your name
          isRequired: true
          width: 1/2
        - type: EmailFormControl
          name: email
          label: Email
          placeholder: Your email
          isRequired: true
          width: 1/2
        - type: TextFormControl
          name: home-address
          label: Home address
          placeholder: Your home address
          isRequired: true
          width: full
        - type: CheckboxFormControl
          name: updates
          label: Sign me up to receive updates
          width: full
      submitLabel: Send Message
    feature:
      type: ImageBlock
      url: /images/contact.png
      altText: Contact form image
    type: ContactSection
  - type: HeroSection
    title: About Us...
    subtitle: Who We Are
    topGap: none
    bottomGap: none
    text: >-
      Contrary to popular belief, Lorem Ipsum is not simply random text. It has
      roots in a piece of classical Latin literature from 45 BC, making it over
      2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney
      College in Virginia, looked up one of the more obscure Latin words.
    feature:
      type: ImageBlock
      url: /images/about.jpg
      altText: About us
  - type: CtaSection
    title: Careers
    text: >-
      There are many variations of passages of Lorem Ipsum available, but the
      majority have suffered alteration in some form, by injected humour, or
      randomised words which don't look even slightly believable.
    topGap: none
    bottomGap: none
    contentAlignVert: top
    heigth: short
    variant: variant-a
    colors: colors-c
    badge: {}
    actions:
      - type: Button
        label: Learn more
        url: /
        style: primary
layout: PageLayout
---
