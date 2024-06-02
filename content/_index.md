---
# Leave the homepage title empty to use the site title
title: "Sasa's Website"
date: 2024-06-02
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: hero
    content:
      title: Reach Out
      text: If you want to collaborate or need my services 😃
    primary_action:
      text: Email me
      url: 'mailto:sasinhe@gmail.com'
      icon: envelope
    secondary_action:
      text: See my work
      url: https://github.com/sasinhe/
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
