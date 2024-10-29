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
  - block: markdown
    content:
      title: 'Talks'
      subtitle: ''
      text: "Here is a table of selected talsk."
      table_data:
        - ["Year", "Event"]
        - ["2024", "Workshop in honor of Gary Charness, UNavarra and Public University of Navarra, organizer. Invited speaker; Workshop in honor of Marie Claire Villeval, University Carlos III. Keynote speaker, Neuroscience, Cognition and Behavioral Economics Conference III edition, UN Development program."]
        - ["2023", "19th General Meeting of the European Association of Social Psychology, Latin American and the Caribbean Economic Association (LACEA) Annual Meeting"]
        - ["2022", "Research seminar University Carlos III; Keynote speaker, Neuroscience, Cognition and Behavioral Economics Conference Pontifical Xavierian University, Invited speaker United Nations University World Institute for Development Economics Research (UNU-WIDER), VII Colombian Economic Congress"]
        - ["2021", "Bogota Experimental Economics Conference (Universidad del Rosario). CREDO Econ and CST Virtual Workshop, NCID seminar, Universidad de Navarra"]
        - ["2019", "DeNicola Center for Ethics and Culture Fall Conference, U Notre Dame. Building Sustainable Peace: Ideas, Evidence, and Strategies, Kroc Institute for Peace Studies, University of Notre Dame. Catholic Peacebuilding and Mining: Integral Peace, Development, and Ecology, Kroc Institute for Peace Studies, University of Notre Dame. Symposium speaker at the Paul Volcker Symposium in Behavioral Economics, Maxwell School of Citizenship and Public Affairs, Syracuse University. LACEA BRAIN First Annual Meeting, Washington, DC. Guest speaker at CAL alumni Association, UC Berkeley."]
        - ["2018", "Central Bank of Colombia (Bogota), Bogota Experimental Economics Conference (Universidad del Rosario), Central Bank of Colombia (Medellin), McGrath Institute for Church Life, Kellogg Institute for International Studies, National Planning Department (DNP-COL)"]
        - ["2017", "Fall Ethics Conference University of Notre Dame, Krannert School of Management Purdue University, First Latin-American Workshop on Experimental and Behavioral Social Sciences (LAWEBESS), Advances in Field Experiments (UChicago), UC Berkeley, University of Los Andes, University of Massachusetts-Amherst, University of Notre Dame Economics, Pontifical Xavierian University, NYU CESS 10th Annual Experimental Political Science Conference"]
    #    design:
     # columns: '2'
    #       background:
    # Choose a color such as from https://html-color-codes.info
       # color: '#EFF8FB'
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
       # text_color_light: false
 
---
