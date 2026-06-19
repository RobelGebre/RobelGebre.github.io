---
title: PET Tracer Classification
date: 2026-06-01
tags:
  - PET
  - Deep Learning
  - Quality Control
  - Alzheimer's Disease
---
A deep learning model that reads a brain PET scan and identifies which radiotracer produced it.

<!--more-->

Large PET datasets often carry missing or incorrect tracer labels, which quietly breaks downstream analysis. We trained a 2.5D ConvNeXt model to identify the tracer directly from the image and validated it across ADNI, SCAN, and an external cohort. The model supports automated quality control and curation of large imaging archives. This work is currenlty ynder review.
