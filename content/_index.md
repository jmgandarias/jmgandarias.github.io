---
# Leave the homepage title empty to use the site title
title: Juan M. Gandarias
date: 2023-08-23
type: landing

sections:
  - block: hero
    content:
      title: 
      image:
        filename: juanma_florencia.png
      cta:
        label: '**Biography**'
        url: https://jmgandarias.com/#about
      # cta_alt:
      #   label: '**Contact me**'
      #   url: https://jmgandarias.com/#contact
      # cta_note:
      #   label: >-
      #     <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Hi, I'm Juanma Gandarias!**

        I am an Assistant Professor in the Systems Engineering and Automation Department and a researcher at the Robotics and Mechatronics group at the University of Malaga.
        
        My research interests include physical Human-Robot Interaction, human modeling, haptics, and soft robotics.
        
        Here you can find preprints of my publications, overviews of past and ongoing research projects, teaching material, and my contact information.

        # <!--Custom spacing-->
        # <div class="mb-3"></div>
        # <!--GitHub Button JS-->
        # <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: ''
        gradient_start: ''
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  #       - name: Photography
  #         description: 10%
  #         icon: camera-retro
  #         icon_pack: fas
  - block: experience
    content:
      title: Academic Career
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: June 1991
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor
          company: University of Malaga
          company_url: 'https://uma.es'
          company_logo: logo_uma_blanco
          location: Malaga, Spain
          date_start: '2023-07-25'
          date_end: ''
          description: |2-
              * Teching
              * Academic research
              * Mentoring PhD, MS, and BS students
              * Project management
        - title: Postdoctoral Researcher
          company: Istituto Italiano di Tecnologia
          company_url: 'https://iit.it'
          company_logo: iit_logo_blanco
          location: Genova, Italy
          date_start: '2020-10-01'
          date_end: '2023-07-24'
          description: |2-
              * Academic research
              * Mentoring PhD, MS, and BS students
              * Project management
        - title: Postdoctoral Researcher
          company: University of Malaga
          company_url: 'https://uma.es'
          company_logo: logo_uma_blanco
          location: Malaga, Spain
          date_start: '2020-03-31'
          date_end: '2020-10-01'
          description: |2-
              * Academic research
              * Mentoring PhD, MS, and BS students
              * Teaching assistant in laboratory sessions
        - title: PhD Research Visitor
          company: University College London
          company_url: 'https://ucl.ac.uk'
          company_logo: logo_ucl_blanco
          location: London, UK
          date_start: '2019-03-01'
          date_end: '2019-07-01'
          description: |2-
              * Academic research
              * Mentoring MS students
        - title: PhD Student
          company: University of Malaga
          company_url: 'https://uma.es'
          company_logo: logo_uma_blanco
          location: Malaga, Spain
          date_start: '2017-04-07'
          date_end: '2020-03-30'
          description: |2-
              * Academic research
              * Mentoring MS and BS students
              * Teaching assistant in laboratory sessions
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: jmgandarias@uma.es
      # phone: 888 888 88 88
      appointment_url: 'https://calendly.com/juanmagandarias11'
      address:
        street: Calle Dr Ortiz Ramos 
        city: Malaga
        postcode: '29010'
        country: Spain
        # map: https://www.google.com/maps?client=ubuntu&hs=0fg&sca_esv=560980485&channel=fs&output=search&q=calle+doctor+ortiz+ramos+escuela+de+ingenierias+industriales&source=lnms&entry=mc&sa=X&ved=2ahUKEwi7qMqO5IGBAxWidqQEHU3zAgoQ0pQJegQIDRAB
        # country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Tuesday 09:00 to 11:00'
        - 'Wednesday 09:00 to 11:00'
      contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM me on Twitter
        #   link: 'https://twitter.com/jmgandarias'
        # - icon: teams
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: true
    design:
      columns: '2'
---
