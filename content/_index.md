---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin		#NAO MEXER.
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: https://github.com/luizalober/portfolio/blob/8f3acf4ce3e7a7a58d65fb5faa1ed606baa74f3a/static/uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: networks.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks and Posters
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
