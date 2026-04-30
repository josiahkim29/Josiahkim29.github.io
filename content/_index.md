---
title: ""
date: 2025-07-29
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: "Just Show Up!!"
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: My Research
      subtitle: AI for climate and weather across Africa
      text: |-
        I work at the intersection of machine learning and atmospheric science, building models that improve weather prediction accuracy. My thesis, **PiggyCast**, applies a stacking-based ensemble approach to nowcasting and short-range forecasting — contributing to the urgent challenge of climate adaptation across Africa.

        I am always open to collaboration. Reach out if our interests overlap.
    design:
      columns: '1'

  - block: collection
    content:
      title: Selected Projects
      text: A selection of things I have built and researched.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: markdown
    content:
      title: "Get in Touch"
      subtitle: ""
      text: |-
        Whether you want to discuss research, explore collaboration, or just say hello — I would love to hear from you.

        **Email:** josiah@aims.ac.za
    design:
      columns: '1'
---
