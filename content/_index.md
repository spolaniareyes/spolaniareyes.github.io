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
      avatar: true
      #text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Polania_CV.pdf
    design:
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
      title: Publications
      subtitle: ''
      text: '' 
    folders:
      - publication
    design:
      columns: 2
      view: citation
      padding: [0, 0, 0, 0]
  - block: collection
    id: wp
    content:
      title: Working papers
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: 2
      padding: [0, 0, 0, 0]
  - block: markdown
    id: talks
    content:
      title: 'Talks'
      subtitle: ''
      text: |-
        See my CV.
     # filters:
      #  folders:
       #   - event
    design:
      view: compact
      columns: 2
      padding: [0, 0, 0, 0]
---
