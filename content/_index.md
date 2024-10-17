---
# Leave the homepage title empty to use the site title
title: ""
#date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography-3
    id: section1
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
  - block: markdown
    id: publications
    content:
      title: 'Publications'
      subtitle: ''
      text: 'Measuring perceptions of post conflict actors’ economic behavior: The case of Colombia. 2021. Peace and Conflict: Journal of Peace Psychology. With Santiago Alonso-Díaz, et al.
        “Building social capital: Conditional cash transfers and cooperation”. 2015. With Orazio Attanasio and Luca Pellerano Journal of Economic Behavior and Organization. 118, October, 22–39.
        “Economic incentives and social preferences: substitutes or complements?” 2012. With Sam Bowles. Journal of Economic Literature. 50, June, 368-425. 
        “Building trust? Conditional cash transfer programs and social capital”. 2009. With Orazio Attanasio and Luca Pellerano. Fiscal Studies, 30, 139–177. 
        “Social Capital and Household Income in Urban Colombia”. 2005. Revista Desarrollo y Sociedad. University of Los Andes. 56. September, 221-284.' 
    design:
      columns: '1'
      view: citation
  - block: markdown
    id: workpapers
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
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
