---
# Leave the homepage title empty to use the site title
title: 'Robel Gebre'
summary: ''
date: 2022-10-24
type: landing
design:
  spacing: '6rem'
sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: '🧠 My Research'
      subtitle: ''
      text: |-
        I develop computational and analytical methods for quantifying neurodegenerative and musculoskeletal disease from medical images, using deep learning, explainable AI, biophysical modeling, disease progression modeling, and multimodal biomarker integration. My current work focuses on tau PET quantification in Alzheimer's disease, imaging heterogniety that distinguish multiple system atrophy from Parkinson's disease, and MRI harmonization for multi-site studies. I created the THETA score, the first tau PET metric that captures the full spatial heterogeneity of tau spread across the brain in a single clinically usable valuen. During my PhD, I applied similar quantitative approaches to musculoskeletal imaging, developing methods to detect hip osteoarthritis and fracture risk from clinical CT. 
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
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
    id: news
    content:
      title: Recent News
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
