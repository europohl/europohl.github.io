---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing
design:
  # Default section spacing
  spacing: '6rem'
sections:
  # 1. DEIN PROFIL (Das Wichtigste)
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'About Me'
        education: 'Education'
        interests: 'Interests'
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium
        shape: circle

  # 2. DEINE FORSCHUNG / ÜBER DICH
  - block: markdown
    content:
      title: '📚 My Research & Focus'
      subtitle: 'Sustainable Future & Geodata Analysis'
      text: |-
        Passionate about a sustainable future: Studied Natural Resource Management and Ecological Engineering in Halle, Vienna, Lisbon and Christchurch, specializing in geodata analysis, natural area restoration and environmental policy. 
        
        Practical experience from the wind energy industry. Particularly eager to actively support the achievement of [SDG 7](https://sdgs.un.org/goals/goal7), [SDG 13](https://sdgs.un.org/goals/goal13) and [SDG 15](https://sdgs.un.org/goals/goal15).
    design:
      columns: '1'

  # # 3. PUBLIKATIONEN (Falls vorhanden)
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Projects & Publications
  #     filters:
  #       folders:
  #         - publications
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2

  # # 4. VORTRÄGE (Kannst du auskommentieren mit #, wenn leer)
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card

  # # 5. NEWS / BLOG (Kannst du auskommentieren mit #, wenn leer)
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     page_type: blog
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     offset: 0
  #     order: desc
  #   design:
  #     view: card
  #     spacing:
  #       padding: [0, 0, 0, 0]
---
