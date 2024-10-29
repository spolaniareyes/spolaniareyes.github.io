---
# Leave the homepage title empty to use the site title
title: ""
#date: 2022-10-24
type: landing

design:   # Default section spacing
  #spacing: '1rem'
sections:
  - block: resume-biography-3
    content: 
      username: spolaniareyes
      avatar: true
      #text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Polania_CV.pdf
        font-size: 25px
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
      #columns: 4
     # align: left    
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
  - block: collection
    id: art
    content:
      title: Publications
      count: 10
      filters:
        folders:
          - art
    design:
      view: citation
      spacing:
          padding: [0, 0, 0, 0]
          margin: [0, 0, 0, 0]
  - block: collection
    id: chapter
    content:
      title: Book Chapters
      filters:
        folders:
          - chapter
        #publication_type: ["6"]
        #exclude featured: true   
      order: desc
    design:
      columns: 3
      view: article-grid
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
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
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]

    #       background:
    # Choose a color such as from https://html-color-codes.info
       # color: '#EFF8FB'
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
       # text_color_light: false
 
---
