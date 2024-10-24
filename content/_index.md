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
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '0', '0', '0']
        margin: ['0', '0', '0', '0']
  - block: collection
    id: publications
    content:
      title: Publications
      #subtitle:
      #text: ''
      count: 10
    filters:
      folders:
        - publication
      exclude featured: false    
    design:
      background:
    # Choose a color such as from https://html-color-codes.info
        color: 'Azure'
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['0', '0', '0', '0']
        margin: ['0', '0', '0', '0']
  - block: collection
    id: chapter
    content:
      title: Book Chapters
      #subtitle:''
      #text: ''
    filters:
      folders:
        - chapter
      exclude featured: false    
    design:
      columns: 3
      view: article-grid
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
  - block: collection
    id: wp
    content:
      title: Working Papers
      count: 10
      filters:
        folders:
          - wp
    design:
      view: citation
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
      background:
    # Choose a color such as from https://html-color-codes.info
        color: 'Azure'
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
#  - block: markdown
 #   id: talks
  #  content:
   #   title: 'Talks'
    #  subtitle: ''
     # text: |-
      #  See my CV.
     # filters:
      #  folders:
       #   - event
    #design:
     # view: compact
      #columns: 2
      #padding: [0, 0, 0, 0]
---
