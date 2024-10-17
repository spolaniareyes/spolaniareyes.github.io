---
# Leave the homepage title empty to use the site title
title: ""
#date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: ''

sections:
  - block: resume-biography-3
    margin:
      top: 0px
      right: 0px
      bottom: 0px
      left: 0px
    padding:
      top: 0px
      bottom: 0px
      left: 0px
      right: 0px
    id: section1
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: spolaniareyes
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Polania_CV.pdf
    design:
      css_class: light
      padding: [0, 0, 0, 0]
      background:
        color: ''
        image:
          # Add your image background to `assets/media/`.
          filename: ''
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: collection
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: '' 
    folders:
      - publication
    design:
      columns: '1'
      view: citation
      padding: [0, 0, 0, 0]
  - block: markdown
    id: wp
    content:
      title: Working papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: 1
  - block: markdown
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
