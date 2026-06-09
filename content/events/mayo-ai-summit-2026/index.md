---
title: "PET Tracer Classification and the Tau Therapeutic Window"
date: '2026-06-05T00:00:00Z'   # TODO: set to the actual summit date

event_name: Mayo Clinic AI Summit            # TODO: confirm the official summit name
event_url: ''                                # TODO: add the summit page URL if one exists

location: Mayo Clinic, Rochester, MN
address:
  street: 200 First St SW
  city: Rochester
  region: MN
  postcode: '55905'
  country: United States

summary: A podium talk on a 2.5D deep learning classifier for PET tracer identification, and a poster introducing the tau therapeutic window as an eligibility criterion for anti-amyloid therapy.
abstract: |
  I presented two contributions at the Mayo Clinic AI Summit.

  In the podium talk, I described a 2.5D ConvNeXt classifier that identifies the radiotracer of a brain PET scan directly from the image. The model reached a Matthews correlation coefficient of 0.93 across tracer classes. This accuracy supports automated quality control and harmonization in large multitracer imaging archives, where tracer labels are often missing or inconsistent.

  The poster introduced the tau therapeutic window, a biologically grounded eligibility criterion for anti-amyloid therapy. Using the Mayo PROMOD cohort, I estimated the window with two independent models, SILA and an accelerated failure time model. The two approaches converged within 0.3 years and defined a tau PET window over the SUVR range [1.28, 1.51]. The window identifies patients early enough in the disease course for treatment to plausibly change the trajectory.

# Talk start and end times.
event_start: '2026-06-05T09:00:00Z'   # TODO: adjust to real start time
event_end: '2026-06-05T17:00:00Z'     # TODO: adjust to real end time
event_all_day: false

authors:
  - admin                              # TODO: match your author id (the showcase used `me`)

tags:
  - PET
  - Deep Learning
  - Tau
  - Alzheimer's Disease
  - Neuroimaging

featured: true

image:
  caption: 'Mayo Clinic AI Summit'
  focal_point: Center

links:
  - icon: file-pdf
    name: Poster
    url: ''                            # TODO: link the TTW poster PDF
  - icon: person-chalkboard
    name: Slides
    url: ''                            # TODO: link the PET classifier slides

slides: ""

projects: []
---

## Overview

I presented two pieces of work at the Mayo Clinic AI Summit: a podium talk on automated PET tracer classification and a poster on the tau therapeutic window.

## PET Tracer Classification

The classifier reads a brain PET volume and predicts which radiotracer produced it. It uses a 2.5D ConvNeXt backbone and reached a Matthews correlation coefficient of 0.93 across tracer classes. Reliable tracer labels matter for any pipeline that pools amyloid, tau, and FDG scans, so this model removes a manual step that scales poorly across thousands of images.

## Tau Therapeutic Window

The poster defined the tau therapeutic window, a tau PET SUVR range over which anti-amyloid therapy can plausibly alter the disease course. I estimated the window in the Mayo PROMOD cohort with two independent models, SILA and an accelerated failure time model. The estimates converged within 0.3 years and gave a window over the SUVR range [1.28, 1.51].

## Photos

![Mayo Clinic AI Summit](summit-01.jpg)

![Mayo Clinic AI Summit](summit-02.jpg)

![Mayo Clinic AI Summit](summit-03.jpg)

![Mayo Clinic AI Summit](summit-04.jpg)