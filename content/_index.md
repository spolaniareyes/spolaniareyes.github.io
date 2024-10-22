---
# Leave the homepage title empty to use the site title
title: ""
#date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '1rem'

sections:
  - block: resume-biography-3
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
        filename: 'avatar.jpg'
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
  - block: stats
    content:
      items:
        - statistic: "17"
          description: |
            Publications + Manuscripts 
        - statistic: "1,600+"
          description: |
            Citations
        - statistic: "11"
          description: |
            h-index
    design:
      columns: 4
      align: left    
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
  - block: collection
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: '' 
    folders:
      - publication
    design:
      columns: '2'
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
      columns: 2
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
