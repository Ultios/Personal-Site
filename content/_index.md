---
# Leave the homepage title empty to use the site title
title: Aulia Rahman
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      view: compact
      columns: '2'
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
          - title: Research Assistant
          company: Graduate School of Engineering, University of Tokyo
          company_url: 'https://www.t.u-tokyo.ac.jp/en/study-at-utokyo/soe/seut-ra'
          location: Bunkyo, Tokyo
          date_start: '2025-10-01'
          date_end: '2026-09-30'
          description: |2-
              Awarded as part of SEUT-RA program, a competitive incentives program designed to support exceptional doctoral student.
        - title: Lead Project Officer
          company: Central Java and Yogyakarta National Road Implementation Center, Indonesian Ministry of Public Works and Housing
          company_url: 'https://binamarga.pu.go.id/balai-jateng-diy/'
          location: Middle Java Province and Special Region of Yogyakarta
          date_start: '2023-03-01'
          date_end: '2023-10-05'
          description: |2-
              Responsibilities include:
              * Modelling traffic impact
              * Proposing alternatives
              * Cost benefit analysis
              * Project reporting and presenting
        - title: Project Officer
          company: Central Java and Yogyakarta National Road Implementation Center, Indonesian Ministry of Public Works and Housing
          company_url: 'https://binamarga.pu.go.id/balai-jateng-diy/'
          location: Middle Java Province and Special Region of Yogyakarta
          date_start: '2022-01-01'
          date_end: '2022-12-31'
          description: |2-
              Responsibilities include:
              * Modelling traffic impact
              * Proposing alternatives
              * Cost benefit analysis
              * Project reporting and presenting
        - title: Project Officer
          company: Metropolis Department, Directorate General of Highway, Indonesian Ministry of Public Works and Housing
          company_url: 'https://binamarga.pu.go.id/'
          location: Metropolis region of Mataram, Yogyakarta, Tasikmalaya, Balikpapan and Samarinda
          date_start: '2020-01-01'
          date_end: '2020-12-31'
          description: |2-
              Responsibilities include:
              * Modelling traffic impact
              * Planning sustainable road development of new capital city of Nusantara
              * Infrastructure and accessibility planning for MotoGP's Mandalika International Circuit
    
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Feel free to contact me about anything you may want to ask!
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
