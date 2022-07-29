---
title: Laiškas
sections:
  - type: hero_section
    title: Susisiekite!
    subtitle: ''
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ### Parašykite mums laišką!


      Norime įspėti, jog į elektroninius laiškus atsakome per 24 valandas. Jeigu
      norite susisiekti skubiai, siūlome kreiptis telefonu.


      ### Duomenų sauga.


      Informuojame, jog jūsų pateikti duomenys yra saugomi ir bus naudojami tik
      susiekimo tikslais. Juos pasiekti gali tik personalas, atsakingas už
      komunikaciją.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Vardas
        default_value: Jūsų vardas
        is_required: true
        options:
          - lorem-ipsum
      - input_type: email
        name: email
        label: El. pašto adresas
        default_value: Jūsų el. pašto adresas
        is_required: true
      - input_type: textarea
        name: message
        label: Žinutė
        default_value: Jūsų žinutė
        is_required: true
      - input_type: checkbox
        name: consent
        label: 'Sutinku, kad mano duomenys būtų saugomi susisiekimo tikslais.'
        is_required: true
    submit_label: Siųsti
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
template: advanced
---
