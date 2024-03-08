---
# Leave the homepage title empty to use the site title
title: Linying Zhang
date: 2024-03-07
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Intern
          company: MOX
          company_url:
          company_logo: 
          location: Politecnico di Milano, Italy
          date_start: '2023-09-01'
          date_end: '2024-03-01'
          description: Development of a data-driven surrogate modeling using shape-informed framework to deal with problems with variable domain.

        - title: Open Source Promotion Plan (OSPP 2023)
          company: Baidu
          company_url: 'https://ir.baidu.com/'
          company_logo: 
          location: Baidu, Beijing
          date_start: '2023-07-01'
          date_end: '2023-09-01'
          description: Developed PDE solvers based on the framework of PaddleScience with deep learning algorithms.
     #     description: |2-
     #         Responsibilities include:
     #
     #              * Analysing
     #        * Modelling
     #        * Deploying
            
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
          tag: PINN-DVM
        - name: Other
          tag: 
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
 # - block: tag_cloud
 #   content:
 #     title: Popular Topics
 #   design:
 #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: lyzhangnna@gmail.com
      phone:  
      # appointment_url: 'https://calendly.com'
      address:
        street: Xueyuan Road, 37
        city: Beijing
        region: Beijing
        postcode: '100191'
        country: China
      directions:  School of Aeronautic Science and Engineering
      contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
        # - icon: linkedin
        #   icon_pack: fab
        #   name: Connect on
        #   link: 'https://linkedin.com/in/paolo--conti'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---