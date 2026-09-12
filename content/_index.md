---
# Leave the homepage title empty to use the site title
title: 'Neuroimaging and AI Research'
summary: "Robel Gebre is an Assistant Professor of Radiology at Mayo Clinic researching tau PET biomarkers, Alzheimer's disease, MRI harmonization, and machine learning in neuroimaging."
date: 2022-10-24
type: landing
design:
  spacing: '4rem'
sections:
  - block: resume-biography
    content:
      username: me
      text: >-
        I develop PET and MRI biomarkers that reveal how neurodegenerative disease
        varies across people and over time.
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      background:
        gradient_mesh:
          enable: false
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: Research Focus
      subtitle: ''
      text: |-
        I use deep learning, explainable AI, and disease progression models to turn medical images into useful measures of disease. My current work focuses on tau PET quantification, MRI harmonization across sites, and imaging differences between multiple system atrophy and Parkinson's disease.

        I created the [THETA score](/projects/theta/), a tau PET measure that captures the spatial pattern of tau across the brain.

        My publications also appear under Robel K. Gebre and Robel Kebede Gebre.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      count: 0
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3

  - block: collection
    content:
      title: Latest Publications
      text: ''
      count: 5
      filters:
        folders:
          - publications
        exclude_featured: true
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: blog
    content:
      title: Recent Blogs
      subtitle: ''
      text: ''
      page_type: blog
      count: 100
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
