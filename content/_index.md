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
    banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: images.jpg
      css_class: light
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      background:
        color: ''
        image:
          # Add your image background to `assets/media/`.
          filename: ''
          filters:
            brightness: 1.0
          size: ''
          position: ''
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "9"
          description: |
            Publications  
        - statistic: "8"
          description: |
            Manuscripts under submission 
        - statistic: "1,600+"
          description: |
            Citations
        - statistic: "11"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: light
      # Reduce spacing
      spacing:
        padding: ["2rem", 0, "2rem", 0]        
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
