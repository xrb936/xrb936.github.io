---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "4"
          description: |
            Publications
        - statistic: "11"
          description: |
            Citations
        - statistic: "2"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Hello 你好 👋'
      subtitle: ''
      text: |-
        Rongbing Xu is a Ph.D. student in Systems Design Engineering at the University of Waterloo, specializing in aeronautics, cognitive modeling, and human factors. Under the supervision of [Dr. Shi Cao](https://uwaterloo.ca/systems-design-engineering/profile/s34cao) and [Dr. Michael Barnett-Cowan](https://uwaterloo.ca/kinesiology-health-sciences/profiles/michael-barnett-cowan), his research focuses on enhancing pilot training and performance evaluation through computational cognitive modeling and machine learning, using real-world flight and physiological data.

        He earned his MASc in Systems Design Engineering from the University of Waterloo, where he developed a cognitive architecture-based model for simulating pilot behavior during pre-flight and take-off tasks. He also holds a B.Sc. in Computer Science with a minor in Mathematics from the University of New Mexico.

        Xu has published peer-reviewed work in journals such as Journal of Aviation/Aerospace Education & Research and has presented at international conferences including the Human Factors and Ergonomics Society Annual Meeting and the International Symposium on Aviation Psychology. His recent projects involve consumer-grade EEG and wearable technology for real-time stress detection in general aviation pilots.

        In addition to his research, Xu serves as a Teaching Assistant in systems design engineering courses and contributes actively to the professional community as the Director of Communications for the University of Waterloo’s Human Factors and Ergonomics Society Student Chapter. He is a reviewer for IEEE Transactions on Human-Machine Systems and HFES proceedings, and a member of IEEE and HFES.
    design:
      columns: '1'
  # - block: collection
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
