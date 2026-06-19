---
title: Contact
date: 2026-06-18
type: landing

design:
  spacing: '5rem'

sections:
  - block: contact
    id: contact
    content:
      title: Get in Touch
      text: |-
        I am glad to discuss neuroimaging, biomarkers, disease progression modeling, and potential collaborations. The fastest way to reach me is by email.
      # Contact details. Email shows as a clickable link (no form needed).
      email: Gebre.RobelKebede@mayo.edu
      address:
        street: 200 First Street SW
        city: Rochester
        region: MN
        postcode: '55905'
        country: United States
        country_code: US
      # Academic and code profiles
      contact_links:
        - icon: brands/github
          name: GitHub
          link: 'https://github.com/RobelGebre'
        - icon: academicons/google-scholar
          name: Google Scholar
          link: 'https://scholar.google.com/schhp?hl=en&inst=12058184521150304743'
        - icon: academicons/orcid
          name: ORCID
          link: 'https://orcid.org/0000-0002-5746-0994'
      # Link the email/phone automatically rather than show as plain text.
      autolink: true
      # Email form provider.
      # Left disabled because GitHub Pages cannot process Netlify forms.
      # To enable later: register at formspree.io, then set
      #   form:
      #     provider: formspree
      #     formspree:
      #       id: YOUR_FORM_ID
      # and remove the `email:` field above (use a form OR a shown email, not both).
    design:
      columns: '1'
---
