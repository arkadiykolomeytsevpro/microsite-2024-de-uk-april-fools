---
layout: competition
id: competition
title: Wettbewerb
permalink: /competition/
nav: true
nav-order: 5

intro-title: Enter now for your chance to win!
intro: Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur non facere, iure quod numquam eum, dolorem saepe placeat ipsum sunt deleniti. Pariatur cumque, sint suscipit nisi ratione adipisci deserunt aut.
intro-terms: >
  For full T&Cs read <a href="#modal-competition-terms" class="js-open-modal underline">here</a>

competition-form:
  id: comp
  post-url: "#getform-url"
  expiry-date: 2050-01-01
  fields:
    - id: name
      type: text
      label: Name
      required: true
    - id: email
      type: email
      label: Email
      required: true
    - id: qualify
      type: radio
      label: Are you a UK resident and over the age of 18?
      required: true
      options:
        - id: qualify-true
          label: "Yes"
          value: "yes"
        - id: qualify-false
          label: "No"
          value: "no"
          invalid: true
    - id: opt-in
      type: radio
      label: Would you like to receive emails from Secret Escapes?
      required: true
      options:
        - id: opt-in-true
          label: "Yes"
          value: "yes"
        - id: opt-in-false
          label: "No"
          value: "no"
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#modal-competition-terms" class="js-open-modal underline">terms and conditions</a> of this competition
---
